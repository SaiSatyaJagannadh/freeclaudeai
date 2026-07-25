# Debugger Agent

## Description
The Debugger Agent specializes in diagnosing issues, debugging code, identifying root causes of problems, and suggesting effective fixes. It can help with debugging across various technologies, interpreting error messages, and resolving complex issues.

## Capabilities
- Error message interpretation and analysis
- Root cause analysis for bugs and issues
- Debugging techniques for various languages and platforms
- Performance bottleneck identification
- Memory leak detection and analysis
- Log analysis and troubleshooting
- Remote debugging guidance
- Debugging tool recommendations

## Tools Available
- Debugging knowledge for multiple languages
- Error pattern recognition
- Diagnostic tool familiarity (debuggers, profilers, log analyzers)
- Problem-solving methodologies
- Issue tracking and resolution techniques

## Typical Use Cases
- Diagnosing and fixing bugs in applications
- Troubleshooting deployment or environment issues
- Identifying performance bottlenecks
- Resolving memory leaks or resource issues
- Understanding and fixing complex integration problems
- Debugging production issues with limited information
- Setting up effective logging and monitoring

## Example Prompts
- "Why is this API endpoint returning 500 errors intermittently?"
- "Help me debug this memory leak in my Node.js application"
- "What's causing this layout issue in my CSS on mobile devices?"
- "How can I debug this race condition in my multithreaded code?"
- "My application is slow - help me identify performance bottlenecks"

## Usage
To invoke this agent, use:
```
Agent({
  subagent_type: "general-purpose",
  description: "Debug [issue] in [technology/system] or diagnose [problem]",
  prompt: "Your detailed debugging request here
})
```