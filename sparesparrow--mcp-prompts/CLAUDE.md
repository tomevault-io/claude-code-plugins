# core

> - No dependencies on specific adapters

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/core/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# MCP Prompts Core Package Rules

## Domain Logic Purity
- No dependencies on specific adapters
- Pure TypeScript types and functions
- Business logic only in core/

## Module Structure
- entities/ - Domain entities
- ports/ - Interface definitions
- services/ - Domain services
- No infrastructure dependencies

## Testing Approach
- Unit tests with Jest
- Mock all external dependencies
- Test business logic in isolation
- Coverage > 90%

## Import Rules
- No imports from adapter packages
- Only standard library and domain contracts
- Use dependency injection patterns

---
> Source: [sparesparrow/mcp-prompts](https://github.com/sparesparrow/mcp-prompts) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
