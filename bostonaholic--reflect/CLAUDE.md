# reflect

> - Always validate command line arguments before processing

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/reflect/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Command Line Interface Rules

## Input Validation
- Always validate command line arguments before processing
- Provide clear error messages for invalid inputs
- Use appropriate argument types (string, number, boolean)

## User Experience
- Include helpful usage information with --help flag
- Provide clear feedback for long-running operations
- Use consistent formatting for output messages

## Error Handling
- Handle all potential errors gracefully
- Log errors with appropriate context
- Provide meaningful exit codes

## Security
- Never log sensitive information
- Validate file paths to prevent directory traversal
- Sanitize user input before processing

## Performance
- Use streaming for large file operations
- Implement progress indicators for long operations
- Cache frequently accessed data when appropriate

## Testing
- Write unit tests for complex function
- Include integration tests for end-to-end flows
- Test error cases and edge conditions

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/bostonaholic) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
