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

## Project Sponsors

### Role Summary
Project Sponsors provide the executive alignment, authority, and resources needed to pursue a project and realize its business value.

### Responsibilities
- Confirm the business need, priority, and expected outcomes
- Secure or escalate decisions about funding, resources, and scope that exceed the delivery team's authority
- Resolve escalations raised by the Project Manager (PM) or Product Manager (PdM)
- Support stakeholder alignment at key decision gates

### Goals
- Ensure the project remains aligned with organizational priorities
- Enable timely decisions and remove organizational blockers
- Confirm that expected business value justifies continued investment

### Typical Communication
- Project approval and milestone decision points
- Escalations and decision requests from the PM or PdM
- Periodic outcome and status updates

### Interactions with Existing Roles
- Partners with the PdM on business outcomes and strategic priority; the PdM remains responsible for product direction and backlog ordering.
- Partners with the PM on governance, resources, and escalations; the PM remains responsible for delivery coordination and status reporting.
- Provides direction and decisions to stakeholders without taking over day-to-day work from Developers or QA/Testing.

---

## UX / User Research Leads

### Role Summary
UX / User Research Leads represent user needs in discovery and delivery, helping teams create usable, accessible experiences grounded in evidence.

### Responsibilities
- Plan or conduct user research and synthesize findings
- Translate user needs into design guidance and usability considerations
- Identify accessibility and usability risks and help define acceptance criteria
- Validate proposed solutions with users where appropriate

### Goals
- Ensure product decisions reflect user evidence and needs
- Reduce usability and accessibility gaps before release
- Help teams validate that delivered work solves the intended problem

### Typical Communication
- Research findings and design reviews
- Collaboration on discovery, refinement, and acceptance criteria
- Usability and accessibility feedback during implementation and QA

### Interactions with Existing Roles
- Works with the PdM to refine problem statements, user needs, and outcome hypotheses; the PdM retains prioritization and product decisions.
- Collaborates with Developers and QA/Testing to make designs feasible, accessible, and testable.
- Coordinates research and design dependencies with the PM, who owns the overall schedule and delivery plan.
- Shares relevant findings with Stakeholders to support informed decisions.

---

## Technical Leads / Architects

### Role Summary
Technical Leads / Architects guide technical design and integration so that solutions are reliable, maintainable, and aligned with project needs.

### Responsibilities
- Facilitate technical design and document significant decisions
- Guide architecture, interfaces, and integration choices
- Identify technical risks, quality attributes, and cross-team dependencies
- Advise on technical feasibility, effort, and implementation trade-offs

### Goals
- Enable a coherent, secure, and maintainable technical solution
- Surface technical constraints early enough to inform planning
- Support Developers in delivering quality increments

### Typical Communication
- Technical design discussions and decision records
- Implementation and code reviews
- Risk and dependency updates during planning and delivery

### Interactions with Existing Roles
- Guides and supports Developers without replacing their implementation ownership.
- Advises the PdM on feasibility and technical trade-offs; the PdM remains accountable for product scope and prioritization.
- Keeps the PM informed about technical risks, dependencies, and delivery impacts; the PM coordinates the plan and escalations.
- Partners with QA/Testing on testability and technical quality requirements.

---

## Release / Operations Leads

### Role Summary
Release / Operations Leads coordinate operational readiness and the safe deployment and support of project changes.

### Responsibilities
- Coordinate release readiness, deployment activities, and operational handoffs
- Confirm monitoring, support, and rollback or mitigation plans are prepared
- Surface operational risks and dependencies before release
- Coordinate incident response and post-deployment verification with the appropriate teams

### Goals
- Make releases observable, supportable, and low risk
- Reduce disruption to customers and operations
- Ensure teams can detect and respond to deployment issues

### Typical Communication
- Release readiness reviews and deployment coordination
- Operational checklists, monitoring signals, and incident updates
- Post-release verification and lessons learned

### Interactions with Existing Roles
- Works with Developers on deployment, monitoring, and rollback details and with QA/Testing on release verification.
- Coordinates release timing and communications with the PM, who owns the integrated project schedule.
- Aligns expected customer impact and release scope with the PdM, who owns product decisions.
- Provides Stakeholders and support teams with operationally relevant release updates.

---

## Data / Analytics Leads

### Role Summary
Data / Analytics Leads help teams measure whether a project achieves its intended outcomes and interpret evidence after delivery.

### Responsibilities
- Define measurement approaches and instrumentation for agreed success metrics
- Identify data dependencies and quality considerations
- Help analyze results and distinguish observed outcomes from assumptions
- Share measurement findings and recommend follow-up analysis where appropriate

### Goals
- Make project outcomes measurable and interpretable
- Improve decisions through reliable, relevant evidence
- Support ongoing learning after release

### Typical Communication
- Metric definitions and instrumentation plans
- Data quality and implementation discussions
- Post-release dashboards, analysis, and outcome reviews

### Interactions with Existing Roles
- Partners with the PdM to define outcome measures and interpret results; the PdM remains accountable for product goals and prioritization.
- Collaborates with Developers on instrumentation and data dependencies.
- Works with the PM to include measurement milestones and findings in project reporting and follow-up.
- Shares relevant evidence with Stakeholders while making assumptions and limitations clear.

---

## Applying Roles to a Project

- Assign each responsibility to a clear owner, but do not assume every role requires a separate person. On smaller teams, one person may cover multiple roles when capacity and conflicts of interest allow.
- Keep decision ownership clear: Sponsors provide organizational authority, PdMs own product direction and prioritization, and PMs coordinate delivery. Specialist leads advise and own their defined areas without replacing these accountabilities.
- Identify the roles needed during initiation and planning, and revisit ownership when scope, risks, or release needs change.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
