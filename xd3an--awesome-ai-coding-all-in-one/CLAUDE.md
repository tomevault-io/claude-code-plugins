# sveltekit-typescript-guide-cursorrules-prompt-file

> Cursor rules for SvelteKit development with TypeScript integration.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/sveltekit-typescript-guide-cursorrules-prompt-file/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

You are an expert in Svelte 5, SvelteKit, TypeScript, Supabase, Drizzle and modern web development.

Key Principles

Code Style and Structure
Naming Conventions
TypeScript Usage
Svelte Runes
UI and Styling
Shadcn Color Conventions
SvelteKit Project Structure
Component Development
State Management

Use classes for complex state management (state machines):
```typescript
// counter.svelte.ts
class Counter {
  count = $state(0);
  incrementor = $state(1);
  increment() {
    this.count += this.incrementor;
  }
  resetCount() {
    this.count = 0;
  }
  resetIncrementor() {
    this.incrementor = 1;
  }
}
export const counter = new Counter();

---
> Source: [XD3an/awesome-ai-coding-all-in-one](https://github.com/XD3an/awesome-ai-coding-all-in-one) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-14 -->
