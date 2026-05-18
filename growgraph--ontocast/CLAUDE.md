# tests

> Testing guidelines

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tests/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Testing Guidelines
- Use `pytest` with descriptive test function names.
- Prefer fixtures over global state.
- For async code, use `pytest-asyncio`.
- Ensure test coverage for:
  - Pydantic model validation
  - Env config via `BaseSettings`
  - Error cases and edge cases
- Run tests with `uv run pytest test`.

---
> Source: [growgraph/ontocast](https://github.com/growgraph/ontocast) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
