# PB-AI-003 — Classify AI artifacts by execution role

- type: OPERATIONAL
- source: PB-GDS-SRC-007

## Classes

INSTRUCTION = persistent behavioral context.
PROMPT = task-specific reusable request.
AGENT = specialist configuration with defined behavior/tools/context.
SKILL = reusable procedural capability.
WORKFLOW = ordered multi-step operating procedure.
TEMPLATE = structured starting point with variables.
EVALUATION = test case used to measure output quality.

## Agent behavior

Before storing or reusing an AI artifact, assign one primary class.

Do not store an agent profile as if it were merely a prompt.

## Related

PB-AI-004
PB-GH-006
PB-QA-002
