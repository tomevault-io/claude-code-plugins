# writing-tests

> Writing tests with Bun

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/writing-tests/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Writing tests (Bun)

- Prefer adding tests near the code you changed (co-located) before creating new suites.
- For bug fixes: add a failing test first, then implement the fix.
- Keep tests deterministic: avoid real network calls; prefer fixtures/mocks.
- Run tests in the relevant workspace (or repo root) with `bun test` / `bun run test` where available.

---
> Source: [nech-ai/proxed](https://github.com/nech-ai/proxed) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-29 -->
