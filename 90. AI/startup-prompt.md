# Startup Prompt

Use this prompt when starting a new AI session inside The Codex:

```text
You are working inside my Obsidian vault **The Codex**.

Before doing anything, read:

1. `90. AI/me.md`
2. `90. AI/memory.md`
3. `90. AI/vault-map.md`
4. `90. AI/skill-map.md`

Confirm which files you loaded.

When I give you a task, check whether one of the skills in `90. AI/skills/` applies.

If a skill applies, read the skill file before acting.

Rules:

- Do not delete files.
- Do not move files unless I ask.
- Do not overwrite notes without backup.
- Do not edit `90. AI/memory.md` automatically. Create a memory update proposal first and wait for my approval.

- Memory updates follow this workflow:

```text
Weekly Review → Memory Proposal → Pedro Approval → memory.md Update → memory-changelog.md entry
```

- Do not edit `90. AI/memory.md` automatically. Create a proposal first in `90. AI/generated/`.
- Put AI drafts in `90. AI/generated/`.
- Put saved AI conversations in `90. AI/history/`.
- Inbox notes go in `01. Inbox/`.
- Source notes go in `02. Source Materials/`.
- Main notes go in `03. Main Notes/`.
- Tags are notes in `04. Tags/`, using links like `[[Kubernetes]]`.
- MOCs go in `05. MOCs/`.
- Attachments go in `50. Attachments/`.
- Templates go in `99. Templates/`.

After long sessions, system changes, or major note-processing work, suggest creating a Session Handoff using:

`90. AI/skills/session-handoff.md`

Before moving AI-generated notes into `03. Main Notes/`, use:

`90. AI/skills/note-quality-checker.md`

Reusable command prompts live in:

`90. AI/commands/`

Use them when Pedro wants to run common workflows in DeepSeek / VS Code.

Keep the system simple.

Now wait for my instruction.
```

Suggested text expansion shortcut:

```text
;codex
```
