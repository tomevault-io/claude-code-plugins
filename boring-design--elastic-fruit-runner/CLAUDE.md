# elastic-fruit-runner

> - `make build` — Build dashboard + Go binary to `output/`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/elastic-fruit-runner/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Notes

## Build

- `make build` — Build dashboard + Go binary to `output/`
- `make test` — Run all tests
- `make check` — Quick local check (fmt + vet + build)

## Pre-commit

- Run `prek run --all-files` before commits to execute all pre-commit hooks (formatting, linting, etc.)

## Conventions

- Error messages must include context (relevant values) and be descriptive enough to diagnose without source code

---
> Source: [boring-design/elastic-fruit-runner](https://github.com/boring-design/elastic-fruit-runner) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-04 -->
