# LaundryDesk business workflow

LaundryDesk is a one-computer offline counter application for laundry and dry-cleaning shops. Set up the shop and owner, then add customer contacts and garment/service prices.

## Modules

- **Customers:** contact/address records and notes.
- **Service catalog:** a named garment/treatment, such as Shirt / Wash & iron, with a unit price and care notes.
- **Laundry tickets:** bag/ticket label, customer, received/promised dates, garment/service quantities, conditions, special instructions, manual tag references, an optional condition photo and payment balance.
- **Supply stock:** manual quantities/units for detergent, bags or other consumables.
- **Expenses:** dated costs for supplies, utilities, wages and other operations.

## First working day

1. Add the service catalog with separate entries for different garments or treatments. For example, dry-cleaning a coat and ironing a shirt should have their own price entries.
2. Add a customer with a reachable contact number.
3. Create a Laundry ticket. Enter each garment/service and counted quantity, received date, promised collection date and the garments' initial condition. Record physical tag references and care instructions when needed.
4. Verify the calculated total, enter the actual advance and print the ticket. The ticket's reference/number and garment quantities provide the counter record.
5. Move through Received, Washing, Pressing and Ready. Later payments are entered through the payment action.
6. Before handover, check the ticket quantities and outstanding balance. Enter the collector/collection note, then mark Collected. Finalize notes before this terminal state.
7. Enter expenses and manual supply quantity adjustments; export a backup to another drive.

## Garment and payment handling

A line quantity means garments for that listed service; it does not assign unique digital identities or independent status to every garment. Individual tags are manually recorded text and must be matched against physical tags at the counter. Collected is a workflow status, not proof of full payment or a signature. Completed/collected tickets can still receive outstanding collections, but cannot otherwise be edited.

Catalog care notes are guidance; enter ticket-specific instructions/conditions directly on the ticket so its saved document has the relevant record. Supply stock is manually maintained and is not automatically consumed by wash loads. Record expenses once; do not double-count an expense by also treating a manual stock adjustment as a payment.

## Current limits

No barcode-scanner integration, garment-tag printing layout, per-garment workflow, automatic consumable recipes, SMS notification, pickup routes, loss/damage claims or refunds. One owner account and one computer. Physical garment counts and customer handover remain the operator's responsibility. Keep external backups.

This document describes the pilot configuration; it does not claim hardware or live-shop verification. Use repository verification notes for tests actually executed.
