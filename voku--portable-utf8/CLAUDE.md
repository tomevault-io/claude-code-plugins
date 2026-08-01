# portable-utf8

> - Install project dependencies with `composer install` from the repository root.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/portable-utf8/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Setup

- Install project dependencies with `composer install` from the repository root.
- Install documentation generator dependencies with `composer install` from `build/`.

## Validation

- Run the test suite with `php vendor/bin/phpunit -c phpunit.xml`.

## Documentation

- `README.md` is generated. Do not edit the generated API section by hand.
- Regenerate it from the repository root with `php build/generate_docs.php`.
- The generator reads `build/docs/base.md` and `src/voku/helper/UTF8.php`.

## Notes

- Keep changes focused and minimal.
- When updating public UTF8 APIs, regenerate `README.md` if the API documentation changes.

---
> Source: [voku/portable-utf8](https://github.com/voku/portable-utf8) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
