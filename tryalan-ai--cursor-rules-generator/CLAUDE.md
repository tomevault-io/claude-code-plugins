# project-structure

> Project structure guidelines and organization

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/project-structure/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Structure Guidelines

## Directory Organization
- Project Type: single
- Source Directory: src/
- Component Organization: type-based

## File Naming Conventions
- Components: camelCase
- Files: camelCase
- Import Style: relative

## Structure Requirements

- Single application structure
- Clear separation of concerns
- Modular component organization


## Best Practices
- Keep related files together
- Use consistent naming across the project
- Maintain clear import/export patterns
- Document architectural decisions

## Code Examples:

```
src/

├── components/
├── hooks/
├── services/
├── pages/
└── utils/

```

---
> Source: [tryalan-ai/cursor-rules-generator](https://github.com/tryalan-ai/cursor-rules-generator) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-26 -->
