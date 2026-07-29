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

## Additional Personas

To reduce handoff ambiguity and ensure cross-cutting responsibilities are explicitly owned, add the following personas. Each entry includes responsibilities and how they interact with existing roles.

- Engineering Manager (EM)
  - Responsibilities: Owns team staffing, performance, capacity planning, and career growth. Manages long-term technical investment decisions at the team level and supports resource requests.
  - Interactions: Works with the Project Manager to confirm team capacity during planning; partners with Tech Lead on trade-offs and with Product Manager on prioritization and roadmap commitments.

- Technical Lead (Tech Lead)
  - Responsibilities: Provides technical direction and architecture guidance, performs design reviews, mentors developers, and enforces technical quality and standards.
  - Interactions: Advises Product Manager on feasibility and effort estimates; collaborates with Engineering Manager on staffing/resourcing; works with QA to define test strategy and SRE to meet operational requirements.

- Release Manager
  - Responsibilities: Coordinates release schedules, runbooks, rollback plans, release communications, and confirms completion of release checklists and stakeholder notifications.
  - Interactions: Collaborates with Project Manager and Product Manager to schedule releases; coordinates with QA and SRE/Platform for staging verification and production rollouts; notifies stakeholders and support teams.

- SRE / Platform Engineer
  - Responsibilities: Ensures production reliability, observability, deployment pipelines, and operational runbooks. Advocates for operability and supports incident response.
  - Interactions: Works with Developers and Tech Lead to define monitoring and alerting needs; supports Release Manager during rollouts; participates in incident triage with PM/Project Manager.

- UX Researcher / Designer
  - Responsibilities: Owns user research, usability validation, accessibility checks, and the delivery of design artifacts. Validates user flows before release.
  - Interactions: Partners with Product Manager to define user needs and acceptance criteria; coordinates with Developers and QA to confirm implementation fidelity.

- QA Lead / Test Engineer
  - Responsibilities: Defines test strategy and quality gates, organizes test plans and automation efforts, coordinates manual QA, and signs off on release quality.
  - Interactions: Works with Developers and Tech Lead to identify required test coverage; provides test outcomes to Project Manager and Release Manager.

- Data / Analytics Engineer
  - Responsibilities: Implements and validates metrics, telemetry, and analytics pipelines. Ensures success metrics are instrumented and dashboards are available.
  - Interactions: Works with Product Manager to define success metrics; partners with Developers and SRE to implement and validate telemetry; supports post-release analysis.

How these additions improve outcomes:
- Clear ownership reduces handoff ambiguity and accelerates decisions.
- More accurate planning when EMs and Tech Leads participate in capacity and dependency conversations.
- Smoother releases and incident response with explicit Release Manager and SRE roles.
- Higher product quality and validated user value through dedicated QA and UX roles.

Suggested placement and format:
- Add this "Additional Personas" section beneath the existing persona definitions.
- Keep entries short and actionable: Role name, 1–3 responsibility bullets, 1–2 interactions bullets.
- Link to role-handoff-checklist.md for operational steps to ensure responsibilities are assigned at kickoff and handoffs are tracked.
