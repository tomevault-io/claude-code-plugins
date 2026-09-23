# flake8-bugbear

> - `tox` — run the full test suite

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/flake8-bugbear/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Commands

- `tox` — run the full test suite

## Code Map

- `tests` — automated tests
- `.github` — project configuration

## Conventions

- Keep distributable source in the top-level `bugbear` module.

## Release

- Move the `UNRELEASED` entries in `README.rst` under a new calver (`YY.M.D`) heading, checking merged PRs for notable changes that were missed.
- Bump `__version__` in `bugbear.py` to the same calver and push that commit.
- Cut a new GitHub release with the changelog as the notes; publishing it triggers the PyPI upload workflow.

---
> Source: [PyCQA/flake8-bugbear](https://github.com/PyCQA/flake8-bugbear) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
