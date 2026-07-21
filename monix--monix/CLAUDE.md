# monix

> This file contains mandatory rules for AI agents (Copilot, Claude, Cursor, etc.) working on this repository.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/monix/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Instructions for Monix

This file contains mandatory rules for AI agents (Copilot, Claude, Cursor, etc.) working on this repository.
**Any violation is a CI-breaking mistake!**

---

## Code rules

- Never workaround the compiler, make an effort to solve errors in an idiomatic way:
  - Avoid `asInstanceOf` downcasting, unless there's no other way (e.g., untagged union types in Scala 3).
  - `@nowarn` annotations, or other ways for supressing warnings/errors, are not permitted without the user's consent.
    - We fix warnings, we don't ignore them.
- Use package imports, instead of fully qualified names.
- Make an effort to write idiomatic, yet performant Scala code.

---
> Source: [monix/monix](https://github.com/monix/monix) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-20 -->
