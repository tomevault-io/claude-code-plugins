# pi-omo-slim

> An unofficial, lightweight OMO-slim-style orchestration setup for Pi: a workflow-oriented Orchestrator plus six specialist agents (Explorer, Librarian, Oracle, Designer, Fixer, Verifier). This repo is a configuration bundle — it does not fork Pi, pi-subagents, or OMO-slim.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pi-omo-slim/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# pi-omo-slim

An unofficial, lightweight OMO-slim-style orchestration setup for Pi: a workflow-oriented Orchestrator plus six specialist agents (Explorer, Librarian, Oracle, Designer, Fixer, Verifier). This repo is a configuration bundle — it does not fork Pi, pi-subagents, or OMO-slim.

- TypeScript; npm. Validation: `npm run typecheck` (no build step).
- The sole install entry point is `node scripts/install.mjs` (plan/apply). Never hand-edit a generated plan or silently overwrite same-name custom Agents.
- See README.md for layout and installation; INSTALL_AGENT.md for the install procedure; agents/ holds the six Agent definitions.

---
> Source: [joshua-zyy/pi-omo-slim](https://github.com/joshua-zyy/pi-omo-slim) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-15 -->
