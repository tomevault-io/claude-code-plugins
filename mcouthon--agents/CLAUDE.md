# agents

> VS Code Copilot-specific settings for this repository.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agents/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS Repo - Copilot Instructions

VS Code Copilot-specific settings for this repository.

See [AGENTS.md](../AGENTS.md) for cross-agent instructions including:

- Repository structure
- Post-implementation steps (CHANGELOG, docs, versioning)
- Conventions

## File Conventions

| Type         | Pattern                                                |
| ------------ | ------------------------------------------------------ |
| Templates    | `templates/{agents,skills,instructions}/*.template.md` |
| Agents       | `generated/copilot/agents/*.agent.md`                  |
| Skills       | `generated/copilot/skills/*/SKILL.md`                  |
| Instructions | `generated/copilot/instructions/*.instructions.md`     |
| Research     | `docs/research/RDR-XXX-*.md`                           |

## Testing Changes

After modifying agents or skills:

```bash
make validate
./install.sh
./tests/validate-skills.sh
./tests/test-generate.sh
```

---
> Source: [mcouthon/agents](https://github.com/mcouthon/agents) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-22 -->
