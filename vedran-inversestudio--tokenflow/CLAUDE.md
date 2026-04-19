# tokenflow

> "args": ["simple-server.js"],

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tokenflow/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

{
  "mcpServers": {
    "tokenflow": {
      "command": "node",
      "args": ["simple-server.js"],
      "cwd": "./packages/mcp",
      "env": {
        "BRIDGE_URL": "http://localhost:4000",
        "PROJECT_ID": "default"
      }
    }
  }
} 

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/vedran-inversestudio) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-10 -->
