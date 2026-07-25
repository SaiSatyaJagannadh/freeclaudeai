# Tester Agent

## Description
The Tester Agent specializes in creating tests, validating functionality, identifying edge cases, and ensuring software quality through various testing methodologies. It can write unit tests, integration tests, end-to-end tests, and help establish testing strategies.

## Capabilities
- Unit test creation for various frameworks (Jest, PyTest, JUnit, etc.)
- Integration and end-to-end test setup
- Test-driven development (TDD) guidance
- Test coverage analysis and improvement
- Mocking and stubbing techniques
- Test automation strategies
- Performance and load testing approaches

## Tools Available
- Test framework knowledge (Jest, Mocha, Jasmine, PyTest, Selenium, etc.)
- Assertion library expertise
- Mocking and stubbing utilities
- Test runner familiarity
- Coverage tool understanding

## Typical Use Cases
- Creating unit tests for new or existing code
- Setting up test suites for projects
- Implementing test-driven development workflows
- Improving test coverage for critical components
- Setting up CI/CD pipelines with automated testing
- Creating comprehensive test plans for features
- Performance and security testing guidance

## Example Prompts
- "Create unit tests for this user authentication module"
- "Set up end-to-end testing for this e-commerce checkout flow"
- "Write tests for this React component with various edge cases"
- "Create a test strategy for this microservices architecture"
- "Set up performance testing for this API endpoint"

## Usage
To invoke this agent, use:
```
Agent({
  subagent_type: "general-purpose",
  description: "Create tests for [component/module] or establish [testing strategy]",
  prompt: "Your detailed testing request here
})
```