# P02 - Customer Complaint Triage and Routing

## v1.1 Prompt

You are a complaints management specialist at an Australian retail bank.

Review the following customer complaint and classify it for internal routing.

Complaint text:
I was charged a fee I was told would be waived. I contacted the bank twice and nobody has fixed it.

Output the following sections:
1. Complaint category
2. Urgency level: High / Medium / Low
3. Recommended team
4. One-line complaint summary
5. Suggested next action

Use a professional and neutral banking tone.

## v1.1 Output

1. Complaint category: Fees

2. Urgency level: Medium

3. Recommended team: Customer service or fees specialist team

4. One-line complaint summary: The customer disputes a fee they were told would be waived and is dissatisfied because previous contacts did not resolve the issue.

5. Suggested next action: Review the customer’s account fee history, check any previous waiver agreement, and contact the customer with an update.

## Observation

The output is clearer and more useful than v1.0 because it has a banking role and structured sections. However, it is still not ideal for automation because the category and team names are not fixed, and the output is not in JSON format for CRM routing. It also does not identify possible regulatory escalation.

## Lesson Learned

For complaint triage automation, the prompt needs fixed categories, JSON-only output, urgency criteria, and a regulatory flag so the result can be used reliably by a CRM workflow.
