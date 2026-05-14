# typescript

> - `tsconfig.json` is strict; avoid `any` and prefer precise types

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/typescript/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

- `tsconfig.json` is strict; avoid `any` and prefer precise types
- Prefer `interface` for object shapes that will be extended; use `type` for unions and mapped types
- Derive types from data/validators (e.g., `z.infer<typeof schema>`) to ensure parity
- Use descriptive names (e.g., `isLoading`, `hasError`); avoid abbreviations
- Keep functions small with early returns and clear error handling
- Respect `@/*` alias for imports; avoid deep relative import chains

---
> Source: [Saksham-Goel1107/Dionysus](https://github.com/Saksham-Goel1107/Dionysus) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-13 -->
