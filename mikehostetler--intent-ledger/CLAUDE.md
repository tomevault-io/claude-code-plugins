# intent-ledger

> This repository contains the `intent_ledger` Elixir package.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/intent-ledger/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Notes

This repository contains the `intent_ledger` Elixir package.

## Commands

- `mix test` - run the focused test suite.
- `mix quality` - run the package quality gate.
- `mix docs` - generate HexDocs locally.

## Conventions

- Public modules live under `IntentLedger`.
- Core structs should expose Zoi schemas.
- External/runtime failures should be normalized through `IntentLedger.Error`.
- Runtime persistence is Bedrock-first through `IntentLedger.BedrockStore` and
  `bedrock_job_queue`.

---
> Source: [mikehostetler/intent_ledger](https://github.com/mikehostetler/intent_ledger) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-16 -->
