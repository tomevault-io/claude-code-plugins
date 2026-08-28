# dsh-goalmesh

> This repository contains a DeepSeek Harness Plugin, not a Codex Plugin.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/dsh-goalmesh/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# DSH GoalMesh

This repository contains a DeepSeek Harness Plugin, not a Codex Plugin.

- Treat the architecture in `docs/architecture.md` as the implementation contract.
- Keep the installable bundle, Host tool, and Web companion as separate packages.
- Preserve Cordis lifecycle ownership: every registration and live resource must be disposed with its owning fiber.
- Run `pnpm check` before each implementation-plan commit.
- Keep one commit per numbered point in `docs/execution-plan.md`.

---
> Source: [Jarad-z/dsh-goalmesh](https://github.com/Jarad-z/dsh-goalmesh) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-28 -->
