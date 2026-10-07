---
type: research
domain: mcp
status: researched
verified: 2026-10-07
source_type: primary
---

# Model Context Protocol — Architecture

## Core model

MCP standardizes a connection between AI applications and external systems. Its primitives include tools, resources and prompts. A host contains the AI application, a client speaks MCP, and a server exposes capabilities.

## Design implications

- Tools are action surfaces and require explicit trust boundaries.
- Resources provide contextual data.
- Prompts provide reusable interaction templates.
- Capabilities must be negotiated rather than assumed.
- MCP does not remove the need for application-level authorization, validation or least privilege.

## Skills extension

The MCP Skills extension defines a transport binding for serving Agent Skills through MCP resources. It explicitly uses `SKILL.md` as the minimal skill artifact and supports progressive disclosure of skill files.

## PB-GDS mapping

- PB-AI-003 → distinguish prompt, skill, workflow and agent
- PB-SEC-002 → least privilege
- PB-SEC-003 → third-party automation as trust boundary
- secure-change skill
- actions-audit skill

## Sources

- https://modelcontextprotocol.io/
- https://skills.extensions.modelcontextprotocol.io/specification/stable/skills
- https://ts.sdk.modelcontextprotocol.io/v2/
