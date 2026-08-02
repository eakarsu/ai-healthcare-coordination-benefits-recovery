# Healthcare Coordination of Benefits Recovery

Identify claims where another payer was primary and execute compliant recovery or rebilling workflows.

**Primary buyer:** Health plans and third-party administrators. **Evidence:** member coverage, questionnaires, Medicare data, employer plans, accident details, claims, EOBs, payer order rules, recoveries, and correspondence.

Full local application built with React, Vite, Express, PostgreSQL, and OpenRouter. Includes 15 domain-specific capabilities, 105 custom AI workbench fields, three scenario-fill controls per feature, operational registers, workflow transitions, analytics, professional AI decision briefs, audit history, and at least 15 PostgreSQL records per capability.

## Domain capabilities

- Member coverage registry
- COB questionnaire workflow
- Medicare eligibility matching
- Employer plan matching
- Dependent birthday rule
- Working-aged rules
- Disability ESRD rules
- Accident liability detection
- Claim payer-order calculation
- Overpayment identification
- Provider recovery notice
- Primary payer rebilling
- Member appeal evidence
- Recovery cash ledger
- COB root-cause analytics

Run `./start.sh`, then open <http://127.0.0.1:4648>. API: `5648`.

Administrator: `runtime-admin@example.com` / `LocalDemo!2026`. Operator and reviewer credential buttons are available on the login page.
