---
description: Turn source material (video, article, book, course, transcript) into source notes and main note drafts
args:
  - name: source
    description: Path to the source file or raw text to process
    required: true
---

Read `90. AI/skills/source-to-main-notes.md` and follow its workflow.

Process the provided source material. Create output in `90. AI/generated/`.

## Step 1 — Identify the Source

Capture: title, author/creator, source type, link (if available), date (if available), topic, short summary.

## Step 2 — Create a Source Note Draft

Use the structure from the skill file:

```markdown
# Source Title

## Source
- Type:
- Author:
- Link:
- Date:
- Topic:

## Summary
(write in Pedro's own words)

## Key Ideas
### Idea 1
Source point:
Pedro's understanding:
Possible main note: [[ ]]

## Best Quotes or Timestamps
-

## Main Notes to Create
- [[ ]]

## Tags
- [[ ]]

## MOC Suggestions
- [[ ]]

## Connections
- [[ ]]
```

## Step 3 — Suggest Main Notes

For each key idea, suggest a main note with:
- a clear statement-style title (e.g., "Kubernetes Services give pods stable network access")
- one idea per note
- understandable on its own
- Pedro's own words
- a concrete example
- suggested tags and MOC links

## Step 4 — Suggest Tags

Use `[[Tag]]` format, not hashtags. Suggest tags that already exist in `04. Tags/` when possible.

## Step 5 — Suggest MOC Updates

If the topic is large enough, suggest creating or updating a MOC in `05. MOCs/`.

## Constraints

- Do not create files in `03. Main Notes/` — put everything in `90. AI/generated/`.
- Do not overwrite the original source note.
- Prefer the strongest ideas. Don't create too many notes.
- Write in Pedro's own words. Don't copy long source text.
- Keep the system simple: Inbox → Source Materials → Main Notes → Tags → MOCs.
