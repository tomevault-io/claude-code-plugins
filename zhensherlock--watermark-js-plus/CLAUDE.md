# watermark-js-plus

> Use `AGENTS.md` as the primary project instruction file.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/watermark-js-plus/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# CLAUDE.md - Watermark JS Plus

Use `AGENTS.md` as the primary project instruction file.

When working in a subdirectory, also follow the nearest nested `AGENTS.md` before making changes.

## Claude-Specific Behavior

- Prefer small, reviewable changes.
- Before large refactors, summarize the impact and likely touched areas.
- After code changes, run the most relevant npm checks from `AGENTS.md`.
- Keep shared repo guidance in `AGENTS.md`; keep this file as a lightweight Claude entrypoint.

---
> Source: [zhensherlock/watermark-js-plus](https://github.com/zhensherlock/watermark-js-plus) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-16 -->
