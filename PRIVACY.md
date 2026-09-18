# Privacy

A leadership OS becomes more useful as it gains context, which also increases the cost of careless capture. Keep the minimum context needed for the practice and preserve the boundaries of the original source.

## People context

Store only work-relevant information that a person would reasonably expect to support the working relationship. Prefer observable events, stated preferences, agreed goals, and confirmed commitments.

Employer policy and applicable law govern workplace records whether they are kept in a private GitHub repository, a local Markdown folder, or another note-taking tool. Check those requirements before adding real people context or using it with AI.

Do not store:

- diagnoses, personality labels, or guesses about motivation
- protected personal information
- rumors or unverified allegations
- hidden rankings, sentiment scores, or speculative risk labels
- personal details that do not serve a clear leadership purpose

Write as if the person could read the record. They may someday do so.

## Official records

Do not recreate HR, legal, financial, security, or compliance systems in Markdown. Keep the authoritative record in the approved system and store only a safe reference when one is necessary.

If a Markdown note conflicts with an official record, the official record wins. Correct the digest and preserve a dated note explaining the change.

## Sensitive data

Do not add credentials, access tokens, private keys, recovery codes, government identifiers, payment data, medical information, compensation details, legal advice, investigation material, or security incident secrets.

When a source contains both useful and sensitive material, capture a minimal paraphrase of the useful fact and omit the sensitive detail.

## Messages and meetings

Do not build a transcript archive. Capture decisions, commitments, relevant observations, and unresolved questions.

- Preserve the source boundary. A private message does not become broadly shareable because it was summarized.
- Avoid copying direct messages or private channel content unless there is a clear need and permission.
- Attribute statements only when attribution is necessary and appropriate.
- Distinguish what was said from what you inferred.

## Credentials and tools

Version 1 requires no credentials. Keep local secret files out of Git and use approved secret storage if later integrations are added.

Never place a credential in a prompt, profile, log, digest, decision, issue, pull request, or example file.

## Inference

An agent may propose an interpretation, but it must not present that interpretation as fact.

Use explicit labels:

- **Fact:** supported by a cited source
- **Interpretation:** a possible meaning or pattern
- **Open question:** evidence is missing or conflicting

Consequential inferences about another person require human review before writeback. Some inferences should not be stored at all.

## External actions

Reading and drafting are different from acting. Require explicit approval before:

- sending or editing a message
- publishing or sharing a document
- creating or changing a meeting
- assigning work or changing ownership
- updating an external record
- changing access or permissions
- representing a decision as final

Approval should name the action, target, and content. Approval for one action does not grant ongoing autonomy.

## Public sharing

Assume a populated leadership OS is private. Before publishing any part:

1. Review every changed file, including Git history.
2. Remove names, handles, private links, organization identifiers, and source excerpts.
3. Replace real scenarios with clearly fictional examples.
4. Search for credentials and local paths.
5. Confirm that relative links point only to intended public content.
6. Ask whether the remaining detail is necessary, not merely interesting.

This starter repository is designed to be public. The personal system created from it should use the privacy level appropriate to its content.

This guidance is a practical starting point, not legal or HR approval.

## Retention and correction

- Remove context that no longer has a legitimate purpose.
- Correct factual errors promptly and cite the correction.
- Prefer a brief correction note over silently changing raw history.
- Periodically audit profiles and digests for stale or overly sensitive details.
- If safe handling is unclear, do not capture the information.
