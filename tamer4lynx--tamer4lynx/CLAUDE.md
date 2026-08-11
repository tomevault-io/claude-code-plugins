# example-jsx-types

> How to add TypeScript types for custom native elements in the example package

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/example-jsx-types/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Custom Native Element Types in the Example Package

## The Problem

With `jsxImportSource: "@lynx-js/react"` in tsconfig, TypeScript resolves `JSX.IntrinsicElements` from the **module** `@lynx-js/react/jsx-runtime`, not from the global `JSX` namespace.

Using `declare global { namespace JSX { interface IntrinsicElements } }` silently fails — the type won't be recognized and the build will error.

## The Fix

In `src/rspeedy-env.d.ts`, use **module augmentation** targeting `@lynx-js/react/jsx-runtime`:

```typescript
// ❌ WRONG — global JSX namespace is not used with jsxImportSource
declare global {
  namespace JSX {
    interface IntrinsicElements {
      'my-element': { ... }
    }
  }
}

// ✅ CORRECT — augment the module TypeScript actually resolves
declare module '@lynx-js/react/jsx-runtime' {
  namespace JSX {
    interface IntrinsicElements {
      'my-element': { ... }
    }
  }
}
```

All custom native element types go in `packages/example/src/rspeedy-env.d.ts`.

---
> Source: [tamer4lynx/tamer4lynx](https://github.com/tamer4lynx/tamer4lynx) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-11 -->
