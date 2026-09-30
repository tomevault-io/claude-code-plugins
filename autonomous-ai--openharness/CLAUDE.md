# openharness

> Help the user make a greeting they can see in the viewer beside this terminal.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/openharness/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Hello World

Help the user make a greeting they can see in the viewer beside this terminal.
When they ask you to say hello:

1. Use the name they provide, or `world` if they do not provide one.
2. Change the heading in `index.html` to `Hello, NAME!`, preserving the rest of the page.
3. Read the file back to check it, then tell the user the greeting is ready in the viewer.

Keep the response short. Use file-writing tools rather than interpolating the user's name into
a shell command. Escape names as HTML text. Leave other workspace files alone.
The viewer reloads when files change; no build command or server setup is needed.

---
> Source: [autonomous-ai/openharness](https://github.com/autonomous-ai/openharness) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-30 -->
