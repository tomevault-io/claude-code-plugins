# use-pathe-for-paths

> Prefer pathe over node:path in TypeScript files.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/use-pathe-for-paths/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Use pathe for path operations

Use `pathe` instead of `node:path` for path manipulation:

- Consistent behavior across Windows/macOS/Linux
- Works in non-Node runtimes (Deno, Bun, edge)
- Drop-in replacement with identical API

```typescript
// Good
import { dirname, join, resolve } from 'pathe';

// Avoid
import { dirname, join, resolve } from 'node:path';
```

---
> Source: [prisma/prisma-next](https://github.com/prisma/prisma-next) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
