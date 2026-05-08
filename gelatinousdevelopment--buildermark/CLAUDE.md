# buildermark

> - `local/frontend`: web frontend to view and manage ratings (in sveltekit)

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/buildermark/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Buildermark Local – rate coding agent developer workflows

## Architecture

- `local/frontend`: web frontend to view and manage ratings (in sveltekit)
- `local/server`: server to receive rating from plugins and full API (in golang)
- `plugins/*`: plugins for coding agents, like claude code and codex, for the user to rate their current conversation
- `.data/local.db`: sqlite database for the server

## Important Rules

- Never edit or even read `TODO.md`, `TODO-archive.md`, or `ARCHITECTURE.md`
- This is a greenfield project, so we do not need to maintain backwards compatibility for anything right now.

---
> Source: [gelatinousdevelopment/buildermark](https://github.com/gelatinousdevelopment/buildermark) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
