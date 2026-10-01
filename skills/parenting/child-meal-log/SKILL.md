---
name: child-meal-log
description: "Logs what your child ate at school, daycare and home from the menus and the notes you give it, and flags gaps against a simple balance check. Use when the user asks what the child ate, or sends a photo or note about a meal."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: parenting
---

# Child meal log

A simple, honest picture of what your child eats in a week.

## Requirements

- The school or daycare menu, if available
- Your notes or photos of meals

## When to use

- Daily, when you send a note
- Weekly summary on Sunday

## Steps

1. Record each meal the user reports: day, meal, items, and how much was eaten, in the user's words.
2. Add the school menu for the same days and mark what the user confirms or corrects.
3. At the end of the week count servings of vegetables, fruit, protein and sweets per day.
4. Point out the two most useful patterns, such as "no vegetables on three days", and suggest one easy swap.

## Rules

- Not medical or nutrition advice. For allergies or feeding concerns, talk to a pediatrician.
- Never compare the child with other children.
- Do not turn a picky-eating week into a worry. Keep the tone calm.
- Store the log with the family only.

## Output format

```
Meals this week
- Per day: items and servings
- Patterns: two observations
- One easy swap to try
```
