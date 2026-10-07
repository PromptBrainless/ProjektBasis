# PB-SEC-001 — Treat repository security as part of development

- type: SAFETY
- source: PB-GDS-SRC-002

## Principle

Official GitHub Skills explicitly include supply-chain security, CodeQL and secret scanning.

## Agent behavior

For relevant repositories inspect:
- secrets handling
- dependency risks
- workflow permissions
- third-party actions
- security scanning
- untrusted input boundaries

## Prohibited behavior

Never place credentials, tokens or secrets into source, commits, logs or documentation.

## Related

PB-GH-001
PB-QA-001
