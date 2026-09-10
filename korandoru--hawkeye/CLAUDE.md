# hawkeye

> Use `cargo x` as the source of truth for repository workflows.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/hawkeye/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Instructions

## Cargo XTask

Use `cargo x` as the source of truth for repository workflows.

- Run `cargo x --help` before choosing build, test, lint, or formatting commands.
- Run `cargo x <command> --help` for command-specific behavior.

## Markdown Style

- Keep each prose paragraph and list item on one source line.
- Pad table cells with spaces to align columns in the Markdown source.

## Commits and Pull Requests

Follow the semantic definition at `.github/semantic.yml`.

- Keep title descriptions short.
- Simple PR descriptions should only include a `Summary` section.
- Complex PR descriptions may also include a `Design Notes` section.

---
> Source: [korandoru/hawkeye](https://github.com/korandoru/hawkeye) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-09 -->
