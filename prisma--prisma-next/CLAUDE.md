# capabilities-ownership

> Capabilities are adapter-reported, contracts declare requirements

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/capabilities-ownership/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Capability Ownership

**Capabilities describe the database environment and are reported by adapters.** The contract only declares required capabilities in `contract.capabilities` and pins the resulting `profileHash`.

## Do

- Describe capabilities as adapter-reported and negotiated at connect time
- Frame contract capabilities as requirements, not definitions

## Avoid

- Wording that implies the contract owns or defines capabilities
- Treating `sql.*` as a separate “SQL family” capability set rather than shared adapter keys

---
> Source: [prisma/prisma-next](https://github.com/prisma/prisma-next) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
