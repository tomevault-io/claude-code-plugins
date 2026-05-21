# project-context

> Project-wide context and constraints

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/project-context/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Project Context

Language: TypeScript (Node LTS)

Build: `tsc` -> `dist/`, templates bundled via `scripts/build-templates.ts`

Tests: Mocha + Sinon + Chai, coverage via `nyc`

Lint/format: ESLint + Prettier

Scripts:

- build
- clean
- lint
- test
- coverage

Runtime:

- Node LTS
- Do not import from `dist/`
- CLI entry: `./dist/index.js`

Referenced:
@src/index.ts
@scripts/build-templates.ts

---
> Source: [Sitecore/content-sdk](https://github.com/Sitecore/content-sdk) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
