# optimus-claude

> This directory belongs to invoice-ledger.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/optimus-claude/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Partner feed importer

This directory belongs to invoice-ledger.

Run `python -m unittest discover -s ../tests -p test_importer.py` here.

The partner pads IDs with spaces in transit. Strip this padding only at the
import boundary; preserve case and do not broaden the rule to catalog lookup.
See `../.claude/docs/testing.md` when changing tests.

---
> Source: [oprogramadorreal/optimus-claude](https://github.com/oprogramadorreal/optimus-claude) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-07 -->
