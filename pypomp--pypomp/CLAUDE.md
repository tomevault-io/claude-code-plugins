# pypomp

> Always activate the virtual environment before running tests or commands:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pypomp/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GEMINI.md

## Environment Setup
Always activate the virtual environment before running tests or commands:
```bash
source .venv/bin/activate
```

## Running Tests
To run all tests:
```bash
pytest
```
You may need to run `source .venv/bin/activate && pip install -e .` first to update the package in the environment.

DO NOT preemptively run tests at the beginning of a session. 
DO NOT run tests unless you have made edits to the code already. 
You can assume that the tests work at first unless the user explicitly tells you otherwise.

## Build and Package
This project uses `pypomp` as the main package.

---
> Source: [pypomp/pypomp](https://github.com/pypomp/pypomp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-03 -->
