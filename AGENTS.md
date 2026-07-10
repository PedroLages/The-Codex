# AI Agent Instructions for The Codex

Before working in this vault, read these files first:

1. `90. AI/me.md`
2. `90. AI/memory.md`
3. `90. AI/vault-map.md`
4. `90. AI/skill-map.md`

Then decide whether one of the skill files in `90. AI/skills/` applies to the task.

## Core Rules

- Do not delete files.
- Do not move files unless Pedro explicitly asks.
- Do not overwrite notes without creating a backup.
- Do not turn rough AI output into permanent notes without Pedro reviewing it.
- Put AI drafts in `90. AI/generated/`.
- Put saved AI conversations in `90. AI/history/`.
- Inbox notes go in `01. Inbox/`.
- Source notes go in `02. Source Materials/`.
- Main notes go in `03. Main Notes/`.
- Tags are notes in `04. Tags/`, using links like `[[Linux]]`, not hashtags.
- MOCs go in `05. MOCs/`.
- Attachments go in `50. Attachments/`.
- Templates go in `99. Templates/`.

## Working Style

Keep the vault simple.

This vault follows a simple learning system:

1. Capture unfinished thoughts in Inbox.
2. Save notes from books, videos, courses, articles, podcasts, and documentation in Source Materials.
3. Turn the strongest ideas into Main Notes.
4. Use Tags as linked notes.
5. Use MOCs as maps for larger topics.
6. Keep AI drafts separate until Pedro reviews them.

Do not create a complex productivity system.

Pedro wants a learning system, not a productivity maze.

## Memory Rules

Use `90. AI/memory.md` for stable facts, decisions, preferences, and active project context.

Use `90. AI/memory-changelog.md` to record approved memory changes.

Do not add temporary thoughts to memory.

Do not rewrite or delete memory entries without Pedro's approval.

When adding a memory, include the date.

If a memory becomes outdated, move it to `Outdated / Superseded`.

Memory updates follow this workflow:

```text
Weekly Review → Memory Proposal → Pedro Approval → memory.md Update → memory-changelog.md entry
```

Memory proposals go in:

```text
90. AI/generated/
```

Do not edit `90. AI/memory.md` automatically.

## Command Notes

Reusable AI command prompts live in:

`90. AI/commands/`

These are prompts Pedro can copy and paste into DeepSeek / VS Code.

Do not treat command notes as permanent knowledge notes.

Do not move them into Main Notes.

Do not rewrite them unless Pedro asks.

## Hermes-Style Continuity Rules

After long sessions, major vault changes, AI system changes, or big note-processing work, suggest creating a Session Handoff.

Session handoffs go in:

`90. AI/history/`

Use:

`90. AI/skills/session-handoff.md`

Before promoting AI-generated drafts into `03. Main Notes/`, use the Note Quality Checker skill.

Use:

`90. AI/skills/note-quality-checker.md`

Do not turn every session handoff into memory.

Memory stays small and stable.
