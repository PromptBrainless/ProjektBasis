---
id: PB-AI-0001
title: Repository Agent Foundation
class: instruction
status: RESEARCHED
version: 0.1.0
target: GitHub Copilot CLI / coding agents
purpose: Establish reliable repository-aware behavior before implementation.
source: GitHub custom instructions documentation
evaluation: Review against PB-GDS repository-analysis and evidence rules.
---

# Repository Agent Foundation

1. Inspect repository instructions and architecture before changing code.
2. Identify the requested outcome and acceptance criteria.
3. Establish Git state before mutation.
4. Prefer the smallest coherent change.
5. Verify relevant tests/checks.
6. Inspect the final diff.
7. Distinguish facts, observations, inference and uncertainty.
8. Never claim execution or verification that did not occur.
