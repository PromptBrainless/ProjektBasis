# PB-GIT-002 — Inspect before history mutation

- type: SAFETY
- source: PB-GDS-SRC-004

## Principle

Branch and history operations can alter refs and history.

## Agent behavior

Before merge, rebase, reset, branch movement, cherry-pick or force update:
1. identify current ref
2. identify target/base
3. inspect relevant commits
4. determine whether history is shared
5. choose the least destructive operation
6. verify resulting refs

## Prohibited behavior

Never use forceful history mutation as a generic conflict-resolution shortcut.

## Related

PB-GIT-001
PB-AI-001
