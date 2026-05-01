# adr-examples-must-match-code

> Ensure ADR examples match implemented APIs.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/adr-examples-must-match-code/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# ADR examples must match real code

When adding or editing ADR examples:

- Prefer examples that are **copy/pasteable** and reflect the current API.
- Avoid inventing fluent helper syntax unless it already exists in the codebase.
- If you’re unsure, quickly search for the symbol/method before documenting it.

---
> Source: [prisma/prisma-next](https://github.com/prisma/prisma-next) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
