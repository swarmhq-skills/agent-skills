---
name: moving-house-checklist
description: "Builds a dated moving checklist from the move date: notices, utilities, address changes, packing and first-week tasks. Use when the user says they are moving, or asks what to do before or after a move."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: home
---

# Moving house checklist

A dated checklist for the weeks before and after a move.

## Requirements

- Move date and both addresses
- Optional: calendar access to add reminders

## When to use

- When a move date is set
- Each week until the move
- After moving day

## Steps

1. Ask the move date, whether renting or owning, household size and any pets.
2. List tasks by week counting back from moving day: notice to landlord or agent, movers or van, utilities stop and start, internet, address change for bank, insurance, tax office and mail, school or doctor if relevant.
3. Add a first-week list: meter readings with photos, keys, local registration, unpack essentials first.
4. Offer to add the dated tasks to the calendar. Wait for approval.

## Rules

- Do not state legal notice periods or deadlines. Say "check your contract and local rules".
- Never send notices or change addresses on the user's behalf without approval.
- Do not ask for ID numbers, bank details or passwords.

## Output format

```
Move plan (date)
- 4+ weeks before: tasks
- 2 weeks before: tasks
- Moving week: tasks
- First week after: tasks
- Needs your check: contract or local rules
```
