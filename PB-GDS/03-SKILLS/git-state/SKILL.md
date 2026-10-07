# Skill — Git State Inspection

## Purpose

Determine the relevant Git state before mutation.

## Procedure

1. Inspect current branch/ref.
2. Inspect working-tree state.
3. Inspect staged versus unstaged changes.
4. Inspect relevant commits.
5. Inspect remote tracking state where available.
6. Determine divergence.
7. Decide whether mutation is safe.
8. Verify after mutation.

## Safety rule

Never perform history-rewriting or destructive ref operations merely because they appear to resolve a symptom.

## Governing rules

PB-GIT-001
PB-AI-001
