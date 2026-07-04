# native-errors

> TypeScript error handling with nostics in the native app

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/native-errors/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# TypeScript errors — use `nostics`

Define and report user-facing errors through **`nostics`** in `apps/native/src/lib/errors.ts`.

- Add diagnostic codes, titles, suggestions, and `defineDiagnostics` entries there — not ad hoc strings in components.
- Import `diagnostics` (or helpers like `getRebuildErrorTitle`) from `@/lib/errors` when surfacing errors in UI.
- Rust-side errors exposed to the frontend should map to stable codes that have entries in `errors.ts`.

```typescript
// ❌ BAD — one-off error copy in a component
toast.error("Something went wrong with the provider");

// ✅ GOOD — structured diagnostic
import { diagnostics, DIAGNOSTIC_CODES } from "@/lib/errors";
diagnostics.report(DIAGNOSTIC_CODES.EVOLVE_NO_PROVIDER);
```

---
> Source: [darkmatter/nixmac](https://github.com/darkmatter/nixmac) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-04 -->
