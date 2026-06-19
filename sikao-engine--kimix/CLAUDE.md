# kimix

> - After writing any Python file, run `uv run tools/syntax_check.py <python_file> [<python_file> ...]` to verify python syntax.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/kimix/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Rules:

- After writing any Python file, run `uv run tools/syntax_check.py <python_file> [<python_file> ...]` to verify python syntax.
- Fix all errors reported by the syntax checker before proceeding.
- use `uv run tools/git_diff.py <file> [<file> ...]` to check file diff.
- use `uv sync --extra=all` after update any `pyproject.toml` to verify the changes.

---
> Source: [Sikao-Engine/KimiX](https://github.com/Sikao-Engine/KimiX) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-19 -->
