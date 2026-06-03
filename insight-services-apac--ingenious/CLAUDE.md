# ingenious

> This project uses uv for Python package and environment management.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ingenious/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Package Management: uv

This project uses uv for Python package and environment management.

## Common Commands
- **Run a command in the project environment:**
  `uv run <command>`

- **Add a dependency:**
  `uv add <package>` or `uv add <package> --dev` for dev dependencies

- **Remove a dependency:**
  `uv remove <package>` or `uv remove <package> --group dev` for dev dependencies

- **List out packages in environment in a tree structure**
  `uv tree`

- **Run tests (run after implementing changes to ensure nothing broke):**
  `uv run pytest`

## Note

- Do **not** use `pip` or `pip-tools` directly; use `uv` commands above.

---
> Source: [Insight-Services-APAC/ingenious](https://github.com/Insight-Services-APAC/ingenious) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-03 -->
