# Memory Curator Skill

## Purpose

Keep `90. AI/memory.md` useful, accurate, and clean.

This skill helps AI suggest memory updates without polluting the memory file.

## Core Rule

Do not edit `90. AI/memory.md` unless Pedro explicitly approves.

First create a memory update proposal in:

```text
90. AI/generated/
```

## Official Memory Workflow

The default memory workflow is:

```text
Weekly Review → Memory Proposal → Pedro Approval → memory.md Update
```

Memory should not be updated after every chat.

Memory should not become a daily log.

During the weekly review, create a memory proposal if stable context changed.

Only update `90. AI/memory.md` after Pedro approves the proposal.

## When To Use

Use this skill when Pedro says:

* remember this
* update memory
* save this to memory
* what should be added to memory?
* review memory
* clean memory
* weekly review
* this is important for the future

Also use it after major decisions about:

* vault structure
* AI rules
* active projects
* long-term preferences
* naming decisions
* learning focus
* workflow changes

## What Belongs In Memory

Add only stable information.

Good memory candidates:

* Pedro's long-term preferences
* active projects
* vault decisions
* folder naming decisions
* AI behavior rules
* important workflow decisions
* recurring learning goals
* stable personal context useful for future work

Bad memory candidates:

* temporary thoughts
* random ideas
* one-time tasks
* drafts
* raw notes
* long explanations
* copied source material
* AI guesses
* anything uncertain
* things that belong in Main Notes or Source Materials

## Memory Update Workflow

### Step 1 — Review Context

Look at the current conversation, note, or task.

Identify possible memory candidates.

### Step 2 — Classify Each Candidate

Use one of these labels:

```text
Add
Update
Outdate
Ignore
Needs Pedro Approval
```

### Step 3 — Create Proposal

Create a file in:

```text
90. AI/generated/
```

File name format:

```text
memory-update-proposal-YYYY-MM-DD-HHMM.md
```

Use this format:

```markdown
# Memory Update Proposal

## Date

YYYY-MM-DD

## Reason

Why this memory update is being proposed.

## Proposed Additions

### Addition 1

Section:

Proposed text:

Why it should be remembered:

Confidence:

## Proposed Updates

### Update 1

Current memory:

Proposed replacement:

Why it changed:

Confidence:

## Proposed Outdated Memories

### Outdated 1

Current memory:

Reason it is outdated:

Move to:

`Outdated / Superseded`

## Ignored Items

These were not added because they are temporary or not useful long term:

-

## Approval Needed

Pedro, approve one of these:

1. Approve all
2. Approve selected items
3. Reject all
4. Edit manually
```

### Step 4 — Wait For Approval

Do not edit `90. AI/memory.md` until Pedro approves.

### Step 5 — Apply Approved Updates

After approval:

1. Back up `90. AI/memory.md`.
2. Apply only approved changes.
3. Add dates to new memories.
4. Move outdated memories to `Outdated / Superseded`.
5. Return a change report.

## Rules

* Keep memory short.
* Prefer fewer memories.
* Do not duplicate `90. AI/me.md`.
* Do not store raw notes.
* Do not store source material.
* Do not store temporary project tasks.
* Do not invent facts.
* Do not edit memory without approval.
