# skill-development

> Each skill lives in its own directory under `skills/`:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/skill-development/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Skill Development Rules

## Skill Directory Structure

Each skill lives in its own directory under `skills/`:

```
skills/
  gas-optimization/
    SKILL.md      # Skill metadata + content
```

## SKILL.md Format

```yaml
---
name: skill-name
description: When and why to use this skill. Used for auto-discovery.
---
```

Followed by the skill content in Markdown.

## Naming Conventions
- Directory name: `kebab-case` (e.g., `gas-optimization`)
- SKILL.md name field: same as directory name
- Description: explains WHEN to trigger in Ethereum context

## Quality Rules
- Content must be Ethereum/Solidity specific
- Include Solidity code examples where applicable
- Include checklists for complex patterns
- Reference specific EIPs, ERCs, and tools
- Cross-reference related skills
- Use "onchain" not "on-chain"

## Skill Categories
- Solidity Development: patterns, gas, storage, assembly
- Security: vulnerability patterns, attack vectors, defenses
- DeFi: protocol integration, AMMs, lending, oracles
- Testing: Foundry testing, fuzzing, invariants, formal verification
- Audit: pipeline phases (prep, recon, breadth, depth, verify, report)
- Standards: ERC implementations, proxy patterns
- Tooling: Foundry, Slither, Cast, Anvil
- Infrastructure: subgraphs, frontends, L2, deployment

Consider these rules if they affect your changes.

---
> Source: [ccashwell/evm-cortex](https://github.com/ccashwell/evm-cortex) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-09 -->
