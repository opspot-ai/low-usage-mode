---
name: low-usage-mode
description: Complete requested work with fewer model turns, smaller context and bounded scope, including Ponytail's smallest-complete-change coding rules. Use for routine implementation and agent coordination, or when a user asks to use low usage mode, conserve usage, stop overbuilding, or save capacity for distribution. Preserve required verification and authorized delivery.
---

# Low usage mode

Use this mode by default for routine work. Optimize usage per completed, usable outcome. This is a working policy, not an app speed setting, token quota or permission to pause. A request for depth or "full usage mode for this task" overrides the economy preference for that scope. "Low usage mode" restores it. Preserve explicit model/effort routing; never silently change settings or claim measured savings.

## Included Ponytail coding rules

For coding, debugging, refactoring and code review, read and apply [the installed Ponytail core skill](../ponytail/SKILL.md) once alongside this skill. One invocation of low usage mode includes both; the user does not need to invoke Ponytail separately. Coordination-only work uses this entrypoint without loading additional coding rules.

Default to Ponytail **full**: the smallest change that completely solves the requested task, reuse before invention, and no speculative abstractions or unrequested options. This is Ponytail's coding level, not a request for higher usage. Preserve explicit user choices and project architecture. A proposed smaller solution cannot silently drop admitted features, required delivery, or real tests. Ponytail ultra applies only when requested, and questioning scope never authorizes cancelling accepted work. Its reporting and verification guidance applies proportionally; avoid repetitive skipped-work boilerplate or implementation-mirroring tests for trivial changes.

Installed from [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail/tree/2961b52fc1fe6a5a87c7a959a79512e5c2f3ffe5/skills/ponytail), commit `2961b52fc1fe6a5a87c7a959a79512e5c2f3ffe5`, MIT license. The core instructions are local; no live repository lookup is needed during routine use.

## Bound the outcome

- Start from the current request, its accepted scope and existing checkpoint/card. Identify the user-visible result, necessary dependencies and concrete acceptance. Use existing records; don't create another planning system.
- Tie implementation, review and coordination work to that result. Fix regressions caused by the change and findings that prevent acceptance. New features, optional polish, speculative hardening, refactors and organization projects are separate proposals; discovering one does not admit it.
- Choose the smallest complete solution: reuse the project's components, services, platform capabilities and installed dependencies before adding machinery. Keep the full requested behavior and necessary callers, backend, data and release work. Minimal scope never means a mockup with a missing backend.
- Preserve already admitted work. Reordering for throughput does not cancel other outcomes. An untraceable task needs coordinator reconciliation, not silent cancellation or an invented claim that it was requested.

## Spend on changed evidence

- Read only the relevant instruction, compact checkpoint, changed paths and required evidence. Use targeted searches, excerpts and compact tool responses; avoid whole-board, whole-chat or whole-log dumps and repeated instruction reads without a relevant change.
- Batch independent reads. Reuse tools, saved access, donors and existing artifacts. Don't ask the user to relay work the agent can perform.
- Reuse passing tests, independent verdicts and exact approvals while their source, dependencies, configuration and covered scope remain applicable. Run required pre-release checks and focused checks for changed behavior. Repeat or broaden verification when a new change, failure or unresolved risk justifies it; changing a report label alone is not a reason.
- Keep essential privacy, security, error recovery, correctness and real-device acceptance. Lower usage does not justify skipping required checks, claiming simulated results or using stale evidence for changed code.
- Remove the cause of repeated failures before replaying an expensive operation. No arbitrary retry cap that abandons a fix, and no unchanged retry loop.

## Use parallelism when it advances delivery

- Reuse accountable owners and current attempts. Delegate only when authorized, with a useful independent output, ready inputs, disjoint ownership and a receiving owner. Don't start employees just to keep them busy or gather duplicate status.
- Keep context compact and handoffs actionable. A finished producer sends one completion/blocker event through the project's supported coordinator channel, checkpoints in its existing home and ends its turn. The receiver continues ready authorized work without a manager acknowledgment.
- Use completion events and supported bounded waits. No model-driven idle polling, status sweeps, heartbeat or scheduler merely to keep work alive. Observation is not an approval gate.

## Finish, then stop adding

- Carry an authorized working slice through integration, release and required acceptance immediately. Low usage does not create a usage hold, release stall or new approval step. Preserve real existing approval, account, release-lock and device-lease boundaries.
- Stop the completed task at its acceptance criteria. Submit its result and let the existing coordinator advance a different admitted task; don't append a new feature, redesign, audit or documentation project.
- Report the usable result and evidence level, remaining concrete blocker/owner/action, and a genuinely prepared owner decision when needed. Keep routine source/build chatter in existing work records. Source, review, deployment and customer acceptance remain distinct.
- Check account usage when requested or when a real capacity decision needs fresh evidence. Don't repeatedly poll it, invent per-task savings or reserves, redeem resets, or stop authorized workers because the user expresses concern. A hard budget or pause requires an explicit instruction.

For specialized delivery, production release, or real-device work, follow the current project instructions and required approval, routing, and device-lease boundaries. This mode does not itself authorize a new coordinator, automation, or runtime change.
