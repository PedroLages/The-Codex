---
created: 2026-07-05
domain: "[[Linux]]"
track: "[[DevOps]]"
status: active
tag:
  - "[[Linux]]"
  - "[[Shell]]"
moc:
  - "[[Linux MOC]]"
---

# The pwd command

## Idea

The `pwd` (Print Working Directory) command displays the absolute path of the current directory. It answers the question "Where am I?" — essential after navigating through a deep directory tree or returning to a terminal session.

## Why it matters

Getting lost in the filesystem is easy, especially when working across multiple terminal tabs or returning to a session after a break. `pwd` is the fastest way to reorient yourself. It's also critical in scripts — you often need to know the current directory before acting on relative paths.

## Example

```shell
[pedro@linuxsrv ~]$ cd /etc/nginx/conf.d/
[pedro@linuxsrv conf.d]$ pwd
/etc/nginx/conf.d
```

Using `pwd` in a script:
```bash
#!/bin/bash
echo "Running from: $(pwd)"
```

## Connections

### Upstream — The Bigger Idea

- [[Linux MOC]]
- [[Linux Shell]] — The shell is where you run `pwd`
- [[Linux Commands for Everyday Use]] — `pwd` is one of the core everyday commands

### Downstream — Examples & Details

- (None yet)

### Related Ideas

- [[Linux cd command]] — Navigate somewhere, then `pwd` to confirm
- [[Linux ls command]] — Know where you are, then list what's there
- [[Common Linux Directories]] — Understanding the paths `pwd` shows you

### Opposite

- [[GUI - Graphic User Interface]] — File managers show your location visually; `pwd` tells you textually

## Source

## Review questions

- What is the core idea?
- Where would I use this?
- What mistake does this help me avoid?
- When would I use `pwd` in a script vs. interactively?
