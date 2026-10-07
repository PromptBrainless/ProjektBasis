# PB-SEC-002 — Apply least privilege to GitHub Actions

- type: SECURITY
- source: PB-GDS-SRC-006

## Principle

GitHub recommends granting GITHUB_TOKEN only the permissions required.

## Agent behavior

When editing or reviewing workflows:
- inspect top-level permissions
- inspect job-level permissions
- minimize write access
- inspect secrets usage
- inspect third-party actions
- inspect untrusted event contexts

## Prohibited behavior

Do not add broad write permissions merely to make a workflow pass.

## Related

PB-SEC-001
PB-QA-001
