# project-rules

> - Criar banco compartilhado

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/project-rules/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

Sempre ler:

- AGENTS.md
- ARCHITECTURE.md
- ADR.md
- SYSTEM_DESIGN.md
- EVENT_CATALOG.md
- C4_MODEL.md
- BACKLOG.md
- SPRINT_PLAN.md

Regras obrigatórias:

- .NET 8
- Clean Architecture
- CQRS
- MediatR
- FluentValidation
- PostgreSQL
- RabbitMQ
- OpenTelemetry
- Docker

Nunca:

- Criar banco compartilhado
- Quebrar Database Per Service
- Criar chamadas diretas entre serviços
- Ignorar Saga Pattern
- Ignorar Outbox Pattern

Trabalhar somente na sprint atual.

---
> Source: [Sameque/micro-commerce](https://github.com/Sameque/micro-commerce) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-25 -->
