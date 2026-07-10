---
description: Create or update a Map of Content for a topic
args:
  - name: topic
    description: The topic to create or update a MOC for
    required: true
---

Create or update a MOC for the given topic.

## Step 1 — Search for Relevant Notes

Search these locations for notes related to the topic:

- `03. Main Notes/` — for permanent notes on the topic
- `04. Tags/` — for the relevant tag note
- `02. Source Materials/` — for source notes on the topic
- `05. MOCs/` — for existing MOCs that may already cover this topic

## Step 2 — Determine Action

Decide whether:
- a new MOC is needed (topic has enough notes, no existing MOC)
- an existing MOC should be updated (topic already has a MOC but it's stale)
- the topic isn't ready for a MOC yet (not enough notes — say so honestly)

## Step 3 — Create the Draft

Put the MOC draft in `90. AI/generated/`. Do not overwrite any existing MOC in `05. MOCs/`.

Use this structure:

```markdown
# [Topic] MOC

## Overview
Short explanation of the topic in Pedro's own words.

## Core Notes
- [[Note One]]
- [[Note Two]]

## Subtopics
### Subtopic 1
- [[ ]]

### Subtopic 2
- [[ ]]

## Best Source Materials
- [[ ]]

## Open Questions
-

## Notes To Create Next
-

## Related MOCs
- [[ ]]
```

## Step 4 — Report

At the end, tell Pedro:

- whether a new MOC is needed or an existing one should be updated
- which notes should be linked
- what gaps exist (topics without notes yet)
- what needs Pedro's approval before the MOC goes live

**Safety:** Do not overwrite any existing MOC. Draft only in `90. AI/generated/`.
