# Source to Main Notes Skill

## Purpose

Turn source material into useful Obsidian notes.

This is the main skill for learning.

Use it for:

- transcripts
- YouTube videos
- courses
- books
- articles
- documentation
- podcasts
- raw study notes
- AI conversations used as learning material

## Goal

Create:

1. a clean source material note
2. the key ideas
3. suggested main notes
4. suggested tag notes
5. possible MOC updates

## Output Location

Source note drafts go in:

`90. AI/generated/`

Do not put AI-generated main notes directly in `03. Main Notes/` unless Pedro explicitly asks.

## Workflow

### Step 1 — Identify the Source

Capture:

- title
- author or creator
- source type
- link if available
- date if available
- topic
- short summary

### Step 2 — Create a Source Note Draft

Use this structure:

```markdown
# Source Title

## Source

- Type:
- Author:
- Link:
- Date:
- Topic:

## Summary

Write a short summary in Pedro's own words.

## Key Ideas

### Idea 1

Source point:

Pedro's understanding:

Possible main note:

- [[ ]]

### Idea 2

Source point:

Pedro's understanding:

Possible main note:

- [[ ]]

## Best Quotes or Timestamps

-

## Main Notes to Create

- [[ ]]
- [[ ]]
- [[ ]]

## Tags

- [[ ]]
- [[ ]]

## MOC Suggestions

- [[Linux MOC]]
- [[DevOps MOC]]

## Connections

- [[ ]]
```

### Step 3 — Suggest Main Notes

A main note should:

* focus on one idea
* be understandable on its own
* use Pedro's own words
* include an example
* link to related notes
* link back to the source

Good main note titles:

```text
Kubernetes Services give pods stable network access
Containers package applications with their dependencies
Terraform reduces manual infrastructure drift
MOCs should emerge only when a topic grows
```

Bad main note titles:

```text
Kubernetes notes
Docker course
Interesting ideas
Chapter 1
```

### Step 4 — Suggest Tags

Use tags as linked notes:

```markdown
[[Kubernetes]]
[[Linux]]
[[DevOps]]
[[Learning]]
```

Do not use hashtags as the main system.

### Step 5 — Suggest MOC Updates

If the topic is large, suggest a MOC.

Example:

```text
05. MOCs/Kubernetes MOC.md
```

Do not create a MOC too early.

## Constraints

* Do not create too many notes.
* Prefer the strongest ideas.
* Do not copy long source text.
* Write in Pedro's own words.
* Keep source notes separate from main notes.
* Put generated drafts in `90. AI/generated/`.
