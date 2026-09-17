# Skills

Stored context becomes useful when a repeatable practice applies judgment to it. A skill defines that practice without giving the agent open-ended authority.

Each skill in this directory has a `SKILL.md` file with:

- the context required before work begins
- a bounded sequence of steps
- an output shape that is easy to review
- rules for separating facts from interpretation
- writeback that is allowed
- writeback that requires approval

## Use a skill

Name the skill in your prompt and provide the current goal. For example:

```text
Use the weekly-leadership-review skill. Review this week's evidence, identify
the decisions and tensions that need my attention, and do not write back until
I approve the draft.
```

A skill should stop when evidence is missing, the task crosses its boundary, or a human decision is required.

## Customize a skill

Change:

- required files to match your repository
- questions and review cadence to match your practice
- output headings to match how you make decisions
- writeback permissions to match your risk tolerance

Keep the facts versus interpretation and approval sections explicit.

## Add a skill

Create `.github/skills/<skill-name>/SKILL.md`. Use a lowercase hyphenated directory and matching `name` in the YAML frontmatter.

Start from this shape:

```markdown
---
name: example-skill
description: A specific description of when this skill should be used.
---

# Example skill

## Required context
## Workflow
## Output
## Facts versus interpretation
## Writeback
### Allowed
### Approval required
## Stop conditions
```

Keep the skill narrow enough that a user can predict what it will do.
