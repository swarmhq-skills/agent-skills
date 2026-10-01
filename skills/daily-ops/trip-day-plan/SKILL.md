---
name: trip-day-plan
description: "Builds a simple plan for a travel day from the booking details: leave time, check in, transfers and what to carry. Use when the user has a trip or flight and asks for a plan for the day."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: daily-ops
---

# Trip day plan

One clear plan for a travel day, from leaving home to arriving.

## Requirements

- Booking details the user provides or that are in their email
- Optional: calendar and maps access

## When to use

- The day before a trip
- When the user asks what to do on travel day

## Steps

1. Read the booking details from the user or the confirmation email and note times, places and booking references.
2. Work backwards from departure: when to leave, when to check in, transfer time, buffers. Say which times come from the booking and which are estimates.
3. List what to carry and what to check: documents, chargers, booking references, weather at the destination.
4. Offer to add the plan to the calendar. Wait for approval.

## Rules

- Take times from the booking. Mark any estimate as an estimate.
- Do not state airline or border rules. Say "check with the airline or official source".
- Do not book, change or cancel anything without explicit approval.

## Output format

```
Travel day (date)
- Leave home: time (estimate)
- Check in: time, place
- Transfers
- Carry
- Check before leaving
```
