---
type: research
domain: github
status: researched
verified: 2026-10-07
source_type: primary
---

# GitHub Copilot Customization

## Findings

GitHub documents several customization layers: repository-wide instructions, path-specific instructions, agent instructions, custom agents, skills and MCP servers. Copilot CLI can combine applicable instruction sources rather than relying on a simple priority fallback.

Repository-wide instructions use `.github/copilot-instructions.md`. Path-specific instructions use `.github/instructions/**/*.instructions.md` with `applyTo` patterns. Agent profiles are Markdown files with YAML frontmatter and can define prompts, tools and MCP servers.

## PB-GDS mapping

- PB-GH-006 → native GitHub AI customization locations
- PB-AI-003 → artifact classification
- PB-AI-004 → provenance and evaluation
- PB-QA-002 → evaluation of prompts and agent behavior

## Design rule

Use the narrowest native mechanism that matches the behavior being encoded. Keep large workflow-specific instructions in skills or agents rather than bloating repository-wide instructions.

## Sources

- https://docs.github.com/en/copilot/reference/custom-instructions-support
- https://docs.github.com/en/copilot/how-tos/copilot-cli/customize-copilot/add-custom-instructions
- https://docs.github.com/en/copilot/concepts/agents/copilot-cli/about-custom-agents
- https://docs.github.com/en/copilot/concepts/agents/copilot-cli/comparing-cli-features
