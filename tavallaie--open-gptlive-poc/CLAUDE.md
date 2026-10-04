# open-gptlive-poc

> - Keep the implementation minimal: add the smallest public surface that solves the current slice.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/open-gptlive-poc/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Contribution guide

## Project principles

- Keep the implementation minimal: add the smallest public surface that solves the current slice.
- Prefer straightforward Python over abstractions that do not serve a current use case.
- Use small classes with one responsibility and inject collaborators through constructors or factories.
- Keep protocol and adapter boundaries explicit; the session layer must not import model libraries directly.
- Follow the spirit of the Zen of Python: readable, explicit, simple, and tested.

## Development rules

- Target Python 3.14 for local development; package compatibility starts at Python 3.12.
- Use `open_gptlive_poc` for Python imports and `open-gptlive-poc` for the distribution and CLI names.
- Keep secrets in environment variables or untracked local configuration. Never commit credentials or model weights.
- Prefer `unittest` for dependency-free tests unless a project dependency justifies another test framework.
- Run `git diff --check` and the relevant tests before committing.

---
> Source: [tavallaie/open-gptlive-poc](https://github.com/tavallaie/open-gptlive-poc) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-04 -->
