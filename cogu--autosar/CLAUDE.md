# autosar

> Use the virtual environment in .venv for running unit test and flake8 check.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/autosar/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Test and verification

Use the virtual environment in .venv for running unit test and flake8 check.

Running unit tests:

```bash
python -m unittest discover -v tests test_*.py
```

Checking changes with flake:

```bash
flake8 --max-line-length=120 --extend-ignore=D107,D200,D205,D400,D401 src
flake8 --max-line-length=120 --extend-ignore=D101,D102,D107,D200,D205,D400,D401,E402 tests
flake8 --max-line-length=120 --extend-ignore=D107,D200,D205,D400,D401 examples
flake8 --max-line-length=120 --extend-ignore=D107,D200,D205,D400,D401 dev_utils
```

Running pylint:

```bash
pylint src
```

# Updating enumeration.py

The entries of the enum IdentifiableSubTypes should be kept sorted.

---
> Source: [cogu/autosar](https://github.com/cogu/autosar) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-13 -->
