# data-formulator

> - Always use `uv` instead of `pip` for installing packages (e.g. `uv pip install`, `uv pip install -e .`).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/data-formulator/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Instructions

## Python Environment

- Always use `uv` instead of `pip` for installing packages (e.g. `uv pip install`, `uv pip install -e .`).
- Use `uv run` to execute Python scripts and modules (e.g. `uv run python script.py`, `uv run pytest`).
- The virtual environment is at `.venv/`. Activate it with `source .venv/bin/activate` if needed.
- The Python source is under `py-src/`. The project is installed in editable mode via `uv pip install -e .`.

---
> Source: [microsoft/data-formulator](https://github.com/microsoft/data-formulator) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-01 -->
