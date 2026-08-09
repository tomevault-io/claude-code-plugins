# newscreen

> Use this rule if we are creating a new screen

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/newscreen/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

New screens should put [single_back_action_bar.dart](mdc:lib/views/player/widgets/bottom_actions/single_back_action_bar.dart) in the bottom nav bar unless otherwise specfied. No action bar button at the top, just a title. New strings go in [string_constants.dart](mdc:lib/constants/strings/string_constants.dart) with a description of how they are used.
Top bar titles should be [medito_app_bar_small.dart](mdc:lib/widgets/headers/medito_app_bar_small.dart)

---
> Source: [xuehaipeng/medito-app](https://github.com/xuehaipeng/medito-app) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-09 -->
