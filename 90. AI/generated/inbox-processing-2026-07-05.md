# Inbox Processing Proposal — 2026-07-05

## Inbox Summary

7 notes in inbox: 2 empty stubs, 5 with draft content. All are Linux-related.

---

## Per-Note Recommendations

### 1. `2026-07-05 -.md`

- **Size:** 0 bytes (empty)
- **About:** Nothing — empty file with a date-stamp filename and no topic name
- **Recommendation:** 🗑️ **Delete**
- **Reason:** Empty stub with a malformed filename (space before `.md`, no topic name). No content to salvage.
- **Next action:** Delete the file.

---

### 2. `Linux cd command.md`

- **Size:** 0 bytes (empty)
- **About:** Placeholder for the `cd` command. Referenced as `[[Linux cd command]]` from `Linux Shell`, `Linux Commands for Everyday Use`, and the Linux MOC — so the link is wanted, but the note was never written.
- **Recommendation:** ⚠️ **Needs Pedro review**
- **Reason:** Two options:
  - **Delete the stub** — then create fresh via `/create-main-note Linux cd command`
  - **Keep in Inbox** — if Pedro wants to draft it here himself
- **Next action:** Pedro decides.

---

### 3. `Common Linux Directories.md`

- **Size:** 759 bytes | **Date:** Jun 28 (1 week ago)
- **About:** A catalog of common Linux directories (`/`, `/bin`, `/home`, `/opt`, `/tmp`, `/usr`, `/var`) with one-line descriptions. Already self-marked `[x] Turn into main note`.
- **Recommendation:** 🔀 **Turn into Main Note — but resolve overlap first**
- **Suggested title:** `Common Linux Directories`
- **Suggested tags:** `[[Linux]]`, `[[Filesystem]]`, `[[Linux Basics]]`
- **Suggested MOC:** `[[Linux MOC]]`
- **Issue:** Overlaps with #7 — both cover the same directories. This note is a catalog/list; the Root note explains the *concept* of the root.
- **Recommended split:**
  - `Common Linux Directories` → reference/catalog of standard directories and their purposes (FHS overview)
  - `The Root Directory` → concept note: why `/` is the top, the tree metaphor, everything-is-a-file
- **Frontmatter fix needed:** Uses old conventions (`type: rough-note`, `Topic:`, `labels/tags:`). Needs rewrite to current `domain:` + `track:` + `tag:` style.
- **Next action:** Promote after coordinating with #7.

---

### 4. `Linux ls command.md`

- **Size:** 569 bytes | **Date:** Jun 28 (1 week ago)
- **About:** Explains the `ls` command — lists files and directories. Has a shell example. Links to Linux MOC, Linux Commands for Everyday Use, The pwd command.
- **Recommendation:** ✅ **Turn into Main Note**
- **Suggested title:** `Linux ls command`
- **Suggested tags:** `[[Linux]]`, `[[Linux Basics]]`, `[[Shell]]`
- **Suggested MOC:** `[[Linux MOC]]`
- **Fix needed:** The link `[[cd command]]` should be `[[Linux cd command]]`. Add a "Why it matters" section. Add common flags (`ls -l`, `ls -a`).
- **Next action:** Promote. Ready after small additions.

---

### 5. `SSH (Secure Shell).md`

- **Size:** 1.2 KB | **Date:** Jul 5 (today)
- **About:** Well-structured note on SSH — secure remote access to Linux systems without physical connection or VPN. Covers the idea, why it matters, an example (`ssh root@linux-srv.com`), and has placeholders for pitfalls and review questions.
- **Recommendation:** ✅ **Turn into Main Note** (most complete note in inbox)
- **Suggested title:** `SSH (Secure Shell)`
- **Suggested tags:** `[[Linux]]`, `[[Shell]]`
- **Suggested MOC:** `[[Linux MOC]]`
- **Connections to add:** Upstream → `[[Linux Shell]]`, Related → `[[Linux Commands for Everyday Use]]`
- **Next action:** Promote. Fill in the empty Downstream, Related, and Opposite sections.

