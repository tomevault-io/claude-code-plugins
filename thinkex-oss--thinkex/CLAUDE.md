# thinkex

> - Early-stage repo with effectively no users: treat changes as greenfield. No

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/thinkex/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent notes

- Early-stage repo with effectively no users: treat changes as greenfield. No
  legacy shims, no back-compat paths, and no data migrations for existing rows
  unless explicitly requested. Prefer deleting superseded code over keeping it
  reachable.
- Merging IS shipping: Cloudflare Workers Builds auto-deploys every push to
  `main` to production (wrangler migrations included). The `staging` branch
  deploys to the staging env the same way. There is no manual deploy step.
- Commits carry code and the docs that ship with it. Research notes, analysis
  writeups, and other non-shipping generated markdown (e.g. `docs/research/`)
  stay as untracked working files — commit them only when explicitly asked.

---
> Source: [ThinkEx-OSS/thinkex](https://github.com/ThinkEx-OSS/thinkex) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-08 -->
