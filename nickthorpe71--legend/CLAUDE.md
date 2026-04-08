# legend

> <!-- legend-start -->

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/legend/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

<!-- legend-start -->
# SYSTEM_MANDATE: Legend — Your Long-Term Memory

You MUST use **Legend** to maintain context across sessions.

## Essential Commands
- **Session start:** `cargo run --quiet -- memory start` — returns prior decisions, recent activity, and categorized memories.
- **Record decisions:** `cargo run --quiet -- memory tick <<'EOF'` ... `EOF` — tick decisions with rationale (DECISION:, BUG:, ARCHITECTURE:, BLOCKER: prefixes). Aim for 3-8 ticks per session.
- **Recall context:** `cargo run --quiet -- memory query <<'EOF'` ... `EOF` — query before starting new topics. Top result auto-reinforced.
<!-- legend-end -->

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/nickthorpe71)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/nickthorpe71)
<!-- tomevault:4.0:claude_md:2026-04-07 -->
