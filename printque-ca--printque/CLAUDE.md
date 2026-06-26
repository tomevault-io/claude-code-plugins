# verify-before-done

> Require CI-equivalent checks to pass before marking work as completed

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/verify-before-done/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Verify Before Done

Before declaring any task complete, run the relevant CI checks locally and confirm they pass.

## CI checks (from `.github/workflows/ci.yml`)

| Check | Command | When to run |
|-------|---------|-------------|
| Python lint | `ruff check api/` | After editing any `api/**/*.py` file |
| Backend tests | `cd api && pytest` | After editing any `api/**/*.py` file |
| TypeScript type check | `cd app && npx tsc --noEmit` | After editing any `app/**/*.{ts,tsx}` file |
| Frontend tests | `cd app && npm run test` | After editing any `app/**/*.{ts,tsx}` file |

## Rules

- Run **all** checks that apply to the files you changed — not just one.
- If a check fails, fix the issue before marking the task complete.
- Do not skip checks to save time. A failing CI pipeline is worse than a slow response.

---
> Source: [PrintQue-ca/PrintQue](https://github.com/PrintQue-ca/PrintQue) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-26 -->
