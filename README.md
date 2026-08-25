# Paybrok

Paybrok is a wallet with local signing and a protected payment platform for people, merchants, freelancers, service providers, and local payment operators who need to use digital dollars in real life. Users control their wallet keys; protected funds are locked in Soroban contracts and disputes may be resolved by Paybrok's designated administrator wallet under the published rules.

With Paybrok, a user can create a wallet, receive digital dollars, pay with QR, send funds, use local payment providers, protect a service payment with escrow, send money across routes where providers are available, and document disputes when something goes wrong.

> Paybrok helps people pay and get paid in digital dollars without giving up control of their wallet.

Paybrok is built for practical use cases such as milestone escrow for Latin
American importers, protected Ecuador-China supplier payments with USDC on
Stellar, non-custodial digital dollar wallets, wallet-based service contracts,
remittances with receipts and delivery evidence, and P2P payments with escrow
and reviewable disputes.

Paybrok LLC builds non-custodial payment software for Stellar wallets,
protected payments, remittances, QR collections and local provider workflows.

Spanish version: [docs/readme-es.md](docs/readme-es.md)

Official website: https://paybrok.com

Public documentation sitemap: https://paybrok.github.io/paybrok/sitemap.xml

## Paybrok on Stellar

Paybrok operates in production and is built on the Stellar public network for
practical payment flows with XLM and supported Stellar assets such as USDC and
EURC. The public Stellar profile for Paybrok is available at
https://paybrok.com/stellar and the domain-level Stellar information file is available at
https://paybrok.com/.well-known/stellar.toml.

Paybrok should be described as a non-custodial Stellar wallet and protected
payments platform for Latin America. It supports real-world payment use cases
such as QR payments, P2P orders, remittances, provider workflows, and milestone
escrow for importers, freelancers, and service agreements.

Paybrok operates in production, but does not present itself as a bank,
custodial exchange, or public Stellar anchor. Availability depends on country,
asset, provider liquidity, compliance review, and operational configuration.

## Public Identity and Stellar Verification

Paybrok is developed by Paybrok LLC and a product, engineering, operations, security, and support team led by founder Mario Montaño. Public founder contact: mm@paybrok.com.

The official institutional Stellar account is:

`GA2FD3TA4XUJG5SMFOQDZXQAPNCLAA62W5PMKFE7A3WD6TRAKP7PBAXF`

