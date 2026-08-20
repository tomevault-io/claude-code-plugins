# pathwise

> - Prefer small, focused diffs. Match existing patterns in `src/`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pathwise/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# PathWise — agent notes

- Prefer small, focused diffs. Match existing patterns in `src/`.
- Do not commit `.env.local` or secrets. Use `.env.example` as the template.
- Server-only secrets must **not** use the `VITE_` prefix.
- Decision maps are the product — keep exploration UX calm, clear, and honest.
- After dependency or Vite config changes, run `npm run build` before shipping.

---
> Source: [Amaar-Ali/PathWise](https://github.com/Amaar-Ali/PathWise) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-20 -->
