# tanstack-start-faster

> - Build: `vite build`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tanstack-start-faster/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Commands
- Build: `vite build`
- Lint: `biome lint`
- Format: `biome format`
- Check: `biome check`
- Test: `vitest run`
- Test single: `vitest run <file>`

# Code Style
- **Formatting**: Biome, tab indentation, double quotes
- **Imports**: Organize with Biome, path aliases `@/` for `src/`
- **Types**: Strict TypeScript, no unused locals/parameters
- **Naming**: camelCase for variables/functions, PascalCase for components
- **Error handling**: Zod schemas for validation, console.log for debugging
- **UI**: Shadcn components via `pnpx shadcn@latest add <component>`
- **Styling**: Tailwind CSS with `cn()` utility for class merging
- **Libraries**: TanStack (Router, Query, Form), React 19, Cloudflare Workers

---
> Source: [Vijayabaskar56/tanstack-start-faster](https://github.com/Vijayabaskar56/tanstack-start-faster) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
