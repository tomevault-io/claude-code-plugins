# koowerk

> Use import type whenever you are importing a type.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/koowerk/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

Use import type whenever you are importing a type.

Prefer top-level `import type` over inline `import { type ... }`.

```ts
// BAD
import { type User } from "./user";
```

```ts
// GOOD
import type { User } from "./user";
```

The reason for this is that in certain environments, the first version's import will not be erased. So you'll be left with:

```ts
// Before transpilation
import { type User } from "./user";

// After transpilation
import "./user";
```

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/ehoneahobed)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/ehoneahobed)
<!-- tomevault:4.0:claude_md:2026-04-08 -->
