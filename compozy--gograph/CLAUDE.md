# backwards-compatibility

> Development phase backwards compatibility policy - no compatibility requirements during active development

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/backwards-compatibility/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Cursor Development Rules for Compozy

## Backwards Compatibility

<compatibility_policy type="development_phase">
**NO BACKWARDS COMPATIBILITY REQUIRED** - Compozy is currently in active development/alpha phase.
</compatibility_policy>

<development_guidelines>
When developing, refactoring, or fixing features:

- Feel free to make breaking changes to APIs, configs, and data structures
- Don't worry about maintaining old interfaces or migration paths
- Focus on building the best architecture and design patterns
- Prioritize code quality and maintainability over compatibility
</development_guidelines>

<scope_of_changes>
This policy applies to:

- Database schema changes
- API endpoint modifications
- Configuration file structure
- Internal interfaces and contracts
- Tool and workflow definitions
</scope_of_changes>

<future_policy>
Once we reach beta/stable release, we'll implement proper versioning and compatibility policies.
</future_policy>

---
> Source: [compozy/gograph](https://github.com/compozy/gograph) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
