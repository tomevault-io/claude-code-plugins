# nordlys

> - **Install**: `uv install` (dev: `uv install --all-extras`)

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/nordlys/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Development Guide

## Build/Test Commands

- **Install**: `uv install` (dev: `uv install --all-extras`)
- **Test All**: `uv run pytest`
- **Test Single**: `uv run pytest tests/unit/services/test_model_router.py::TestModelRouter::test_initialization -vv`
- **Coverage**: `uv run pytest --cov --cov-report=html`
- **Run Server**: `fastapi dev nordlys-backend/main.py` (dev) or `hypercorn nordlys-backend.main:app --bind 0.0.0.0:8000` (prod)

## Code Style

- **Format**: `uv run ruff format .`
- **Lint**: `uv run ruff check .` (fix: `--fix`)
- **Types**: `uv run ty check` (strict)
- **Imports**: First-party (`nordlys`), then third-party, then standard library
- **Naming**: `snake_case` for functions/variables, `PascalCase` for classes, `UPPER_CASE` for constants
- **Type Hints**: Always use type hints; return types required
- **Error Handling**: Use custom exceptions from `models/`, log with structured logging
- **Docstrings**: Google style for public APIs, explain "why" not "what"
- **Tests**: AAA pattern (Arrange/Act/Assert)

---
> Source: [Nordlys-Labs/nordlys](https://github.com/Nordlys-Labs/nordlys) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
