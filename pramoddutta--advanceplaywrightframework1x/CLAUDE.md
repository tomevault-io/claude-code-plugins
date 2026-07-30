# test-quality-checks

> Enforce typecheck + lint after every test change

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/test-quality-checks/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Test Quality Checks

After ANY change in `src/tests/**`, you MUST run:

```bash
npm run typecheck
npm run lint
```

Both must pass (exit 0). Do not report work complete until verified.

## Test conventions

- Tag every test: `@p0`, `@p1`, `@e2e`, `@smoke`, or `@lor`.
- No `test.only` / `test.skip` without ticket reference.
- Page Object Model — no raw selectors in specs.
- Use `logger` from `@utils/logger` instead of `console.log`.
- Use path aliases (`@pages`, `@utils`, etc.) — no `../../../` imports.

---
> Source: [PramodDutta/AdvancePlaywrightFramework1x](https://github.com/PramodDutta/AdvancePlaywrightFramework1x) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-29 -->
