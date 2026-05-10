# 60-style-lint-typecheck

> Formatting, linting, and type checking standards

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/60-style-lint-typecheck/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Standards:

- Format code via `rye run format` or `./scripts/format`
- Lint via `rye run lint` or `./scripts/lint`
- Type check via `rye run typecheck` (pyright + mypy)

Guidance:

- Keep code readable and consistent; prefer small, focused functions
- Avoid introducing style or type violations; fix before committing

---
> Source: [scaleapi/scale-agentex-python](https://github.com/scaleapi/scale-agentex-python) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
