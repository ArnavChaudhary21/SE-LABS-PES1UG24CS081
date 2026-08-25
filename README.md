# Lab 1 – Requirements Engineering & UML Use-Case Modelling

**Problem Statement #19 — Healthcare & Telemedicine**
**Personalized Meal & Diet Subscription Manager**

A clinical dietary subscription service that generates weekly menus based on patient
metabolic constraints (allergies, diabetic limits, calorie goals) and tracks daily
delivery fulfillment.

**Actors:** Subscriber, Dietitian *(Payment Gateway as an external system actor)*

## Deliverables

| # | File | Description |
|---|------|-------------|
| 1 | [`deliverables/Requirements_Table.docx`](Requirements_Table.pdf) | 5 Functional Requirements (FR-001–FR-005) + 2 Non-Functional Requirements (NFR-001, NFR-002), each with ID, Type, Description, Priority, Acceptance Criteria, and Rationale. |
| 2 | [`deliverables/usecase_diagram.pdf`](usecase_diagram.pdf) | UML Use-Case Diagram with all actors, primary use cases, one `<<include>>` relationship (UC-02 → UC-07) and one `<<extend>>` relationship (UC-08 → UC-06). |
| 3 | [`deliverables/UseCase_Flow_UC02.docx`](UseCase_Flow_UC02.pdf) | One-page Use-Case Flow Specification for UC-02 "Generate Weekly Meal Plan": Preconditions, Postconditions, Main Success Scenario, and one Alternate Flow. |

## Use Cases Modelled

- UC-01 Manage Dietary Profile
- UC-02 Generate Weekly Meal Plan *(includes UC-07)*
- UC-03 Review & Approve Meal Plan
- UC-04 Modify Subscription Schedule
- UC-05 Track Delivery Fulfillment
- UC-06 Make Payment *(extended by UC-08)*
- UC-07 Validate Allergen & Macro Constraints
- UC-08 Apply Discount Code

## Author

<Arnav chaudhary> — PES University, Dept. of CSE
