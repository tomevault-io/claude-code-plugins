# data-visualization-skills

> - Never stage, commit, or push changes under `docs/`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/data-visualization-skills/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Data Visualization Kit Rules

## Git Protection

- Never stage, commit, or push changes under `docs/`.
- Never stage, commit, or push changes under `plans/`.
- `projects/README.md` stays core-kit owned.
- Project-specific user content belongs under `projects/` and may be committed when explicitly requested.

## Enforcement

- Git hooks live under `.githooks/`.
- Install or refresh them with `npm run kit:hooks:install`.
- The hooks block commits and pushes that include `docs/` or `plans/` paths.

---
> Source: [young-lillo/data-visualization-skills](https://github.com/young-lillo/data-visualization-skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-28 -->
