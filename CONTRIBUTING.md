# Contributing

Contributions should make the leadership practice clearer, safer, or easier to adopt without making the starter heavy.

## Principles

- Keep Markdown portable and readable in a plain text editor.
- Keep examples fictional and free of private or organization-specific details.
- Separate facts, interpretation, decisions, questions, and proposed actions.
- Preserve human approval for consequential people decisions and external actions.
- Prefer a small reusable pattern over a large framework.
- Do not add required credentials, databases, dashboards, or vendor integrations to version 1.
- Use warm, direct, sentence-cased language. Avoid hype and em dashes.

## Making a change

1. Explain the user need the change addresses.
2. Update all directly related examples, paths, and instructions.
3. Check relative links and file names.
4. Search for private identifiers, secrets, unfinished placeholders, and em dashes.
5. Keep pull requests focused.

## Adding a skill

Create `.github/skills/<skill-name>/SKILL.md` with valid YAML frontmatter containing `name` and `description`. Follow [the skills guide](.github/skills/README.md) and define:

- required context
- a bounded workflow
- a stable output shape
- facts versus interpretation rules
- allowed writeback
- approval-required writeback

## Reporting sensitive issues

Do not open a public issue containing private data or a credential. Remove the sensitive content first, rotate any exposed credential, then report the safe technical detail through an appropriate private channel.
