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

# Common Linux Directories

## Idea

Linux organizes files into a standard directory structure defined by the Filesystem Hierarchy Standard (FHS). Each top-level directory has a specific purpose — knowing what lives where makes navigating and troubleshooting any Linux system much faster.

## Why it matters

When you encounter an unfamiliar Linux system, knowing the standard directories lets you find what you need without guessing: binaries are in `/bin`, logs in `/var/log`, configuration in `/etc`. This is especially valuable when debugging — you know where to look before you even start.

## Standard Directories

| Directory | Purpose |
|-----------|---------|
| `/` | The root directory — the top of the entire filesystem tree. See [[The Root Directory]]. |
| `/bin` | Essential user binaries and executable programs (e.g., `ls`, `cp`, `cat`) |
| `/etc` | System-wide configuration files |
| `/home` | Home directories for regular users (`/home/pedro`, `/home/alice`) |
| `/opt` | Optional or third-party software packages |
| `/tmp` | Temporary files — cleared on reboot |
| `/usr` | User-related programs, libraries, and documentation |
| `/var` | Variable data — logs, caches, spools, databases |

## Connections

### Upstream — The Bigger Idea

- [[Linux MOC]]
- [[The Root Directory]] — The root (`/`) is the top of this hierarchy

### Downstream — Examples & Details

- [[The pwd command]] — See your current location in this directory tree
- [[Linux cd command]] — Navigate between these directories

### Related Ideas

- [[Filesystem]] — The larger concept of how data is organized on disk
- [[Linux Shell]] — The environment where you navigate this structure

### Opposite

- [[GUI - Graphic User Interface]] — File managers show the same structure visually

## Source

## Review questions

- What is the core idea?
- Where would I use this?
- What mistake does this help me avoid?
- If I'm looking for logs, which directories should I check first?
