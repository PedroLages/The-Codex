---
created: 2026-07-05
domain: "[[Linux]]"
track: "[[DevOps]]"
status: active
tag:
  - "[[Linux]]"
  - "[[Shell]]"
---

# SSH (Secure Shell)

## Idea

SSH (Secure Shell) is a protocol for securely connecting to and interacting with a remote Linux system over an encrypted channel. It lets a user access a server from anywhere in the world without being physically connected to it.

## Why it matters

- **Remote management without physical access.** SSH is the standard way to administer Linux servers — no need to be in the same room, or even the same country.
- **No VPN required.** SSH provides its own encrypted tunnel. You don't need additional infrastructure like a VPN just to get a terminal on the server.
- **Foundation for other tools.** `scp`, `rsync`, `git` over SSH, and port forwarding all build on top of SSH.

## Example

```bash
ssh root@linux-srv.com
```

A typical workflow:
```bash
ssh pedro@192.168.1.100    # Connect to a server by IP
ssh pedro@web-server       # Connect using a hostname
ssh -p 2222 pedro@server   # Connect on a non-standard port
```

## Connections

### Upstream — The Bigger Idea

- [[Linux MOC]]
- [[Linux Shell]] — SSH gives you a shell on a remote machine

### Downstream — Examples & Details

- [[Linux Commands for Everyday Use]] — Once connected via SSH, these are the commands you'll use

### Related Ideas

- [[Linux cd command]] — Navigating after you connect
- [[Linux ls command]] — Inspecting the remote filesystem

### Opposite

- [[GUI - Graphic User Interface]] — GUI-based remote access (VNC, RDP) vs. text-based SSH
- Physical console access — being at the physical machine vs. remote

## Pitfalls

- **Running as root over SSH.** The same risks as running as root locally apply over SSH — a destructive command like `rm -rf /` will execute with full privileges on the remote system.
- **Password authentication.** Password-based SSH is vulnerable to brute-force attacks. Key-based authentication is the secure default.
- **Exposing port 22 to the internet.** The default SSH port is heavily scanned. Changing the port and using `fail2ban` reduces noise.

## Source

## Review questions

- What is the core idea?
- Where would I use this?
- What mistake does this help me avoid?
- How would I explain this to someone else?
