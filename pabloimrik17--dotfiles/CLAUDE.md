# dotfiles

> This project uses **bun** as the package manager. Always use `bun` instead of `npm`/`yarn`/`pnpm`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/dotfiles/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Package Manager

This project uses **bun** as the package manager. Always use `bun` instead of `npm`/`yarn`/`pnpm`.

## Common npm-to-bun equivalents

| npm                    | bun                             |
| ---------------------- | ------------------------------- |
| `npm install`          | `bun install`                   |
| `npm install <pkg>`    | `bun add <pkg>`                 |
| `npm install -D <pkg>` | `bun add -d <pkg>`              |
| `npm uninstall <pkg>`  | `bun remove <pkg>`              |
| `npm run <script>`     | `bun run <script>`              |
| `npx <cmd>`            | `bunx <cmd>`                    |
| `npm init`             | `bun init`                      |
| `npm test`             | `bun test`                      |
| `npm ci`               | `bun install --frozen-lockfile` |

---
> Source: [pabloimrik17/dotfiles](https://github.com/pabloimrik17/dotfiles) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-24 -->
