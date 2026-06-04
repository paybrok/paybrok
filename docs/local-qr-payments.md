# Local QR Payments

Paybrok supports local QR payment workflows where a user wants to pay a merchant or person using a country-specific payment method.

## Purpose

Many countries have local QR systems or payment links that do not expose full bank details. Paybrok tries to detect the country, method, amount, merchant reference, or provider link when possible.

## Supported Concepts

Paybrok can work with QR data such as:

- Payment links.
- Merchant references.
- Amounts.
- Country codes.
- Payment method names.
- Raw QR contents.

## Examples of Local Methods

Availability depends on configuration and provider support. Paybrok may support flows related to:

- DeUna.
- Nequi.
- Bancolombia.
- Daviplata.
- Wompi.
- Mercado Pago.
- Transfiya.
- Pago Movil.
- CoDi/SPEI.
- QR Simple.

## Important Limitation

Some QR systems only include a proprietary link. If the link does not expose bank account data, Paybrok cannot invent that data. In that case, Paybrok preserves the QR link/reference and shares it with compatible providers so they can complete the local payment through the appropriate app.

