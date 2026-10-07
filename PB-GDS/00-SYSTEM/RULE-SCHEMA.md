# PB-GDS Rule Schema

Every rule uses a stable identifier.

## ID format

PB-<DOMAIN>-<NUMBER>

Domains:
GH, GIT, WF, AI, SEC, QA, REL

## Required fields

id
title
type
source
principle
agent_behavior
prohibited_behavior
verification
risk
related_rules

## Rule types

FACT_DERIVATION
OPERATIONAL
SAFETY
QUALITY
WORKFLOW
RECOVERY

## Rule quality standard

A rule must be:
- atomic where practical
- testable or verifiable
- traceable to a source or explicit project decision
- unambiguous about required behavior
- clear about exceptions
