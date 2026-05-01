# test-import-patterns

> Test import patterns and conventions

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/test-import-patterns/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Test Import Patterns

This rulecard is intentionally short. For more examples, see `docs/reference/test-import-patterns.md`.

## Within-package tests

- **Import from source** (`../src/...`), not from package exports.

## Cross-package / integration tests

- **Import from package exports** (`@prisma-next/...`) to verify the public API.

## Related rules

- `.cursor/rules/test-file-organization.mdc`
- `.cursor/rules/test-fixture-typechecking.mdc`

---
> Source: [prisma/prisma-next](https://github.com/prisma/prisma-next) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
