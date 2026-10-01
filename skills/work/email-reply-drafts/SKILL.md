---
name: email-reply-drafts
description: "Writes draft replies to emails that need an answer, in the user's usual tone, and leaves them as drafts for review. Use when the user asks for a reply draft or when triage marks an email as needing a reply."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: work
---

# Email reply drafts

Short, clear reply drafts in your voice, for you to review.

## Requirements

- Email access (read, draft)
- A few sent emails to learn the tone

## When to use

- When the user asks for a reply
- After email triage

## Steps

1. Read the email and the thread. Note what is asked and by when.
2. Check the user's calendar or facts only when the reply needs them. Do not invent facts, dates or prices.
3. Draft a short reply in the user's tone: answer first, then one clear next step.
4. Save as a draft and show it. List any fact you could not confirm.

## Rules

- Never send. Drafts only, until the user approves each one.
- Never promise, accept, decline or commit the user to anything in a draft without marking it for the user to confirm.
- Do not include private details the recipient does not already have.

## Output format

```
Draft for (sender, subject)
- Draft text
- Facts I could not confirm
- Needs your decision
```
