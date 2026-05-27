# cloudflare-worker-rules

> - ## 1. Syntax Restrictions

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cloudflare-worker-rules/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Your rule content
- ## 1. Syntax Restrictions
- **No Template Strings**: Must use string concatenation (e.g., `"a" + b + "c"`) instead of template literals, as the environment may not support ES6 features [[User Rule]].
- **Avoid ES6+ Syntax**: For compatibility, it is recommended to use ES5 syntax (e.g., `var` instead of `let/const`, function expressions instead of arrow functions) [[4]].

---
> Source: [Cunninger/grok-remain-count](https://github.com/Cunninger/grok-remain-count) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-27 -->
