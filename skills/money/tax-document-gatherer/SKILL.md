---
name: tax-document-gatherer
description: "Builds a checklist of tax documents for the year, finds them in email and files, and lists what is missing. Use when the user asks to prepare for tax season."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: money
---

# Tax document gatherer

Every tax paper in one folder before the deadline.

## Requirements

- Email access and a documents folder
- Country and type of income

## When to use

- Early in tax season
- When the user asks what is missing

## Steps

1. Ask the country and income types (employee, self-employed, rent, investments).
2. List the common documents for that situation from an official source and cite it.
3. Search email and files for each and copy found items into one folder.
4. Report what is missing and where it is usually issued.

## Rules

- This is not tax advice. Official forms and an accountant decide.
- Never submit anything to a tax authority.
- Never use a tax number the user has not given you.

## Output format

```
Tax year (year)
- Found: list
- Missing: list and where
- Deadlines from the official site
```
