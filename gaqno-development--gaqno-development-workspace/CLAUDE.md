# gaqno-development-workspace

> NestJS backend structure — controllers, services, DTOs, @gaqno-backcore

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gaqno-development-workspace/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Backend (NestJS) Standards

**Controllers**: Thin routing only. Handle HTTP mapping and validation; delegate all business logic to services. No business logic in controllers.

**Services**: All business rules and domain logic. Single responsibility; inject deps via constructor; fully unit testable without HTTP.

**DTOs**: Use `class-validator` decorators. Separate request/response DTOs; type-safe contracts. Validate all incoming data.

**Modules**: Feature-based; clear boundaries; import only what’s needed; export services for cross-module use.

**Shared code**: Only truly reusable code in `@gaqno-backcore` (guards, filters, DTOs, base repos, cross-service utils).

**Testing**: Unit tests for all services; integration tests for controllers; E2E for critical flows. High coverage on business logic.

**Worktree**: Use `git worktree add ../<service>-<desc> -b feature/TICKET-KEY-desc` for feature work; remove after PR merged.

Violations: business logic in controller (HIGH), service without tests (CRITICAL), missing DTO validation (HIGH).

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/gaqno-development) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
