# core-principles

> Core development principles for all code

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/core-principles/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Core Development Principles

- **NEVER DUPLICATE CODE** - Edit in place, never create new versions
- **NO PLACEHOLDERS** - Fix existing placeholders or fail with error
- **SEARCH BEFORE ADDING** - Check for existing code before creating new functions/constants
- **NEVER IGNORE TESTS** - Don't reduce assertions to make tests pass, fail loudly
- **KEEP ALL FILES UNDER 500 LOC** - Break large files into focused modules  
- **NEVER COMMIT/PUSH** unless explicitly requested
- **FOLLOW STATIC ANALYSIS** - Pay attention to linters and fix issues
- **MOVE FILES, DON'T COPY** - Use CLI commands to move files
- **NO SWEARING IN CODE** - Keep code professional
- **USE CONSTANTS** - Name values meaningfully instead of using literals
- **SEARCH BEFORE ADDING** - Check for existing code before creating new functions/constants

---
> Source: [MelbourneDeveloper/osprey](https://github.com/MelbourneDeveloper/osprey) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
