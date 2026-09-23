# relay

> When bumping Relay versions, check these version-string locations first:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/relay/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

When bumping Relay versions, check these version-string locations first:

- `/home/runner/work/relay/relay/.github/workflows/docker.yml` for workflow matrix and `RELAY_VERSION`
- `/home/runner/work/relay/relay/docker/**/*.Dockerfile` for Docker build arguments

---
> Source: [cachewerk/relay](https://github.com/cachewerk/relay) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
