# glossary-page-template

> This project provides a single HTML page with a built-in editor for creating a glossary that can be hosted anywhere.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/glossary-page-template/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Glossary Page Template Overview

This project provides a single HTML page with a built-in editor for creating a glossary that can be hosted anywhere.

## Testing instructions

- Use `./node_modules/.bin/elm-test --compiler ./node_modules/.bin/elm` to run the Elm-based tests under `tests/`.
- Use `./node_modules/.bin/elm-verify-examples --compiler ./node_modules/.bin/elm --run-tests` to verify examples in documentation strings.
- Fix any test or type errors until the whole suite is green.
- Add or update tests for the code you change, even if nobody asked.

---
> Source: [hilverd/glossary-page-template](https://github.com/hilverd/glossary-page-template) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-29 -->
