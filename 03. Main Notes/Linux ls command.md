---
created: 2026-07-05
domain: "[[Linux]]"
track: "[[DevOps]]"
status: active
tag:
  - "[[Linux]]"
  - "[[Linux Basics]]"
  - "[[Shell]]"
moc:
  - "[[Linux MOC]]"
---

# Linux ls command

## Idea

The `ls` command lists the files and directories inside a given directory. It's the primary tool for inspecting what's in a folder — the first command you run after `cd`-ing somewhere new.

## Why it matters

`ls` is one of the most-used Linux commands. Knowing its common flags (`-l` for details, `-a` for hidden files, `-h` for human-readable sizes) turns it from a simple lister into a quick inspection tool. Every second saved orienting yourself in a directory is a second you can spend on the actual task.

## Example

```shell
[pedro@linuxsrv ~]$ ls
Desktop  Downloads  notes  projects

[pedro@linuxsrv ~]$ ls -la
total 32
drwxr-xr-x  5 pedro pedro 4096 Jul  5 10:00 .
drwxr-xr-x  3 root  root  4096 Jun 28 14:30 ..
-rw-r--r--  1 pedro pedro  220 Jun 28 14:30 .bashrc
drwxr-xr-x  2 pedro pedro 4096 Jul  1 09:15 Desktop
drwxr-xr-x  2 pedro pedro 4096 Jun 28 14:30 Downloads
```

## Common Flags

| Flag | Meaning |
|------|---------|
| `-l` | Long format — permissions, owner, size, date |
| `-a` | All files, including hidden ones (starting with `.`) |
| `-h` | Human-readable sizes (1K, 234M, 2G) |
| `-t` | Sort by modification time, newest first |
| `-r` | Reverse order |

## Connections

### Upstream — The Bigger Idea

- [[Linux MOC]]
- [[Linux Shell]] — The shell is where you run `ls`
- [[Linux Commands for Everyday Use]] — `ls` is one of the core everyday commands

### Downstream — Examples & Details

- (None yet)

### Related Ideas

- [[The pwd command]] — Know where you are before listing what's there
- [[Linux cd command]] — Navigate, then list
- [[Common Linux Directories]] — Understanding what you're looking at

### Opposite

- [[GUI - Graphic User Interface]] — Point-and-click file browsing vs. command-line listing

## Source

## Review questions

- What is the core idea?
- Where would I use this?
- What mistake does this help me avoid?
- What's the difference between `ls`, `ls -l`, and `ls -la`?
