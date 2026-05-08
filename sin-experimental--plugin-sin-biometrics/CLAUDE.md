# plugin-sin-biometrics

> **Protocol:** A2A (Agent-to-Agent)

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/plugin-sin-biometrics/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent: opencode-biometrics-plugin

**Team:** OpenSIN-AI  
**Protocol:** A2A (Agent-to-Agent)  
**Status:** Active  
**Repository:** https://github.com/OpenSIN-AI/opencode-biometrics-plugin

## Capabilities

Biometrics plugin for OpenCode providing authentication and identity verification capabilities.

## Communication

- **Input:** A2A messages from orchestrator
- **Output:** A2A messages to other agents
- **MCP:** Standard OpenSIN MCP servers

## Security

- All operations logged to OpenSIN-Ledger
- Requires authorization token
- Guardrails enforced on all inputs/outputs

## Setup

```bash
git clone https://github.com/OpenSIN-AI/opencode-biometrics-plugin.git
cd opencode-biometrics-plugin
npm install
npm start
```

## License

MIT

---
> Source: [sin-experimental/Plugin-SIN-Biometrics](https://github.com/sin-experimental/Plugin-SIN-Biometrics) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
