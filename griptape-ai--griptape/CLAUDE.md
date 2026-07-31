# griptape

> An [Agent](../../reference/griptape/structures/agent.md) is the quickest way to get started with Griptape.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/griptape/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


## Overview

An [Agent](../../reference/griptape/structures/agent.md) is the quickest way to get started with Griptape.
Agents take in [tools](../../reference/griptape/structures/agent.md#griptape.structures.agent.Agent.tools) and [input](../../reference/griptape/structures/agent.md#griptape.structures.agent.Agent.input)
directly, which the agent uses to add a [Prompt Task](./tasks.md#prompt-task).

You can access the final output of the Agent by using the [output](../../reference/griptape/structures/structure.md#griptape.structures.structure.Structure.output) attribute.

### Agent Tools

=== "Code"

    ```python
    --8<-- "docs/griptape-framework/structures/src/agents_2.py"
    ```

=== "Logs"

    ```text
    --8<-- "docs/griptape-framework/structures/logs/agents_2.txt"
    ```

### Agent Input

=== "Code"

    ```python
    --8<-- "docs/griptape-framework/structures/src/agents_1.py"
    ```

=== "Logs"

    ```text
    --8<-- "docs/griptape-framework/structures/logs/agents_1.txt"
    ```

---
> Source: [griptape-ai/griptape](https://github.com/griptape-ai/griptape) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-21 -->
