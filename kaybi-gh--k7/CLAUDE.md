# k7-domain

> K7 Domain layer conventions

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/k7-domain/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Domain Layer

Zero dependencies on other projects. Entities inherit `BaseEntity`. Events inherit `BaseEvent`, raised via `AddDomainEvent()`.

Structure: `Common/`, `Constants/`, `Entities/`, `Enums/`, `Events/`, `Exceptions/`, `Interfaces/`, `Models/`, `Settings/`, ...

Service contracts live in Domain; Infrastructure implements them. `IApplicationDbContext` lives in Application (`Common/Interfaces/`).

---
> Source: [kaybi-gh/K7](https://github.com/kaybi-gh/K7) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-30 -->
