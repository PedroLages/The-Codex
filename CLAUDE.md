# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working in this repository.

## Overview

The Codex is Pedro Lages' personal Obsidian vault — a learning and knowledge management system, not a software project. There is no build step, package manager, or test suite. The primary artifact is Markdown notes organized across a small set of numbered folders.

**Primary instruction file:** [AGENTS.md](AGENTS.md) — read it first. This file supplements it with structural context that helps Claude Code navigate the vault efficiently.

## Vault Structure

```
01. Inbox/           — Quick capture, unfinished thoughts, mobile scribbles
02. Source Materials/ — Notes from books, videos, courses, articles, podcasts, docs
03. Main Notes/      — Permanent atomic notes (one idea per note, own words)
04. Tags/            — Tag notes linked as [[TagName]], not #hashtags
05. MOCs/            — Maps of Content for larger topics
50. Attachments/     — Images, PDFs, screenshots, audio
90. AI/              — AI instructions, skills, commands, drafts, history
99. Templates/       — Note templates (Atomic, Source, MOC, Inbox, Course Lab)
```

**Flow:** `Inbox → Source Materials → Main Notes → Tags → MOCs`

## AI Subsystem (`90. AI/`)

The AI folder is the control room — it tells Claude Code how to operate:

| File | Purpose |
|------|---------|
| [me.md](90.%20AI/me.md) | Pedro's identity, interests, preferences, AI boundaries |
| [memory.md](90.%20AI/memory.md) | Stable facts, decisions, preferences, active project context |
| [vault-map.md](90.%20AI/vault-map.md) | Detailed folder-by-folder explanation of the vault |
| [skill-map.md](90.%20AI/skill-map.md) | Index of 10 AI skills — when and how to use each |
| [startup-prompt.md](90.%20AI/startup-prompt.md) | Copy-paste prompt for starting new DeepSeek/VS Code sessions |
| [system-changelog.md](90.%20AI/system-changelog.md) | Log of AI system changes to the vault |
| [memory-changelog.md](90.%20AI/memory-changelog.md) | Log of approved memory changes |

### Skills vs Command Prompts vs Claude Code Commands

- **Skills** (`90. AI/skills/`) — Full workflow instructions. There are 10: `source-to-main-notes`, `sherpa` (learn new topic), `rock-tumbler` (feedback on ideas), `chronicler` (save conversations), `janitor` (vault cleanup), `daily-brief`, `weekly-review`, `memory-curator`, `session-handoff`, `note-quality-checker`.
- **Command prompts** (`90. AI/commands/`) — Copy-paste prompts for external AI tools (DeepSeek, VS Code). Numbered 00–09. Not executed by Claude Code.
- **Claude Code commands** (`.claude/commands/`) — Executable slash commands that run the workflows directly. See below.

### Drafts and History

- AI-generated content goes to `90. AI/generated/` — never directly into `03. Main Notes/` without Pedro's review.
- Saved AI conversations go to `90. AI/history/`.
- After long sessions or major changes, suggest a session handoff using the `session-handoff` skill.

## Key Conventions

- **Tags are notes, not hashtags.** Link with `[[Linux]]`, `[[Kubernetes]]`, etc. Tag notes live in `04. Tags/`.
- **MOCs are maps, not indexes.** Create a MOC only when a topic has enough notes to warrant one. Tags collect; MOCs organize.
- **Atomic notes:** One idea per note, written in Pedro's own words, understandable standalone, with examples and links.
- **Memory is guarded.** Never edit `memory.md` directly — propose changes via `90. AI/generated/` and wait for approval. Every change recorded in `memory-changelog.md`.
- **Do not delete or move files** unless explicitly asked.
- **Backup before overwriting** any existing note.
- **Keep it simple.** No new folder systems, no complex workflows, no productivity-maze features.

## Obsidian Plugins

Six community plugins are active: Style Settings, Quick LaTeX, Dataview, Metadata Menu, Iconic, and Templater. Notes may contain Dataview queries or Metadata Menu frontmatter — preserve these when editing.

## Claude Code Slash Commands

These live in `.claude/commands/` and execute vault workflows directly:

| Command | Purpose |
|---------|---------|
| `/start-session` | Load core files and summarize current vault state |
| `/process-inbox` | Scan inbox, create processing proposal (read-only) |
| `/process-source <file>` | Turn source material into source note + main note drafts |
| `/create-main-note <idea>` | Create a draft atomic main note |
| `/quality-check <file>` | Review a note against quality standards, produce scored report |
| `/update-moc <topic>` | Create or update a Map of Content |
| `/weekly-review` | Full weekly review across inbox, drafts, notes, MOCs |
| `/memory-proposal [context]` | Create a memory update proposal (never edits memory.md) |
| `/session-handoff` | Save session context to `90. AI/history/` |
| `/janitor` | Audit vault for problems (report only, no edits) |

All commands follow vault rules: drafts go to `90. AI/generated/`, memory.md is never auto-edited, and destructive actions require explicit approval.

## When Claude Code Works Here

1. Start by reading the four files listed in [AGENTS.md](AGENTS.md): `me.md`, `memory.md`, `vault-map.md`, `skill-map.md`.
2. For any task, check if a Claude Code command (`/process-inbox`, `/janitor`, etc.) or skill in `90. AI/skills/` applies — if so, use it.
3. Put all generated content in the correct folder per the vault map.
4. Do not edit `memory.md` without creating a proposal first.
