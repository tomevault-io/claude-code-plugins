# airflow-ai-sdk

> This module contains the decorators for the agent.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/airflow-ai-sdk/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# airflow_ai_sdk.decorators.agent

This module contains the decorators for the agent.

## agent

Decorator to execute an `pydantic_ai.Agent` inside an Airflow task.

Example:

```python
from pydantic_ai import Agent

my_agent = Agent(model="o3-mini", system_prompt="Say hello")

@task.agent(my_agent)
def greet(name: str) -> str:
    return name
```

---
> Source: [astronomer/airflow-ai-sdk](https://github.com/astronomer/airflow-ai-sdk) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
