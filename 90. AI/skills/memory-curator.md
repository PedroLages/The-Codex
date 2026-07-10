# Memory Curator Skill

## Purpose

Keep `90. AI/memory.md` useful, accurate, and clean.

This skill exists to prevent memory pollution.

The goal is not to remember everything.

The goal is to remember only what will be useful again.

---

# Official Workflow

The official memory workflow is:

```text
Weekly Review → Memory Proposal → Pedro Approval → memory.md Update → memory-changelog.md entry
```

Do not update memory automatically.

Do not edit `90. AI/memory.md` unless Pedro explicitly approves.

---

# When To Use

Use this skill during:

* weekly reviews
* major vault decisions
* AI workflow changes
* naming decisions
* project direction changes
* long-term preference changes

Also use it when Pedro says:

* remember this
* update memory
* save this to memory
* this is important for the future
* create a memory proposal
* review memory

---

# What Belongs In Memory

Good memory candidates:

* long-term preferences
* stable vault decisions
* folder naming decisions
* AI behavior rules
* active projects
* recurring learning goals
* repeated workflow patterns
* important personal context useful for future work

Bad memory candidates:

* temporary thoughts
* one-time tasks
* raw source notes
* article summaries
* copied transcripts
* AI guesses
* unstable plans
* random ideas
* daily journal entries
* anything that belongs in `03. Main Notes/`
* anything that belongs in `02. Source Materials/`

---

# Memory Test

Before proposing a memory, ask:

1. Will this still be useful in one month?
2. Is this stable, or temporary?
3. Did Pedro clearly say or approve this?
4. Is this already in `90. AI/me.md`?
5. Does this belong in a normal note instead?
6. Is this too detailed?
7. Could this pollute memory?

Only propose the memory if it passes the test.

---

# Proposal Workflow

## Step 1 — Review Context

Review the weekly review, notes, AI drafts, project decisions, or conversation.

Identify possible memory candidates.

## Step 2 — Classify Each Candidate

Use one of these labels:

```text
Add
Update
Outdate
Ignore
Needs Pedro Approval
```

## Step 3 — Create Memory Proposal

Create a proposal file in:

```text
90. AI/generated/
```

Use this filename format:

```text
memory-update-proposal-YYYY-MM-DD-HHMM.md
```

Use this structure:

```markdown
# Memory Update Proposal

## Date

YYYY-MM-DD HH:MM

## Reason

Why this memory update is being proposed.

## Source Context

Where this came from:

- Weekly review:
- Conversation:
- Note:
- Project:

## Proposed Additions

### Addition 1

Section:

Proposed text:

Why this should be remembered:

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

## Step 4 — Wait For Approval

Do not edit `90. AI/memory.md`.

Wait for Pedro.

## Step 5 — Apply Approved Updates

Only after Pedro approves:

1. Back up `90. AI/memory.md`.
2. Back up `90. AI/memory-changelog.md`.
3. Apply only approved memory updates.
4. Move outdated memories to `Outdated / Superseded`.
5. Add a changelog entry to `90. AI/memory-changelog.md`.
6. Return a final report.

---

# Changelog Rule

Every approved memory update must create an entry in:

```text
90. AI/memory-changelog.md
```

The changelog entry must include:

* date
* reason
* approval source
* proposal file
* additions
* updates
* outdated memories
* notes

---

# Safety Rules

* Do not edit memory automatically.
* Do not store temporary details.
* Do not store AI guesses.
* Do not duplicate `90. AI/me.md`.
* Do not turn memory into a diary.
* Do not turn memory into a task list.
* Do not store long explanations.
* Prefer fewer, better memories.
