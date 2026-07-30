# ernie-sdk

> ::: erniebot_agent.agents

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/ernie-sdk/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Agent Module


::: erniebot_agent.agents
    options:
        summary: true
        separate_signature: true
        show_signature_annotations: true
        line_length: 60
        members:
        - Agent
        - FunctionAgent

::: erniebot_agent.agents.callback
    options:
        summary: true
        separate_signature: true
        show_signature_annotations: true
        line_length: 60
        members:
        - CallbackManager
        - CallbackHandler
        - LoggingHandler

::: erniebot_agent.agents.schema
    options:
        summary: true
        separate_signature: true
        show_signature_annotations: true
        line_length: 60
        members:
        - LLMResponse
        - ToolResponse
        - AgentResponse

---
> Source: [PaddlePaddle/ERNIE-SDK](https://github.com/PaddlePaddle/ERNIE-SDK) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-21 -->
