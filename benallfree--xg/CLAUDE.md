# structure

> * this is a monorepo with several packages

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/structure/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

* this is a monorepo with several packages
* packages/site is the frontend site
* packages/extension is the chrome extension
* packages/extension/src/main.ts is the icon popup
* packages/extension/src/content.ts is the entry point for the game
* in extension, use vanjs instead of raw DOM
* frontend is vike, react, daisyui, tailwind, and tailwind typography
* when updating `x-games`, make sure `manifest.json` version is updated too

---
> Source: [benallfree/xg](https://github.com/benallfree/xg) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-21 -->
