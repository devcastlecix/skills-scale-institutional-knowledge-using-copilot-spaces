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

## Delivery/Engineering Managers

### Role Summary
Delivery/Engineering Managers coordinate engineering execution, team capacity, and technical delivery risks so planned scope can be shipped predictably.

### Responsibilities
- Plan engineering capacity against roadmap and milestone commitments
- Coordinate technical dependencies across teams and systems
- Surface delivery risks early and drive mitigation planning with PM and Product
- Support developers with implementation sequencing, review readiness, and unblock plans

### Goals and Decision Rights
- Keep engineering work on-track with agreed iteration and release goals
- Decide engineering staffing, sequencing, and execution trade-offs within approved scope
- Escalate delivery risk when timeline, quality, or dependency thresholds are at risk

### Lifecycle Touchpoints and Communication
- Initiation: validate feasibility and rough delivery shape for go/no-go inputs
- Planning: align estimates, sequencing, and dependency maps with PM and Product
- Execution: monitor throughput and blockers in standups, boards, and weekly syncs
- Release/Retrospective: confirm engineering readiness and lead follow-up improvements

### Interaction with Developers, Product Managers, and Project Managers
- Developers: partner on technical breakdown, estimates, risk identification, and reviews
- Product Managers: align scope decisions with capacity and expected customer outcomes
- Project Managers: co-own timeline confidence, dependency tracking, and escalation paths

---

## UX/Product Designers

### Role Summary
UX/Product Designers define user flows and interaction patterns so the team delivers usable, accessible solutions that meet customer goals.

### Responsibilities
- Translate product requirements into user flows, wireframes, and interaction guidance
- Validate usability assumptions through lightweight research or feedback loops
- Ensure accessibility and consistency across user-facing experiences
- Collaborate on acceptance scenarios that capture user behavior and edge cases

### Goals and Decision Rights
- Improve task success, clarity, and usability for target users
- Decide interaction and content patterns within product goals and technical constraints
- Recommend trade-offs when usability, scope, and timeline priorities conflict

### Lifecycle Touchpoints and Communication
- Initiation: shape problem framing with user needs and journey context
- Planning: provide design artifacts and acceptance scenarios for backlog refinement
- Execution: clarify interactions during implementation and QA validation
- Release/Retrospective: review user feedback signals and recommend improvements

### Interaction with Developers, Product Managers, and Project Managers
- Developers: refine feasible implementation details and behavior states
- Product Managers: align user outcomes, requirements, and prioritization decisions
- Project Managers: synchronize design handoffs, review timing, and dependency risks

---

## QA/Test Leads

### Role Summary
QA/Test Leads own quality strategy and acceptance evidence, ensuring planned increments satisfy definition-of-done and release expectations.

### Responsibilities
- Define test strategy across functional, integration, and regression coverage
- Maintain quality risk visibility and defect triage priorities
- Align acceptance criteria with Product and validation plans with engineering
- Provide release sign-off recommendations backed by test evidence

### Goals and Decision Rights
- Prevent escaped defects that materially impact customer outcomes
- Decide test depth and quality gates required for release confidence
- Escalate unresolved quality risks that should block release readiness

### Lifecycle Touchpoints and Communication
- Initiation: identify initial quality risks and validation needs
- Planning: shape test plans, acceptance checks, and exit criteria
- Execution: track defects, test status, and risk trends in team cadences
- Release/Retrospective: confirm quality evidence and lead defect trend reviews

### Interaction with Developers, Product Managers, and Project Managers
- Developers: collaborate on testability, automation scope, and defect resolution
- Product Managers: confirm acceptance criteria intent and user-impact severity
- Project Managers: align quality status with release gates, risks, and communications

---

## Security/Privacy Partners

### Role Summary
Security/Privacy Partners guide threat, data protection, and compliance considerations so delivery decisions balance speed with security and privacy obligations.

### Responsibilities
- Review architecture and change proposals for security and privacy risks
- Advise on threat modeling, controls, and secure implementation practices
- Flag compliance implications and required approvals for sensitive data flows
- Support incident and vulnerability escalation paths

### Goals and Decision Rights
- Reduce security/privacy exposure in delivered features and operations
- Decide required control checks for high-risk changes before release
- Escalate risks that exceed policy, legal, or acceptable tolerance boundaries

### Lifecycle Touchpoints and Communication
- Initiation: identify sensitive data, trust boundaries, and control requirements
- Planning: review design and backlog items for security/privacy acceptance needs
- Execution: provide advisory reviews on implementation and test evidence
- Release/Retrospective: confirm control readiness and feed lessons into risk updates

### Interaction with Developers, Product Managers, and Project Managers
- Developers: advise on secure patterns, controls, and remediation priorities
- Product Managers: align customer value decisions with policy/compliance constraints
- Project Managers: coordinate risk visibility, approvals, and escalation communication

