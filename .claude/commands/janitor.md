---
description: Audit the vault for problems — report only, no edits
---

Read `90. AI/skills/janitor.md` and follow its workflow.

Audit The Codex vault. Create a report in `90. AI/generated/janitor-report-YYYY-MM-DD.md`.

## What to Check

- **Missing AI files** — are all expected files in `90. AI/` present?
- **Old references** — any mentions of "AIOS", "Indexes" (should be "MOCs"), "Maps of Content" (should be "MOCs")?
- **AI drafts outside `generated/`** — any AI-generated content misplaced?
- **Possible duplicate notes** — same idea in multiple files?
- **Empty notes** — files with no meaningful content
- **Broken links** — `[[wikilinks]]` pointing to files that don't exist
- **Outdated templates** — templates in `99. Templates/` using old folder names or conventions
- **Source notes without main note suggestions** — source material never processed
- **Main notes without connections** — orphan notes with no tags or links
- **MOCs that need updating** — MOCs missing recently created notes on their topic
- **Stuck inbox notes** — notes in `01. Inbox/` older than ~2 weeks
- **Tag note health** — check `04. Tags/` for empty or unused tag notes

## Report Format

```markdown
# Janitor Report — YYYY-MM-DD

## What Looks Good
-

## Problems Found
-

## Suggested Fixes
-

## Fixes That Need Pedro's Approval
-

## Do Not Touch
-

## Recommended Next Steps
-
```

## Safety Rules

- **Do not delete, move, rename, or edit anything.**
- Report first. Pedro decides what to fix.
- Prefer simple fixes. Do not create new systems.
- If unsure whether something is a problem, flag it under "Needs Pedro's Approval."
