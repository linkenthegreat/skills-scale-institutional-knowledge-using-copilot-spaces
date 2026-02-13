# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

---

## UX Designer

### Role Summary
UX Designers craft the user experience and interaction models that guide product decisions. They own design solutions, usability validation, and ensure accessibility and consistency across features.

### Key Responsibilities
- Translate product requirements into user flows, wireframes, and high-fidelity designs.
- Collaborate with Product Managers to define acceptance criteria related to UX.
- Validate designs through user research, usability testing, or lightweight prototypes.
- Produce and maintain a design rationale and design artifacts in the project repo.
- Ensure accessibility and consistency with design system guidelines.

### Interactions with existing roles
- Product Manager: Aligns on user needs, success metrics, and prioritization of UX work.
- Developers: Handoff designs, clarify interaction details, and participate in design reviews.
- QA/Testing: Define testable UX acceptance criteria and support visual/regression checks.
- Project Manager: Communicate timelines for design deliverables that impact the delivery schedule.

### Typical Communication
- Design walkthroughs during planning and sprint reviews.
- Design artifacts and annotations on PRs or design doc links.

### Example success criteria
- Completed usability test with defined improvements and acceptance of results.
- Design deliverables attached to backlog items with clear acceptance steps.

---

## QA Automation Engineer

### Role Summary
QA Automation Engineers design, implement, and maintain automated test suites that verify product behavior and guard against regressions.

### Key Responsibilities
- Develop and maintain end-to-end, integration, and CI-level automated tests.
- Collaborate with Developers and QA analysts to define test coverage goals.
- Own flaky-test triage and stability improvements for CI pipelines.
- Track automated test coverage and key quality metrics (pass rate, flakiness, time to detect regressions).

### Interactions with existing roles
- Developers: Pair on testability, mock strategies, and test data needs.
- QA/Testing: Coordinate which tests are manual vs automated; hand off automation tasks.
- Project Manager: Communicate test coverage and release readiness metrics.

### Typical Communication
- Test coverage dashboards, PR comments with test links, CI status and alerts.

### Example success criteria
- Automated test coverage maintained above target threshold for all new features.
- Flaky test rate reduced to less than 2% of total test suite.
- Critical regressions detected within one CI cycle of introduction.

---

## Release Manager

### Role Summary
Release Managers coordinate release planning and execution to ensure smooth deployments and clear rollback/mitigation steps.

### Key Responsibilities
- Maintain release calendar and coordinate cross-team release windows.
- Validate pre-release checklist and Go/No-Go criteria (QA signoff, security, rollback plan).
- Coordinate communications to stakeholders and support teams for releases.
- Facilitate post-release verification and capture release notes.

### Interactions with existing roles
- Project Manager / Product Manager: Agree on release scope and timing.
- Developers / QA: Verify that release criteria and smoke tests are green.
- Support/Operations: Ensure runbooks and on-call coverage are prepared.

### Typical Communication
- Release planning meetings, pre-launch checks, release announcement templates.

### Example success criteria
- All releases completed within scheduled maintenance windows.
- Zero unplanned rollbacks in the last quarter.
- Release checklist and Go/No-Go criteria documented and approved before each deployment.

---

## Business Analyst

### Role Summary
Business Analysts (BAs) translate stakeholder needs into clear, testable requirements and help refine scope to reduce rework.

### Key Responsibilities
- Elicit and document detailed requirements, acceptance criteria, and business rules.
- Run stakeholder interviews, clarify edge cases, and produce data or process diagrams as needed.
- Assist Product Managers in backlog refinement and grooming sessions.

### Interactions with existing roles
- Product Manager: Align on objectives, trade-offs, and scope details.
- Developers: Clarify requirements, provide example data, and answer questions during implementation.
- QA: Provide acceptance criteria and domain scenarios for test cases.

### Typical Communication
- Requirements docs, backlog item descriptions, and decision logs.

### Example success criteria
- Requirements approved by stakeholders before development starts.
- Less than 10% of stories require requirements clarification during implementation.
- All acceptance criteria testable and documented in backlog items.

---

## Stakeholder Representative

### Role Summary
A Stakeholder Representative is a named person who represents a stakeholder group (e.g., Sales, Support, Legal) and provides ongoing input, approvals, and domain context.

### Key Responsibilities
- Provide timely feedback and business context for decisions that affect their area.
- Review deliverables that impact their domain and sign off on readiness criteria where required.
- Escalate domain-specific risks and ensure mitigation plans are considered.

### Interactions with existing roles
- Product Manager: Validate alignment to business outcomes and acceptance of trade-offs.
- Project Manager: Receive schedule and status updates, participate in key decisions.
- Support/Operations: Coordinate operational readiness and post-launch support.

### Typical Communication
- Periodic review sessions, approval comments on deliverables, and signoff checklists.

### Example success criteria
- Feedback and approvals provided within agreed-upon SLA timeframes.
- All domain-specific approvals completed before release.
- Escalated risks addressed and mitigation plans documented.

---

## How these personas are used

These persona definitions provide a reference for assigning roles, defining responsibilities, and clarifying interactions across project teams. Use them to:

- **Assignment guidance**: Identify who should own each role for a given project and document it in the project charter.
- **Artifact references**: Link to relevant persona descriptions when defining RACI matrices, onboarding new team members, or clarifying responsibilities in project documentation.
- **Role-specific context**: Leverage these definitions as prompts for Copilot Spaces to shape role-specific guidance and suggestions during development.

When defining new roles or updating existing ones, use the [role definition template](templates/role-definition-template.md) to maintain consistency across your project documentation.

