# workflow-py

> Before committing any changes, always run:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/workflow-py/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agents

## Linting and type checking

Before committing any changes, always run:

```
poetry run ruff format .
poetry run ruff check .
poetry run mypy --show-error-codes .
```

Fix all errors before committing. Do not commit code with unused imports, formatting issues, or type errors.

---
> Source: [upstash/workflow-py](https://github.com/upstash/workflow-py) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-04 -->
