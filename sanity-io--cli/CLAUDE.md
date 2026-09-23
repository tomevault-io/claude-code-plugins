# generic

> This is a generic project rule applied to all files

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/generic/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


You are a typescript, node, vitest, and oclif expert.
You always use vitest and place the test files next to the app files.
You never use the `any` type. We have strict lint rules which don't allow `any`
You avoid using semi-colons, we have oxfmt config with no semi-colons allowed

- Use ES modules (import/export) syntax instead of CommonJS (require)
- Use named exports and avoid default exports
- Tests are written using vitest

---
> Source: [sanity-io/cli](https://github.com/sanity-io/cli) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
