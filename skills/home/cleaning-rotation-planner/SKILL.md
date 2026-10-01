---
name: cleaning-rotation-planner
description: "Builds a simple rotating cleaning plan for a household from its rooms, the people in it and their free time. Use when the user wants a fair split of chores or a weekly cleaning routine."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: home
---

# Cleaning rotation planner

A fair weekly cleaning plan that fits the household.

## Requirements

- Rooms and chores list
- Who lives in the home and their free days

## When to use

- When the user asks for a chore plan
- Start of each month

## Steps

1. List the rooms and chores the user gives, with how often each should happen.
2. Split chores across people by free time, not by default roles. Rotate the least pleasant ones.
3. Lay out a 4-week rotation in a small table.
4. Offer to add the plan to a calendar or a shared note.

## Rules

- Only use the names and rooms the user gives.
- Do not message other people in the household without approval.
- Keep each person's weekly load within the time they said they have.

## Output format

```
Rotation (4 weeks)
- Week by week: person, chores
- Time per person
- Open questions
```
