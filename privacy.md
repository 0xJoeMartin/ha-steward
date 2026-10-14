---
title: Steward privacy policy
---

# Steward privacy policy

*Effective 14 October 2026*

Steward is a self-hosted Home Assistant add-on. The current installation is run by its developer, Joe Martin, for his
own home. Steward is not a hosted service and has no accounts for anyone else.

## What Google data Steward accesses

Steward requests one Google permission: **read-only access to Gmail** (`gmail.readonly`) for the owner's own mailbox.
It cannot send, delete or change email.

## How it is used

Steward looks through recent mail for **dated commitments**: bookings, renewals, deliveries, bills, expiring keys
and similar, so it can remind the owner and mention them in the daily briefing. That is its only use.

## Where it is processed

- **Full email content** is read and analysed only on the owner's own hardware, by a language model running locally
  on the owner's network. Full email content is not sent to any third-party service.
- **Short summaries** of what was found (for example, "AppleCare renewal, 13 Oct 2027, $19.99, from apple.com") are
  stored locally. They can appear in the owner's briefings, and in diagnostic data that Steward's daily self-review
  sends to Anthropic's Claude API under the owner's own account.

## Storage, sharing and retention

- Summaries and the Gmail access token are stored only on the owner's own systems (the add-on's storage and the
  owner's backups).
- Google user data is not sold, shared for advertising, or used to train AI models, and no one other than the owner
  reads it.
- The owner can delete everything Steward stored by removing the add-on's data, and can revoke Gmail access at any
  time at <https://myaccount.google.com/permissions>.

## Changes and contact

Changes to this policy are published on this page. Questions: open an issue at
<https://github.com/0xJoeMartin/ha-steward/issues>.
