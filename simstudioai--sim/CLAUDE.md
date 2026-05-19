# sim-typescript

> TypeScript conventions and type safety

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/sim-typescript/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# TypeScript Rules

1. **No `any`** - Use proper types or `unknown` with type guards
2. **Props interface** - Always define for components
3. **Const assertions** - `as const` for constant objects/arrays
4. **Ref types** - Explicit: `useRef<HTMLDivElement>(null)`
5. **Type imports** - `import type { X }` for type-only imports

```typescript
// ✗ Bad
const handleClick = (e: any) => {}

// ✓ Good
const handleClick = (e: React.MouseEvent<HTMLButtonElement>) => {}
```

---
> Source: [simstudioai/sim](https://github.com/simstudioai/sim) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
