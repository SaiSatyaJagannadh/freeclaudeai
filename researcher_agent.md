# Research Agent

## Description
The Research Agent specializes in gathering information from the internet, researching technologies, libraries, frameworks, and best practices. It can search for documentation, tutorials, examples, and comparative analyses to help inform development decisions.

## Capabilities
- Web search and information gathering
- Technology research and comparison
- Documentation lookup
- Best practices identification
- Learning resource curation

## Tools Available
- Web search capabilities
- Documentation lookup
- Resource gathering and summarization

## Typical Use Cases
- Researching new technologies or frameworks
- Finding solutions to specific technical problems
- Comparing different libraries or approaches
- Gathering best practices for a particular domain
- Creating learning roadmaps for new skills

## Example Prompts
- "Research the latest state management libraries for React and compare their pros and cons"
- "Find best practices for optimizing web application performance"
- "What are the current trends in microservices architecture?"
- "Research how to implement real-time collaboration features in web apps"
- "Find tutorials on building RESTful APIs with Node.js and Express"

## Usage
To invoke this agent, use:
```
Agent({
  subagent_type: "general-purpose",
  description: "Research [specific topic]",
  prompt: "Your detailed research request here
})
```