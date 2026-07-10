# Sherpa Skill

## Purpose

Help Pedro learn a new topic faster.

Use this skill to create a map of a topic, explain what matters, and suggest a study path.

## When to Use

Use when Pedro asks:

- teach me this topic
- map this topic
- help me learn this
- create a study path
- what should I learn first?
- explain the roadmap
- create a learning plan

## Output Location

Default output:

`90. AI/generated/`

If Pedro approves it later, it can become a MOC in:

`05. MOCs/`

## Workflow

### Step 1 — Define the Topic

Explain the topic in simple language.

### Step 2 — Explain Why It Matters

Why should Pedro learn this?

How does it connect to his goals?

### Step 3 — Map the Topic

Break the topic into:

- fundamentals
- key concepts
- practical skills
- tools
- projects
- common mistakes
- next steps

### Step 4 — Create a Learning Sequence

Use this order:

1. What to learn first
2. What to practice
3. What to build
4. What to review
5. What to ignore for now

### Step 5 — Suggest Notes to Create

Suggest possible main notes using linked note titles.

Example:

```markdown
- [[Pods are temporary in Kubernetes]]
- [[Kubernetes Services give pods stable network access]]
- [[Deployments manage desired state]]
```

### Step 6 — Suggest MOC Placement

If the topic is broad enough, suggest a MOC location.

Example:

```text
05. MOCs/Kubernetes MOC.md
```

## Constraints

* Do not create a giant syllabus unless Pedro asks.
* Make the path practical.
* Focus on what Pedro needs next.
* Avoid overcomplication.
* Prefer small projects and clear concepts.
