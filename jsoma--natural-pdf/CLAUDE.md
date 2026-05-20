# natural-pdf

> - Use `uv run ...` for all Python project commands.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/natural-pdf/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Natural PDF Agent Instructions

## Command Policy

- Use `uv run ...` for all Python project commands.
- Do not invoke raw `python`, `pytest`, `black`, `isort`, `mypy`, or `nox`.
- Examples:
  - `uv run python -m pytest tests/test_ocr_cache.py`
  - `uv run pytest tests/ -x`
  - `uv run black --check natural_pdf tests`
  - `uv run nox -s lint`

## Local Context

- Package manager: `uv`
- Virtual environment: `.venv`
- Temp files go in `temp/`.
- Test files go in `tests/`.
- Prefer existing PDFs in `pdfs/` for tests.

---
> Source: [jsoma/natural-pdf](https://github.com/jsoma/natural-pdf) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-19 -->
