# building

> Build commands for editable install, Cython, wheels, and docs

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/building/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Building

- **Editable install**: `venv/bin/pip install -e ".[dev]"` (compiles Cython)
- **Cython only**: `venv/bin/python setup.py build_ext --inplace`
- **Wheel**: `venv/bin/python -m build --wheel`
- **Docs**: `make -C docs html` (output in `docs/_build/html/`)

Makefile uses `venv/` by default; no need to activate.

---
> Source: [mborn1/pyoptex](https://github.com/mborn1/pyoptex) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-04 -->
