# event-bus-and-communication

> Event bus usage for cross-module communication

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/event-bus-and-communication/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Event Bus and Communication

- Use the global `eventBus` from [`src/utils/eventbus.ts`](mdc:src/utils/eventbus.ts) for cross-module messaging
- Define event names and types in [`src/common/event.ts`](mdc:src/common/event.ts)
- Prefer `eventBus.on/once` for subscriptions and `eventBus.emit` for async fan-out
- Keep listener counts reasonable; `EventBus` warns when exceeding `maxListeners`
- Remove listeners when appropriate for long-lived modules

Example pattern:
```ts
import { eventBus } from '@/utils/eventbus'

eventBus.on('settings:open', (payload) => {
  // handle open
})
```

---
> Source: [RonkTsang/gemini-chat-extension](https://github.com/RonkTsang/gemini-chat-extension) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-06 -->
