# virtualregion-releases

> Read `.virtualregion-repository.json` first. This repository has role `release` and contains only

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/virtualregion-releases/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# VirtualRegion release repository contract

Read `.virtualregion-repository.json` first. This repository has role `release` and contains only
release documentation plus `latest.json`.

- Never add Android project code, signing keys, R8 mappings, or committed APK files here.
- Upload APK binaries as GitHub Release assets.
- Publish through the script declared by the matching machine contract so the release asset and
  `latest.json` remain consistent.
- Do not change an APK version on behalf of the user.

---
> Source: [zhou6514-ctrl/VirtualRegion-Releases](https://github.com/zhou6514-ctrl/VirtualRegion-Releases) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-28 -->
