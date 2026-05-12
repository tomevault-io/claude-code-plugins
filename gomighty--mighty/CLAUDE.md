# mighty

> Before finishing your work, you must run the FULL verification suite below.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mighty/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

Before finishing your work, you must run the FULL verification suite below.

```sh
pnpm build                              # Build all packages (required before test/typecheck)
pnpm run typecheck                      # Typecheck
pnpm run ci:biome                       # Format + lint check
pnpm test                               # Run tests
```

If issues arise, fix the issues and run the FULL verification suite again. Repeat this process until the ENTIRE suite passes.

Use the following command to fix format and lint issues.

```sh
  pnpm exec biome check --write <files>   # Format + lint fix
```

---
> Source: [gomighty/mighty](https://github.com/gomighty/mighty) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-07 -->
