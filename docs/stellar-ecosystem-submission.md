# Paybrok Stellar Ecosystem Submission

## Summary

Paybrok operates in production as a non-custodial Stellar wallet and protected
payments platform for Latin America. It supports practical payment flows with
XLM and supported Stellar assets such as USDC and EURC, including QR payments,
P2P orders, remittances, provider workflows, and milestone escrow for importers,
freelancers, and service agreements.

Public profile: https://paybrok.com/stellar

Stellar information file: https://paybrok.com/.well-known/stellar.toml

Public documentation: https://paybrok.com/docs

Public GitHub documentation: https://github.com/paybrok/paybrok

## Integration With Stellar

Paybrok uses Stellar as the payment network for fast, low-cost digital asset
movement. The product is designed around non-custodial wallet use: users keep
control of their wallets and Paybrok does not ask for recovery phrases, seeds,
or private keys through support, email, chat, or provider messages.

Paybrok focuses on real-world payment workflows:

- Wallet creation, restoration, balance display, send, receive, and transaction
  history for supported Stellar assets.
- Payment links and QR flows for collecting or initiating payments.
- P2P orders with escrow, status tracking, evidence, and dispute workflows.
- Remittance-style flows through approved providers or bridges where available.
- Provider workflows for local liquidity, local payment methods, and delivery
  evidence where operationally available.
- Milestone escrow for importers, freelancers, and service agreements.
- Security guidance and public documentation for self-custody, recovery words,
  dispute evidence, and operational risk.

## Product Scope

- Non-custodial Stellar wallet.
- Support for XLM and supported Stellar assets such as USDC and EURC.
- QR payments and payment links.
- Protected service payments with milestones.
- P2P and escrow workflows.
- Remittance-style flows where providers are available.
- Provider and merchant workflows for local payment operations.
- Public security and compliance documentation.
- Domain-level Stellar information through `/.well-known/stellar.toml`.

## Important Clarifications

Paybrok operates in production, but does not present itself as a bank, custodial
exchange, or public Stellar anchor. Availability depends on country, asset,
provider liquidity, compliance review, and operational configuration.

Paybrok is not PayBrokers. Paybrok LLC builds non-custodial payment software
for Stellar wallets, protected payments, remittances, QR collections, and local
provider workflows.
