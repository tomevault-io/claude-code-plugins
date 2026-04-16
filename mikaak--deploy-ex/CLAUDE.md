# deploy-ex

> Testing conventions for the DeployEx codebase

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/deploy-ex/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Testing Rules

## General
- Run tests from the application directory, never from the umbrella root.
- Treat compiler warnings as errors; test output must be clean.
- Use `refute` instead of `assert` when asserting something is not true.

## Data setup
- Use `FactoryEx` for database insertions and building test schemas.
- Avoid mocking libraries; prefer real modules and fixture files.
- Never use `Application.put_env` in tests.

## Fixtures
- Keep fixture files (e.g., mix deps tree output, lock file diffs) up to date when parser logic changes.
- Add new fixtures when introducing new parsing rules.

## Conventions
- Keep tests aligned with `{:ok, _}` / `{:error, ErrorMessage}` return conventions.
- When a test fails, determine whether the code or the test is correct before choosing what to fix.
- Always run tests after writing them.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/MikaAK) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-13 -->
