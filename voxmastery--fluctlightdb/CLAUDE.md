# fluctlightdb

> This monorepo uses FluctlightDB (`FluctlightDB`) for durable agent memory:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/fluctlightdb/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## FluctlightDB (project memory)

This monorepo uses FluctlightDB (`FluctlightDB`) for durable agent memory:

- Hub: `.fluctlight/project/` (shared decisions + handoffs)
- Spokes: `.fluctlight/agents/{cursor,claude,codex}/`

Use `from fluctlightdb import connect_project` and call `session_context()`, `recall()`, `remember()`, and `handoff()` when switching agents or resuming work. See `.claude/skills/fluctlight-memory/SKILL.md`.

---
> Source: [voxmastery/FluctlightDB](https://github.com/voxmastery/FluctlightDB) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-17 -->
