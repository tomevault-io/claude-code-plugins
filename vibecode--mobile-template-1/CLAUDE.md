# project

> Rules for the whole project

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/project/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

This is an Expo/React Native project with TypeScript.

- Use `bun` instead of `npm` and `bunx` instead of `npx`
- Use TailwindCSS (used as Nativewind) `className` prop for styling
- Use file-based routing with Expo Router. The root layout is [_layout.tsx](mdc:src/app/_layout.tsx)
- Screens are defined in `./src/app/**`
- Components are defined in `./src/components/**`
- Other TypeScript files like hooks, constants, config, etc. are in `./src/lib/**`
- Use Drizzle + Drizzle Kit for a local SQLite DB. You can find the relavent files in `./drizzle/**` and `./src/lib/db/**`

---
> Source: [vibecode/mobile-template-1](https://github.com/vibecode/mobile-template-1) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-22 -->
