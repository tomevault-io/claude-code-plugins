# valueos

> **Paths:** `src/tools/*` & `src/services/tools/*`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/valueos/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Tool Libraries

**Paths:** `src/tools/*` & `src/services/tools/*`

- Tools must implement `Tool<TInput, TOutput>` interface
- Register in `ToolRegistry.ts` (dynamic creation FORBIDDEN)
- Check `LocalRules` (LR-001) before execution
- External API tools MUST use `RateLimiter` middleware

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/Valynt) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-10 -->
