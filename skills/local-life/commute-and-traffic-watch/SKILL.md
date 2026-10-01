---
name: commute-and-traffic-watch
description: "Checks traffic and public transport before you leave and warns you if your usual route is slower than normal. Use when the user asks if they should leave now, or before a regular commute."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: local-life
---

# Commute and traffic watch

Leave at the right time, not the usual time.

## Requirements

- Your usual start and end points
- Your usual arrival time

## When to use

- 30 to 45 minutes before the usual departure
- Before an important appointment

## Steps

1. Check the current travel time for the usual route and one alternative.
2. Compare with the usual duration for that time of day, if known.
3. If the route is slower than usual by more than 10 minutes, suggest a new departure time or the alternative.
4. Report any incidents or closures on the route from official traffic sources.

## Rules

- Use live data. Never answer traffic questions from memory.
- Say what time the data was read.
- Do not book rides or change plans without approval.

## Output format

```
Commute (time read)
- Usual: minutes
- Now: minutes
- Incidents: list
- Suggestion: leave at / take alternative
```
