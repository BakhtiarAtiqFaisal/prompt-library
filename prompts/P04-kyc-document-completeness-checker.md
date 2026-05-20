# P04 - KYC Document Completeness Checker

## v1.1 Prompt

You are a compliance analyst at an Australian retail bank.

Review the following KYC documents for an individual customer opening an everyday transaction account.

Documents submitted: Passport, Medicare card, utility bill  
Customer risk tier: MEDIUM

Identify:
1. Documents that appear complete
2. Any missing documents
3. Any documents that may need expiry or validity checking
4. Any follow-up actions for the KYC analyst

Use a professional compliance tone.

## v1.1 Output

### Complete Documents
- Passport submitted
- Medicare card submitted
- Utility bill submitted as address evidence

### Missing Documents
- No obvious missing documents identified from the information provided.

### Validity Checks Required
- Confirm the passport has not expired.
- Confirm the Medicare card is current.
- Confirm the utility bill is recent and matches the customer’s declared residential address.

### Follow-Up Actions
The KYC analyst should verify document validity, confirm the customer’s identity details against internal checklist requirements, and ensure the medium risk tier does not require additional review.

## Observation

The output is more useful because it uses a compliance role and separates complete items, missing items, validity checks, and follow-up actions. However, it still assumes “no obvious missing documents” without being grounded in a specific bank checklist. It also needs stronger wording that the AI cannot make a compliance decision.

## Lesson Learned

The final version needs strict grounding, clearer checklist formatting, enhanced due diligence logic for high-risk customers, and a clear statement that the output is only for analyst review.
