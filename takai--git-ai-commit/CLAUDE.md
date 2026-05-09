# git-ai-commit

> - Follow the standard Go project layout.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/git-ai-commit/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Overview

## Directory Structure

- Follow the standard Go project layout.

## Documentation

- README.md – User guide

## Build Commands

- `make build` – Build the project
- `make test` – Apply fixes and format the code
- `make format` – Run tests

## Development Guidelines

- Use the red/green/refactor TDD cycle.
- After changing code, run `make format` and `make test`.
- Use `git ai-commit` to create commits.
  - Always include a short, clear summary in English using the `--context` option.

---
> Source: [takai/git-ai-commit](https://github.com/takai/git-ai-commit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
