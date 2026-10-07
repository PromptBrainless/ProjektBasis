# PB-SEC-003 — Third-party automation is a trust boundary

- type: SECURITY
- source: PB-GDS-SRC-006

## Agent behavior

When reviewing Actions or automation, inspect:
- action owner
- pinned version/reference
- permissions
- token/secrets access
- event trigger
- untrusted input
- execution context

Treat external actions as code with supply-chain implications.

## Related

PB-SEC-001
PB-SEC-002