That account declares `paybrok.com` as its home domain on the Stellar public network. The matching public identity file is available at [paybrok.com/.well-known/stellar.toml](https://paybrok.com/.well-known/stellar.toml). See [Official Identity and Verification](docs/official-identity.md) for the complete set of references.

## Why Paybrok Exists

Digital dollars are useful, but everyday payments still have friction:

- A client does not want to pay a contractor before the work is delivered.
- A contractor wants proof that the client has funds available.
- A person wants to pay a local QR but only has digital dollars.
- A merchant wants to charge with a link or QR instead of manually sending wallet addresses.
- A user wants to move value across countries with a local provider.
- A buyer and seller need a safer way to coordinate a P2P payment.

Paybrok brings these flows into one product: wallet, QR, P2P, escrow, service milestones, remittances, providers, disputes, and notifications.

## Why Paybrok Is Different

Paybrok is not just another wallet, and it is not just a P2P listing board. Its strength is that it connects the full payment journey in one product.

Many tools solve only one piece: storing funds, sending crypto, making QR requests, finding a local buyer, coordinating a remittance, or managing a service payment. Paybrok brings these layers together:

- Self-custody wallet.
- QR and payment links.
- Local providers.
- P2P liquidity.
- Escrow.
- Service milestones.
- Remittance-style flows.
- Disputes with evidence.
- Notifications.
- Provider review.
- Risk and sanctions controls.
- Local encrypted vault and local unlock protections.
- Brute-force protection concepts for sensitive unlock flows.

That combination is Paybrok's advantage: users can move from holding digital dollars to actually using them in real-world payments, with more structure and protection than an informal transfer or chat-based deal.

## What Users Can Do

### Wallet

- Create a Paybrok wallet.
- Restore a wallet with recovery words.
- View balances and wallet status.
- Send supported assets.
- Receive supported assets.
- Copy, share, or scan wallet/payment information.
- Review movement history.
- Use a web wallet with a local encrypted vault.
- Use Freighter as an advanced web option where supported.

### QR and Payment Links

- Create a QR to collect a payment.
- Create payment links.
- Scan payment QR codes.
- Open Paybrok payment links with pre-filled details.
- Use local QR flows when Paybrok can detect country, method, amount, merchant reference, or provider link.

### Paybrok Local

Paybrok Local connects digital dollars with local payment methods through approved providers.

Users can:

- Buy or sell digital dollars where liquidity is available.
- Choose country, asset, amount, and method.
- Match with local providers.
- Use escrow protection.
- Track order state.
- Open a dispute with evidence if needed.

### Protected Service Payments

Paybrok can protect service payments by splitting a project into milestones.

Example:

A client hires an architect for a 100 USDC job. Instead of paying everything upfront, the client can split the payment:

- 30 USDC for the initial concept.
- 40 USDC for the reviewed draft.
- 30 USDC for the final delivery.

Funds can be locked in escrow and released as work is delivered. If the work is not delivered, the client can open a dispute with evidence.

Service agreements can also include clear operating rules before both sides accept them:

- Delivery deadline.
- Review or inspection period after the provider marks work as ready.
- Automatic release rules when the client does not respond within the agreed window.
- Late delivery penalty options agreed before acceptance.
- Milestone percentages or amounts for partial releases.

These rules help both sides know what happens before money moves, while keeping the payment flow simple.

This can be useful for:

- Architecture.
- Design.
- Repairs.
- Construction.
- Consulting.
- Technology services.
- Freelance work.

### Remittances

Paybrok supports remittance-style flows through approved providers or bridges where available.

Users can:

- Choose a route.
- Choose amount and asset.
- Select a provider or delivery method when available.
- Lock funds in escrow.
- Confirm delivery or open a dispute.

### Providers and Merchants

Approved providers can support local liquidity, remittances, local QR payments, or service delivery.

Provider capabilities may include:

- Accepting local orders.
- Offering payment methods by country.
- Delivering local payments.
- Supporting remittance routes.
- Participating in protected service flows.
- Building operational reputation through completed orders.

### Disputes

Paybrok includes a dispute flow so users can document problems instead of relying only on informal chat.

Evidence may include:

- Screenshots.
- Payment receipts.
- Chat history.
- Delivery proof.
- Transaction hashes.
- Local payment references.

## Safety and Security

Paybrok is designed around self-custody.

- Paybrok does not ask users to send their seed phrase to Paybrok servers.
- Paybrok does not ask for recovery words by Telegram, email, chat, phone, or provider message.
- The web wallet uses a local encrypted vault.
- Sensitive actions require local unlock where applicable.
- Escrow helps reduce counterparty risk.
- Provider review, sanctions/risk controls, and dispute documentation support safer operations.

Users must keep their recovery words safe. If a user loses the device/browser storage and does not have recovery words, Paybrok cannot recover the wallet.

## What Paybrok Is Not

- Paybrok is not a bank.
- Paybrok is not a centralized exchange.
- Paybrok does not guarantee local liquidity or exchange rates.
- Paybrok does not guarantee that every provider, country, asset, or route is always available.
- Paybrok does not replace a formal legal contract for high-value services.
- Paybrok does not make users immune to fraud; it provides safer structure, escrow, evidence, and review flows.

## Documentation

- [Guía operativa paso a paso ES](docs/guia-operativa-es.md)
- [Product Overview](docs/product-overview.md)
- [Product Overview ES](docs/product-overview-es.md)
- [Market Positioning](docs/market-positioning.md) / [Posicionamiento ES](docs/market-positioning-es.md)
- [Features](docs/features.md) / [Funciones ES](docs/features-es.md)
- [Capabilities](docs/capabilities.md) / [Capacidades ES](docs/capacidades-es.md)
- [Wallet](docs/wallet.md) / [Wallet ES](docs/wallet-es.md)
- [P2P and Escrow](docs/p2p-escrow.md) / [P2P y Escrow ES](docs/p2p-escrow-es.md)
- [Protected Service Payments](docs/service-contracts.md) / [Servicios ES](docs/service-contracts-es.md)
- [Local QR Payments](docs/local-qr-payments.md) / [QR Local ES](docs/local-qr-payments-es.md)
- [Remittances](docs/remittances.md) / [Remesas ES](docs/remittances-es.md)
- [Retiro de efectivo ES](docs/withdrawals-es.md)
- [Providers](docs/providers.md) / [Proveedores ES](docs/providers-es.md)
- [Security](docs/security.md) / [Seguridad ES](docs/security-es.md)
- [Compliance](docs/compliance.md) / [Compliance ES](docs/compliance-es.md)
- [Stellar Ecosystem Submission](docs/stellar-ecosystem-submission.md)
- [FAQ](docs/faq.md) / [FAQ ES](docs/faq-es.md)
- [Public Roadmap](docs/roadmap.md) / [Roadmap ES](docs/roadmap-es.md)

## Status

Paybrok is in active development and production operation. Feature availability can vary by platform, country, asset, provider liquidity, compliance review, and operational configuration.

## Public Contact

- Website: https://paybrok.com
- Reddit: https://www.reddit.com/user/Signal_You6871/
- Support: support@paybrok.com
- Legal: legal@paybrok.com
- Privacy: privacy@paybrok.com
- Compliance: compliance@paybrok.com
