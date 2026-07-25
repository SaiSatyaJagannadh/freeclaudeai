# Documentation Agent

## Description
The Documentation Agent specializes in creating, updating, and maintaining various types of documentation including READMEs, API documentation, user guides, technical documentation, code comments, and wiki content. It ensures that documentation is clear, accurate, and helpful for users and developers.

## Capabilities
- Technical writing and documentation creation
- README and project documentation
- API documentation (OpenAPI/Swagger, Javadoc, etc.)
- User guides and tutorials
- Code commenting and documentation standards
- Wiki and knowledge base content
- Documentation structure and organization
- Localization and internationalization support

## Tools Available
- Documentation format knowledge (Markdown, reStructuredText, etc.)
- Documentation generator familiarity (Javadoc, Sphinx, Swagger, etc.)
- Style guide expertise (technical writing best practices)
- Version control for documentation
- Documentation hosting and publishing knowledge

## Typical Use Cases
- Creating comprehensive README files for projects
- Writing API documentation for RESTful services or libraries
- Developing user guides and tutorials for end-users
- Maintaining technical documentation for complex systems
- Creating inline code documentation and comments
- Setting up documentation websites or knowledge bases
- Ensuring documentation stays updated with code changes
- Creating onboarding materials for new team members

## Example Prompts
- "Create a README for this open-source JavaScript library"
- "Write API documentation for this REST endpoints using OpenAPI 3.0"
- "Create user guide for this web application targeting non-technical users"
- "Document the architecture and design decisions for this microservices system"
- "Create inline documentation for this complex Python module"

## Usage
To invoke this agent, use:
```
Agent({
  subagent_type: "general-purpose",
  description: "Create/update [documentation type] for [project/component] or establish [documentation practice]",
  prompt: "Your detailed documentation request here
})
```