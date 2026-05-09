# components

> 1. Use Primevue components for all UI components.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/components/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Components

1. Use Primevue components for all UI components.
2. Use `<script setup lang="ts">` for all components.

## Structure

Use the following layout for every component to keep imports and growth consistent:

```text
ComponentName/
  ├─ index.ts           # Re-export (single public entry)
  ├─ Container.vue      # Main component implementation
  ├─ useForm.ts         # Optional: composable when logic grows (e.g. forms)
  └─ DependentComponent.vue
```

ComponentName/index.ts
```ts
export { default as ComponentName } from "./Container.vue";
```

When a child piece becomes complex or needs its own hook, use the same pattern as the parent:

```text
ComponentName/
  └─ DependentComponent/
       ├─ index.ts
       └─ Container.vue
```

---
> Source: [caido-community/authswap](https://github.com/caido-community/authswap) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-05 -->
