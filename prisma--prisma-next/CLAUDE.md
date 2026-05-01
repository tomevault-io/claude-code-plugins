# cli-test-fixture-cleanup

> Avoid committing generated CLI test fixtures

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cli-test-fixture-cleanup/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# CLI Test Fixture Cleanup

## Key points

- Treat `test-*/` directories under fixture apps as ephemeral test output.
- Keep gitignore patterns in sync for fixture apps to avoid committing generated artifacts.
- Cleanup logic in tests should remove temporary directories after each run.

---
> Source: [prisma/prisma-next](https://github.com/prisma/prisma-next) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
