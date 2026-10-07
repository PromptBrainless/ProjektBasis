# Source 006 — GitHub Actions security and policies

Canonical sources:
https://docs.github.com/en/actions/reference/security/secure-use
https://docs.github.com/en/actions/reference/workflows-and-actions/workflow-syntax
https://docs.github.com/en/actions/concepts/about-actions-policies

## Extracted principles

GitHub documents least-privilege permissions for GITHUB_TOKEN, secure handling of secrets, risks from untrusted code and third-party actions, and workflow execution protections.

## Operational consequence

CI/CD configuration is security-sensitive code.

PB-GDS must inspect permissions, triggers, third-party actions, secrets, untrusted input and deployment boundaries.

## Derived rule IDs

PB-SEC-001
PB-SEC-002
PB-QA-001
PB-GH-005
