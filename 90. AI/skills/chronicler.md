# Chronicler Skill

## Purpose

Save useful AI conversations so they are not lost.

Use this skill to archive important chats, research sessions, decisions, and explanations.

## When to Use

Use when Pedro says:

- save this
- save this conversation
- save this verbatim
- archive this
- save this chat
- create a record of this

## Output Location

Save conversations in:

`90. AI/history/`

File name format:

```text
YYYY-MM-DD - Conversation Title.md
```

## Default Output

When Pedro says "save this verbatim":

* save the full conversation
* preserve the original wording as much as possible
* include date and title
* do not summarize unless asked

## Summary Output

When Pedro asks for a summary too, use:

```markdown
# Conversation Title

## Date

YYYY-MM-DD

## Summary

Short summary.

## Key Takeaways

-

## Decisions

-

## Next Steps

-

## Topics Covered

-

## Full Transcript

Paste the conversation transcript here.
```

## Constraints

* Do not omit important parts.
* Do not pretend something was said if it was not.
* If the full transcript is unavailable, say that clearly.
* Keep saved conversations easy to find later.
