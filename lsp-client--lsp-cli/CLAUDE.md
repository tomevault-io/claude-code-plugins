# lsp-cli

> - Lint & format: `ruff check --fix && ruff format`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/lsp-cli/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Development Commands

- Lint & format: `ruff check --fix && ruff format`
- Type checking: `ty check <dir_or_file>`
- Run tests: `uv run pytest`
- Sync latest deps: `uv sync --upgrade`

## Code Style Guidelines

- Python: 3.12+ required
- `attrs` for class definitions
- `anyio` and `asyncer` for async programming
- `typer` for cli, `rich` for printing

---
> Source: [lsp-client/lsp-cli](https://github.com/lsp-client/lsp-cli) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-17 -->
