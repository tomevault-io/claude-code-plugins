# stacksafe

> Use `cargo x` as the source of truth for repository workflows.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/stacksafe/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Instructions

## Cargo XTask

Use `cargo x` as the source of truth for repository workflows.

- Run `cargo x --help` before choosing build, test, lint, or formatting commands.
- Run `cargo x <command> --help` for command-specific behavior.

## Commits and Pull Requests

Follow the semantic definition at `.github/semantic.yml`.

- Keep title descriptions short.
- Simple PR descriptions should only include a `Summary` section.
- Complex PR descriptions may also include a `Design Notes` section.

---
> Source: [fast/stacksafe](https://github.com/fast/stacksafe) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-08 -->
