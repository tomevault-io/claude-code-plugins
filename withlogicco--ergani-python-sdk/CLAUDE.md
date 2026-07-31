# ergani-python-sdk

> - Before handing work over, run autofixable checks first. Use `uv run ruff format && uv run ruff check --fix`, then verify with `uv run ruff format --check && uv run ruff check`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ergani-python-sdk/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Instructions

- Before handing work over, run autofixable checks first. Use `uv run ruff format && uv run ruff check --fix`, then verify with `uv run ruff format --check && uv run ruff check`.
- For Python test validation in this repo, use `PYTHONPATH=$PWD uv run --no-project --with requests python3 -m unittest discover -s tests`.

---
> Source: [withlogicco/ergani-python-sdk](https://github.com/withlogicco/ergani-python-sdk) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
