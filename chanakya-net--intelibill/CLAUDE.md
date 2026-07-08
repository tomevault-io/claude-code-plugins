# intelibill

> **For the complete and up-to-date project documentation, see [AGENTS.md](../../AGENTS.md) at the repo root.**

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/intelibill/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Guidelines

**For the complete and up-to-date project documentation, see [AGENTS.md](../../AGENTS.md) at the repo root.**

All guidelines, conventions, build commands, architecture boundaries, and backend/frontend standards are documented in the primary file to maintain consistency across all tools.

## Quick Reference

- Build: `dotnet build src/backend/Intelibill.slnx`
- Test: `dotnet test src/backend/Intelibill.slnx`
- Frontend: Bun only (not npm/yarn)
- Error handling: ErrorOr result pattern
- Multi-shop: RLS-enforced row isolation per active_shop_id

See [AGENTS.md](../../AGENTS.md) for full details.

---
> Source: [chanakya-net/intelibill](https://github.com/chanakya-net/intelibill) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-08 -->
