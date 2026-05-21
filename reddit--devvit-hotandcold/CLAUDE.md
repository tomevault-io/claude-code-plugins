# client

> Use when writing webview code

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/client/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Guidelines:

- Use NPM dependencies if needed, ensure they are web compatible
- You cannot use websockets. Call devvit_search and query for "realtime" to get more information
- Ensure you are using "preact" instead of "react"
- Prefer the use of preact signal over hooks
- When testing, target the specific file with this command: npm run test:client -- guess.test.ts

---
> Source: [reddit/devvit-HotAndCold](https://github.com/reddit/devvit-HotAndCold) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
