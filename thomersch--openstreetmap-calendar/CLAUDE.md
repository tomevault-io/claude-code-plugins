# openstreetmap-calendar

> This project uses [devbox](https://www.jetify.com/devbox). `devbox shell` is

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/openstreetmap-calendar/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Development environment

This project uses [devbox](https://www.jetify.com/devbox). `devbox shell` is
interactive-only and `devbox run --` doesn't reliably forward arbitrary
commands, so for non-interactive use (agents, scripts), load the devbox
environment into the current shell first:

eval "$(devbox shellenv)" && ./manage.py test osmcal.test_views

This puts `.venv/bin`, GDAL/GEOS, and postgres on PATH for the rest of the
command.

# Linting

Run ruff before considering Python changes done:

eval "$(devbox shellenv)" && ruff check . && ruff format --check .

---
> Source: [thomersch/openstreetmap-calendar](https://github.com/thomersch/openstreetmap-calendar) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
