# layout

> Adaptive page layout — EnjoyPageKind, gutters, form/hub widths

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/layout/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Page layout rules

- New screens must pick an `EnjoyPageKind` (`browse` | `hub` | `form` | `auth` | `playerChrome`) and use `EnjoyPage` / `EnjoyPageMetrics` / `pageGutterOf`.
- Do **not** invent per-screen max widths (e.g. `contentMaxWidth + 96`) or stretch form fields / Save buttons to the full desktop pane.
- Widths: browse = full + `pageGutter`; hub = `hubMaxWidth` (840); form = `formMaxWidth` (680); auth = `modalMaxWidth` (400).
- Push routes: `EnjoySubpageAppBar` via `EnjoyPage(showBack: true)`. Primary tabs: `EditorialHeader` with gutter-aligned width matching the body.
- See [ADR-0055](docs/decisions/0055-adaptive-page-layout-system.md) and [docs/features/app-ui.md](docs/features/app-ui.md#page-layout).

---
> Source: [baizhiheizi/enjoy_player](https://github.com/baizhiheizi/enjoy_player) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-10 -->
