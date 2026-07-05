# react

> React.js Best Practices

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/react/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# React Best Practices

Use functional components and hooks for state management.
Ensure components are reusable and maintainable.
Prefer React Server Components for fetching data.
Prefer server actions over API requests for mutating data.
Maintain a separation of concerns between client and server components.

Prefer arrow functions for React components:
✅ export const Component = () => { ... }
❌ export function Component() { ... }
❌ export default function Component() { ... }

---
> Source: [lacymorrow/paperclip-hub](https://github.com/lacymorrow/paperclip-hub) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-04 -->
