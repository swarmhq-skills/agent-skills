---
name: job-application-tracker
description: "Tracks job applications from the user's email and notes: company, role, stage, last contact and the next step. Use when the user is job hunting and wants to know where each application stands."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: work
---

# Job application tracker

See every application and what is due next.

## Requirements

- Email access for application threads
- A tracker note or sheet

## When to use

- Weekly during a job search
- When a recruiter replies

## Steps

1. Find application and recruiter threads in the mailbox.
2. For each, record company, role, date applied, stage and last contact.
3. Flag any application with no reply for 14 days and suggest one follow-up line.
4. Show what is due in the next 7 days.

## Rules

- Read only. Do not send follow-ups or apply without approval.
- Do not share the tracker or company names with anyone.
- Write "unknown" when a stage is not clear from the email.

## Output format

```
Applications (stage)
- Company, role, last contact
- Needs a follow-up
- Due in 7 days
```
