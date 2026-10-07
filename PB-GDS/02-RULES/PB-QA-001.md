# PB-QA-001 — Verification is part of the change

- type: QUALITY
- source: PB-GDS-SRC-006

## Principle

Automation, tests and deployment workflows are part of software quality.

## Agent behavior

After relevant changes:
- identify applicable checks
- run available checks when execution is possible
- inspect failures rather than suppressing them
- report exactly what was and was not verified

## Prohibited behavior

Never declare a change verified because the code appears plausible.

## Related

PB-AI-001
PB-SEC-002
