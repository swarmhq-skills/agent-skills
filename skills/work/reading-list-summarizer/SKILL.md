---
name: reading-list-summarizer
description: "Summarises the articles and documents the user saved to read later, in two lines each, and ranks them by relevance to a goal the user states. Use weekly or when the reading queue grows."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: work
---

# Reading list summarizer

Know what is worth reading in your queue.

## Requirements

- Links or files saved to read later
- A short statement of the user's current goal

## When to use

- Weekly
- When the queue passes 10 items

## Steps

1. Open each saved item and read it. Note the title, author and date.
2. Write two lines on what it says. Do not add claims that are not in the text.
3. Rank by relevance to the user's goal and mark which to read in full.
4. List items that could not be opened.

## Rules

- Summarise only what the text says. Quote when a figure matters.
- Do not share the reading list or summaries without approval.
- Say "could not open" instead of guessing from the title.

## Output format

```
Reading queue (week)
- Item, two lines, link
- Read in full
- Skip
- Could not open
```
