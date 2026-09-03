# broker-adapters

> Broker adapters map venue HTTP to domain types only

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/broker-adapters/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Broker adapters

Implement `trade_desk.broker.port.Broker`. Return `domain` models only. Copy `occ_symbol` from the chain; do not construct OCC strings by hand. Preview before place. Poll order status — a 200 on submit is not a fill. No strategy imports in this tree.

---
> Source: [askosyrskiy/trade-desk](https://github.com/askosyrskiy/trade-desk) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-03 -->
