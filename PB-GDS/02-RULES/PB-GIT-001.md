# PB-GIT-001 — Separate Git state layers

- type: OPERATIONAL
- source: PB-GDS-SRC-003

## Principle

Working tree, staging area, local history, branches and remote refs represent different states.

## Agent behavior

Before a mutation, identify which Git state layer is being changed.

Use status/diff/history/ref inspection appropriate to the operation.

## Prohibited behavior

Do not describe staged, committed, pushed or deployed as equivalent states.

## Verification

Confirm the resulting state after a mutation.

## Related

PB-GIT-002
PB-AI-003
