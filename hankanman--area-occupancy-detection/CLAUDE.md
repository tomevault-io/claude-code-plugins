# assumptions

> These assumptions are guaranteed by the integration's architecture and validation:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/assumptions/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


## Integration Assumptions

These assumptions are guaranteed by the integration's architecture and validation:

1. **At least one area exists**: When the integration is installed, the user must create at least one area. We can therefore assume that there will always be at least one area configured.

2. **Each area has at least one motion sensor**: Validated in config flow (`config_flow.py:734-735`) before the integration is installed. Runtime code can assume motion sensors exist.

3. **Areas are initialized before use**: Coordinator setup ensures areas are loaded before any entities or services use them. Platform entities are created after areas are initialized.

4. **When `area_name` is None, first area always exists**: Methods that accept `area_name: str | None = None` can assume that when `area_name` is `None`, `get_area_or_default(None)` will always return the first area (since at least one area exists).

5. **After area validation, area exists**: When `_validate_area_exists()` succeeds, the area is guaranteed to exist. Redundant None checks after validation are unnecessary.

These assumptions allow us to remove defensive checks for empty areas, None areas when `area_name` is None, and areas after validation.

---
> Source: [Hankanman/Area-Occupancy-Detection](https://github.com/Hankanman/Area-Occupancy-Detection) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
