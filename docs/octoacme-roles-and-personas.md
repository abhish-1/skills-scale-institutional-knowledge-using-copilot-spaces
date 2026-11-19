# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Assign these responsibilities to named team members as appropriate; one person may hold more than one role, and role ownership should be agreed at project kickoff.

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

## Release Managers

### Role Summary
Release Managers coordinate release readiness and deployment activities, ensuring the required approvals, checks, communications, and contingency plans are in place.

### Responsibilities
- Coordinate release scope, schedule, readiness reviews, and go/no-go inputs
- Confirm acceptance criteria, CI, security checks, smoke tests, release notes, and rollback plans are accounted for
- Track release blockers and coordinate their resolution or escalation
- Ensure deployment and post-deployment verification steps are completed
- Coordinate release announcements with relevant stakeholders and support teams

### Goals
- Deliver predictable releases with minimal disruption
- Make release status, decisions, and risks visible
- Ensure teams are prepared to respond to deployment issues

### Typical Communication
- Release readiness reviews and deployment coordination
- Release plans, checklists, notes, and status updates
- Post-deployment verification and incident channels

### Interactions with Existing Roles
- Partners with Developers and QA/Testing to verify quality checks, smoke tests, and readiness evidence
- Aligns release scope and customer impact with Product Managers
- Coordinates timelines, dependencies, risks, approvals, and stakeholder updates with Project Managers
- Works with Stakeholders and Customer/Support Representatives on announcements and support readiness
- Consults the Security Lead on outstanding security findings and required controls

---

## Security Leads

### Role Summary
Security Leads provide security guidance throughout project delivery and coordinate security review and escalation in line with the organization's security processes.

### Responsibilities
- Identify applicable security requirements and risks during planning and design
- Advise teams on secure implementation, data handling, and security testing
- Review or coordinate security findings and track remediation with owners
- Escalate suspected security incidents through the established security incident process
- Contribute security readiness input before release

### Goals
- Identify and address security risks early
- Make security ownership and required actions clear
- Support secure delivery without avoidable late-stage surprises

### Typical Communication
- Security requirements and review notes
- Risk register entries, remediation tracking, and design discussions
- Security incident channels and release readiness reviews

### Interactions with Existing Roles
- Advises Developers on secure design, implementation, and remediation; developers remain responsible for changes to their components
- Works with Product Managers to surface security-related product trade-offs and clarify requirements
- Partners with Project Managers to record security risks, owners, milestones, and escalations
- Coordinates with QA/Testing on security test coverage and with Stakeholders on material risks or decisions
- Shares release readiness concerns with the Release Manager and follows established incident escalation paths

---

## UX/Design Leads

### Role Summary
UX/Design Leads shape user-centered workflows and interfaces, helping ensure that proposed solutions are usable, accessible, and consistent with customer needs.

### Responsibilities
- Lead or coordinate user research, journey mapping, and interaction design as appropriate
- Translate user needs into design artifacts and usability considerations
- Review designs and delivered experiences against agreed requirements
- Identify usability and accessibility risks and propose improvements
- Collaborate on acceptance criteria for user-facing work

### Goals
- Deliver clear, accessible, and coherent user experiences
- Validate design decisions with user evidence where practical
- Reduce rework by involving design expertise early

### Typical Communication
- Design briefs, prototypes, and research findings
- Design reviews with Product Managers and Developers
- Usability feedback and acceptance criteria

### Interactions with Existing Roles
- Partners with Product Managers to connect customer needs, outcomes, and priorities to design decisions
- Works with Developers to assess feasibility, clarify behavior, and refine implementation details
- Coordinates with Project Managers on design milestones, dependencies, and review timing
- Collaborates with QA/Testing on usability and accessibility validation
- Shares research insights and design trade-offs with relevant Stakeholders

---

## Customer/Support Representatives

### Role Summary
Customer/Support Representatives bring customer-facing feedback and operational support needs into project decisions and help prepare teams to support delivered changes.

### Responsibilities
- Share recurring customer questions, pain points, and field feedback
- Identify support workflows, documentation, and training needs
- Review customer-facing release communications for clarity and support readiness
- Help route customer-impacting issues and feedback to appropriate owners
- Contribute to post-release feedback and outcome assessment

### Goals
- Make delivered changes understandable and supportable
- Close the loop between customer experience and product decisions
- Reduce avoidable support friction after release

### Typical Communication
- Customer feedback summaries and support trend reports
- Support readiness reviews, help content, and release communications
- Post-release issue and feedback channels

### Interactions with Existing Roles
- Shares customer evidence with Product Managers to inform prioritization and success measures
- Works with Developers to clarify customer-reported behavior and reproduce issues when possible
- Coordinates readiness tasks, ownership, and communications with Project Managers
- Partners with the Release Manager on release timing, announcements, and support handoffs
- Provides QA/Testing with representative customer scenarios and shares relevant updates with Stakeholders

---

## Technical Program/Delivery Leads

### Role Summary
Technical Program/Delivery Leads coordinate technical sequencing and cross-team delivery for complex initiatives, helping teams manage integration points and dependencies. This role complements rather than replaces the Project Manager's overall project coordination.

### Responsibilities
- Map technical workstreams, integration points, and cross-team dependencies
- Coordinate engineering sequencing, milestones, and integration readiness
- Surface technical risks, decisions, and capacity constraints to project leadership
- Facilitate resolution of cross-team technical blockers
- Maintain visibility of technical status and handoffs across teams

### Goals
- Reduce integration surprises and dependency delays
- Keep technical workstreams aligned with project outcomes and milestones
- Clarify engineering ownership across team boundaries

### Typical Communication
- Technical plans, dependency maps, and integration checkpoints
- Coordination with engineering leads and delivery teams
- Risk and status updates in project syncs and decision records

### Interactions with Existing Roles
- Works with Project Managers, who retain ownership of the integrated project plan, stakeholder communication, and overall project risks
- Partners with Developers and engineering leads on sequencing, interfaces, estimates, and technical blockers
- Aligns with Product Managers on technical options, scope trade-offs, and product priorities
- Coordinates with QA/Testing, Release Managers, and Security Leads on integration, verification, and release dependencies
- Reports cross-team status and decisions to relevant Stakeholders through agreed project channels

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
