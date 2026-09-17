# Capture workflow

## Purpose

Preserve the smallest amount of evidence needed for future leadership continuity.

## Inputs

- a user-provided note, observation, outcome, or source reference
- the date and context of the event
- the intended person or workstream record
- any known privacy or official-record boundary

## Steps

1. Decide whether the information has a future leadership use.
2. Remove sensitive detail that is not required.
3. Separate facts, interpretation, commitments, decisions, and open questions.
4. Add a dated entry to the relevant raw log using the matching template.
5. Link rather than copy an official record.
6. Propose a digest update only if the current view materially changed.
7. Ask for approval for consequential or durable writeback.

## Allowed files

- `people/*/conversation-log.md`
- `workstreams/*/meeting-log.md`
- a new draft created from `templates/conversation-entry.md`
- the relevant digest, after approval
- `me/decisions-log.md`, after decision confirmation

## Approval boundaries

Approval is required before recording a consequential judgment about a person, changing a profile, finalizing a decision, editing historical evidence, or copying information from a more restricted source.

## Failure behavior

- If the source, date, or subject is unclear, do not guess.
- If the content includes restricted or sensitive data, stop and suggest a safer abstraction.
- If an official system owns the record, store only a safe reference.
- If fact and interpretation cannot be separated, capture an open question instead.

## Exit criteria

- the useful evidence is dated and attributable
- interpretation is labeled
- no unnecessary sensitive detail was copied
- commitments and decisions are clearly confirmed or proposed
- any digest update is approved or listed as proposed
