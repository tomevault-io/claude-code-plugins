# office-stamper

> This document contains guidelines specific to the Office-stamper engine. For general Java coding standards, naming

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/office-stamper/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Office-stamper Specific Guidelines

This document contains guidelines specific to the Office-stamper engine. For general Java coding standards, naming
conventions, and testing principles, refer to the root [.junie/AGENTS.md](../../.junie/AGENTS.md).

## Project-Specific Details

### Dependencies

- Modules should never depend on test artifacts (e.g., `test-jar`) from other modules. Shared test utilities should be
  moved to the main source set of an appropriate module (e.g., `asciidoc` or `utils`).

---
> Source: [verronpro/office-stamper](https://github.com/verronpro/office-stamper) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-09 -->
