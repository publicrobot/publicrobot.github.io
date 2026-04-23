# Contributing Checklist Items and Deployment Anecdotes

This guide explains how to share your own public HRI deployment experience with the checklist project. Contributions can be concrete checklist items, short anecdotes from a deployment, broader suggestions, or notes about missing topics.

## Contribution Options

Use the GitHub repository:

https://github.com/publicrobot/publicrobot.github.io

There are two useful paths:

- **Your own experience/study:** create a branch with your proposed checklist additions or edits.
- **Make broader suggestions:** open an issue for comments, concerns, missing areas, or discussion.

## Branching the GitHub Repository

1. Go to the repository:
   https://github.com/publicrobot/publicrobot.github.io

2. Create or use a GitHub account.

3. Fork the repository to your own account.

4. In your fork, create a new branch with a descriptive name, for example:
   `museum-deployment-checklist-items`
   `outdoor-navigation-anecdote`
   `accessibility-suggestions`

5. Make your edits in the branch.

6. Submit a pull request back to the main repository.

7. In the pull request description, briefly explain:
   - What kind of deployment or study your contribution comes from.
   - Which checklist phase it affects: Before, During, or After.
   - Which column it affects: Robot, Human, or Public.
   - Whether your contribution is based on direct experience, a general suggestion, or both.

## Where Checklist Items Live

Checklist content is stored in `latest_cards.json`.

Each checklist topic has this structure:

```json
{
  "title": "Short Topic Title",
  "content": [
    "Checklist item one",
    "Checklist item two",
    "Checklist item three"
  ],
  "description": "A longer explanation of why this topic matters."
}
```

The top-level sections identify the row and column:

- `before-robot`
- `before-human`
- `before-public`
- `during-robot`
- `during-human`
- `during-public`
- `after-robot`
- `after-human`
- `after-public`

## How to Write Checklist Items

Checklist items should be practical, specific, and actionable.

Prefer:

- `Test emergency shut-down procedure on site before participants arrive.`
- `Locate power sources and confirm permission to use them.`
- `Identify where post-interaction interviews can happen without blocking public flow.`

Avoid:

- `Think about safety.`
- `Be prepared.`
- `Consider the site.`

Good checklist items usually start with action verbs:

- Test
- Confirm
- Identify
- Document
- Prepare
- Locate
- Verify
- Coordinate
- Review

## How to Write Anecdotes

Anecdotes should help explain why a checklist item matters. They do not need to name people, institutions, companies, study sites, or exact locations.

Use this format when possible:

```markdown
### Anecdote

Deployment context:
Briefly describe the kind of site, robot, or interaction.

What happened:
Describe the issue, surprise, failure, workaround, or successful practice.

Why it matters:
Explain what future teams should learn from it.

Suggested checklist item:
Write one concise item that could be added to the checklist.
```

Example:

```markdown
### Anecdote

Deployment context:
Indoor public venue with variable crowding throughout the day.

What happened:
The team tested the robot in the morning, but afternoon crowding changed pedestrian flow and made the planned robot path difficult to use.

Why it matters:
Site conditions can change substantially across the day. A successful morning test may not reveal later constraints.

Suggested checklist item:
Visit or test the site at a time that matches the expected deployment conditions.
```

## Privacy and Double-Blind Review

If the project is under double-blind review, keep identifying details out of public contributions unless the maintainers say otherwise.

Avoid including:

- Author names
- Institution names
- Exact deployment locations
- Participant names or identifying details
- Photos or media that reveal identities
- Proprietary robot logs or private site documents

Use general descriptions instead:

- `a museum`
- `a transit site`
- `an outdoor pedestrian area`
- `a university building`
- `a public event`

## What Makes a Useful Contribution

A useful contribution usually does at least one of these things:

- Adds a missing checklist item.
- Makes an existing checklist item more specific.
- Explains why an item matters through a short deployment anecdote.
- Identifies a checklist topic that should be moved to a different row or column.
- Points out a confusing title, unclear wording, or duplicate item.
- Adds accessibility, ethics, safety, legal, or site-coordination concerns that are not already covered.

## Suggested Pull Request Format

```markdown
## Contribution Type

- [ ] New checklist item
- [ ] Edit to existing checklist item
- [ ] Anecdote or deployment experience
- [ ] Broader suggestion

## Relevant Matrix Location

Phase: Before / During / After
Column: Robot / Human / Public

## Context

Briefly describe the deployment, study, or concern without identifying authors, institutions, participants, or sites.

## Proposed Change

Describe the checklist item, topic, or wording you suggest.

## Why This Matters

Explain what problem this would help future deployment teams avoid.
```

## Suggested Issue Format

Use issues for broader suggestions or questions:

```markdown
## Topic

Short name for the suggestion or concern.

## What is missing or unclear?

Describe the gap.

## Suggested improvement

Describe what should be added, removed, clarified, or discussed.

## Relevant phase and column

Before / During / After
Robot / Human / Public
```

## Questions or Anonymous Feedback

Questions and feedback can be addressed anonymously to:

hriiprobot@gmail.com
