---
name: email-triage
description: "Sorts the inbox into reply today, reply this week, FYI and ignore, and drafts short replies for approval. Use when the user asks to triage email, or twice a day."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: work
---

# Email triage

Zero guilt inbox: only what needs you.

## Requirements

- Email access (read)

## When to use

- Morning and mid-afternoon
- When the user feels behind

## Steps

1. Read unread email since the last triage.
2. Sort into: reply today, this week, FYI, ignore. Give one line on why.
3. Draft replies for the reply-today group, in the user's usual tone.
4. Show drafts. Send nothing.

## Rules

- Never send, delete or archive without approval.
- Mark anything that looks like phishing and do not open links.
- Drafts quote facts only from the thread.

## Output format

```
Inbox
- Reply today: sender, why
- This week
- FYI
- Drafts ready
```
