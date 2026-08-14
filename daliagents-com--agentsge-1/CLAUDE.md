# agentsge-1

> This project stores all agent instructions in `.agents/`. Read these files on session start.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agentsge-1/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Intelligence

This project stores all agent instructions in `.agents/`. Read these files on session start.

## Required (read first, in parallel)

- `.agents/config.yaml` — project name, stack, structure, commands
- `.agents/rules/*.md` — all rule files are mandatory, apply them throughout the session

## Recommended

- `.agents/knowledge/_index.md` — team knowledge index; read on start, drill into linked files when relevant
- `.agents/skills/` — reusable workflows; read when a matching task arises

---
> Source: [Daliagents-com/agentsge-1](https://github.com/Daliagents-com/agentsge-1) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-13 -->
