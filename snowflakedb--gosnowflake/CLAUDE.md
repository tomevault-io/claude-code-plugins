# gosnowflake

> - Follow Go formatting standards (use `gofmt`)

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gosnowflake/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Cursor Rules for Go Snowflake Driver

## General Development Standards

### Code Quality
- Follow Go formatting standards (use `gofmt`)
- Use meaningful variable and function names
- Include error handling for all operations that can fail
- Write comprehensive documentation for public APIs

### Project Structure
- Place test files in the same package as the code being tested
- Use `test_data/` directory for test fixtures and sample data
- Group related functionality in logical packages

### Testing
- Test files should be named `*_test.go`
- **For test-specific rules, see `testing.mdc`**
- Write both positive and negative test cases
- Use table-driven tests for testing multiple scenarios

### Code Review Guidelines
- Ensure code follows Go best practices
- Verify comprehensive test coverage
- Check that error messages are descriptive and helpful for debugging
- Validate that public APIs are properly documented

---
> Source: [snowflakedb/gosnowflake](https://github.com/snowflakedb/gosnowflake) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-27 -->
