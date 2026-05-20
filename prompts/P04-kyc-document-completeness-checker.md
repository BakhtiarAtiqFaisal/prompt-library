# P04 - KYC Document Completeness Checker

## v1.0 Prompt

Check whether these KYC documents are complete.

Account type: Everyday transaction account  
Entity type: Individual  
Documents submitted: Passport, Medicare card, utility bill  
Customer risk tier: MEDIUM

## v1.0 Output

The KYC documents appear mostly complete because the customer has submitted a passport, Medicare card, and a utility bill. These documents should generally be enough to confirm identity and address for an individual customer. The application can likely proceed, although the compliance team may still need to check whether the documents are valid and current.

## Observation

The output is too vague for a compliance workflow. It says the documents are “mostly complete” without clearly listing which items are complete, missing, expired, or requiring follow-up. It also sounds like the application can proceed, which is risky because a human analyst must make the final compliance judgement.

## Lesson Learned

The next version needs a clear compliance role, document-check categories, and risk-tier context so the output becomes useful for a KYC analyst rather than a general summary.
