# protected-files

> These are entry points that bootstrap the app. They rarely need changes:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/protected-files/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Protected Files - Do Not Edit

## Never Edit These Files

These are entry points that bootstrap the app. They rarely need changes:

- `index.html` - Vite entry point
- `src/ui/main.tsx` - React bootstrap
- `package.json` - Use `pnpm add <package>` instead of editing directly

## If Build Breaks

Do NOT try to fix config files. Instead:

1. Check if recent code changes caused the error
2. Suggest running `pnpm install` if dependencies are missing
3. Ask the user to share the full error message

---
> Source: [hoshikitsunoda/figma-plugins-vibe-coding-template](https://github.com/hoshikitsunoda/figma-plugins-vibe-coding-template) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
