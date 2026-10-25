---
name: invoice-chaser
description: Write payment reminders for overdue invoices that get paid without burning the relationship - a 4-step sequence from a friendly nudge to a firm final notice, in email and WhatsApp versions. Use when the user says "chase this invoice", "client hasn't paid", "payment reminder", "overdue invoice" or pastes unpaid invoice details.
---

# Invoice chaser

Write the right reminder for how late the payment is. Polite, specific, easy to act on.

## 1. Get the facts (ask only for what is missing)
- Client name and contact person
- Invoice number, amount and currency, due date
- What was delivered (one line)
- How to pay (bank / UPI / payment link)
- Days overdue, and any earlier reminders already sent
- Relationship: new client, regular client, or one who often pays late

Never invent an amount, date, invoice number or payment detail. If one is missing, leave a clear `[placeholder]` and say so.

## 2. Pick the stage
| Days overdue | Stage | Tone |
|---|---|---|
| 0-3 (or due tomorrow) | 1. Friendly nudge | Assume they forgot. Warm, short. |
| 4-14 | 2. Clear reminder | Restate amount, due date, how to pay. Ask for a payment date. |
| 15-30 | 3. Firm follow-up | Mention earlier reminders by date. Ask them to confirm today. Offer a call if something is wrong. |
| 30+ | 4. Final notice | Calm and factual. State the next step the user chose (pause work, late fee per the contract, formal recovery). Only mention late fees or legal steps the user confirms are in their terms. |

## 3. Write it
For each reminder give:
- **Email:** subject line (include invoice number and amount) + body of 60-120 words.
- **WhatsApp version:** 2-4 short lines, no formatting.

Every message contains: invoice number, amount, original due date, what it was for, exactly how to pay, and one clear ask ("Could you confirm the payment date?"). One ask only.

## 4. Rules
- No guilt-tripping, sarcasm or threats the user didn't approve.
- Never claim a late fee, interest or legal action unless the user says it is in their contract.
- Keep the door open: offer to resend the invoice or split the payment if the user allows it.
- Write in the user's language and match how they address the client (first name vs. formal).

## 5. Output
The chosen stage, the email (subject + body), the WhatsApp version, and one line suggesting when to send the next stage if this one gets no reply.
