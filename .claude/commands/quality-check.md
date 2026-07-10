---
description: Review a note against main note quality standards and produce a scored report
args:
  - name: note
    description: Path to the note file to review
    required: true
---

Read `90. AI/skills/note-quality-checker.md` for the full quality rubric.

Review the provided note. Do not edit it.

Create a quality report in `90. AI/generated/quality-check-<note-name>-YYYY-MM-DD.md`.

## Check Each Criterion

1. **One idea?** — Does it focus on a single, clear idea?
2. **Clear title?** — Is the title a statement, not a vague label?
3. **Own words?** — Is it written in Pedro's voice, not copied from source?
4. **Standalone?** — Can someone understand it without the original source?
5. **Why it matters?** — Does it explain the significance of the idea?
6. **Example?** — Is there at least one concrete, practical example?
7. **Source link?** — Does it link back to source material if applicable?
8. **Tag links?** — Does it use `[[Tag]]` links to connect to broader topics?
9. **MOC connection?** — Is it linked to a MOC if the topic warrants it?
10. **Atomicity?** — Should this be split into multiple notes, improved, or is it ready?

## Report Format

```markdown
# Quality Check: [Note Title]

## Status: Ready / Needs Work / Not a Main Note Yet

## Score: X/10

## What Is Strong
-

## What Needs Work
-

## Suggested Edits
-

## Better Title Options
-

## Suggested Tags
- [[ ]]

## Suggested MOC Links
- [[ ]]

## Next Action for Pedro
-
```

## Rules

- Report only. Do not edit the note unless Pedro explicitly asks.
- Be honest about quality. A low score with clear feedback is more useful than false encouragement.
- If the note isn't ready, give specific, actionable suggestions.
