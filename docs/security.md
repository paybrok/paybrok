# Security

Paybrok is designed with a security-first approach, especially around wallet custody.

## Core Principles

- Users control their wallet.
- Paybrok does not store user seed phrases on Paybrok servers.
- Sensitive wallet actions require local unlock.
- Recovery words must be protected by the user.
- Escrow reduces counterparty risk in marketplace flows.

## User Safety Rules

Users should never share:

- 12 recovery words.
- Stellar secret key.
- Web wallet password.
- PIN.
- Private wallet credentials.

Paybrok will not request these through support, Telegram, email, phone, or provider chat.

## Web Wallet Security

The Paybrok web wallet encrypts sensitive wallet material locally in the browser using a password created by the user.

Important:

- If the encrypted vault remains, Paybrok can restore the local wallet session.
- If the browser deletes all site storage, the user must restore with recovery words.
- Different browsers may not share the same vault.

## Escrow Security

Escrow helps reduce risk by preventing immediate release of funds before the agreed action is completed.

Escrow does not eliminate all risk. Users should document agreements, keep evidence, and use milestones for service payments.

## Operational Security

Paybrok also uses operational controls such as:

- Abuse monitoring.
- Dispute review.
- Provider review.
- Sanctions and risk checks.
- Notification and event tracking.
- Security logging and monitoring where appropriate.

