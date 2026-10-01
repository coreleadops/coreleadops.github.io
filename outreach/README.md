# Denver STR license help: launch pack

Status: DRAFT. Nothing in this folder has been sent.

## Before anything is sent (blockers)
1. **Lead endpoint.** Set `LEAD_ENDPOINT` in `denver-str-license.html` (e.g. a Make webhook that writes to a sheet and notifies you). Until set, the form says requests are not enabled.
2. **Payments.** Create Stripe payment links for the three packages ($349 / $149 / $79) and add them to the page. Not created; requires your Stripe account.
3. **Business details.** Confirm the legal entity name, a physical mailing address (CAN-SPAM requires one in commercial email), and a reply-to address.
4. **Prospect list.** Build from public sources only (see below).
5. **Prices are proposed**, not market-tested. Adjust freely.

## Compliance rules for outreach
- **Email only, no cold SMS.** Cold texting strangers triggers TCPA liability. Do not use the existing SMS scenario for this offer.
- Every email: truthful sender and subject, physical address, working unsubscribe, honor opt-outs within 10 business days (CAN-SPAM).
- Do not claim affiliation with the City of Denver, and do not guarantee approval.
- Verify every rule claim against denvergov.org before sending.

## Who to contact
- Hosts with public Denver STR listings who display a license number: renewal and compliance offer.
- Hosts whose listings show **no** license number: they may be out of compliance. Keep the tone helpful, not accusatory, and never threaten to report them.
- Local property managers and co-hosts: partnership offer (referral fee).

## Files
- `email-templates.md`: three first-touch emails and one follow-up.
