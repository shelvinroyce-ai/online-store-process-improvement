# Project 03 — IT BA Project — Software Feature Specification

**Feature:** Intelligent Order Modification & Cancellation System
**Company:** UrbanThread (Simulated)
**Project Type:** Business Analysis + IT Business Analysis

---

## Important Disclaimer

> This is a student portfolio project. All company details, metrics, stakeholder interviews, user data, and business context are simulated / fictional unless explicitly stated otherwise. No real client work or production data is represented.

---

## Project Overview

This project demonstrates a complete IT Business Analyst workflow for specifying a software
feature, from business problem identification through to UAT scenarios. The feature enables
customers to self-serve order modifications and cancellations within defined business rules,
with automated inventory release, payment adjustments, and notifications.

## Business Problem

UrbanThread's customer service team is overwhelmed by order modification and cancellation
requests that could be handled through self-service. The current process is manual,
error-prone, and inconsistent. It results in high operational cost, customer friction,
revenue leakage, inventory inefficiency, inconsistent outcomes, and limited scalability.

## Proposed Solution

A rules-based, self-service feature integrated into the customer portal and mobile app,
backed by:

- An **Eligibility Rules Engine** that evaluates order status, fulfillment stage, and business rules in real time.
- An **Order Orchestration Service** that coordinates updates across OMS, WMS, payment, and notifications.
- A **Payment Adjustment Service** for refunds and payment method updates.
- An **Inventory Release Service** for cancelled items.
- A **Notification Service** for email, SMS, and push.
- An **Audit Log Service** for compliance and dispute resolution.

## Key BA Artifacts

| Artifact | Count |
|----------|-------|
| Business Requirements | 12 |
| Functional Requirements | 18 |
| Non-Functional Requirements | 10 |
| User Stories | 24 |
| Acceptance Criteria | 35+ |
| Use Cases | 8 |
| UAT Scenarios | 30 |
| Risks | 10 |
| Assumptions | 10 |
| Dependencies | 10 |

## Project Scope

**In scope:** Order modification (address, shipping speed, payment method), full and
item-level cancellation, eligibility engine, inventory release, payment adjustment,
notifications, audit trail, customer portal UI, support agent view, reporting.

**Out of scope:** Returns and exchanges, post-delivery modifications, subscription orders,
B2B/wholesale orders, international orders, partial quantity modification, split shipment
modifications, real-time carrier interception.

## Tools / Techniques Demonstrated

- Business problem analysis; root cause analysis (5 Whys, Fishbone, Problem Tree)
- Stakeholder analysis and personas
- AS-IS / TO-BE process modeling (swimlane)
- Requirements elicitation and structured documentation (BR/FR/NFR with IDs)
- User story writing (role / capability / value)
- Acceptance criteria definition (Given / When / Then)
- Use case modeling (main, alternative, exception flows)
- MoSCoW prioritization
- Traceability matrix (BR → FR → US → AC → UAT)
- Edge case and error handling design
- API / integration considerations (conceptual, not production specs)
- UAT scenario design
- KPI framework and success metrics
- AI-assisted BA workflow with human validation

## Workbook Contents

`Requirements-Workbook.xlsx` contains 14 sheets:

1. Executive Dashboard
2. Stakeholder Matrix
3. Business Requirements
4. Functional Requirements
5. Non-Functional Requirements
6. User Stories
7. Acceptance Criteria
8. Use Cases
9. MoSCoW Prioritization
10. Traceability Matrix
11. UAT Scenarios
12. Risk Register
13. Assumptions & Dependencies
14. KPI Success Metrics

## Diagram Contents

`Diagrams/`:

- `01-AS-IS-Process-Flow.png` — Current manual process swimlane
- `02-TO-BE-Process-Flow.png` — Proposed self-service swimlane
- `03-System-Architecture.png` — Conceptual layered architecture
- `04-Feature-Sequence.png` — Sequence-style interaction flow
- `05-Implementation-Roadmap.png` — Phased delivery roadmap

## How to Navigate the Project

1. Start with `Case-Study.pdf` for the full narrative.
2. Open `Requirements-Workbook.xlsx` and begin on the **Executive Dashboard** sheet.
3. Use the **Traceability Matrix** sheet to follow the BR → FR → US → AC → UAT chain.
4. Review the **Diagrams/** folder for visual context.
5. Use the **Risk Register** and **KPI Success Metrics** sheets for governance context.

## Limitations

- Simulated company, data, and business context — no real-world validation.
- No actual stakeholder interviews; requirements based on hypothetical needs.
- No production system access; technical feasibility not fully validated.
- No real user testing; UX assumptions not validated.
- No actual metrics; KPIs are proposed, not measured.
- API specifications are conceptual, not production-ready.
- No legal review; compliance requirements are assumed.
- Single BA perspective; no team collaboration represented.

## Portfolio Use

This is a **portfolio simulation**. It must not be represented as production work,
client work, or real-world experience. Metrics, stakeholders, and outcomes are
fictional and clearly labelled as simulated or proposed.

---

*End of README*
