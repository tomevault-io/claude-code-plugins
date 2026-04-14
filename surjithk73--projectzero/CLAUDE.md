# projectzero

> name: typescript-best-practices.mdc

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/projectzero/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

---
name: typescript-best-practices.mdc
description: TypeScript coding standards and type safety guidelines
globs: **/*.{ts,tsx}
---

- Always use `"strict": true` in `tsconfig.json` for **strict type checking**.
- Prefer **interfaces over types** for better extensibility.
- Use **type guards and assertions** for runtime type checking.
- Implement **proper type inference** to reduce unnecessary annotations.
- Use **utility types** like `Partial<>`, `Readonly<>`, and `Pick<>` effectively.
- Avoid using `any`; use `unknown` or `never` where appropriate.
- Enforce **consistent function signatures** and avoid overloading when possible.
- Prefer **readonly properties** to prevent accidental mutations.
- Use `Record<K, V>` and `Mapped Types` for flexible data structures.
- Utilize **strict null checks** (`strictNullChecks: true`) to prevent runtime errors.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/Surjithk73)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/Surjithk73)
<!-- tomevault:4.0:claude_md:2026-04-09 -->
