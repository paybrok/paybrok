# Security

Paybrok is designed with a security-first approach around wallet custody, protected payments, provider risk, and dispute documentation.

## Core Principles

- Users control their wallet.
- Paybrok does not store user seed phrases on Paybrok servers.
- Recovery words must be protected by the user.
- Sensitive wallet actions require local unlock where applicable.
- Escrow helps reduce counterparty risk in marketplace flows.
- Provider review and dispute evidence help reduce informal-payment risk.

## User Safety Rules

Users should never share:

- 12 recovery words.
- Stellar secret key.
- Web wallet password.
- PIN.
- Private wallet credentials.

Paybrok will not request these through support, Telegram, email, phone, social media, provider chat, or any informal channel.

## Web Wallet Protection

The Paybrok web wallet uses a local encrypted vault. The user's sensitive wallet material is encrypted in the browser with a password created by the user.

Important:

- If the encrypted vault remains, Paybrok can restore the local wallet session.
- If the browser deletes all site storage, the user must restore with recovery words.
- Different browsers may not share the same vault.
- The local password is not the recovery phrase.

## Local Unlock and Brute-Force Protection

Paybrok includes local unlock protections for sensitive actions. These protections are designed to make repeated guessing harder and to protect the user when too many incorrect attempts occur.

Public security concept:

- Sensitive flows require local confirmation or password/PIN depending on platform and wallet mode.
- Repeated incorrect attempts can trigger protective behavior.
- Users should use strong local passwords and keep recovery words offline.

This section describes the public security behavior only. It does not expose internal implementation details.

## Security Differentiators

Paybrok's security advantage is not one isolated control. It combines several layers that support real payment use:

- Self-custody wallet model.
- Local encrypted web vault.
- Local unlock for sensitive actions.
- Repeated-attempt protection concepts.
- Escrow for P2P, remittances, and service payments.
- Dispute evidence and review workflows.
- Provider review.
- Sanctions and risk controls.
- AML/CTF public policy.

Together, these controls help Paybrok support practical digital-dollar payments without relying only on blind trust between users.

## Escrow Security

Escrow helps reduce risk by preventing immediate release of funds before the agreed action is completed.

Escrow can support:

- P2P orders.
- Local provider flows.
- Remittances.
- Protected service payments.
- Milestone-based releases where enabled.
- Soroban escrow where configured.

Document the agreement, keep delivery evidence and use milestones for service payments. Escrow governs the release of funds; the parties remain responsible for verifying the actual delivery and opening disputes within the applicable window.

## Dispute Safety

Paybrok includes dispute workflows so users can document what happened.

Useful evidence includes:

- Screenshots.
- Receipts.
- Payment references.
- Chat records.
- Delivery proof.
- Transaction hashes.

## Risk, Sanctions, and Provider Controls

Paybrok applies operational controls to support safer usage.

These may include:

- Provider review.
- Country and method restrictions.
- Risk-based monitoring.
- Sanctions screening.
- Abuse detection.
- Dispute documentation.
- Suspension or restriction of suspicious activity.
- Manual review where appropriate.

These controls support provider review and transaction follow-up. Check the counterparty, payment receipt and delivery evidence for each order; provider review is a platform process, not an insurance policy or a guarantee of performance.

## Keep Access and Review Each Payment

- Keep an offline copy of your recovery words. Recovery requires those words or a working local key; Paybrok has no copy to restore access if both are lost.
- Confirm the available provider, quote, limits and delivery method before accepting.
- Verify payment in the receiving account and confirm delivery before release. Escrow and dispute review follow the accepted rules; outcomes depend on the facts and evidence.
- For high-value agreements, retain written specifications, delivery records and any additional contracts.
- Read the [terms](https://paybrok.com/terms) for digital-asset risks and responsibilities.
