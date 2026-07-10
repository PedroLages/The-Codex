---
description: Create a memory update proposal — never edits memory.md directly
args:
  - name: context
    description: What changed or what context to review for memory (optional — if omitted, reviews recent activity)
    required: false
---

Read `90. AI/skills/memory-curator.md` and follow its workflow.

Read `90. AI/memory.md` to understand the current memory state.

Review the provided context (or recent vault activity if no context given). Create a memory update proposal in `90. AI/generated/memory-proposal-YYYY-MM-DD.md`.

## Classification

For each potential memory item, classify as:

- **Add** — new stable fact, preference, decision, or project context
- **Update** — existing memory entry needs revision
- **Outdate** — existing memory entry is no longer true → move to Outdated / Superseded
- **Ignore** — interesting but not stable enough for memory
- **Needs Pedro Approval** — uncertain, let Pedro decide

## What Belongs in Memory

Only propose:
- stable facts
- stable preferences
- vault decisions
- naming decisions
- AI workflow decisions
- active project context
- long-term learning focus
- repeated patterns useful for future work

## What Does NOT Belong

Do not propose:
- temporary thoughts
- raw notes
- source material
- AI guesses
- one-time tasks
- long summaries
- things that belong in Main Notes or Source Materials

## Proposal Format

```markdown
# Memory Update Proposal — YYYY-MM-DD

## Proposed Additions
-

## Proposed Updates
-

## Proposed Outdates
-

## Items to Ignore (with reasons)
-

## Needs Pedro's Decision
-
```

## Critical Rule

**Do not edit `90. AI/memory.md`.** This is a proposal only.

After Pedro approves, the workflow continues:
Memory Proposal → Pedro Approval → memory.md Update → memory-changelog.md entry.
