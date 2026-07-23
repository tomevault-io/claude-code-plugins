# transformers-tutorials

> Use `uv` alongside the virtual environment when running Python scripts or notebooks.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/transformers-tutorials/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Python enviromnent

Use `uv` alongside the virtual environment when running Python scripts or notebooks.

When requiring environment variables, use:

```bash
uv run --env-file keys.env main.py
```

Do not edit the `pyproject.toml` file manually. Always use `uv add` to let uv add Python packages to the virtual environment.

---
> Source: [NielsRogge/Transformers-Tutorials](https://github.com/NielsRogge/Transformers-Tutorials) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-21 -->
