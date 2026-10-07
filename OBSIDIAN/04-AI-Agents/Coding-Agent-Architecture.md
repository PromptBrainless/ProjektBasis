---
type: research
domain: coding-agents
status: researched
verified: 2026-10-07
source_type: primary
---

# Coding Agent Architecture

## Model

A coding agent is not merely a prompt. It is a bounded system combining instructions, tools, repository context, skills, execution, verification and reporting.

## Minimum contract

1. Establish repository context.
2. Read applicable instructions.
3. Identify desired outcome and acceptance criteria.
4. Inspect relevant code and Git state.
5. Plan before non-trivial mutation.
6. Make the smallest coherent change.
7. Run applicable verification.
8. Inspect the resulting diff.
9. Report evidence, limitations and remaining risk.

## GitHub alignment

GitHub Copilot CLI supports custom instructions, custom agents, skills, MCP servers and hooks. Custom agents can define tools and MCP servers through Markdown agent profiles.

## PB-GDS mapping

- feature-development skill
- bug-investigation skill
- pr-review skill
- secure-change skill
- recovery skill
- PB-WF-001
- PB-AI-001
- PB-AI-002
- PB-AI-003
- PB-QA-001

## Source

https://docs.github.com/en/copilot/concepts/agents/copilot-cli/about-custom-agents
