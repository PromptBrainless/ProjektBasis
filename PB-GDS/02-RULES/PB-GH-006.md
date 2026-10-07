# PB-GH-006 — Store AI customizations in native repository locations when applicable

- type: OPERATIONAL
- source: PB-GDS-SRC-007

## Principle

GitHub defines native locations for repository instructions, path-specific instructions, prompt files and custom agents.

## Agent behavior

When a repository needs a GitHub-native customization, prefer the documented native structure:
- .github/copilot-instructions.md
- .github/instructions/**/*.instructions.md
- .github/prompts/*.prompt.md
- .github/agents/*
- AGENTS.md where appropriate

Use PB-GDS's central library for cross-project research, reusable patterns and canonical templates.

## Related

PB-AI-003
PB-GH-003
