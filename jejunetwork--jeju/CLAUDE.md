# bun-conventions

> Bun runtime conventions for Jeju

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/bun-conventions/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Bun Conventions

**Use Bun for all operations, not npm/npx:**
- Run: `bun run dev` or `bun scripts/deploy.ts`
- Install: `bun install ethers`
- TypeScript runs directly, no transpilation
- `.env` auto-loaded, no dotenv package needed

---
> Source: [JejuNetwork/jeju](https://github.com/JejuNetwork/jeju) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
