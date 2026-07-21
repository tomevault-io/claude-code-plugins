# nextlytics

> - **Bun** — package manager and script runner. Use `bun install`, `bun run <script>`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/nextlytics/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Development

## Tooling

- **Bun** — package manager and script runner. Use `bun install`, `bun run <script>`
- **tsup** — bundling the `@nextlytics/core` package
- **Vitest** — testing

## Commands

```bash
bun run typecheck    # Type check all packages
bun run build        # Build all packages
bun run lint         # Lint all packages
bun run test         # Run tests
bun run format       # Format code with Prettier
bun run format:check # Check formatting

bun run website:dev  # Run website in dev mode
```

NEVER use pnpm!

---
> Source: [jitsucom/nextlytics](https://github.com/jitsucom/nextlytics) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-20 -->
