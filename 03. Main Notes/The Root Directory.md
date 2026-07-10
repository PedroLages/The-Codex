---
created: 2026-07-05
domain: "[[Linux]]"
track: "[[DevOps]]"
status: active
tag:
  - "[[Linux]]"
  - "[[Linux Basics]]"
  - "[[Filesystem]]"
moc:
  - "[[Linux MOC]]"
---

# The Root Directory

## Idea

The root directory, represented as `/`, is the top of the Linux filesystem hierarchy. Every file, directory, and mounted device on the system lives somewhere under `/`. You can think of it as the trunk of a tree — all branches and leaves descend from it.

## Why it matters

In Linux, **everything starts with `/`**. There is no "C: drive" or "D: drive" — just a single unified tree. Understanding this is the foundation for navigating the filesystem. When you see a path like `/home/pedro/notes/linux.md`, you're reading a trail from the root down to a specific file. This also means that devices, processes, and even kernel parameters appear as files somewhere under `/`.

## Example

The root directory contains the standard top-level directories:

```
/
├── bin/      → Essential binaries
├── etc/      → Configuration files
├── home/     → User directories
├── opt/      → Third-party software
├── tmp/      → Temporary files
├── usr/      → User programs and libraries
└── var/      → Variable data (logs, caches)
```

Each of these is detailed in [[Common Linux Directories]].

## Connections

### Upstream — The Bigger Idea

- [[Linux MOC]]
- [[Filesystem]] — The filesystem is organized as a tree with `/` at its root

### Downstream — Examples & Details

- [[Common Linux Directories]] — The standard directories that live under `/`
- [[Linux cd command]] — Navigate from the root to any location
- [[The pwd command]] — See your current position in the tree relative to `/`

### Related Ideas

- Absolute vs. relative paths — `/home/pedro` starts from root; `./notes` starts from where you are
- Mount points — External drives and partitions are mounted onto directories under `/`

### Opposite

- Windows drive letters — `C:\`, `D:\` are separate roots; Linux has only `/`

## Pitfalls

- **Running destructive commands from `/`.** If you're in the root directory and run `rm -rf *`, you're deleting everything. Always double-check your working directory with `pwd`.
- **Confusing `/root` with `/`.** `/root` is the home directory of the root user — not the root of the filesystem.

## Source

## Review questions

- What is the core idea?
- Where would I use this?
- What mistake does this help me avoid?
- How would I explain the difference between `/` (root directory) and `/root` (root user's home)?
