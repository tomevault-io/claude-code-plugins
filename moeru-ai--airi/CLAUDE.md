# airi

> - Use Valibot for all server data that crosses a trust boundary.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/airi/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Server Guide

## Runtime contracts

- Use Valibot for all server data that crosses a trust boundary.
- This includes HTTP data, Pub/Sub messages, queue jobs, WebSocket events, database JSON, and provider responses.
- Define each schema beside the contract owner.
- Use `parse` if the caller converts invalid data into an error.
- Use `safeParse` if the caller branches on valid and invalid data.
- Do not use `typeof`, `Record<string, unknown>`, or type casts as runtime input validation.
- Infer TypeScript types from Valibot schemas. Do not duplicate the contract in an interface.

---
> Source: [moeru-ai/airi](https://github.com/moeru-ai/airi) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-16 -->
