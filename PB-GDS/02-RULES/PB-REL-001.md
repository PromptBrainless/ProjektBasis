# PB-REL-001 — Release state must be explicit

- type: WORKFLOW
- source: PB-GDS-SRC-004

## Principle

A working tree, branch, merged change, tagged release and deployed artifact are different states.

## Agent behavior

For release work, identify:
- source commit
- target ref
- version/tag
- build artifact
- deployment target
- verification evidence

Never imply deployment merely because a commit or tag exists.

## Related

PB-GIT-001
PB-AI-001
PB-QA-001
