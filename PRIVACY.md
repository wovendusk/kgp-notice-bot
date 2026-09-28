# Privacy Policy - KGP Notice Bot

_Last updated: 2026-09-28_

KGP Notice Bot is a personal tool used by a single person (its developer) on their own computer.
It is not offered to or used by anyone else.

## What Google data it accesses

- It requests the **read-only Gmail scope** (`gmail.readonly`) for the developer's own account.
- It reads only recent messages, looking for the one-time password (OTP) email sent by the
  IIT Kharagpur ERP portal, and extracts the OTP digits from it.

## How the data is used

- The OTP is used once, immediately, to complete a login to the ERP portal, then discarded.
- No email content is stored, logged, or kept after the OTP has been used.
- It never sends, modifies, or deletes email.

## Sharing

No Google user data is shared with, sold to, or transferred to any third party. Nothing is sent
anywhere except the OTP itself, to the ERP portal it was issued by.

## Storage and security

The only Google-related data stored is the OAuth token, kept locally on the developer's own
machine with file permissions limiting access to that user. Access can be revoked at any time
at https://myaccount.google.com/permissions.

## Contact

Questions about this policy: open an issue at https://github.com/wovendusk/kgp-notice-bot/issues.

Use of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.
