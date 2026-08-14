# titanclip-server

> TitanClip server — Express ESM, routes, heartbeat, adapters

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/titanclip-server/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Server (`@titanclip/server`)

- Package is **ESM** (`"type": "module"` in `server/package.json`). Prefer **NodeNext** resolution and existing patterns for routes, services, heartbeat, and adapter registration.
- After substantive changes: `pnpm --filter @titanclip/server typecheck`.
- Tests: use Vitest via the `server` project in root `vitest.config.ts` or the server’s local Vitest config as appropriate.

---
> Source: [CES-Ltd/TitanClip](https://github.com/CES-Ltd/TitanClip) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-14 -->
