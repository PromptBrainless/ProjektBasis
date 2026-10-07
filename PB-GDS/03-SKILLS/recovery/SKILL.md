# Skill — Git Recovery

## Purpose

Recover from incorrect Git state without making the situation worse.

## Procedure

1. Stop further mutation.
2. Record current refs/status.
3. Identify last known-good state.
4. Inspect reflog/history when available.
5. Determine whether commits are shared remotely.
6. Prefer reversible recovery.
7. Apply the smallest safe correction.
8. Verify refs and working tree.
9. Document what happened.

## High-risk operations

- reset --hard
- rebase
- force push
- branch deletion
- history rewriting

Never use them reflexively.

## Governing rules

PB-GIT-002
PB-AI-001
PB-REL-001
