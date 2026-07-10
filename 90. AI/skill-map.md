# Skill Map

This file lists the AI skills available in **The Codex**.

If a task matches one of these skills, load the skill file before acting.

All skills live in:

```text
90. AI/skills/
```

## 1. Source to Main Notes

File:

`90. AI/skills/source-to-main-notes.md`

Use when Pedro gives:

* a transcript
* a YouTube video
* a course lesson
* an article
* a book chapter
* documentation
* raw notes
* pasted text
* an AI conversation to process

Purpose:

Turn source material into:

1. a source note
2. key ideas
3. possible main notes
4. tag suggestions
5. MOC suggestions if needed

This is the most important skill for Pedro's learning system.

## 2. Sherpa

File:

`90. AI/skills/sherpa.md`

Use when Pedro wants to learn a new topic.

Purpose:

Create a learning map, explain what matters first, and suggest a clear study route.

## 3. Rock Tumbler

File:

`90. AI/skills/rock-tumbler.md`

Use when Pedro wants feedback on an idea, note, draft, or piece of writing.

Purpose:

Improve the thinking without replacing Pedro's voice.

Use open-ended questions.

## 4. Chronicler

File:

`90. AI/skills/chronicler.md`

Use when Pedro says:

* save this
* save this conversation
* save this verbatim
* archive this chat

Purpose:

Save useful AI conversations into `90. AI/history/`.

## 5. Janitor

File:

`90. AI/skills/janitor.md`

Use when Pedro asks to:

* clean the vault
* audit the system
* check for problems
* find messy notes
* review AI files

Purpose:

Maintain the system without making it more complicated.

## 6. Daily Brief

File:

`90. AI/skills/daily-brief.md`

Use when Pedro asks for:

* daily brief
* today's focus
* morning review
* what should I focus on today?

Purpose:

Help Pedro start the day with clarity.

## 7. Weekly Review

File:

`90. AI/skills/weekly-review.md`

Use when Pedro asks for:

* weekly review
* review my week
* what did I learn this week?
* what should I focus on next week?

Purpose:

Review learning, progress, open loops, and next actions.

## 8. Memory Curator

File:

`90. AI/skills/memory-curator.md`

Use when Pedro says:

- remember this
- update memory
- save this to memory
- review memory
- clean memory
- create a memory proposal

Also use at the end of weekly reviews.

Purpose:

Keep `90. AI/memory.md` accurate without polluting it.

Default workflow:

```text
Weekly Review → Memory Proposal → Pedro Approval → memory.md Update → memory-changelog.md entry
```

Important rule:

Do not edit `90. AI/memory.md` automatically.

First create a proposal in:

`90. AI/generated/`

Every approved memory change must be recorded in:

`90. AI/memory-changelog.md`

## 9. Session Handoff

File:

`90. AI/skills/session-handoff.md`

Use when Pedro says:

- create handoff
- summarize this session
- save where we are
- create next steps
- close this session
- what did we change?

Purpose:

Create a clear handoff note after long AI sessions so Pedro can continue later without losing context.

Default output:

`90. AI/history/`

This is not memory. If something should become memory, use the Memory Curator skill.

## 10. Note Quality Checker

File:

`90. AI/skills/note-quality-checker.md`

Use when Pedro says:

- check this note
- is this a good main note?
- review this note
- is this ready?
- improve this atomic note
- quality check

Purpose:

Check whether a note is ready to become a strong main note in `03. Main Notes/`.

Default output:

A quality report. Do not edit the note unless Pedro asks.

## Dispatch Rules

1. Read the matching skill file before acting.
2. Use only the skills needed for the task.
3. Do not invent a complex workflow.
4. Put drafts in `90. AI/generated/`.
5. Preserve Pedro's own thinking.
6. Ask only when a question would materially improve the result.
7. For memory updates, create a proposal first.
8. Do not edit `90. AI/memory.md` without Pedro's approval.
9. Use Session Handoff after long sessions or major system changes.
10. Use Note Quality Checker before promoting AI drafts into `03. Main Notes/`.
