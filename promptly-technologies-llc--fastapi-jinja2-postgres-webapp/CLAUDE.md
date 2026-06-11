# general

> General guidelines

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/general/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

This project uses `uv` for dependency management. To add or remove a dependency, use `uv add <packagename>` or `uv remove <packagename>`. To update a dependency to the latest version, use `uv lock --upgrade-package <packagename>` For development dependencies, add the `--group dev` flag to these commands. Dependencies can be installed with `uv sync`.

When building out features, always keep changes atomic and make sure to write and run tests. To run tests, use:

```bash
uv run pytest tests   # or the path to a specific test file
```

All code should be rigorously type hinted so as to pass a static type check with `ty`. To run a `ty` check, use:

```bash
uv run ty check .
```

---
> Source: [Promptly-Technologies-LLC/fastapi-jinja2-postgres-webapp](https://github.com/Promptly-Technologies-LLC/fastapi-jinja2-postgres-webapp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-11 -->
