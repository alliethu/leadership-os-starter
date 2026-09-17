---
name: leadership-os-audit
description: Audit the leadership OS for freshness, evidence traceability, privacy boundaries, decision clarity, and useful writeback.
---

# Leadership OS audit

Use this skill to keep the system trustworthy and small. It audits the records and operating rules, not the quality of the leader.

## Required context

- `ARCHITECTURE.md`
- `PRIVACY.md`
- `me/_profile.md`
- `me/weekly-digest.md`
- `me/decisions-log.md`
- `me/relationships.yml`
- a scoped set of people and workstream records

## Workflow

1. Agree on the files and time horizon in scope.
2. Check whether digests have dates, sources, owners, and open questions.
3. Sample material digest claims against raw history.
4. Check that profiles contain durable context rather than status.
5. Check that decisions are confirmed, owned, and linked to outcomes.
6. Identify duplicated, stale, overly sensitive, or unsourced content.
7. Rank cleanup by risk and usefulness.
8. Propose small, reviewable changes.

## Output

| Priority | Finding | Evidence | Risk | Suggested change | Approval |
| --- | --- | --- | --- | --- | --- |

Then include:

### Healthy patterns
### Missing evidence
### Privacy review
### Smallest useful cleanup

## Facts versus interpretation

Report file conditions as facts with paths. Label judgments about usefulness, staleness, or risk as audit interpretation. Do not infer why a file was neglected.

## Writeback

### Allowed

- Fix broken relative links and mechanical formatting.
- Add missing structural headings without changing meaning.
- Draft an audit report in the conversation.

### Approval required

- Delete, move, redact, or materially rewrite records.
- Change profile facts, digests, decisions, or relationship entries.
- Broaden file access or share audit findings.
- Introduce automation or external integrations.

## Stop conditions

Stop if scope is undefined, restricted content cannot be reviewed safely, a suspected secret is found, or cleanup could remove evidence or change meaning.
