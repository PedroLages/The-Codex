# Vault Map

This file explains how **The Codex** is organized.

The system is intentionally simple.

Do not add extra folder systems unless Pedro explicitly asks.

## Folder Structure

```text
The Codex/
├── 01. Inbox/
├── 02. Source Materials/
├── 03. Main Notes/
├── 04. Tags/
├── 05. MOCs/
├── 50. Attachments/
├── 90. AI/
└── 99. Templates/
```

## 01. Inbox

Use this folder for quick capture.

Examples:

* random ideas
* quick thoughts
* questions
* things to process later
* unfinished thinking
* notes created quickly on mobile
* temporary notes

Rule:

Capture fast. Clean later.

## 02. Source Materials

Use this folder for notes from things Pedro consumes.

Examples:

* books
* YouTube videos
* courses
* articles
* documentation
* podcasts
* transcripts
* AI conversations used as source material

Recommended subfolders:

```text
02. Source Materials/
├── Articles/
├── Books/
├── Courses/
├── Documentation/
├── Podcasts/
└── Videos/
```

Rule:

Source Materials = what the source says + what Pedro thinks it means.

Do not just copy the source.

Help Pedro explain the idea in his own words.

## 03. Main Notes

This is the heart of the vault.

Use this folder for permanent learning notes.

A main note should:

* contain one idea
* be written in Pedro's own words
* be understandable on its own
* include an example when useful
* link to related notes
* link back to source material when possible

Rule:

One note = one idea.

## 04. Tags

Tags are notes.

Use linked notes like:

```markdown
[[Linux]]
[[Kubernetes]]
[[DevOps]]
[[Photography]]
```

Do not use normal hashtags as the main tagging system.

Tag notes should live in:

```text
04. Tags/
```

Rule:

Tags are entry points into ideas.

## 05. MOCs

MOC means Map of Content.

Use MOCs to organize larger topics.

Create a MOC only when a topic has enough notes.

Examples:

```text
05. MOCs/
├── Linux MOC.md
├── DevOps MOC.md
├── Kubernetes MOC.md
├── Docker MOC.md
└── Obsidian MOC.md
```

Rule:

Tags collect. MOCs organize.

## 50. Attachments

Use this folder for:

* images
* PDFs
* screenshots
* audio files
* exports
* other attachments

## 90. AI/commands

This folder stores reusable command prompts for DeepSeek / VS Code.

These are not permanent knowledge notes.

They are launch prompts Pedro can copy and paste when working with AI.

Examples:

- Start Session
- Process Inbox
- Process Source Material
- Create Main Note Draft
- Quality Check Main Note
- Create or Update MOC
- Weekly Review
- Memory Proposal
- Session Handoff
- Janitor Audit

Command notes live in:

`90. AI/commands/`

## 90. AI

The AI folder is not the main knowledge system.

It is the AI control room.

Use it for:

* AI instructions
* vault maps
* skill files
* generated drafts
* saved AI conversations
* maintenance reports

Important folders:

```text
90. AI/commands/
90. AI/generated/
90. AI/history/
90. AI/skills/
```

## 99. Templates

Templates live here.

Keep templates simple.

Useful templates include:

```text
99. Templates/
├── Atomic Note.md
├── Course Lab Note.md
├── Inbox Notes.md
├── MOC.md
└── Source Material Note.md
```

Do not create too many templates.

## Where New Things Go

Quick thought:

`01. Inbox/`

Book, course, video, article, podcast, or documentation note:

`02. Source Materials/`

Permanent idea note:

`03. Main Notes/`

Tag note:

`04. Tags/`

Topic map:

`05. MOCs/`

Attachment:

`50. Attachments/`

AI draft:

`90. AI/generated/`

Saved AI conversation:

`90. AI/history/`

Template:

`99. Templates/`

## Safety Rules

* Do not delete files.
* Do not move files unless Pedro asks.
* Do not overwrite notes without a backup.
* Do not create large folder systems.
* Do not create too many tags.
* Do not promote AI drafts into main notes without review.
* Keep the vault simple.
