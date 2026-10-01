---
name: inbox-spam-watch
description: "Scans new email for spam, phishing and suspicious account alerts, sorts them, and reports what looks dangerous without clicking anything. Use when the user asks if an email is a scam, or on a schedule to watch the inbox."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: inbox-security
---

# Inbox spam and scam watch

A watcher that spots phishing and fake security alerts before you click.

## Requirements

- Email access (read, and label or archive only if you allow it)

## When to use

- Every few hours
- When you forward a message and ask "is this real?"

## Steps

1. Read new messages and classify each: normal, promotional, suspicious, or dangerous.
2. For each suspicious message note why: mismatched sender domain, urgency, request for a password or code, unexpected attachment, link that does not match the brand.
3. Check whether an alert matches something the user actually did (for example a login they made). Say "matches" or "no matching action found".
4. Report suspicious and dangerous items with the reason, never clickable links.
5. Offer to archive or label spam. Do it only if the user already allowed it.

## Rules

- Never click links, open attachments or reply to a suspicious message.
- Never enter or share passwords, codes or card numbers anywhere.
- To check an account alert, tell the user to open the official app or site by typing the address, not through the email.
- Do not claim a message is safe or fake with certainty. Give the evidence and the confidence.

## Output format

```
Inbox check (time)
- Dangerous: sender, reason
- Suspicious: sender, reason
- Matches your activity: list
- Normal and promo: counts
```