---

### 6. `The pwd command.md`

- **Size:** 636 bytes | **Date:** Jun 28 (1 week ago)
- **About:** Explains the `pwd` command — prints the present working directory. Has a shell example. Empty connection sections.
- **Recommendation:** ✅ **Turn into Main Note**
- **Suggested title:** `The pwd command`
- **Suggested tags:** `[[Linux]]`, `[[Linux Basics]]`, `[[Shell]]`
- **Suggested MOC:** `[[Linux MOC]]`
- **Connections to add:** Upstream → `[[Linux Shell]]`, Related → `[[Linux ls command]]`, `[[Linux cd command]]`, `[[Linux Commands for Everyday Use]]`
- **Next action:** Promote. Fill in empty connection sections and review questions.

---

### 7. `The Root directory is the top of the Linux filesystem.md`

- **Size:** 870 bytes | **Date:** Jun 28 (1 week ago)
- **About:** Explains the root directory concept — `/` is the top of the filesystem hierarchy, everything lives under it. Uses the tree metaphor.
- **Recommendation:** 🔀 **Turn into Main Note — with shorter title, resolve overlap**
- **Suggested title:** `The Root Directory` (current title is a full sentence — titles should be noun phrases)
- **Suggested tags:** `[[Linux]]`, `[[Filesystem]]`, `[[Linux Basics]]`
- **Suggested MOC:** `[[Linux MOC]]`
- **Issue:** Overlaps with #3. See resolution plan under #3.
- **Frontmatter fix needed:** Uses very old conventions (`type: Atomic Note`, `labels/tags:`, `Topic:`, `cssclasses:`, empty `track:` and `tag:`). Needs full rewrite.
- **Grammar fixes needed:** "directorys" → "directories", "leave under" → "live under"
- **Next action:** Promote with shorter title and updated frontmatter. Coordinate overlap with #3.

---

## Summary

### Ready to process (clear action, no ambiguity)

| # | Note | Action | Priority |
|---|------|--------|----------|
| 4 | `Linux ls command.md` | → Main Note | High — already linked from MOC |
| 5 | `SSH (Secure Shell).md` | → Main Note | High — most complete, fresh |
| 6 | `The pwd command.md` | → Main Note | High — already linked from MOC |

### Needs Pedro's decision

| # | Note | Decision needed |
|---|------|-----------------|
| 1 | `2026-07-05 -.md` | Confirm deletion of empty stub? |
| 2 | `Linux cd command.md` | Delete empty stub or keep to write in? |
| 3 + 7 | `Common Linux Directories` + `The Root directory…` | Split into concept + catalog, or merge into one note? |

### Duplicates / Overlaps Found

**`Common Linux Directories` ↔ `The Root directory is the top of the Linux filesystem`**

Both cover: `/`, `/bin`, `/home`, `/tmp`, `/usr`, `/var`, `/opt`.

**Recommended approach — split by purpose:**
- **The Root Directory** — the *concept*: why `/` is the top, the tree hierarchy, everything-is-a-file
- **Common Linux Directories** — the *catalog*: what each standard directory is for (FHS basics)

If Pedro prefers one note, merge them into `Common Linux Directories` and lead with the root concept as its opening section.

### Suggested Next Steps

1. **Delete** `2026-07-05 -.md` (confirm first)
2. **Decide on** `Linux cd command.md` — delete stub or keep
3. **Resolve the overlap** between #3 and #7
4. **Promote the 3 ready notes** — `SSH`, `ls`, `pwd`
5. **Then promote the directory notes** — once overlap is resolved
6. **After all promotions, run `/update-moc Linux`** — refresh the MOC with new links

my answers
1. delete
2. delete
3. resolve the overlap
4. yes
5. do it
6. do it