# mdk

> Tests for the Marmot Hermes plugin in `../../marmot` and its installer/helper scripts.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/mdk/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md - integrations/hermes/tests/marmot

## Scope

Tests for the Marmot Hermes plugin in `../../marmot` and its installer/helper scripts.

Keep test-only fixtures outside the plugin source directory so Hermes's standard source installer scans and copies only runtime files. Do not move secrets, fake `nsec` values, subprocess harnesses, or workspace files back under the plugin directory.

## Verification

```sh
PYTHONDONTWRITEBYTECODE=1 python3 -m unittest discover -s integrations/hermes/tests/marmot
integrations/hermes/tests/marmot/test_dev_scripts.sh
python3 integrations/hermes/tests/marmot/test_real_hermes_plugin.py \
  --hermes-source /path/to/hermes-agent \
  --mdk-source . \
  --mdk-ref HEAD
```

---
> Source: [marmot-protocol/mdk](https://github.com/marmot-protocol/mdk) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-24 -->
