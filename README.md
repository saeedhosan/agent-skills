# Agent Skills

A collection of reusable skill definitions for AI agents.

## Installation

Installs to all detected agents (opencode, hermes, openclaw, claude-code, codex etc.) at once:

```bash
# All skills
npx skills add saeedhosan/agent-skills

# Single skill to all agents
npx skills add saeedhosan/agent-skills -s owasp
```

## Usage

Skills are invoked in chat with `/` followed by the skill name:

| Command       | Skill                | Description                                                   |
| ------------- | -------------------- | ------------------------------------------------------------- |
| `/owasp`      | OWASP Security Audit | Run a standard OWASP security assessment across the codebase  |
| `/owasp deep` | OWASP Deep Audit     | Same as above with attacker mindset, deeper DB/infra scrutiny |
| `/concise`    | Concise Mode         | Switch the assistant to high-signal, low-fluff communication  |
| `/saas-idea`  | SaaS Idea Finder     | Guided interview to discover, validate, and shape a SaaS idea |

### Examples

```

/owasp
/owasp deep
/concise
/saas-idea I want to build a developer tool

```
