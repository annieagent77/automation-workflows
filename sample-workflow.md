# Free sample: New inquiry → lead record and acknowledgement

This excerpt is a platform-neutral specification, not an import-ready Zapier, Make, or n8n workflow. Connector availability and account-plan limits vary. Test with dummy data first; keep customer-facing email disabled until the account owner approves the copy and test.

## Purpose

Capture new website inquiries in one place and make the assigned owner aware of them.

## Trigger and actions

- **Trigger:** A new website form submission.
- **Action 1:** Create a lead record with name, email, source, received time, and status.
- **Action 2:** Notify the assigned owner.
- **Optional action 3:** Send a business-approved receipt acknowledgement, only after testing sender and recipient mapping.

## Setup checklist

- Map only the fields needed; avoid unnecessary sensitive data.
- Define the record owner and how duplicate submissions are handled.
- Have the business approve any acknowledgement wording and response-time promise.
- Confirm the selected form, CRM/spreadsheet, and email connectors are available in accounts the business controls.

## Acceptance test

Submit a dummy inquiry. Confirm that exactly one correctly mapped record is created and the owner receives the intended internal alert. Check duplicate handling. If customer email is enabled, first verify it using an address controlled by the account owner; confirm no message can reach an unintended recipient.

## Safety and limits

Do not enable live customer-facing actions until the account owner approves them. This sample does not include software, an installed integration, or a promise of revenue, time savings, compliance, or universal compatibility.

The full five-recipe pack contains four additional onboarding specifications. [View the offers and checkout details](index.html).
