# f4

> - Use the system Go build cache reported by `go env GOCACHE` for all Go builds and tests.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/f4/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project instructions

## Go build cache

- Use the system Go build cache reported by `go env GOCACHE` for all Go builds and tests.
- Do not redirect `GOCACHE` to `/tmp`, the repository, or another task-local directory unless the user explicitly asks for it.
- If the system cache is unavailable or not writable, report that constraint instead of silently creating a substitute cache.

---
> Source: [unxed/f4](https://github.com/unxed/f4) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-08 -->