---

## Site Reliability/Operations Engineers

### Role Summary
Site Reliability/Operations Engineers ensure services are operable, observable, and recoverable in production throughout release and incident lifecycles.

### Responsibilities
- Define operational readiness checks (monitoring, alerting, runbooks, rollback)
- Validate deployment safety, reliability, and post-release verification approach
- Support incident response communication and service restoration workflows
- Track recurring operational risks and reliability improvements

### Goals and Decision Rights
- Maintain service reliability and reduce incident impact/duration
- Decide operational readiness requirements and go/no-go recommendations for release
- Escalate release or production concerns when resilience criteria are unmet

### Lifecycle Touchpoints and Communication
- Initiation: identify operability implications and infrastructure dependencies
- Planning: align release and support needs with delivery timelines
- Execution: review observability and runbook updates alongside feature progress
- Release/Retrospective: lead readiness confirmation and post-incident follow-through

### Interaction with Developers, Product Managers, and Project Managers
- Developers: validate telemetry, deployment controls, and rollback mechanisms
- Product Managers: communicate reliability trade-offs and customer impact risks
- Project Managers: coordinate release gates, incident comms plans, and risk tracking

---

## Technical Writers/Documentation Owners

### Role Summary
Technical Writers/Documentation Owners keep product, operational, and process documentation accurate so teams and users can adopt changes reliably.

### Responsibilities
- Maintain user-facing and internal documentation aligned to shipped behavior
- Define documentation acceptance checks as part of definition-of-done
- Coordinate doc updates across feature, release, and support workflows
- Validate clarity and completeness with PM, Product, QA, and engineering inputs

### Goals and Decision Rights
- Reduce ambiguity in usage, operations, and support guidance
- Decide documentation structure and publishing readiness for release artifacts
- Escalate release risk when required documentation is incomplete or inaccurate

### Lifecycle Touchpoints and Communication
- Initiation: identify documentation scope and audiences
- Planning: add documentation tasks and review checkpoints to backlog/release plans
- Execution: iterate docs alongside implementation and QA validation
- Release/Retrospective: publish final updates and capture documentation debt actions

### Interaction with Developers, Product Managers, and Project Managers
- Developers: capture technical behavior, configuration, and operational notes
- Product Managers: align messaging, user guidance, and expected outcomes
- Project Managers: include documentation milestones in status, risks, and sign-off

---

## Executive Sponsors/Business Owners

### Role Summary
Executive Sponsors/Business Owners provide strategic direction, funding and priority decisions, and escalation support for high-impact delivery outcomes.

### Responsibilities
- Approve strategic intent, investment boundaries, and success criteria
- Resolve priority conflicts and major cross-functional escalations
- Review progress, risk posture, and value realization at key decision gates
- Champion stakeholder alignment and organizational support

### Goals and Decision Rights
- Ensure delivery outcomes align with business priorities and constraints
- Decide go/no-go at major initiation, release, and escalation gates
- Approve significant scope, funding, or timeline changes

### Lifecycle Touchpoints and Communication
- Initiation: approve charter-level direction and planning authorization
- Planning: confirm priority and resourcing alignment
- Execution: review milestone status and high-severity risks
- Release/Retrospective: confirm outcome acceptance and sponsor follow-up actions

### Interaction with Developers, Product Managers, and Project Managers
- Developers: receive escalations when constraints threaten strategic outcomes
- Product Managers: align target outcomes, trade-offs, and success measures
- Project Managers: review status, major risks, and decision requests at governance points

---

## Responsibility and Collaboration Matrix

| Activity | Primary Owner | Key Collaborators |
| --- | --- | --- |
| Initiation approval (go/no-go) | Executive Sponsor/Business Owner | Product Manager, Project Manager, Delivery/Engineering Manager, Security/Privacy Partner |
| Backlog prioritization | Product Manager | Delivery/Engineering Manager, UX/Product Designer, Project Manager, Developers |
| Risk ownership and escalation | Project Manager | Delivery/Engineering Manager, Security/Privacy Partner, Site Reliability/Operations Engineer, Product Manager |
| Quality sign-off recommendation | QA/Test Lead | Developers, Product Manager, Project Manager, Delivery/Engineering Manager |
| Release readiness decision | Project Manager + Site Reliability/Operations Engineer | QA/Test Lead, Delivery/Engineering Manager, Product Manager, Security/Privacy Partner |
| Incident communication | Site Reliability/Operations Engineer + Project Manager | Delivery/Engineering Manager, Product Manager, Executive Sponsor/Business Owner |
| Retrospective follow-up tracking | Project Manager | Delivery/Engineering Manager, Product Manager, QA/Test Lead, Technical Writer/Documentation Owner |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
