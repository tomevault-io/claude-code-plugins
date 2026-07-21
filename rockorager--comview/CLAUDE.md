# comview

> This repository uses `mise` for tool versions and common development tasks.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/comview/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent instructions

This repository uses `mise` for tool versions and common development tasks.

- Run the full check with `mise run check`.
- Fix Go lint and formatting issues with `mise run fix`.
- Prefer running Go commands through mise, e.g. `mise exec -- go test ./...`, so the pinned Go version and environment from `mise.toml` are applied.

---
> Source: [rockorager/comview](https://github.com/rockorager/comview) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-20 -->
