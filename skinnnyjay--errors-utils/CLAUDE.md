# errors-utils

> - **src/shared/** – AppError, error codes, serializeError; runtime-agnostic.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/errors-utils/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# @simpill/errors.utils – Agent guidelines

## Structure

- **src/shared/** – AppError, error codes, serializeError; runtime-agnostic.
- **src/client** and **src/server** – Re-export shared.
- **__tests__/shared/unit/** – Unit tests for all public APIs.

## Conventions

- Use AppError for domain/application errors; preserve code and meta when serializing.
- Keep shared code free of Node/browser APIs; 80%+ coverage; file size limit 400 lines.

## Commands

- `npm run build` – compile to `dist/`
- `npm test` / `npm run test:coverage` – run tests
- `npm run check:fix` – lint and format
- `npm run verify` – format, lint, typecheck, test, build

---
> Source: [SkinnnyJay/errors.utils](https://github.com/SkinnnyJay/errors.utils) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-12 -->
