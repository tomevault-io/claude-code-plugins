# ui

> UI/dashboard rules — vanilla JS, no frameworks

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ui/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# UI rules

- The UI is a single vanilla-JS shell. **No frameworks, no CDN
  fetches, no build step for the UI.**
- `src/ui/public/app.js` must stay < 120 KB uncompressed (currently
  < 100 KB).
- No synchronous disk reads on the UI poll path or REPL redraw path.
- Watchers are ref-counted so multiple surfaces share one file
  watcher — preserve that pattern.
- Before adding a dependency, ask whether a ~20-line hand-written
  utility would do. It almost always does.

---
> Source: [hoangsonww/Forge-Agentic-Coding-CLI](https://github.com/hoangsonww/Forge-Agentic-Coding-CLI) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-23 -->
