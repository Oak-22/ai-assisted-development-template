# Incident Reports

This README defines the purpose of the incident reports section of the
engineering knowledge base.

Store concise writeups for failures, debugging journeys, and
postmortems that produced useful learning.

## Recommended Report Structure

1. Summary: what happened and customer impact.
2. Timeline: key events and detection points.
3. Root Cause: technical and process contributors.
4. Resolution: immediate fix and why it worked.
5. Prevention: safeguards, tests, alerts, or process updates.
6. Lessons: what changed in engineering behavior.

## Example Enterprise-Oriented Reports

- `incident-api-timeouts-during-traffic-spike.md`
- `incident-misconfigured-feature-flag-rollout.md`
- `incident-data-pipeline-late-arrival-regression.md`
- `incident-cicd-secret-rotation-build-failures.md`

## Quality Bar

Avoid blame language. Focus on reproducible causes, system-level fixes,
and measurable prevention.
