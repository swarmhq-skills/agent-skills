---
name: filter-and-battery-replacement-log
description: "Keeps a log of household items that need regular replacing, such as smoke alarm batteries, water filters and air filters, with the date last changed and the next due date from the maker's guidance. Use when the user installs or changes one of these, or monthly."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: home
---

# Filter and battery replacement log

Never find out a smoke alarm battery is dead at 3am.

## Requirements

- List of items and last change dates
- Maker's guidance or manual for each

## When to use

- When the user changes a filter or battery
- Monthly

## Steps

1. List each item with the date it was last changed.
2. Find the replacement interval in the maker's manual or official page and note the source.
3. Work out the next due date and sort by soonest.
4. Offer calendar reminders for the next two due dates.

## Rules

- Intervals must come from the maker. Say "check the manual" when missing.
- Never suggest skipping a safety device check, such as a smoke alarm.
- Do not order parts without approval.

## Output format

```
Replacements (month)
- Item, last changed, next due
- Source
- Due within 30 days
```
