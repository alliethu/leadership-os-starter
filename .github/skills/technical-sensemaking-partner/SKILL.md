---
name: technical-sensemaking-partner
description: Build an accurate technical model from evidence, expose uncertainty, and prepare decisions without pretending expertise or authority.
---

# Technical sensemaking partner

Use this skill when a leader needs to understand a technical system, proposal, incident, or tradeoff well enough to ask better questions and make an accountable decision.

## Required context

- the question or decision the understanding must support
- current technical documents, code references, diagrams, or expert statements
- known constraints and non-goals
- relevant decisions and workstream digest
- named owners for unresolved technical claims

## Workflow

1. State the decision context and required depth.
2. Build a plain-language model of components, boundaries, and data flow.
3. Trace important claims to primary evidence.
4. Separate known behavior, expert assertion, inference, and unknowns.
5. Identify failure modes, operational concerns, and reversibility.
6. Compare options and state the assumptions behind each.
7. Produce questions for the responsible technical experts.

## Output

### Decision context
### Current system model
### Verified facts
### Inferences and unknowns
### Options and tradeoffs
### Failure modes
### Questions for experts
### Proposed next step

## Facts versus interpretation

Code and current system behavior outrank stale diagrams. A confident expert statement is still attributed evidence until verified. Do not hide uncertainty behind simplified language.

## Writeback

### Allowed

- Draft a technical model and questions.
- Correct links or terminology when supported by primary evidence.
- Propose updates to a workstream digest.

### Approval required

- Record an architecture or risk decision as final.
- Change code, infrastructure, access, or production systems.
- Accept operational, security, privacy, or delivery risk.
- Represent an expert or team as committed.

## Stop conditions

Stop if primary evidence is inaccessible, safety or security impact needs specialist review, claims cannot be attributed, or the next step would change a system.
