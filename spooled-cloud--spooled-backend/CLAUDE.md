# spooled-backend

> Update docs/ai/knowledge when this repo changes

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/spooled-backend/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Knowledge base maintenance

Before finishing a change that affects API, auth, billing, queue/gRPC defaults, workers, or public SDK surface:

1. Read `docs/ai/knowledge/00-START-HERE.md` and `MAINTENANCE.md`.
2. Update the listed dataflows/contracts/findings in the **same commit**.
3. Prefer path:line evidence. Mark finding status FIXED/open.
4. Workspace multi-repo map (if present): `../docs/ai/workspace/`.

---
> Source: [Spooled-Cloud/spooled-backend](https://github.com/Spooled-Cloud/spooled-backend) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-27 -->
