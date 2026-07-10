# System Changelog

This file records approved changes to the AI system inside **The Codex**.

This is different from `memory-changelog.md`.

## Difference

`memory-changelog.md` records changes to:

- `90. AI/memory.md`

`system-changelog.md` records changes to:

- AI rules
- AI skills
- AI prompts
- vault maps
- startup instructions
- workflow decisions
- folder naming decisions
- safety rules

## Rule

Every meaningful change to the AI system should be recorded here.

Do not use this as a daily log.

---

# Format

```markdown
## YYYY-MM-DD HH:MM — System Update

Reason:

Approved by:

Files changed:

- 

Changes made:

- 

Notes:
```

---

# Changelog

## 2026-07-04 — Hermes-Style Improvements Added

Reason:

Added a small Hermes-style layer while keeping The Codex simple.

Approved by:

Pedro

Files changed:

* `90. AI/system-changelog.md`
* `90. AI/skills/session-handoff.md`
* `90. AI/skills/note-quality-checker.md`
* `90. AI/skill-map.md`
* `90. AI/startup-prompt.md`
* `AGENTS.md`

Changes made:

* Added system changelog.
* Added session handoff skill.
* Added note quality checker skill.

Notes:

The Codex should stay simple. AI assists the learning system but does not control it.
