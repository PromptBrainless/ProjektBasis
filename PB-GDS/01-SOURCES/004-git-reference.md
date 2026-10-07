# Source 004 — Git Reference

Canonical source:
https://git-scm.com/docs

## Scope

The official Git reference covers porcelain and plumbing commands, including repository creation, cloning, status, staging, commits, branches, merging, rebasing, remotes, patching, debugging and repository administration.

## Operational consequence

PB-GDS must distinguish:
- working tree
- index
- commit graph
- refs
- remote-tracking refs
- remotes
- reflogs
- worktrees

A command is never modeled only by its surface syntax; its effect on repository state matters.

## Derived rule IDs

PB-GIT-001
PB-GIT-002
PB-GIT-003
PB-GIT-004
PB-AI-001
