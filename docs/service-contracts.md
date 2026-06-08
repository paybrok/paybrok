# Protected Service Payments

Paybrok can be used to pay for services with escrow protection and milestone-based releases.

## Example: Architecture Service for 100 USDC

A client wants to hire an architect for a 100 USDC project. Instead of sending the full amount upfront, the client creates a protected service payment.

Example milestones:

- 30 USDC for initial concept or sketch.
- 40 USDC for reviewed draft.
- 30 USDC for final delivery.

## Roles

- Client: the person paying for the service.
- Service provider: the professional delivering the work, such as an architect, designer, contractor, consultant, or technician.
- Paybrok: the platform that structures the order and escrow workflow.

## Flow

1. The client enters "Pay for a service".
2. The client chooses a category such as Architecture.
3. The client defines amount, asset, title, details, milestones, and agreement rules.
4. A provider accepts or is matched according to availability.
5. Funds are locked in escrow.
6. The provider delivers each milestone and marks the service as ready.
7. The client reviews the delivery and releases the corresponding payment when satisfied.
8. If the work is not delivered, the client may open a dispute with evidence.

## Agreement Rules

Service agreements can include predefined rules that are visible before acceptance:

- Delivery deadline.
- Review or inspection period.
- Automatic release if the client does not respond within the agreed review window.
- Late delivery penalty options.
- Milestone amounts or percentages.

Penalties are agreed before acceptance and should not exceed the value of the milestone where they apply. This keeps the agreement clear and prevents an unfair penalty from being larger than the payment being reviewed.

## Milestones

Milestones let the client release money by stage instead of paying everything at once. A 900 USDC project over 90 days, for example, can be split into three 300 USDC milestones. Paybrok keeps the full structure visible so both sides can track what is locked, what is released, and what remains pending.

## What Makes a Good Service Agreement

A service order should clearly define:

- What must be delivered.
- Format of delivery.
- Timeline.
- Review period.
- Late delivery rule, if used.
- Number of revisions.
- Payment milestones.
- What counts as a valid delivery.
- How communication and evidence will be documented.

## What Paybrok Does Not Do

Paybrok does not replace a formal legal contract for complex projects. For high-value work, users should also have a written agreement outside the app.

