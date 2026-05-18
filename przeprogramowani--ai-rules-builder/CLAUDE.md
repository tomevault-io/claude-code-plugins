# playwright-e2e-testing

> E2E testing with Playwright

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/playwright-e2e-testing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


## TESTING

### Guidelines for E2E

#### PLAYWRIGHT

- Initialize configuration only with Chromium/Desktop Chrome browser
- Use browser contexts for isolating test environments
- Implement the Page Object Model for maintainable tests in ./e2e/page-objects
- Use locators for resilient element selection
- Leverage API testing for backend validation
- Implement visual comparison with expect(page).toHaveScreenshot()
- Use the codegen tool for test recording
- Leverage trace viewer for debugging test failures
- Implement test hooks for setup and teardown
- Use expect assertions with specific matchers
- Leverage parallel execution for faster test runs
- Follow 'Arrange', 'Act', 'Assert' approach to test structure for simplicity and readability.

---
> Source: [przeprogramowani/ai-rules-builder](https://github.com/przeprogramowani/ai-rules-builder) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
