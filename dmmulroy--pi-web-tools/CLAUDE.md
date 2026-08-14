# pi-web-tools

> - Parse external data at boundaries before passing it inward.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pi-web-tools/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Pi Web Tools

## Guardrails

- Parse external data at boundaries before passing it inward.
- Preserve SSRF protections, URL credential redaction, response limits, and output truncation.
- Model expected failures with the local `Result` type; throw at the Pi adapter only to mark a tool execution as failed.
- Put runtime libraries in `dependencies` and Pi core packages in `peerDependencies`.
- Run `npm run check` after changes.

---
> Source: [dmmulroy/pi-web-tools](https://github.com/dmmulroy/pi-web-tools) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-14 -->
