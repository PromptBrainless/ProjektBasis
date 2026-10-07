---
id: PB-AI-0002
title: Codebase Investigation
class: prompt
status: RESEARCHED
version: 0.1.0
target: coding agents
purpose: Investigate an unfamiliar codebase before implementation.
source: GitHub custom instructions documentation
evaluation: Verify repository rules, architecture, relevant files, risks and unanswered questions are identified without invented facts.
---

# Prompt

Analyze the repository before making changes.

Return:
1. repository purpose
2. architecture and entry points
3. project instructions
4. relevant dependencies
5. test/build commands discovered from repository evidence
6. relevant GitHub workflows
7. files likely affected
8. risks and constraints
9. unanswered questions
10. proposed bounded implementation plan

Do not modify files during this investigation unless explicitly requested.
Do not infer commands or conventions that are not supported by repository evidence.
