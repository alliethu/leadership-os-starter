# System audit workflow

## Purpose

Keep the leadership OS current, traceable, private, and small enough to use.

## Inputs

- `ARCHITECTURE.md`
- `PRIVACY.md`
- the profile, digest, decision, relationship, people, and workstream files in scope
- the time horizon for freshness

## Steps

1. Define the file scope and audit period.
2. Run the leadership-os-audit skill.
3. Check digest freshness and evidence links.
4. Sample current claims against raw logs.
5. Check profiles for temporary status or unsupported interpretation.
6. Check decisions for confirmation, ownership, source, and review signal.
7. Check for duplicated, overly sensitive, stale, or orphaned content.
8. Rank findings by privacy risk, loss of trust, and maintenance cost.
9. Apply only approved cleanup.

## Allowed files

- all Markdown and YAML records explicitly included in the audit scope
- repository documentation for mechanical link or structure fixes
- no external systems

## Approval boundaries

Mechanical link and formatting fixes are allowed. Approval is required before deleting, moving, redacting, or materially rewriting records, changing a profile or digest, changing a decision, or introducing automation.

## Failure behavior

- If a suspected secret appears, stop, avoid repeating it, and ask the user to rotate and remove it.
- If a file is outside the agreed scope, do not inspect or change it.
- If evidence needed to validate a claim is unavailable, mark the claim unverified.
- If cleanup could remove history or meaning, propose the change without applying it.

## Exit criteria

- findings cite paths
- facts and audit interpretation are distinct
- privacy risks are surfaced first
- the smallest useful cleanup is identified
- only approved, reviewable changes are applied
