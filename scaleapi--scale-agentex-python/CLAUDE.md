# 50-tests-and-mocking

> Testing workflow and mock server details

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/50-tests-and-mocking/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Testing:

- Run tests with `rye run pytest` or `./scripts/test`
- To run a specific test: `rye run pytest path/to/test_file.py::TestClass::test_method -v`
- A mock server is automatically started for tests on port 4010

When writing tests:

- Prefer deterministic unit tests that do not depend on external services
- Use the mock server and fixtures provided in the repository

---
> Source: [scaleapi/scale-agentex-python](https://github.com/scaleapi/scale-agentex-python) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
