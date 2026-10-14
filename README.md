# Low Usage Mode

A pair of Codex skills for completing requested work with bounded context and effort while preserving the full accepted outcome, required checks, authorization, and delivery. The low-usage-mode skill covers routine implementation and agent coordination. For coding, debugging, refactoring, or code review, it includes Ponytail's smallest-complete-change rules.

## Install

From this repository's root, run this in a POSIX shell. It installs both skill folders into the Codex user skills directory (CODEX_HOME/skills when CODEX_HOME is set, otherwise HOME/.codex/skills) and stops if either destination already exists:

~~~sh
set -eu
skills_dir="${CODEX_HOME:-$HOME/.codex}/skills"
mkdir -p "$skills_dir"
if [ -e "$skills_dir/low-usage-mode" ] || [ -e "$skills_dir/ponytail" ]; then
  printf '%s\n' "Refusing to overwrite an existing low-usage-mode or ponytail skill." >&2
  exit 1
fi
mkdir "$skills_dir/low-usage-mode"
mkdir "$skills_dir/ponytail"
cp -R skills/low-usage-mode/. "$skills_dir/low-usage-mode/"
cp -R skills/ponytail/. "$skills_dir/ponytail/"
~~~

If the second mkdir or a copy fails, remove only the newly created empty or partial destination folders before retrying.

Invoke $low-usage-mode for routine implementation or coordination, or when the user asks to conserve usage or stop overbuilding. One invocation also applies Ponytail for coding work; there is no need to invoke $ponytail separately.

## License and credits

The low-usage-mode skill and this repository's documentation are licensed under MIT; see [LICENSE](LICENSE). The included Ponytail instruction body is unchanged from DietrichGebert's [upstream skills/ponytail/SKILL.md at commit 2961b52fc1fe6a5a87c7a959a79512e5c2f3ffe5](https://github.com/DietrichGebert/ponytail/blob/2961b52fc1fe6a5a87c7a959a79512e5c2f3ffe5/skills/ponytail/SKILL.md). The bundled Codex frontmatter adapts the upstream argument-hint into metadata.argument_hint and adds metadata.source and metadata.source_commit provenance fields. Its MIT license text is copied byte-for-byte from the upstream repository-root LICENSE at that commit and retained at [skills/ponytail/LICENSE](skills/ponytail/LICENSE). See [NOTICE.md](NOTICE.md) for details.

This skill does not report measured usage savings or establish behavior across agent hosts.
