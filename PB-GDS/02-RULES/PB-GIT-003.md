# PB-GIT-003 — Separate fetch from integration

- type: OPERATIONAL
- source: PB-GDS-SRC-004

## Principle

Obtaining remote information and integrating it into a local branch are separate concerns.

## Agent behavior

When remote state matters:
1. inspect or fetch remote state
2. determine divergence
3. choose merge, rebase or another integration strategy
4. integrate deliberately
5. verify

Do not treat pull as a universally interchangeable operation.

## Related

PB-GIT-001
PB-GIT-002
PB-WF-002
