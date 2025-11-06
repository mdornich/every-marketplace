# Compounding Engineering Plugin

AI-powered development tools that get smarter with every use. Make each unit of engineering work easier than the last.

## Overview

This Claude Code plugin embodies the **compounding engineering philosophy**: each unit of engineering work should make subsequent units of work easier—not harder. It includes 17 specialized AI agents and 6 powerful commands designed to enhance your development workflow.

## What's Included

- **17 Specialized Agents** - Expert AI agents for code review, security, performance, and more
- **6 Workflow Commands** - Powerful slash commands to streamline your development process
- **0 Hooks** - (Coming soon)

## Installation

```bash
# Add the marketplace
claude /plugin marketplace add https://github.com/EveryInc/every-marketplace

# Install the plugin
claude /plugin install compounding-engineering
```

## Agents

### Code Review Agents

Expert reviewers for different languages and frameworks:

- **kieran-rails-reviewer** - Super senior Rails code reviewer with strict conventions and exceptional quality standards
- **kieran-typescript-reviewer** - Super senior TypeScript code reviewer with strict type safety and quality standards
- **kieran-python-reviewer** - Super senior Python code reviewer with strict conventions and quality standards
- **dhh-rails-reviewer** - Brutally honest Rails code review from DHH's perspective, identifying anti-patterns
- **code-simplicity-reviewer** - Reviews code for unnecessary complexity and suggests simplifications

### Architecture and Quality Agents

System-level analysis and quality assurance:

- **architecture-strategist** - System architecture expert analyzing code changes and design decisions
- **security-sentinel** - Elite security specialist performing comprehensive vulnerability assessments
- **performance-oracle** - Elite performance optimization expert identifying bottlenecks and ensuring scalability
- **data-integrity-guardian** - Data integrity specialist ensuring database consistency and transaction safety

### Research and Knowledge Agents

Information gathering and best practices:

- **best-practices-researcher** - Expert technology researcher discovering and synthesizing best practices
- **framework-docs-researcher** - Framework documentation specialist researching official docs
- **repo-research-analyst** - Repository research analyst examining structure and conventions
- **feedback-codifier** - Feedback analyst codifying review patterns to improve reviewer agents

### Specialized Analysis Agents

Deep-dive analysis for specific concerns:

- **pattern-recognition-specialist** - Pattern recognition expert identifying recurring themes and anti-patterns
- **git-history-analyzer** - Git history expert analyzing commit patterns and code evolution
- **pr-comment-resolver** - PR comment specialist systematically resolving review feedback

### Content and Style Agents

Editorial and content quality:

- **every-style-editor** - Expert copy editor ensuring compliance with Every's editorial standards

## Commands

### Workflow Commands

- **/review** - Perform exhaustive code reviews using multi-agent analysis and Git worktrees
- **/plan** - Transform feature descriptions into well-structured GitHub issues
- **/work** - Analyze work documents and systematically execute tasks
- **/triage** - Present findings one by one for decision making

### Productivity Commands

- **/resolve_todo_parallel** - Resolve all TODO comments using parallel processing
- **/generate_command** - Create custom Claude Code commands for your workflow

## Usage Examples

### Using Agents

```bash
# Review Rails code with Kieran's standards
claude agent kieran-rails-reviewer "Review the authentication controller changes"

# Security audit your code
claude agent security-sentinel "Audit the API endpoints for vulnerabilities"

# Research best practices
claude agent best-practices-researcher "What are the best practices for FastAPI?"
```

### Using Commands

```bash
# Review a pull request
claude /review 123

# Create a GitHub issue from a description
claude /plan "Add user authentication with OAuth"

# Execute a work plan
claude /work path/to/plan.md

# Triage code review findings
claude /triage
```

## Philosophy: Compounding Engineering

This plugin is built on the principle that **each unit of engineering work should make subsequent units of work easier**:

1. **Plan** → Understand the change needed and its impact
2. **Delegate** → Use AI tools to help with implementation
3. **Assess** → Verify changes work as expected
4. **Codify** → Update knowledge with learnings

The more you use these tools, the more they learn your patterns and preferences, making your workflow progressively more efficient.

## Key Features

### Multi-Agent Code Review

The `/review` command orchestrates multiple specialized agents in parallel to provide comprehensive code analysis from different perspectives:

- Language-specific reviewers (Rails, TypeScript, Python)
- Security and performance analysis
- Architecture and pattern recognition
- Git history analysis

### Parallel Processing

Commands like `/resolve_todo_parallel` use parallel agent execution to resolve multiple issues simultaneously, dramatically reducing turnaround time.

### Knowledge Capture

The `feedback-codifier` agent learns from your review patterns and updates reviewer configurations, making reviews more aligned with your standards over time.

### Context-Aware Planning

The `/plan` command researches your repository conventions and existing patterns before creating issues, ensuring consistency with your project standards.

## Contributing

This plugin is part of the Every marketplace. To contribute:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

MIT

## Author

**Kieran Klaassen**
Email: kieran@every.to
GitHub: [@kieranklaassen](https://github.com/kieranklaassen)

## Resources

- [Blog Post: My AI Had Already Fixed the Code Before I Saw It](https://every.to/source-code/my-ai-had-already-fixed-the-code-before-i-saw-it)
- [Claude Code Documentation](https://docs.claude.com/en/docs/claude-code)
- [Plugin Marketplace Documentation](https://docs.claude.com/en/docs/claude-code/plugin-marketplaces)

---

**Built with compounding engineering principles** - Each use makes the next one easier.
