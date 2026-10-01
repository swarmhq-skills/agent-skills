---
name: local-events-watch
description: "Watches official local sources (city council, venues, school and neighborhood pages) for events near you and sends a short digest with dates, prices and links to the official page. Use when the user asks what is on nearby, or weekly."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: local-life
---

# Local events watch

What is happening near you this month, from official sources only.

## Requirements

- Your area (city or neighborhood)
- Optional: interests and ages of children

## When to use

- Weekly digest
- When something new is announced, such as construction or a festival

## Steps

1. Search the official city, venue and neighborhood pages for the next 30 days.
2. List each event with date, time, place, price and the official link.
3. Mark how you know: "official listing" or "unconfirmed". Drop anything unconfirmed after one more check.
4. If the user asks about a structure or road change, say what the sources actually say and what they do not explain.
5. Offer family-friendly picks if the user asked for them.

## Rules

- Use official sources first. Say when a page looks old or recurring.
- Never buy tickets or reserve without explicit approval.
- Do not guess reasons for road or construction changes. Report what is published.

## Output format

```
Near you (date range)
- Events: date, place, price, link
- Changes: roads or works, what is published
- Unconfirmed: list
```
