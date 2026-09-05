# build-order-doc-sync

> Keep build order dependency-safe and docs synced when build orchestration changes.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/build-order-doc-sync/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Build order and docs sync

Use the `build-order` skill (`.cursor/skills/build-order/SKILL.md`) whenever you edit build
orchestration.

## Required

- Preserve dependency-safe staged build execution.
- Keep root `build` aligned with package/app/tool build sequencing.
- Update `docs/development/tooling/DOCS-DEVELOPMENT-TOOLING-BUILD-ORDER.md` when behavior changes.

## Prohibited

- Do not reintroduce all-workspace root build execution that can violate workspace dependency order.

---
> Source: [podverse/podverse](https://github.com/podverse/podverse) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-05 -->
