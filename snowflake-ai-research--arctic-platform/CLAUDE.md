# arctic-platform

> Always run the tests before and after changing any code in `dss_client/`:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/arctic-platform/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Instructions for `dss-client`

Always run the tests before and after changing any code in `dss_client/`:

```bash
cd /home/repo/dss-client
python3 -m pytest tests/ -v
```

All tests must pass.

## Context

`dss_client/neutrino_client.py` calls into the **Neutrino SNOWAPI** exposed by
Global Services. When changing the wire format, cross-check these:

- SNOWAPI spec (source of truth for the REST schema):
  `/home/repo/snowflake/GlobalServices/modules/snowapi/snowapi-codegen/src/main/openapi/specs/neutrino.yaml`
- Mock SNOWAPI server (for local end-to-end testing):
  `/home/repo/cortex/neutrino/cmd/mock-snowapi/` (see its `README.md`)

---
> Source: [Snowflake-AI-Research/Arctic-Platform](https://github.com/Snowflake-AI-Research/Arctic-Platform) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
