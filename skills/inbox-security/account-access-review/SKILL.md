---
name: account-access-review
description: "Reviews which apps and AI tools have access to your accounts and flags permissions you do not recognize. Use when the user gets a \"new access granted\" alert, or on a monthly schedule."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: inbox-security
---

# Account access review

A monthly look at who and what can see your accounts.

## Requirements

- Access to the security or connected-apps pages of your accounts, or a list you paste

## When to use

- Monthly
- After any "new app has access" email

## Steps

1. List connected apps and permission levels for each account the user names.
2. Mark each: used recently and recognized, not used for 90 days, or not recognized.
3. For the not recognized, give the exact page where the user can revoke it. Do not revoke anything yourself.
4. Check whether recent "new access" alerts match an action the user took.

## Rules

- Read-only. Revoking access is always the user's action.
- Never follow a link from an alert email. Go to the account settings directly.
- Do not store passwords or codes.

## Output format

```
Access review (date)
- Recognized and in use: count
- Unused 90 days: list
- Not recognized: list and where to revoke
```
