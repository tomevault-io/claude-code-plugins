# aleph

> Aleph is a Python CLI for capturing Google Street View photos, satellite imagery, and OSM data for AI agents. It requires no browser or API key.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/aleph/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Project

Aleph is a Python CLI for capturing Google Street View photos, satellite imagery, and OSM data for AI agents. It requires no browser or API key.

- `aleph.py`: command-line entry point
- `src/`: capture, networking, geometry, Street View, and terrain code
- `tests/`: unit tests
- `README.md`: setup, usage, and troubleshooting.
- `resources/`: assets and resources

## Changes

- Keep the CLI minimal and simple
- Completely ignore backward compatibility
- Avoid excessive testing, test what matters only

## Validation

- Run `python -m unittest discover -s tests -v` after Python changes

---
> Source: [Belluxx/Aleph](https://github.com/Belluxx/Aleph) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
