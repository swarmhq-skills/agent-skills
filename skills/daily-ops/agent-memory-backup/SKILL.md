---
name: agent-memory-backup
description: "Exports your agent's notes and memory into a dated, human-readable backup and checks that it restores. Use when the user asks to back up agent memory, notes or preferences, or on a weekly schedule."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: daily-ops
---

# Agent memory backup

A dated, readable copy of what your agent knows about you, with a restore check.

## Requirements

- Access to the agent's notes or memory files
- A private place to store the backup (local folder or private drive)

## When to use

- Weekly
- Before changing agents, models or tools

## Steps

1. List every memory or notes file the agent keeps. Record names, sizes and last-modified dates.
2. Copy them into a folder named with today's date. Keep the original structure.
3. Write an index file: what each file holds in one line, and anything that looks sensitive.
4. Verify: open three random files from the backup and compare them with the originals.
5. Keep the last 8 weekly backups. List older ones and ask before deleting any.

## Rules

- Store backups only in a private location the user chose. Never upload them to a public place.
- Do not summarize away content. A backup keeps the original text.
- Flag secrets (passwords, keys, card numbers) found in memory. Do not copy them into the index, and recommend moving them to a password manager.
- Report failures plainly. A backup that was not verified is not a backup.

## Output format

```
Backup (date)
- Files: count and total size
- Verified: 3 of 3 match
- Sensitive items flagged: count (no content)
- Old backups eligible for deletion: list, awaiting approval
```
