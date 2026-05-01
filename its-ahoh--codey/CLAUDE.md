# codey

> Task: CLI `setProfile` — numbered profile list

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/codey/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Scratchpad
Task: CLI `setProfile` — numbered profile list

[X] List profiles as numbered options (match `setModel` / `setAgent` style)
[X] `npm run build`

# Lessons
- Keep `channel` typed as `UserMessage['channel']` / `GatewayResponse['channel']` end-to-end; avoid widening to plain `string` in helper methods that call `sendResponse`.
- Keep runtime progress metadata structured in `AgentResponse` (`statusUpdates`, `states`) so gateway formatters can show more than just final output.

---
> Source: [its-ahoh/codey](https://github.com/its-ahoh/codey) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-01 -->
