# docker-dev

> Docker Compose dev stack for per-worktree isolation

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/docker-dev/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Docker dev stack

Never run bare `docker compose up` from `docker-compose/web/`.

- **Start**: `scripts/dev-compose.sh up` (runs detached)
- **URLs**: run `scripts/dev-compose.sh urls` before testing the web UI or API; use the printed `CONDUCTOR_PORT` URL
- **Stop**: `scripts/dev-compose.sh down` (also runs automatically via `sessionEnd` hook when the agent session ends)
- **Setup only** (symlink env files): `scripts/dev-compose.sh setup`

`uv-cache` and `hf-cache` Docker volumes are shared across worktrees intentionally.

---
> Source: [isundaylee/istaroth](https://github.com/isundaylee/istaroth) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-01 -->
