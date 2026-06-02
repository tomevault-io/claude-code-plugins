# testing-rules

> - Don't use Mock fixtures. All our tests are integration tests

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/testing-rules/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Testing Patterns for FastWorkflow

- Don't use Mock fixtures. All our tests are integration tests
- Do not remove pytest tests without explicit user approval

## MCP Integration Testing

### Test Structure
- **./tests** - Folder with all the tests
- **[tests/conftest.py](mdc:tests/conftest.py)** - Pytest configuration and shared fixtures
- **[tests/README.md](mdc:tests/README.md)** - Testing documentation and usage guide

### Testing Best Practices

#### Integration Testing Philosophy
```python
# ✅ DO: Use real test workflows
workflow_path = os.path.join("tests", "example_workflow") 
workflow_path = os.path.join("tests", "hello_world_workflow") 

# ✅ DO: Test end-to-end functionality
result = mcp_server.call_tool("get_user_details", {"user_id": "sara_doe_496"})

# ❌ DON'T: Mock FastWorkflow components
# ❌ DON'T: Use fake data when real data is available
```

---
> Source: [radiantlogicinc/fastworkflow](https://github.com/radiantlogicinc/fastworkflow) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-02 -->
