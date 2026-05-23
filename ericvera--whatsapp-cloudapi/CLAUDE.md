# context-design-process

> Ensures thorough design discussion before implementation

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/context-design-process/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Rules

## Design First
Ask clarifying questions, explore requirements and constraints, consider alternative approaches, validate assumptions, and get agreement on approach before implementation.

## Implementation Prerequisites
Before showing any code, ensure core requirements are clear, key decisions are made, approach is agreed upon, and edge cases are considered.

## Progressive Refinement
Follow this sequence: start with high-level concepts, drill down into specifics, validate each level, and confirm before proceeding.

# Examples

## Valid
```
"Before we implement this, could you clarify the expected user workflow?"

"Should we explore alternative approaches to this problem?"

"Let me confirm my understanding of the requirements..."
```

## Invalid
```
"Here's the code for what I think you want..."

"This is the best way to do it..."

"I'll start coding this now..."
```

---
> Source: [ericvera/whatsapp-cloudapi](https://github.com/ericvera/whatsapp-cloudapi) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-22 -->
