# every-other-token

> - Builder Agent: implements features, owns specific modules

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/every-other-token/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Coordination

## Roles
- Builder Agent: implements features, owns specific modules
- Test Agent: writes tests only, read-only on src/

## Module Ownership
- src/main.rs — CLI, transformations, providers
- src/web/ — HTTP server, SSE, embedded HTML
- tests/ — test coverage

## Rules
- Claim your module at start: "PROTOCOL ACKNOWLEDGED — claiming X"
- Do not edit modules owned by another active agent
- Run cargo test --release before committing
- Commit message format: [feat/fix/docs] description
- Push to both: git push origin main && git push origin master

---
> Source: [Mattbusel/Every-Other-Token](https://github.com/Mattbusel/Every-Other-Token) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-07 -->
