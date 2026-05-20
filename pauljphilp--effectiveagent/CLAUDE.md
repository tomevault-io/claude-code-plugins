# typescript-best-practices

> // ... existing code ...

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/typescript-best-practices/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# TypeScript Best Practices

## Type System
// ... existing code ...

## Spread Operator Type Safety
- Use `Parameters<typeof functionName>` for typing spread arguments
- Apply type assertions when slicing argument arrays
- Avoid raw spread of untyped arrays
- Ensure spread arguments match function parameter types

// ... existing code ... 

---
> Source: [PaulJPhilp/EffectiveAgent](https://github.com/PaulJPhilp/EffectiveAgent) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
