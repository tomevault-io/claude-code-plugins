# pyrefly-bzl

> All agents must follow the project contribution guidelines in [`CONTRIBUTING.md`](CONTRIBUTING.md).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pyrefly-bzl/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository instructions

All agents must follow the project contribution guidelines in [`CONTRIBUTING.md`](CONTRIBUTING.md).

## Starlark

- Preserve depsets through analysis and avoid `depset.to_list()` in production code. Prefer
  depset-aware APIs such as `Args.add_all`; only flatten a depset when an API genuinely requires
  materialized values, such as test assertions.

## Formatting and linting

- Format supported files with `bin/format.sh`.
- Run `bin/lint.sh` and resolve all findings.
- Run all tests with `bin/test.sh`.

---
> Source: [canva-public/pyrefly.bzl](https://github.com/canva-public/pyrefly.bzl) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-28 -->
