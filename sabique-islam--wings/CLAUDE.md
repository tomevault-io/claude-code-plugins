# testing

> Playwright E2E and Vitest editor test conventions

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/testing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Testing rules

- Vitest for wiring/schema; Playwright for keyboard and DOM (Enter, slash, caret).
- E2E: dismiss cookie banner via `focusEditor()` before typing.
- Use `/__editor-e2e` harness; assert parity test IDs when testing serialize path.
- Slash menu in E2E: click menu buttons, not Enter alone.
- CI: `bun run test:ci` with frozen lockfile and Playwright chromium install.

---
> Source: [sabique-islam/wings](https://github.com/sabique-islam/wings) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-22 -->
