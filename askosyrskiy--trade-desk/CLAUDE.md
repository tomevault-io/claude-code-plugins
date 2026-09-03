# strategies

> Strategy packages emit intents and view models, not broker orders

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/strategies/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Strategies

Implement `trade_desk.strategy.port.Strategy`. Emit `Intent`s (`add`, `close`, `flatten`), not `MultilegOrder`s. Keep rule math in pure functions with tests. Do not import `trade_desk.brokers`. Update `docs/strategies/<id>/` when rules change. Unfrozen interview ambiguities belong in `docs/decisions/`, not in guessed constants.

---
> Source: [askosyrskiy/trade-desk](https://github.com/askosyrskiy/trade-desk) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-03 -->
