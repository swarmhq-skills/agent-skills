---
name: school-app-watch
description: "Checks the school or daycare app and emails for new posts, notices and schedule changes about your child and turns them into a short list of what you need to do or bring. Use when the user asks what the school posted, or daily on school days."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: parenting
---

# School app watch

Know what the school said today without opening five apps.

## Requirements

- Read access to the school app or email notices (any app: ClassDojo, GrowApp, email newsletters)
- Optional: calendar, to add events with your approval

## When to use

- Each school morning
- When you ask "did the school post anything?"

## Steps

1. Open the school app or the notice emails and read everything posted since the last check.
2. Extract only items that need action: arrival time changes, things to bring, trips, payments, meetings, closures.
3. For each item write who, what, when, and whether it applies to your child. Say so if an image or document could not be read.
4. If an item has a date, offer to add it to the calendar. Wait for approval.

## Rules

- Read only. Never reply to the school, accept invitations or pay anything without explicit approval.
- Say "not sure this applies to my child" when a post does not name the group.
- Keep other children's names and photos out of the summary.
- Do not copy photos of children anywhere.

## Output format

```
School (date)
- Action needed: item, date, who it applies to
- FYI: one line each
- Could not read: list
```
