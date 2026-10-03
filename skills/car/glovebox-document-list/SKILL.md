---
name: glovebox-document-list
description: "Builds a list of the documents the user keeps in or for the car, with expiry dates from the user's own papers, and reminds before they lapse. Use when buying a car or each year."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: car
---

# Glovebox document list

Know which papers belong in the car and when they expire.

## Requirements

- Documents the user has for the car
- Expiry dates the user reads from them

## When to use

- When getting a car
- Once a year

## Steps

1. Ask the user which documents they have and list them.
2. Record each expiry date the user gives.
3. Sort by the nearest date and mark any that are missing.
4. Remind the user a few weeks before each date.

## Rules

- Never store document numbers or copies. Keep only names and dates.
- Do not tell the user which documents the law requires. Point to the official page for their country.
- Do not renew anything without approval.

## Output format

```
Car documents
- Document and expiry date
- Missing
- Reminders set
```
