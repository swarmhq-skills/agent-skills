---
name: doctor-visit-prep
description: "Turns the user's symptoms, timeline and questions into a one-page summary to bring to a doctor. Use when the user is going to a medical appointment."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: health
---

# Doctor visit prep

Make the most of a short appointment.

## Requirements

- What the user tells you: symptoms, timeline, questions

## When to use

- Before an appointment

## Steps

1. Ask about the main issue, when it started, what changes it and what has been tried.
2. Organize it as a timeline of three to six lines.
3. List medicines and allergies the user states.
4. Write the questions to ask and leave space for answers.

## Rules

- Never diagnose or suggest treatment.
- Write only what the user said.
- Recommend urgent care for red-flag symptoms.

## Output format

```
Visit summary
- Main issue and timeline
- Medicines and allergies as stated
- Questions
```
