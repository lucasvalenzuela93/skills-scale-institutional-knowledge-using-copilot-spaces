# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It includes core delivery personas as well as cross-functional and governance roles that improve clarity and accountability.

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

## Product Managers (PdM)

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

## Project Managers (PM)

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

## Additional Personas (new)

These personas are recommended additions to provide better ownership for cross-functional activities, governance, releases, security, data, and support. Each includes responsibilities and primary interactions with existing roles.

### Technical Program Manager (TPM)
- Responsibilities:
  - Coordinate cross-team dependencies, manage milestones and scheduling for complex initiatives.
  - Track release readiness and own cross-team risk tracking.
  - Facilitate dependency resolution and ensure delivery cadence.
- Interactions:
  - Works closely with PM, PdM, Engineering Leads, and Release Manager.
  - Escalates unresolved cross-team blockers to Product Lead or Sponsor during weekly syncs.

### Engineering Lead
- Responsibilities:
  - Make technical design decisions, maintain architectural consistency and code ownership.
  - Mentor developers and guide technical delivery.
  - Ensure non-functional requirements (performance, reliability, observability) are considered.
- Interactions:
  - Collaborates with Developers, QA, TPM, and PdM to translate product goals into implementation plans.
  - Reviews and approves technical approaches during planning.

### Design Lead
- Responsibilities:
  - Own UX and visual design; ensure accessibility and usability standards are met.
  - Produce handoff artifacts (Figma, specs) and acceptance criteria related to UX.
- Interactions:
  - Works with PdM and Developers to validate designs against user needs.
  - Coordinates usability testing with researchers and provides design sign-off.

### Security Lead
- Responsibilities:
  - Define security requirements, conduct threat modeling, and perform security reviews.
  - Approve releases with security implications and maintain security acceptance criteria.
- Interactions:
  - Advises PMs, Engineers, and TPMs during planning and release.
  - Coordinates with Security on-call for incidents and coordinates remediation actions.

### Data Analyst
- Responsibilities:
  - Define and instrument success metrics, build dashboards, and analyze release impact.
  - Validate data quality and measurement assumptions for success criteria.
- Interactions:
  - Works closely with PdM and PM to ensure data-driven decisions.
  - Coordinates with Developers to implement instrumentation and telemetry.

### Release Manager
- Responsibilities:
  - Coordinate release windows, rollback plans, release communications, and post-release verifications.
  - Ensure runbooks and deployment checklists are complete prior to production cutover.
- Interactions:
  - Works with TPM, Ops/SRE, QA, and Support Liaison to schedule and validate releases.
  - Communicates release status and mitigations to stakeholders.

### Support Liaison (Customer/Support Representative)
- Responsibilities:
  - Triage customer issues, maintain support runbooks, and provide early signals from production.
  - Own communication to customer-facing teams post-release.
- Interactions:
  - Works with PM, SRE, and Developers to surface recurring issues and drive fixes.
  - Participates in incident post-mortems and tracks follow-up action items.

---

## How to use these personas
- Add persona ownership to backlog items (owner field) where relevant.
- Use the checklist in docs/personas-and-responsibilities-checklist.md when introducing a new persona to a project.
- Include persona points of contact in the project README and release notes.

---

## Using persona definitions in the exercise
- Use these persona definitions to frame scenarios and sample interactions in Skills Exercises.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
