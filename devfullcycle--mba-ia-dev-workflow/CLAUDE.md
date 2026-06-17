# coding

> Use when writing TypeScript code. Covers naming conventions, file organization, and TypeScript best practices.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/coding/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Coding Conventions

## Naming

- **camelCase**: variables, functions, parameters, object properties
- **PascalCase**: classes, interfaces, type aliases, enums
- **UPPER_SNAKE_CASE**: constants and enum values
- **kebab-case**: file names and directory names (e.g., `create-user.usecase.ts`, `typeorm-user.repository.ts`)

## Files

- One main export per file — name the file after what it exports
- Suffix files by their role: `.usecase.ts`, `.repository.ts`, `.controller.ts`, `.entity.ts`
- Use `.js` extensions in imports (ESM requirement)

## TypeScript

- Always use explicit return types on exported functions
- Prefer `interface` over `type` for object shapes
- Prefer `unknown` over `any` — never use `any` unless absolutely necessary
- Use `readonly` for properties that should not be reassigned

---
> Source: [devfullcycle/mba-ia-dev-workflow](https://github.com/devfullcycle/mba-ia-dev-workflow) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-17 -->
