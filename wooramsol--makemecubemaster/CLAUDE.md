# project-version

> Current app release version for agents and deploy checks

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/project-version/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Project version

**Current release:** `v1.18.4`

- Source of truth: `package.json` → `version`
- Runtime: `src/lib/appVersion.ts` (`__APP_VERSION__` from Vite)
- UI: main screen header (`AppTitle`) and loading overlay show `v{version}`
- After bumping version, merge to `main` and push — GitHub Actions deploys to Pages automatically

Live URL: https://wooramsol.github.io/makemecubemaster/

---
> Source: [wooramsol/makemecubemaster](https://github.com/wooramsol/makemecubemaster) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-17 -->
