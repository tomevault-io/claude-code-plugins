# minion

> when creating BaseAgent or CodeAgent,

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/minion/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Development Guidelines
when creating BaseAgent or CodeAgent,
Please use .create cls method instead of constructor,
# Create CodeAgent with budget-related tools
CodeAgent.create(brain=brain,tools=[GetTeamMembersTool(),GetExpensesTool(),GetBudgetByLevelTool()])

instead of
    agent = CodeAgent(brain=brain)
    agent.add_tool(GetTeamMembersTool())
    agent.add_tool(GetExpensesTool())
    agent.add_tool(GetBudgetByLevelTool())
    await agent.setup()  # Initialize the agent

since .setup() is handled in .create

# Note

---
> Source: [femto/minion](https://github.com/femto/minion) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-01 -->
