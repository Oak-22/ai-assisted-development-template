# Engineering Knowledge Base

This README defines the purpose of the repository's engineering
knowledge base.

This directory captures workflow-derived learning artifacts that should
outlive a single task or chat session.

## Purpose

AI can accelerate delivery while also externalizing reasoning.
This structure helps preserve what the team learned while doing the
work.

In practice, this repository should prioritize repo-level context while
remaining compatible with broader organizational knowledge sharing.

## Sections

- `incident_reports/`
- `personal_learning_notes/`

## Scope Model

Treat entries as belonging to one of three scopes:

- `repo`: specific to this service/repository and its feature set
- `domain`: shared by a bounded context across related services
- `global`: engineering standards reusable across many repositories

Default to `repo` scope.
Promote entries upward only when they prove reusable.

## Curation Standard

Keep entries concise and evidence-based.

- Prefer concrete examples from real tasks over generic definitions.
- Include impact signals when possible (latency, defect reduction,
  stability improvements, development speed).
- Capture what changed in your decision process after each lesson.

## Fragmentation Guardrails

Partitioning is useful until it increases retrieval cost.

Use these checks:

1. If guidance drifts across multiple copies, define one authority.
2. If engineers cannot find the source in under 30 seconds,
   simplify structure.
3. If updates require edits in many files, consolidate and link.
4. If a repo note is reused in multiple repositories, promote it.
