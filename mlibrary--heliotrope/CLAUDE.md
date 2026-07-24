# heliotrope

> - **Run specs**: `bundle exec rspec spec/`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/heliotrope/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot Instructions

## Commands
- **Run specs**: `bundle exec rspec spec/`
- **Check style**: `bundle exec rubocop`
- **Auto-fix style**: `bundle exec rubocop -A`

## Conventions
- Use `Time.zone.today` not `Date.today`
- Table names are plural: `counter_summaries`
- Service modules: `FeatureService::ClassName` to avoid conflicts
- Private methods should be defined below `private` keyword and indented an extra level (private methods will be indented 2 spaces right of the `private` keyword)
- Always test and lint after changes

---
> Source: [mlibrary/heliotrope](https://github.com/mlibrary/heliotrope) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
