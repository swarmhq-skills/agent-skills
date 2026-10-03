---
name: free-activities-finder
description: "Finds free events and places near the user from official council, library and park pages, and builds a short list for the weekend. Use when the user wants something to do without spending."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: local-life
---

# Free activities finder

Things to do nearby that cost nothing.

## Requirements

- The user's town
- Dates the user is free
- Optional: ages in the group

## When to use

- Before a weekend
- During school holidays

## Steps

1. Check the council, library and park pages for the user's area.
2. List events with date, time and place, and note the date each page was seen.
3. Mark any that need booking or have limited places.
4. Suggest three options that fit the user's free time.

## Rules

- Use only official or organiser pages.
- Say "not verified" if an event is on another source.
- Do not book or register without approval.

## Output format

```
Free this weekend
- Event, date, time, place
- Booking needed?
- Source and date seen
```
