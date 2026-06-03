# testing

> RaQuet Help

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/testing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


- This is a Python project
- Expect that a virtualenv .venv directory already exists and use it when it does
- The raquet module and requirements are described in pyproject.toml
- When we run tests in this project, we use pytest with this command: `python -m pytest -m "not integration"`
- The project linter is ruff, new commits should always pass lint:
    - `python -m ruff check raquet/*.py tests/*.py`
    - `python -m ruff format raquet/*.py tests/*.py`

---
> Source: [CartoDB/raquet](https://github.com/CartoDB/raquet) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-03 -->
