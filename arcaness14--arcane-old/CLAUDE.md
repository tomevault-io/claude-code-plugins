# ss14-shared

> <!-- SPDX-License-Identifier: LicenseRef-OpenSpace-AgentPrompts-Restricted -->

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ss14-shared/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

<!-- SPDX-License-Identifier: LicenseRef-OpenSpace-AgentPrompts-Restricted -->

---
description: Shared SS14 rules for replicated state, shared events, localization identifiers, and prediction-aware gameplay code.
globs:
  - Content.Shared/**/*.cs
  - Content.Goobstation.Shared/**/*.cs
  - Content.Goobstation.Common/**/*.cs
  - Content.Goobstation.Maths/**/*.cs
  - Content.Shared.Database/**/*.cs
alwaysApply: false
---

Apply @.agents/rules/ss14-csharp-style.md

Read these skills before editing matching files:

- @.agents/skills/ss14-ecs-components/SKILL.md
- @.agents/skills/ss14-ecs-entities/SKILL.md
- @.agents/skills/ss14-ecs-systems/SKILL.md
- @.agents/skills/ss14-events/SKILL.md
- @.agents/skills/ss14-prediction/SKILL.md
- @.agents/skills/ss14-netcode/SKILL.md
- @.agents/skills/ss14-localization-code/SKILL.md

---
> Source: [ArcaneSS14/arcane-old](https://github.com/ArcaneSS14/arcane-old) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-06 -->
