# slim

> Prefer JSDoc block comments over line comments

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/slim/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Comment style

Use JSDoc-style block comments (`/** */`) for explanatory comments in application and library source. Do not use `//` line comments for explanations.

```js
// ❌ BAD
// Re-open the XHR and restore headers before retrying.
request.open(method, url, true)

// ✅ GOOD
/** Re-open the XHR and restore headers before retrying. */
request.open(method, url, true)
```

Multi-line:

```js
/**
 * When Range is ignored, complete from the buffered body instead of
 * appending — otherwise coordinates duplicate and the loop never ends.
 */
```

Exceptions (keep `//`):
- Tooling directives: `eslint-disable`, `@ts-expect-error`, `biome-ignore`, `prettier-ignore`
- Temporarily commented-out code
- Shebang lines

Public APIs should still use proper JSDoc tags (`@param`, `@returns`, etc.) inside `/** */`.

---
> Source: [ImagingDataCommons/slim](https://github.com/ImagingDataCommons/slim) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-16 -->
