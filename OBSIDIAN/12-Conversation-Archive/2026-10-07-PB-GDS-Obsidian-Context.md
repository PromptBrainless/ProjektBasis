---
type: conversation-archive
category: conversation-archive
status: archived
date: 2026-10-07
scope: current-conversation
---

# Conversation Archive — PB-GDS / Obsidian Knowledge System

## 1. Purpose

This archive preserves the substantive context, decisions, architecture and implementation state developed in this conversation around Git, GitHub, PB-GDS, AI artifacts and Obsidian.

This is a structured knowledge archive, not a verbatim transcript. Executable project artifacts remain canonical in GitHub.

## 2. Initial objective

The goal was to build a serious, research-backed Git/GitHub development and knowledge system for PromptBrainless.

The user requested that GitHub, Git, GitHub Skills, Microsoft GitHub training, Learn Git Branching and related documentation be researched carefully, including relevant articles and sub-articles, and that working instructions, numbered rules, skills, workflows and reusable AI artifacts be derived from evidence rather than assumptions.

Important source areas originally identified:
- GitHub Start Your Journey
- git-scm.com
- Git documentation
- GitHub Skills
- Microsoft GitHub training
- Learn Git Branching

## 3. PB-GDS

PB-GDS means PromptBrainless Git/GitHub Development System.

Current conceptual structure:

```
PB-GDS/
├── 00-SYSTEM/
├── 01-SOURCES/
├── 02-RULES/
├── 03-SKILLS/
├── 04-WORKFLOWS/
├── 05-AI-LIBRARY/
└── 99-INDEX/
```

The system separates evidence, rules, procedural skills, workflows and reusable AI artifacts.

## 4. Core operating principles

- Evidence before confidence.
- Never claim execution that was not verified.
- Inspect repository and Git state before mutation.
- Use branches as collaboration boundaries.
- Separate fetching remote state from integration.
- Commit only intentional state.
- Verification is part of the change.
- Security and least privilege are part of repository engineering.
- AI artifacts require provenance and evaluation.
- Provider-specific behavior must be distinguished from provider-neutral knowledge.
- Obsidian is not a second source of truth for executable project configuration.

## 5. Git/GitHub rules established

Relevant PB-GDS rules include:

- PB-GH-001 — GitHub as lifecycle platform
- PB-GH-002 — plan before non-trivial implementation
- PB-GH-004 — branches as collaboration boundaries
- PB-GH-005 — CI/CD and Actions as repository contract
- PB-GH-006 — GitHub native AI customization locations
- PB-GIT-001 — separate Git state layers
- PB-GIT-002 — inspect before history mutation
- PB-GIT-003 — separate fetch from integration
- PB-GIT-004 — commit only intentional state
- PB-AI-001 — never claim unverified execution
- PB-AI-002 — evidence before confidence
- PB-AI-003 — classify AI artifacts by execution role
- PB-AI-004 — provenance and evaluation for prompts
- PB-SEC-001 — repository security
- PB-SEC-002 — least privilege for Actions
- PB-SEC-003 — third-party automation as trust boundary
- PB-QA-001 — verification is part of change
- PB-QA-002 — prompt/AI artifact evaluation
- PB-REL-001 — explicit release state
- PB-WF-001 — bounded development lifecycle

## 6. Skills established

PB-GDS contains/references skills for:

- repository analysis
- Git state analysis
- change review
- secure change
- feature development
- bug investigation
- release audit
- PR review
- recovery
- GitHub Actions audit

The coding-agent lifecycle is:

```
UNDERSTAND
→ INSPECT
→ PLAN
→ BRANCH
→ IMPLEMENT
→ TEST
→ REVIEW
→ INTEGRATE
```

## 7. AI Library

The AI library is structured as:

```
PB-GDS/05-AI-LIBRARY/
├── sources/
├── instructions/
├── prompts/
├── agents/
├── skills/
├── workflows/
├── templates/
├── evaluations/
└── deprecated/
```

Artifact status:

```
DRAFT
→ RESEARCHED
→ TESTED
→ VALIDATED
→ DEPRECATED
```

No artifact should be called validated or production-ready without provenance and an explicit evaluation method.

Existing researched artifacts include:
- repository-agent-foundation
- codebase-investigation prompt
- code-reviewer agent
- code-reviewer evaluation cases
- artifact schema
- AI customization source material

## 8. GitHub AI customization research

The conversation researched official GitHub documentation around:

- repository-wide custom instructions
- path-specific instructions
- AGENTS.md and related agent instruction files
- custom agents
- prompt files
- skills
- MCP servers
- Copilot CLI customization

The key architectural decision was to distinguish:

```
Instructions
Prompts
Agents
Skills
Workflows
Templates
Evaluations
```

rather than treating all Markdown AI files as interchangeable.

## 9. Obsidian decision

The user asked whether Obsidian should be connected.

The selected architecture is:

```
GitHub = operational source of truth
Obsidian = knowledge layer
AI agents = consumers/operators
```

