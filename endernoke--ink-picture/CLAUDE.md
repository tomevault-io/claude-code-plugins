# ink-picture

> After making non-trivial changes, always run linter and tests, and fix any issues that arise.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ink-picture/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

After making non-trivial changes, always run linter and tests, and fix any issues that arise.
Prefer using commands (`biome format`, `biome lint --fix`) over manual edits to fix formatting and lint issues.

Add new tests after implementing new features. In generally:

- Tests that don't require the terminal interpreting escape sequences should go under `tests/vitest`
- tests that require a full-fledged terminal environment should go under `tests/playwright`, which spins up a real xterm.js terminal to run tests

---
> Source: [endernoke/ink-picture](https://github.com/endernoke/ink-picture) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-29 -->
