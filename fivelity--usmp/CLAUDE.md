# 05-code-practices-quality

> General coding standards (readability, comments, type hinting, linting, error handling).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/05-code-practices-quality/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# 05-code-practices-quality

## Code Practices & Quality

STRICT REQUIREMENT:
- Readability & Maintainability: Use clear, concise, well-commented code.
- Type Hinting: Use Python type hints and TypeScript interfaces extensively.
- Linting & Formatting: Follow `flake8` and `black` for Python; `eslint` and `prettier` for TypeScript/Svelte.
- Error Handling: Implement try/catch for JavaScript and try/except for Python.
- Avoid Early Returns: Print error messages instead of exiting early.
- Firestore Querying: Avoid `orderBy()`—fetch and sort in memory.

---
> Source: [fivelity/usmp](https://github.com/fivelity/usmp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-31 -->
