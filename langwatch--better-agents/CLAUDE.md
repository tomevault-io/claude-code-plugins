# typescript-strict-typing

> Enforce strict TypeScript typing without any types

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/typescript-strict-typing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# TypeScript Strict Typing

**Never use `any` type.** Use `unknown` for dynamic data, proper interfaces for complex objects, and specific union types for known value sets.

### Examples:
```typescript
// ❌ Bad
function processData(data: any) { ... }
const context: Record<string, any>;

// ✅ Good
type LogContext = Record<string, unknown>;
interface Config { language: string; framework: string; }
type Status = 'success' | 'error' | 'pending';
```

---
> Source: [langwatch/better-agents](https://github.com/langwatch/better-agents) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-17 -->
