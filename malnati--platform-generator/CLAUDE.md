# platform-generator

> MultiDataTable Config

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/platform-generator/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

rule MultiDataTableConfig
description "Ensure correct definition of MultiDataTable configurations."
config-file "src/db/MultiDataTable.ts"
checks [
  { tableName: "tb_platforms", fields: ["++id", "name", "*apps", "*specifications"] },
  { tableName: "appsDB", fields: ["++id", "name", "*microservices"] },
  { tableName: "microservicesDB", fields: ["++id", "name", "*databases"] },
  { tableName: "storesDB", fields: ["++id", "name", "*frontends"] }
]

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/Malnati) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
