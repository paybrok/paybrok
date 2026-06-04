# P2P and Escrow

Paybrok Local is the P2P layer that connects users with approved providers for local payment needs.

## Why Escrow Matters

Without escrow, a user may have to trust an unknown counterparty. Escrow reduces that risk by locking funds until the expected action is completed.

## Basic Flow

1. A user creates or selects a P2P order.
2. The order defines amount, asset, country, method, and terms.
3. Funds are locked in escrow.
4. The counterparty completes the agreed local action.
5. Funds are released when the order is completed.
6. If something goes wrong, a dispute can be opened.

## Disputes

A dispute should include evidence such as:

- Screenshots.
- Payment references.
- Chat history.
- Bank/payment confirmations.
- Delivery proof.
- Transaction hashes.

Paybrok support may review evidence and decide whether to release, refund, or keep the dispute open for more information.

## Soroban Escrow

Where enabled, Paybrok can use Soroban escrow for more transparent on-chain escrow workflows. Availability depends on asset, configuration, and operational readiness.

## Important Limitations

- Paybrok does not guarantee that every order will find a provider.
- Provider availability depends on country, method, limits, liquidity, compliance review, and risk.
- Escrow reduces risk but does not eliminate all operational, fraud, or legal risk.

