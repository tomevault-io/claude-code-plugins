# typescript-style

> TypeScript style — prefer arrow functions and consistent callbacks

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/typescript-style/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# TypeScript style

Follow **`eslint.config.mjs`** (Airbnb + TypeScript + Prettier) first; this file only adds **arrow-function** preferences for the AI.

- **Named / exported helpers:** Prefer `const fn = (): ReturnType => { ... }` over `function fn() { ... }`, unless hoisting is required, you need `function` for `this`/`arguments`, or the file already uses a pattern you must match in a tiny edit.
- **Callbacks:** Use arrow functions — e.g. `.map((x) => ...)`, `promise.then((v) => ...)`, `array.filter((item) => ...)`. Avoid `function` callbacks unless the API requires a non-arrow receiver.
- **Inline handlers:** Prefer `(args) => { ... }` for tool `execute`, event handlers, and similar.
- **Consistency:** When touching existing code, prefer arrows for **new** lines; do not rewrite an entire file only to switch declaration style unless the user asks.

---
> Source: [bobbylkchao/ai-phone-agent](https://github.com/bobbylkchao/ai-phone-agent) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-05 -->
