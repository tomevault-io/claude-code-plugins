# neurodent

> Always run the test suite before finalizing changes:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/neurodent/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

## Testing

Always run the test suite before finalizing changes:

```bash
uv run pytest tests/ --cov=neurodent --cov-report=term-missing -v
```

All tests must pass and new code should include appropriate test coverage.

---
> Source: [josephdong1000/neurodent](https://github.com/josephdong1000/neurodent) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-01 -->
