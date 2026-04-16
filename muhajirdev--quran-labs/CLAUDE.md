# quran-labs

> - Everytime you create new component / functionality, create it new file.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/quran-labs/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


- Everytime you create new component / functionality, create it new file.
- Always try to use design tokens from app.css, dont use hardcoded values if possible.
- Always try to keep the file size small under 50 lines of code. If the components becomes bigger extract it into smaller components, and make new files.
- Remember that we're using "react-router" , not remix and not "react-router-dom" , so import from "react-router"
- We can use `export const clientLoader` for client-side data fetching before page is loaded and `export consts loader` for server-side data fetching
- Always try to zoom out first, make plan, before implementing
- Remember we have jotai if you need global state management
- Avoid using regex for LLM related works

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/muhajirdev) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-13 -->