GitHub remains canonical for:
- source code
- executable configuration
- agent files
- skills
- workflows
- releases
- PRs
- issues
- repository history

Obsidian is intended for:
- concepts
- research
- relationships
- architecture knowledge
- prompt engineering
- evaluations
- project context
- lessons learned
- cross-project knowledge

The system deliberately avoids maintaining two independent mutable sources of truth.

## 10. Obsidian vault architecture

Current planned vault:

```
OBSIDIAN/
├── 00-Dashboard/
├── 01-MOCs/
├── 02-Concepts/
├── 03-Git-GitHub/
├── 04-AI-Agents/
├── 05-Prompt-Engineering/
├── 06-AI-Generators/
├── 07-MCP/
├── 08-Engineering/
├── 09-Security/
├── 10-Projects/
├── 11-Research/
├── 12-Conversation-Archive/
├── 90-Templates/
└── 99-Archive/
```

The new category created by this archive is:

**12-Conversation-Archive**

Its purpose is to preserve conversation-derived project decisions and context without mixing them into canonical technical knowledge.

## 11. Obsidian structures created

Existing knowledge-layer structures include:

- Dashboard
- Knowledge System MOC
- Git/GitHub MOC
- AI Agents MOC
- Prompt Engineering MOC
- AI Generators MOC
- Research MOC
- Source-of-Truth concept
- Research lifecycle
- Agent lifecycle
- Prompt evaluation
- Prompt template
- Generator provider profile
- ProjektBasis project note

## 12. Research layer

The second research layer added structured notes for:

### GitHub
GitHub Copilot customization and native instruction/agent mechanisms.

### Coding agents
A coding agent is treated as a bounded system combining:
- instructions
- tools
- repository context
- skills
- execution
- verification
- reporting

Minimum agent contract:
1. establish repository context
2. read applicable instructions
3. identify outcome and acceptance criteria
4. inspect code and Git state
5. plan
6. make smallest coherent change
7. verify
8. inspect diff
9. report evidence and limitations

### Prompt engineering
Prompts require:
- target
- purpose
- variables
- expected output
- provenance
- evaluation
- limitations

One successful generation is not sufficient evidence of quality.

### AI generators
The provider-neutral architecture separates:
- image
- video
- audio
- music
- speech
- multimodal
- 3D
- general generation

The first provider-specific research note created was Midjourney.

### MCP
The architecture distinguishes:
- host
- client
- server
- tools
- resources
- prompts
- capability negotiation
- authorization/trust boundaries

MCP Skills were also identified as a relevant bridge between skills and MCP resources.

## 13. Research registry

The research registry tracks:

- GitHub Copilot customization
- coding-agent architecture
- prompt research/evaluation methodology
- Midjourney
- MCP architecture

Future providers should be added only after authoritative research.

## 14. Repository work performed

The conversation used the GitHub connector and deliberately worked through branches rather than directly mutating main.

Relevant branches included:
- chore/pb-gds-foundation
- chore/obsidian-knowledge-system
- docs/conversation-archive-obsidian

Repository identity/cover work was also prepared for several PromptBrainless repositories, including:
- ProjektBasis
- copilot-cli
- tinymce-ai-skills
- worldforge-studio
- Fokus-Dokus
- Feldwerk

Repository cover graphics and README integration were developed on isolated branches.

## 15. Repository ecosystem identified

Repositories observed in the PromptBrainless GitHub context included:
- ProjektBasis
- copilot-cli
- tinymce-ai-skills
- worldforge-studio
- Fokus-Dokus
- Feldwerk

These represent different project/application areas and are intended to benefit from shared PB-GDS knowledge while retaining repository-specific instructions.

## 16. Important architectural decisions

### Decision A — GitHub and Obsidian are complementary

Do not synchronize everything indiscriminately.

### Decision B — Research precedes reusable prompts

No large unverified prompt dump.

### Decision C — Provider-neutral and provider-specific prompting are separate

A generic prompt methodology must not be confused with a vendor's current syntax or parameters.

### Decision D — AI artifacts require evaluation

Prompt, agent and skill quality must be demonstrated rather than assumed.

### Decision E — Conversation archives are separate

Conversation-derived context belongs in the Conversation Archive category rather than being silently promoted to technical truth.

## 17. Next intended development stage

The next logical expansion is a researched provider matrix covering:

- image generation
- video generation
- audio/music generation
- speech/voice generation
- 3D generation
- multimodal generation
- coding agents
- MCP servers and skills

For each provider/system:

```
Official documentation
→ capability model
→ prompt/input model
→ controls
→ constraints
→ evaluation cases
→ empirical observations
→ reusable prompt
→ skill/agent if justified
→ PB-GDS integration
```

## 18. Quality boundary

The central quality rule for the entire system is:

> Research first. Separate documented fact from inference. Evaluate behavior before promoting an artifact to reusable or validated knowledge.

## 19. Archive status

This archive represents the current structured state of the conversation and the resulting project decisions.

Canonical executable artifacts remain in PB-GDS.

Obsidian remains the curated knowledge layer.
