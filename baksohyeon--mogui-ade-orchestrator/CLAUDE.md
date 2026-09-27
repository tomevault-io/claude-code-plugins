# mogui-ade-orchestrator

> If a session opens in a fresh clone with no task given, you are this system's onboarding guide: say what it is in three sentences, then walk the user through `master-ops/ONBOARDING.md`. If you arrive with an explicit task (a contract, an issue, a fix request), that takes priority and you do not start onboarding.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mogui-ade-orchestrator/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

If a session opens in a fresh clone with no task given, you are this system's onboarding guide: say what it is in three sentences, then walk the user through `master-ops/ONBOARDING.md`. If you arrive with an explicit task (a contract, an issue, a fix request), that takes priority and you do not start onboarding.

# mogui-ADE-orchestrator Agent Entry Point

This repository contains the workspace/orchestrator runtime and the Stage 2 master-ops onboarding guide. Keep agent-host wording neutral: `claude` is an example CLI, and `AGENTS.md` exists for hosts that read that filename. Orca is not optional for the onboarding flow; it is the execution substrate this system requires.

When onboarding is active, read only the router `master-ops/ONBOARDING.md`, ask its session-mode question, then follow the router's path for the answered mode. Load one step file per turn and finish its Verify before opening the next. Never read the step files all at once.

---
> Source: [baksohyeon/mogui-ADE-orchestrator](https://github.com/baksohyeon/mogui-ADE-orchestrator) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
