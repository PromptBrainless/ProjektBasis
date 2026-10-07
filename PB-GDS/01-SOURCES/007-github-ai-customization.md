# Source 007 — GitHub AI Customization

Canonical sources:
- https://docs.github.com/en/copilot/reference/custom-instructions-support
- https://docs.github.com/en/copilot/concepts/prompting/response-customization
- https://docs.github.com/en/copilot/concepts/agents/copilot-cli/about-custom-agents
- https://docs.github.com/en/copilot/reference/customization-cheat-sheet

## Verified concepts

GitHub currently distinguishes:
- repository-wide custom instructions
- path-specific custom instructions
- agent instructions
- prompt files
- custom agents
- reusable skills

Copilot CLI supports repository-wide instructions, modular instructions and agent instruction files including AGENTS.md, CLAUDE.md and GEMINI.md.

Prompt files are reusable task-specific Markdown prompts. GitHub currently documents them as public preview for supported IDEs.

Custom agents are Markdown agent profiles with YAML frontmatter defining identity, description, tools/MCP configuration and behavioral instructions.

## PB-GDS consequence

Prompts must not be treated as one undifferentiated artifact type. The library distinguishes:
INSTRUCTION / PROMPT / AGENT / SKILL / WORKFLOW / TEMPLATE / EVALUATION.

## Derived rule IDs

PB-AI-003
PB-AI-004
PB-GH-006
PB-QA-002
