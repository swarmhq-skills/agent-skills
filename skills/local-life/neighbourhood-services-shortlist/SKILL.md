---
name: neighbourhood-services-shortlist
description: "Builds a shortlist of local services such as plumbers, vets or dentists from official listings and public reviews, with opening hours and how to book. Use when the user needs a local service."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: local-life
---

# Neighbourhood services shortlist

Find a reliable local plumber, vet or dentist.

## Requirements

- The service needed and the area
- Any must-haves (language, hours)

## When to use

- When the user needs a local service

## Steps

1. Confirm the service, area and must-haves.
2. Find 3 options from official sites and public listings. Note each source and the date seen.
3. Check opening hours and how to book on the business's own page.
4. Show a short comparison and say what could not be verified.

## Rules

- Every detail needs a source link and a date. Say "not verified" otherwise.
- Do not call, book or pay without approval.
- Do not share the user's address or details without approval.

## Output format

```
Shortlist (service, area)
- Option, hours, how to book
- Source and date
- Not verified
```
