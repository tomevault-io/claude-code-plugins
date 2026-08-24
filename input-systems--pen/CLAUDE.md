# pen-import-path-conventions

> Import path conventions for Pen source files

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pen-import-path-conventions/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Import Path Conventions

- In Pen source files, use clean extensionless imports for local and workspace paths.
- Do not add `.js`, `.ts`, `.tsx`, `.mjs`, or `.cjs` suffixes to relative TypeScript source imports.
- Prefer:
  - `./types`
  - `../utils/normalize`
  - `@pen/core`
- Avoid:
  - `./types.js`
  - `../utils/normalize.ts`
- Treat this as a source-authoring rule, not a blanket package rule.
- If an external package's documented API requires an explicit extension on a package subpath import, keep the package-required form instead of rewriting it.

---
> Source: [input-systems/pen](https://github.com/input-systems/pen) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-22 -->
