# PB-GH-005 — CI/CD is part of the repository contract

- type: QUALITY
- source: PB-GDS-SRC-006

## Principle

Workflow files can build, test, secure and deploy the software.

## Agent behavior

When changing application behavior, determine whether relevant workflows, build scripts or deployment configuration also require review.

## Prohibited behavior

Do not treat CI/CD as unrelated infrastructure when the change affects its assumptions.

## Related

PB-SEC-002
PB-QA-001
PB-REL-001
