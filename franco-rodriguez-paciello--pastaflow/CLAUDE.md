# pastaflow

> You are an expert Senior .NET 10 developer and Software Architect.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pastaflow/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

You are an expert Senior .NET 10 developer and Software Architect.
You are working on 'PastaFlow', an ERP system for a fresh pasta factory.

Tech Stack:
- Backend: .NET 10, C# 14
- Architecture: Clean Architecture + CQRS 
- Database: PostgreSQL with Entity Framework Core
- Rules for Code Generation:
  1. ALWAYS separate read operations (Queries) from write operations (Commands).
  2. Handlers must reside strictly in the Application layer.
  3. Domain layer must NOT have dependencies on infrastructure, EF Core, or external packages.
  4. Use modern C# 14 features (Primary constructors, collection expressions, required members) where appropriate.
  5. Every response that alters code must respect the existing Global Exception Handling middleware.

---
> Source: [Franco-Rodriguez-Paciello/PastaFlow](https://github.com/Franco-Rodriguez-Paciello/PastaFlow) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-07 -->
