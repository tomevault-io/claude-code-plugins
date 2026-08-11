# backend-global-config

> Read environment through GlobalConfig, not getEnv in app code

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/backend-global-config/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Backend configuration access

- **Single source of truth**: Runtime settings for the API come from `config` in `backend/config/GlobalConfig.ts`, populated via `getEnv` / `getEnvNumber` / `getEnvBoolean` from `backend/config/envHelper.ts` only inside that file (and any bootstrap that must run before `config` exists).

- **Do not** call `getEnv`, `process.env[...]`, or import `envHelper` directly in `connections/`, `services/`, `controllers/`, `repositories/`, `integrations/providers/`, `middlewares/`, or routes. Add new keys to `GlobalConfig` and read `config.<section>.<field>` instead.

- **Exceptions**: `envHelper.ts` itself; `GlobalConfig.ts`; tests that intentionally stub env.

The assistant should follow this when adding or editing backend code.

---
> Source: [Ratimon/openquok-monorepo](https://github.com/Ratimon/openquok-monorepo) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-11 -->
