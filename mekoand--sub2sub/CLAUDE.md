# sub2sub

> Before planning, creating, implementing or updating work, read [the GitHub issue workflow](docs/agents/issue-tracker.md). Future requirements, specifications and work status live in `mekoand/sub2sub` Issues.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/sub2sub/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# sub2sub development

## Agent skills

### Issue tracker

Before planning, creating, implementing or updating work, read [the GitHub issue workflow](docs/agents/issue-tracker.md). Future requirements, specifications and work status live in `mekoand/sub2sub` Issues.

### Triage labels

When triaging issues or selecting work, use [the five triage roles](docs/agents/triage-labels.md). Readiness and completion are separate.

### Domain docs

Before exploring or changing code, follow [the domain reading rules](docs/agents/domain.md).

## Product boundary

Before changing delegation, read [the architecture](docs/architecture.md). The provider checks the quality of its work; the caller checks delivery completeness. Plugin regression tests are separate from those task checks.

For implementation, testing and review, follow [CONTRIBUTING.md](CONTRIBUTING.md).

---
> Source: [mekoand/sub2sub](https://github.com/mekoand/sub2sub) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-07 -->
