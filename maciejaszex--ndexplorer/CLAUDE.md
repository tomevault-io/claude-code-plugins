# testing

> Testing conventions — Vitest + happy-dom

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/testing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Testing

- **Vitest 4.x** + **happy-dom** for DOM tests
- Pragmatic — one `it()` covers a full scenario, not individual edge cases
- Mock data in `tests/utils/mocks.ts` (17 fake logs, no real data)
- Helpers in `tests/utils/` — test files contain only assertions
- All UI text must be tested for both PL and EN key parity
- Run: `npm test` (single), `npm run test:watch` (watch)

---
> Source: [maciejaszex/ndexplorer](https://github.com/maciejaszex/ndexplorer) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-30 -->
