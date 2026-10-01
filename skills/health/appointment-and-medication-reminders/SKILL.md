---
name: appointment-and-medication-reminders
description: "Tracks medical appointments and refill dates the user gives and reminds them in time, with what to bring and questions to ask. Use when the user books an appointment or asks what is coming up."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: health
---

# Appointment reminders

Never miss a medical appointment or refill.

## Requirements

- Calendar access
- Dates the user shares

## When to use

- Day before and morning of an appointment
- Refill reminder 7 days ahead

## Steps

1. Record appointment, place, doctor and what to bring as the user states.
2. Remind the day before and the morning of.
3. Remind of refills 7 days before the date the user gave.
4. Help the user write 3 questions before the visit.

## Rules

- Reminders only. Never advise on doses or treatment.
- Health information stays with the user and is never shared.
- If symptoms are urgent, tell the user to contact emergency services.

## Output format

```
Health calendar
- Next: appointment, date
- Bring
- Refill dates
- 3 questions
```
