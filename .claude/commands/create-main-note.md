---
description: Create a draft atomic main note from an idea or source
args:
  - name: idea
    description: The idea, topic, or path to a source note to turn into a main note
    required: true
---

Create a draft Main Note from the provided idea or source reference.

## The Note Must

- focus on exactly one idea
- have a clear statement-style title (not a topic label)
- be written in simple, clear language
- explain the idea in Pedro's own words
- explain why the idea matters
- include one concrete, practical example
- suggest tags as `[[Tag]]` links
- suggest related notes (search `03. Main Notes/` for connections)
- suggest a MOC if the topic is large enough
- link back to source material if available

## Title Quality

Good titles (statement-style, specific):
- "Kubernetes Services give pods stable network access"
- "Containers package applications with their dependencies"
- "Terraform reduces manual infrastructure drift"

Bad titles (vague, topic labels):
- "Kubernetes notes"
- "Docker course"
- "Interesting ideas"
- "Chapter 1"

## Output

Put the draft in `90. AI/generated/`. Use a filename that matches the suggested title.

After the draft, include:

- suggested final file name
- suggested folder (`03. Main Notes/`)
- quality self-assessment score from 0-10
- what Pedro should review before approving
- whether the note is ready to promote or needs work

Do not move it to `03. Main Notes/`. Pedro reviews and promotes manually.
