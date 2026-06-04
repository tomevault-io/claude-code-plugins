# typescript

> **Description**: Guidelines for TypeScript usage and type safety

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/typescript/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# TypeScript

**Description**: Guidelines for TypeScript usage and type safety

## General

- Define proper types for all variables and functions
- Use type inference when types are obvious
- Use .tsx extension for React components
- Use .ts extension for non-React files
- Define proper types for operations:
  - ✓ `type GetTasks = QueryFn<void, Task[]>`
  - ✓ `type CreateTask = ActionFn<{ description: string }, Task>`

## Type Definitions

- Place shared types in the same file they will be used in.
- Use interface for object types that can be extended
- Use type for unions, intersections, and mapped types

---
> Source: [wardbox/roke](https://github.com/wardbox/roke) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-04 -->
