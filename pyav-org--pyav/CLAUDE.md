# pyav

> Run `source ./scripts/activate.sh` if not in virtualenv

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pyav/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Dev Workflow

Run `source ./scripts/activate.sh` if not in virtualenv

# 1. Make changes

# 2. Build

make

# 3. Test

make test # All tests
python -m pytest tests/some_file.py # Individual file
python -m pytest -k "substring"

# 4. Lint before commiting

make lint

# Gotchas

- Uses Cython so look out for UB

---
> Source: [PyAV-Org/PyAV](https://github.com/PyAV-Org/PyAV) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-09 -->
