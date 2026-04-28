# fitness-ai-app

> You are building a fitness app with AI-generated, personalized training plans. The stack includes Fastify + gRPC (BE), React Native (mobile), React (web), PostgreSQL with Prisma, and OpenAI APIs.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/fitness-ai-app/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Context (Fitness AI App)
You are building a fitness app with AI-generated, personalized training plans. The stack includes Fastify + gRPC (BE), React Native (mobile), React (web), PostgreSQL with Prisma, and OpenAI APIs.

# Core Principles
- TypeScript everywhere, no `any`
- Use Fastify for API with gRPC endpoints
- All AI logic is handled by backend calls to OpenAI
- Plan updates are made only via `updateTrainingPlan()`
- Feedback flow: `submitSessionFeedback()` → AI Agent → Suggestion
- Training plans are progressive and adaptive, not static

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/73nko) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-10 -->
