# clean-architecture-template

> - Follow standard C# conventions.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/clean-architecture-template/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Copilot Instructions

## 1. Coding Standards
- Follow standard C# conventions.
- **Comments:** Strictly "Why" not "What." Do not explain syntax; explain business context and architectural decisions.
- **Self-Documenting Code:** Prioritize meaningful variable/method names over comments.

## 2. Tech Stack & Architecture
### Backend (C# .NET)
- **DI Container:** Microsoft.Extensions.DependencyInjection.
- **Data Access:** 
  - **MongoDB Connectors:** Specifically for MongoDB interactions.
  - **Repository Pattern:** Implemented for data access abstraction.
- **Validation:** FluentValidation.
- **Testing:** xUnit, Reqnroll.

### Infrastructure
- **DB:** MongoDB or SQL Server (depending on the use case).
- **Caching:** Redis.

---
> Source: [Genocs/clean-architecture-template](https://github.com/Genocs/clean-architecture-template) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
