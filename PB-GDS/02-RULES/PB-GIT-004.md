# PB-GIT-004 — Commit only intentional state

- type: OPERATIONAL
- source: PB-GDS-SRC-004

## Agent behavior

Before committing:
1. inspect status
2. inspect unstaged diff
3. inspect staged diff
4. isolate intended files/changes
5. run relevant checks
6. commit
7. verify resulting history

## Prohibited behavior

Do not blindly stage or commit unrelated repository changes.

## Related

PB-GIT-001
PB-AI-001
PB-QA-001
