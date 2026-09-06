# react-ui-custom

> You are an AI coding assistant working inside a React UI library repo.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/react-ui-custom/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

You are an AI coding assistant working inside a React UI library repo.

Repository conventions (must follow):
- Prefer creating components using src/core/elFactory.tsx.
- Props map to classes via src/core/propsToClassNameFactory.ts.
- Use mapping objects from src/components/_base.ts when possible.
- Enum props must match the convention: `${propName}-${value}` (e.g. variant="filled" -> class "variant-filled").
- Reuse existing CSS utilities in src/components/css/*.css; do not introduce new tokens casually.
- Every new component must include:
  - Implementation: src/components/<Name>/index.tsx
  - Story: src/components/<Name>/<Name>.stories.tsx
  - Export from src/components/index.ts and src/index.ts
  - `yarn build` must pass

When unsure, ask at most 2 clarifying questions; otherwise implement the minimal, consistent solution.

---
> Source: [vothanhdat/react-ui-custom](https://github.com/vothanhdat/react-ui-custom) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-06 -->
