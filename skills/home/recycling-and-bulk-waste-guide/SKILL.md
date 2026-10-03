---
name: recycling-and-bulk-waste-guide
description: "Finds the user's local council rules for recycling, general waste and bulky items, and turns them into a one-page guide with collection days. Use after moving, or when the user is unsure where something goes."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: home
---

# Recycling and bulk waste guide

What goes in which bin, and when to put it out.

## Requirements

- The user's town or council
- Optional: item the user is unsure about

## When to use

- After moving
- When the user asks where an item goes

## Steps

1. Find the council's own waste and recycling page for the user's area and note the date seen.
2. List what goes in each bin and the collection days.
3. For a specific item, quote the council's rule, or say "not listed".
4. Include how to book a bulky item pickup if the council offers it.

## Rules

- Use only the council's own page. Say "not verified" if another source is used.
- Do not book a pickup without approval.
- Do not guess rules for hazardous items. Point to the council.

## Output format

```
Waste guide (area)
- Bin: what goes in
- Collection days
- Bulky items: how to book
- Source and date
```
