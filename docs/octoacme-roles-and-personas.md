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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Expanded Personas

Add these persona cards to clarify responsibilities, ownership, and handoffs. Keep each card short (1–3 bullets), then provide a short interaction note describing who they work with and when.

- Technical Lead
  - Responsibilities: Drive technical design decisions, mentor developers, ensure architectural alignment, and own code-level quality.
  - Interactions: Works with PM/PdM to translate requirements into technical scope; pairs with Developers on implementation; flags architecture risks to the Engineering Manager and Product Lead.

- Engineering Manager
  - Responsibilities: Manage team capacity, hiring, performance coaching, and cross-team coordination.
  - Interactions: Partners with PM on resourcing and priorities; escalates people or capacity issues to the Product Lead; supports Developers and Technical Leads with staffing and performance matters.

- Release Manager
  - Responsibilities: Coordinate release windows, validate release readiness, maintain rollback/runbook, and communicate release status to stakeholders.
  - Interactions: Works with PM, SRE, QA, and Security to schedule deployments; ensures release checklists are complete; notifies Stakeholders and Customer Success of releases or impacts.

- SRE / On-call Engineer
  - Responsibilities: Operate and monitor production systems, define and maintain runbooks, respond to incidents, and drive production reliability improvements.
  - Interactions: Collaborates with Developers for fixes and instrumentation; partners with Release Manager for deployment impacts; coordinates incident communication with PM for stakeholder updates.

- UX Researcher / Designer
  - Responsibilities: Conduct user research, define UX acceptance criteria, produce UX artifacts, and validate usability of solutions.
  - Interactions: Works with the PdM to shape requirements and acceptance criteria; provides prototypes and research outputs to Developers and QA; participates in demos and usability validation.

- Data Analyst
  - Responsibilities: Define success metrics, design instrumentation, create dashboards, and analyze results to validate outcomes.
  - Interactions: Partners with PdM on success metrics and measurement plans; works with Developers to implement telemetry; supplies dashboards for weekly reporting.

- Security Engineer
  - Responsibilities: Review designs for security risks, define security acceptance criteria, perform threat modeling, and run security scans.
  - Interactions: Engages during planning and PR review; coordinates with SRE and Release Manager for compliance, remediation, and secure rollout.

- Customer Success Manager
  - Responsibilities: Represent customer-facing concerns, coordinate beta programs, capture customer feedback, and manage customer communications during releases or incidents.
  - Interactions: Works with PdM and PM on prioritization of customer requests; informs Release Manager of customer-impacting changes and helps communicate release notes to customers.

Suggested deliverables to include in the doc update:
- Persona cards: short descriptions (1–3 bullets) for each role, decisions owned, and primary handoffs.
- "Who to contact for" matrix: mapping common activities to primary and secondary contacts (e.g., deployments → Release Manager (primary) / SRE (secondary)).
- Handoff and escalation flows: short examples showing steps and responsible roles (e.g., incident → SRE -> PM -> Product Lead -> Sponsor).
