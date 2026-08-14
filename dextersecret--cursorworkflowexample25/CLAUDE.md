# auth

> Follow these rules when working on auth.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/auth/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Auth Rules

Follow these rules when working on auth.

It uses Clerk for authentication.

## General Rules

- Import the auth helper with `import { auth } from "@clerk/nextjs/server"` in server components
- await the auth helper in server action

---
> Source: [dextersecret/cursorWorkflowExample25](https://github.com/dextersecret/cursorWorkflowExample25) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-14 -->
