---
name: pet-care-schedule
description: "Keeps a simple care schedule for a pet: vaccines, treatments, vet visits, food and licence renewals, and reminds before each date. Use when the user asks about their pet's care dates or wants reminders."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: home
---

# Pet care schedule

Feeding, vet and treatment dates for your pet, in one place.

## Requirements

- Pet type, age and the dates the user already has
- Optional: vet emails or records, calendar access

## When to use

- When a new date is known
- Monthly review
- When the user asks "what is due for my pet?"

## Steps

1. Collect the dates the user gives or that appear in vet emails and records, with the source for each.
2. Build a list of what is due now, soon and later. Never invent due dates for vaccines or treatments.
3. Offer reminders two weeks before each date, added to the calendar after approval.
4. Note questions to ask the vet at the next visit.

## Rules

- Not veterinary advice. For symptoms or emergencies, contact a vet.
- Only use dates found in records or given by the user. Say "ask your vet" for anything else.
- Do not share the pet's or owner's details with anyone without approval.

## Output format

```
Pet care (name)
- Due now
- Due soon
- Later
- Questions for the vet
```
