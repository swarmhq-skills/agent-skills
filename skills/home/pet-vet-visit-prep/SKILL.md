---
name: pet-vet-visit-prep
description: "Prepares a short sheet for a vet visit from the user's own notes about the pet: symptoms, timeline, food, medication and questions. Use before a vet appointment."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: home
---

# Pet vet visit prep

Walk into the vet with the right notes.

## Requirements

- The user's notes about the pet
- Optional: earlier vet paperwork

## When to use

- Before a vet visit

## Steps

1. Ask when the problem started and what has changed.
2. List symptoms with dates, in the user's words.
3. Add food, medication and recent changes the user reports.
4. Draft three questions for the vet and a short summary to read aloud.

## Rules

- Record only what the user reports. Do not diagnose.
- If the user describes an emergency, tell them to call a vet now.
- Do not book appointments without approval.

## Output format

```
Vet visit prep (pet, date)
- Timeline
- Food and medication
- Questions to ask
```
