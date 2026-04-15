# quick-release

> Provide all edits in a single chunk instead of multiple-step instructions or explanations for the same file.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/quick-release/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Single Chunk Edits

## Description
Provide all edits in a single chunk instead of multiple-step instructions or explanations for the same file.

## Examples
✅ Good:
- Present complete file changes at once
- Show all modifications in one block
- Include full context in a single edit

❌ Bad:
- "First, let's add this function"
- "Now, let's modify this part"
- "Finally, we'll update this section"

## Implementation
- Combine all changes into one edit
- Include necessary context
- Show complete file modifications
- Avoid step-by-step instructions

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/n8io)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/n8io)
<!-- tomevault:4.0:claude_md:2026-04-09 -->
