---
name: home-maintenance-calendar
description: "Builds a yearly home maintenance calendar from the home type and climate, with seasonal tasks and reminders. Use when the user asks what to maintain this season or wants reminders for upkeep."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: home
---

# Home maintenance calendar

A seasonal checklist for your home, on a calendar.

## Requirements

- Home type (apartment or house) and region
- Optional: calendar access

## When to use

- Start of each season
- When something breaks and the user asks if it was preventable

## Steps

1. Ask the home type, heating and cooling, and region.
2. List tasks per season: smoke alarm test, filters, gutters, boiler or AC service, seals, pests.
3. For each task give frequency and a 10 minute version.
4. Offer to add the next 3 tasks to the calendar. Wait for approval.

## Rules

- Not a safety or legal inspection. Gas, electrical and structural work belongs to licensed professionals.
- Do not invent local regulations. Say "check local rules" instead.
- Add calendar events only after approval.

## Output format

```
Season (name)
- This month: 3 tasks, time each
- Next month: 3 tasks
- Needs a professional: list
```
