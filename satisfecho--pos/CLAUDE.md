# angular-frontend-docker-logs

> After changing Angular frontend code, check docker logs to verify the app compiles

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/angular-frontend-docker-logs/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Angular Frontend – Verify Build via Docker Logs

When you change frontend (Angular) code under `front/`:

1. **After editing** components, templates, styles, or config under `front/`, **always check Docker logs** to confirm the app compiles and runs without errors.
2. Prefer checking logs from the container that serves or builds the frontend (e.g. dev server or build step).
3. If the logs show compilation or runtime errors, fix them before considering the change done.

This ensures Angular build and dev server stay healthy after code changes.

---
> Source: [satisfecho/pos](https://github.com/satisfecho/pos) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-19 -->
