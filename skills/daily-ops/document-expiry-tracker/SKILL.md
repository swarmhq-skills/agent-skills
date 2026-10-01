---
name: document-expiry-tracker
description: "Tracks the expiry dates of identity documents, licences, insurance and cards, and reminds well before each one. Use when the user asks which documents are expiring or wants reminders for renewals."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: daily-ops
---

# Document expiry tracker

Know when passports, licences and cards expire, before it matters.

## Requirements

- Document names and expiry dates the user provides
- Optional: calendar access

## When to use

- Quarterly review
- Before travel
- When a new document is added

## Steps

1. Ask the user for each document name and expiry date. Never ask for document numbers or copies.
2. Sort by date and mark each as soon, within six months, or later.
3. Remind at six months, three months and one month, added to the calendar after approval.
4. Before any trip, check passport validity against the destination rule the user finds on an official source.

## Rules

- Never store or ask for document numbers, photos or scans.
- Do not state renewal rules, fees or processing times. Say "check the official source".
- Dates come only from the user. Say "not sure" if a date is missing.

## Output format

```
Documents
- Expiring soon: name, date
- Within six months: name, date
- Later: name, date
- Next reminder
```
