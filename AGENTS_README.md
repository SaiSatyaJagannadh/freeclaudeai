# Software Development Agents for Claude Code

## Overview
This directory contains agent definition files for various software development tasks that can be used with Claude Code's Agent tool. These agents specialize in different aspects of software development and can be invoked to help with research, coding, testing, debugging, DevOps, and documentation tasks.

## Created Agent Files
- `researcher_agent.md` - For researching technologies, gathering information, and learning
- `coder_agent.md` - For writing, modifying, and refactoring code
- `tester_agent.md` - For creating tests, validating functionality, and quality assurance
- `debugger_agent.md` - For diagnosing issues, debugging code, and suggesting fixes
- `devops_agent.md` - For deployment, CI/CD, infrastructure, and DevOps tasks
- `documentation_agent.md` - For creating/updating documentation, READMEs, and comments

## Installation
To use these agents, you need to:
1. Create the `.claude/agents/` directory in your project root (if it doesn't exist)
2. Copy the agent files to `.claude/agents/` directory
3. Optionally rename the files to remove the `_agent` suffix (e.g., `researcher_agent.md` → `researcher.md`)

## Usage
Once installed, you can invoke these agents using the Agent tool:

```javascript
Agent({
  subagent_type: "general-purpose",  // Using general-purpose as the base type
  description: "Research [specific topic]",  // Brief description of what you want the agent to do
  prompt: "Your detailed instructions or question here
})
```

### Examples

**Research Agent:**
```javascript
Agent({
  subagent_type: "general-purpose",
  description: "Research state management solutions for React",
  prompt: "Compare Redux, MobX, Zustand, and Recoil for a medium-sized React application. Include pros, cons, and recommendations."
})
```

**Coder Agent:**
```javascript
Agent({
  subagent_type: "general-purpose",
  description: "Add user authentication to Node.js API",
  prompt: "Implement JWT-based authentication for this Express.js API including login, logout, and middleware for protecting routes."
})
```

**Tester Agent:**
```javascript
Agent({
  subagent_type: "general-purpose",
  description: "Create unit tests for payment processing function",
  prompt: "Write comprehensive unit tests for the calculateTotal function including edge cases, error conditions, and various payment scenarios."
})
```

## Agent Capabilities

### Research Agent
- Web search and information gathering
- Technology research and comparison
- Documentation lookup
- Best practices identification
- Learning resource curation

### Coder Agent
- Code generation in multiple languages
- Code refactoring and optimization
- Bug fixing and issue resolution
- Feature implementation based on specifications
- Code review and quality improvement

### Tester Agent
- Test creation (unit, integration, end-to-end)
- Test strategy development
- Test automation guidance
- Quality assurance methodologies
- Test data generation

### Debugger Agent
- Issue diagnosis and root cause analysis
- Debugging techniques and tools
- Error interpretation and resolution
- Performance bottleneck identification
- Debugging session guidance

### DevOps Agent
- Deployment strategies and tools
- CI/CD pipeline creation and optimization
- Infrastructure as Code (IaC)
- Containerization and orchestration
- Monitoring and logging setup
- Release management processes

### Documentation Agent
- Technical documentation creation
- README and getting started guides
- API documentation
- Code comments and inline documentation
- User guides and tutorials
- Documentation maintenance and updates

## Customization
You can customize these agents by:
- Modifying the descriptions to better match your needs
- Adding specific tools or capabilities relevant to your projects
- Changing the example prompts to match your common use cases
- Creating specialized variants for specific technologies or domains

## Notes
- These agents use the "general-purpose" subagent type as a base since custom agent types need to be defined in the agent files themselves
- For more specialized agents, you can modify the subagent_type field in the Agent call
- The effectiveness of these agents depends on the clarity and specificity of your prompts