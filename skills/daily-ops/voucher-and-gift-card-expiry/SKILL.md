---
name: voucher-and-gift-card-expiry
description: "Finds vouchers, gift cards and loyalty credits in the user's email, and lists them with the balance and expiry date. Use monthly, or before shopping."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: daily-ops
---

# Voucher and gift card expiry

Use the voucher before it expires.

## Requirements

- Email access
- A notes file for codes

## When to use

- Monthly
- Before a purchase

## Steps

1. Search email for vouchers, gift cards and credit notes.
2. Record the merchant, amount, expiry date and where to use it.
3. List those expiring in the next 30 days first.
4. Offer a reminder a week before each expiry.

## Rules

- Never copy codes into messages or notes. Point to the email that holds them.
- Read only. Do not spend or transfer a voucher without approval.
- Write "expiry not shown" when the date is missing.

## Output format

```
Vouchers (expiry first)
- Merchant, amount
- Expires
- Where the code is
```
