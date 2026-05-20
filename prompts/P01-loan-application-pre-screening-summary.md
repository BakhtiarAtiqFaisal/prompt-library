# P01 - Loan Application Pre-Screening

## v1.1 Prompt

You are a credit assessment officer at an Australian retail bank.

Review the following loan application data and produce a structured pre-screening summary.

Application details:
Applicant name: Mia Nguyen
Loan type: Personal loan
Loan amount: $18,000
Annual income: $74,000
Employment status: Full-time
Credit score: 724
Existing debts: $9,500 credit card debt

Output the following sections:
1. Eligibility indicator: PROCEED / REFER / DECLINE with one-line rationale
2. Key risk factors, maximum 3 bullet points
3. Missing information required before final assessment
4. Recommended next step

Use a professional banking tone.

## v1.1 Output

### 1. Eligibility Indicator: PROCEED

Mia Nguyen may proceed to the next stage of assessment because she has full-time employment, a good credit score of 724, and an annual income of $74,000.

### 2. Key Risk Factors

- Existing credit card debt of $9,500 may affect repayment capacity.
- No living expense information has been provided.
- No repayment history or credit conduct details are included.

### 3. Missing Information Required

- Monthly living expenses
- Existing repayment obligations
- Employment verification
- Credit history details
- Purpose of the personal loan

### 4. Recommended Next Step

Proceed to full credit assessment and verify income, expenses, debt obligations, and credit history before making a final lending decision.

## v1.1 Change Made

Added a banking role, business context, and a structured output format.

## v1.1 Observation

The output is much better because it has a banking role and structured sections. However, it still needs stronger risk controls. It should clearly say not to infer missing data and not to provide a final approval or decline decision.

## v1.1 Lesson Learned

For banking workflows, the prompt must include compliance-style safeguards such as “use only the information provided,” “do not infer,” and “human assessor must make the final decision.”
