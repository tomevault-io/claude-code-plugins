# base-class-contract

> Check all subclasses when modifying base class interfaces

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/base-class-contract/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Changes to abc.py base classes (BaseTrainer, BaseAdapter, BaseRewardModel) affect ALL subclasses.
Before modifying:
- List ALL subclasses that override the changed method
- Update each subclass to match the new signature
- Verify no trainer/adapter/reward is broken
See constraints #11-#14 in .agents/knowledge/constraints.md.

---
> Source: [X-GenGroup/Flow-Factory](https://github.com/X-GenGroup/Flow-Factory) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
