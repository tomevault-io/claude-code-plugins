# imports

> Prefer @/mocks and @/utils; absolute imports; no wildcard imports

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/imports/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Imports

Applies to all import statements in TypeScript/JavaScript files. Prefer `@/` when the relative path goes up more than one level.

- When using mocks, prefer to use `@/mocks/...` import path instead of relative paths or other aliases.
- When using utils, prefer to use `@/utils/...` import path instead of relative paths or other aliases.
- Prefer absolute imports when the relative path goes up more than one folder level (e.g., `../../` should be converted to an absolute import like `@/...`).
- Prefer to import from barrel export files (e.g., `index.ts` or `index.tsx`) when available, rather than importing directly from individual files within the same directory.

### No Wildcard Imports

- Never use wildcard imports (`import * from`).
- Always use named imports for better tree-shaking, clarity, and IDE support.

- ✅ Good:
  ```typescript
  import { getScenariosDevelopmentsImages, orderScenarios } from '@/utils/scenarios'
  import { type ReactNode, useState } from 'react'
  ```

- ❌ Bad:
  ```typescript
  import * as scenarios from '@/utils/scenarios'
  import * as React from 'react'
  ```

---
> Source: [rcrdk/rcrdk.dev](https://github.com/rcrdk/rcrdk.dev) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-10 -->
