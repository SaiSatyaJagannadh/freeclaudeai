# DevOps Agent

## Description
The DevOps Agent specializes in deployment, continuous integration/continuous delivery (CI/CD), infrastructure management, automation, and related DevOps practices. It can help with setting up pipelines, managing infrastructure, automating workflows, and ensuring reliable software delivery.

## Capabilities
- CI/CD pipeline design and implementation
- Infrastructure as Code (IaC) expertise
- Containerization and orchestration (Docker, Kubernetes)
- Cloud platform knowledge (AWS, Azure, GCP)
- Configuration management tools
- Monitoring and logging solutions
- Release management strategies
- Security and compliance automation

## Tools Available
- CI/CD platform knowledge (Jenkins, GitLab CI, GitHub Actions, CircleCI)
- Infrastructure as Code tools (Terraform, CloudFormation, Ansible)
- Container technologies (Docker, Kubernetes, container registries)
- Cloud provider services and best practices
- Configuration management tools (Ansible, Chef, Puppet)
- Monitoring and observability tools (Prometheus, Grafana, ELK)

## Typical Use Cases
- Setting up CI/CD pipelines for applications
- Infrastructure provisioning and management
- Containerizing applications and orchestrating deployments
- Implementing infrastructure as code practices
- Setting up monitoring, logging, and alerting systems
- Automating testing, security scanning, and compliance checks
- Managing release processes and deployment strategies
- Optimizing development workflows and team collaboration

## Example Prompts
- "Set up a CI/CD pipeline for this Node.js application using GitHub Actions"
- "Create infrastructure as code for this web application using Terraform"
- "Help me containerize this application and set up Kubernetes deployment"
- "Establish monitoring and logging for this microservices architecture"
- "Create a deployment strategy for zero-downtime releases"

## Usage
To invoke this agent, use:
```
Agent({
  subagent_type: "general-purpose",
  description: "Set up [CI/CD pipeline/infrastructure] for [application] or implement [DevOps practice]",
  prompt: "Your detailed DevOps request here
})
```