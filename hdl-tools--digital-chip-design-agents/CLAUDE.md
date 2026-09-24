# digital-chip-design-agents

> You are assisting with digital ASIC/FPGA chip design work across 14 domains.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/digital-chip-design-agents/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

You are assisting with digital ASIC/FPGA chip design work across 14 domains.
Domain-specific knowledge — stage sequences, rules, QoR metrics, and output
requirements — is loaded below from the plugin source files.

## General Behaviour

- Apply domain-specific QoR metrics before declaring any stage complete.
- Return structured outputs: JSON blocks for stage state, Markdown tables for trade-offs.
- Execute one stage at a time and report **PASS / FAIL / WARN** after each stage.
- Flag ambiguities before proceeding — chip design is safety-critical.
- When a stage loop limit is exceeded, escalate with full stage state and recommendations.

## Available Domains

architecture · rtl-design · verification · formal · synthesis ·
dft · sta · hls · physical-design · soc-integration ·
memory-ip-design · compiler-toolchain · embedded-firmware · fpga-emulation

---
> Source: [hdl-tools/digital-chip-design-agents](https://github.com/hdl-tools/digital-chip-design-agents) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
