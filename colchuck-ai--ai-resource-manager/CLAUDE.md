# ai-resource-manager

> Admit when things are too complex instead of pretending to understand

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ai-resource-manager/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


---
namespace: grug-brained-dev
ruleset:
  id: grug-brained-dev
  name: Grug Brained Developer Rules
  rules:
    - eighty-twenty
    - readable-over-clever
    - test-simply
    - complexity-enemy
    - say-no
    - fear-of-looking-dumb
    - avoid-abstractions
    - simple-tools
    - avoid-premature-optimization
    - debuggable-code
rule:
  id: fear-of-looking-dumb
  name: Overcome Fear of Looking Dumb
  enforcement: SHOULD
  priority: 75
  scope:
    - files: ["**/*"]
---

# Overcome Fear of Looking Dumb (SHOULD)

grug notice many developer afraid to say "this too complex for grug"

This bad because:
- Complex code stay complex
- Problems get worse over time
- Team suffer in silence

Better to say "grug not understand, can we make simpler?"

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/colchuck-ai) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
