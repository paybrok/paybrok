# Paybrok Capabilities

This document summarizes the public capabilities of Paybrok without exposing private source code, internal infrastructure, secrets, keys, or operational security details.

## 1. Non-Custodial Wallet

Paybrok lets users create or restore a Stellar wallet.

Capabilities:

- Create a wallet.
- Restore a wallet with recovery words or a Stellar secret key.
- View balances.
- View public wallet address.
- Send supported assets.
- Receive supported assets.
- Scan QR codes.
- Generate payment QR codes and links.
- View movement history.
- Keep custody of wallet credentials locally.

Security principle:

Paybrok does not ask users to send their seed phrase to Paybrok servers.

## 2. Web Wallet

Paybrok includes a browser-based wallet mode.

Capabilities:

- Create a Paybrok web wallet.
- Encrypt the seed locally in the browser with a user-created password.
- Unlock the wallet locally for sensitive actions.
- Recover wallet state if browser metadata is partially lost but the encrypted vault remains.
- Use Freighter as an advanced external signer where supported.

Limitations:

- If a browser deletes all site storage, including the encrypted vault, the user must restore with recovery words.
- Different browsers on the same device may not share the same local vault.

## 3. QR Payments and Collection

Paybrok supports QR-based payments and collection.

Capabilities:

- Generate payment QR codes.
- Generate payment links.
- Scan QR codes.
- Detect payment information when available.
- Support local QR payment flows where the QR includes a provider link, merchant reference, amount, or method.

## 4. P2P Local Market

Paybrok Local connects users who need digital dollars or local money with approved providers.

Capabilities:

- Create local buy/sell orders.
- Filter by country, asset, amount, and payment method.
- Match with providers.
- Use escrow protection.
- Track order state.
- Open disputes when needed.
- Notify parties about important order events.

## 5. Escrow Protection

Escrow is used to reduce counterparty risk.

Capabilities:

- Lock funds during an order.
- Release funds when conditions are met.
- Hold funds while a dispute is reviewed.
- Support partial/milestone releases where enabled.
- Use Soroban escrow where configured and available.

## 6. Protected Service Payments

Paybrok can be used to pay for services by milestones.

Examples:

- Architecture plans.
- Design work.
- Repairs.
- Construction tasks.
- Consulting.
- Technology services.

Capabilities:

- Define service category.
- Define service title and details.
- Set total amount.
- Split the amount into milestones.
- Define delivery deadline and review period.
- Use automatic release rules when the client does not respond within the accepted window.
- Use agreed late delivery penalties where applicable.
- Use escrow to avoid paying everything upfront.
- Release funds as work is delivered.
- Open a dispute with evidence if something goes wrong.

## 7. Remittances

Paybrok supports remittance-style flows through approved local bridges.

Capabilities:

- Choose origin and destination route.
- Choose asset and amount.
- Select delivery method when available.
- Lock funds in escrow.
- Let a bridge/provider deliver locally.
- Release or dispute depending on delivery.

## 8. Providers and Merchants

Approved providers can support local liquidity and payment delivery.

Capabilities:

- Provider application/review flow.
- Provider profile and operational details.
- Local payment methods.
- Country and method-specific liquidity.
- Reputation and dispute history concepts.
- Provider panel and operational tools where enabled.

## 9. Notifications

Paybrok supports notifications for operational events.

Capabilities:

- Order updates.
- Dispute events.
- Provider/order status changes.
- Wallet-related notices where supported.
- Web local notification registration.
- Mobile push notification support where available.

## 10. Compliance and Safety

Paybrok includes public-facing and operational controls for responsible use.

Capabilities:

- Terms of Service.
- Privacy Policy.
- AML/CTF Policy.
- Arbitration notice.
- Sanctions and risk controls.
- Abuse monitoring.
- Dispute documentation.
- Provider review.
- Support/admin review workflows.

