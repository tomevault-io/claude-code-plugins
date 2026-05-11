# general-coding-rules

> General Coding Rules

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/general-coding-rules/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# General Coding Rules

## Constants and Magic Numbers

- NEVER hardcode numeric values directly in code.
  Always use descriptive named constants.

- All numeric constants must have clear, descriptive names and docstrings explaining
  their purpose.

- Constants should be defined in appropriate settings files (e.g., `settings.ts`) for
  easy maintenance.

  ```typescript
  // BAD: Hardcoded numbers
  const tradeCount = Math.min(trades.length, 50);
  
  // GOOD: Named constants with documentation
  /**
   * Execution statistics counting limits for dialog tab display.
   * These control the "X+" display thresholds and query performance.
   */
  export const EXECUTION_STATS_LIMITS = {
    /** Maximum trades to count before showing "50+" */
    maxTradeCount: 50,
    /** Maximum conversation turns to count before showing "100+" */
    maxConversationTurnCount: 100,
  } as const;
  
  // Usage:
  const tradeCount = Math.min(trades.length, EXECUTION_STATS_LIMITS.maxTradeCount);
  ```

---
> Source: [jlevy/tryscript](https://github.com/jlevy/tryscript) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-08 -->
