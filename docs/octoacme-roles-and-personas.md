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

## Project Sponsor

### Role Summary
Project Sponsors champion the business purpose and investment of a project and support organizational decisions within their delegated authority.

### Responsibilities
- Consider the Product Manager's (PdM's) value proposition and success metrics alongside the Project Manager's (PM's) plan and risks when deciding whether to initiate or continue work.
- Consult Developers through the PM on feasibility and capacity; communicate approved investment decisions and rationale to the PdM, PM, and affected team.
- Approve budget and resource commitments only within delegated organizational authority; route decisions outside that authority to the appropriate approver.
- Resolve escalated business conflicts without taking over day-to-day backlog or delivery management.
- Record decisions, scope, rationale, and any conditions in the decision log.

### Goals
- Keep investment aligned with business purpose and expected outcomes
- Enable timely decisions and resolution of escalated business conflicts
- Make approval authority and decision rationale transparent

### Typical Communication
- Initiation or continuation decisions based on the project one-pager and PM's plan
- Milestone reviews of PdM outcome metrics, delivery status, and material risks
- Escalations from the PM with a decision log entry for the outcome and rationale

---

## Technical Lead

### Role Summary
Technical Leads guide technical direction and make design choices visible so the team can deliver maintainable, testable solutions.

### Responsibilities
- Coordinate technical design, assess dependencies, and support estimates with Developers.
- Review maintainability, performance, and testability trade-offs; record significant design decisions and rationale.
- Discuss feasibility and value trade-offs with the PdM and communicate technical risks and schedule impacts to the PM.
- Hand off an agreed design, dependencies, and unresolved technical risks to Developers and the PM.
- Record the project's technical decision-maker in the role allocation; the Technical Lead's title alone does not grant decision authority. Do not own product priorities or business approvals.

### Goals
- Reduce technical rework and unmanaged dependencies
- Support maintainable, performant, and testable solutions
- Give the PM and PdM timely, evidence-based feasibility information

### Typical Communication
- Design reviews and decision records shared with Developers and the PM
- Feasibility and trade-off discussions with the PdM
- Estimates, dependency updates, and schedule-risk escalations to the PM

---

## QA/Testing

### Role Summary
QA/Testing makes product quality and verification evidence visible to support acceptance and release decisions.

### Responsibilities
- Prepare test plans and run integration, regression, and critical-flow smoke tests.
- Triage defects, record verification evidence, and report residual quality risks to the PM and relevant decision-makers.
- Work with the PdM to clarify acceptance criteria, with Developers on testability and fixes, and with the PM on verification progress.
- Support quality guidance for the Definition of Done (DoD); Developers retain responsibility for unit tests.
- Do not act as the sole approver of business release authorization.

### Goals
- Find critical defects early and reduce gaps in verification
- Make coverage, results, and residual quality risks clear
- Help the team meet agreed acceptance criteria and DoD

### Typical Communication
- Test plans and acceptance questions with the PdM and Developers
- Defect reports with reproduction steps and verification evidence for Developers
- Progress, release-readiness findings, and residual risks to the PM and release decision-makers

---

## UX/User Research

### Role Summary
UX/User Research helps the team understand user needs and design usable, accessible experiences.

### Responsibilities
- Conduct user research and document findings, user flows, design proposals, and design rationale.
- Evaluate usability and accessibility, and share evidence and implications with the PdM.
- Discuss implementation constraints with Developers and usability test perspectives with QA/Testing.
- Coordinate research and review timing with the PM; hand off research findings and approved design artifacts to the PdM, Developers, and QA/Testing.
- UX evidence informs product decisions but does not set backlog priorities or approve business outcomes or technical implementation.

### Goals
- Align solutions with evidenced user needs
- Improve usability and accessibility
- Reduce rework caused by misunderstood requirements or design intent

### Typical Communication
- Research findings and evidence to the PdM to inform product decisions
- Design reviews and implementation constraints with Developers
- Usability and accessibility test perspectives with QA/Testing, with timing coordinated through the PM

---

## Release/Operations

### Role Summary
Release/Operations prepares and executes technical deployment and operational handoff, supporting verification and service stability.

### Responsibilities
- Prepare deployment steps, monitoring, rollback plans, runbooks, and operational handoff artifacts.
- Coordinate deployment requirements with Developers, smoke-test arrangements with QA/Testing, and timing and communications with the PM.
- Perform or coordinate post-deployment verification and share user impact and operational status with the PdM.
- Follow existing on-call and incident procedures; hand off runbooks, monitoring details, and known operational risks to the receiving operations/on-call team.
- Distinguish business release authorization from technical deployment execution; deployment execution does not itself grant business go/no-go approval.

### Goals
- Reduce deployment failures and operational handoff omissions
- Enable prompt detection, rollback, and recovery when needed
- Ensure operational owners have usable runbooks and monitoring information

### Typical Communication
- Readiness, deployment window, and rollback coordination with Developers, QA/Testing, and the PM
- Deployment and post-deployment verification status to the PM and PdM
- Incident updates through existing on-call and incident communication channels

---

## Security

### Role Summary
Security supports the assessment and mitigation of security, privacy, and data-handling risks.

### Responsibilities
- Review threats, data and privacy handling, and security scan results with Developers and the Technical Lead.
- Record findings, mitigation owners and status, and residual-risk evidence; inform the PM and consult the PdM on user and product impact.
- Use the existing security incident runbook and Security on-call route for security incidents.
- The person authorized to accept residual security risk must be explicitly assigned under organizational policy; risk acceptance is not implicitly delegated to Security.

### Goals
- Identify security and privacy risks early
- Make mitigations and residual risks traceable
- Ensure security decisions follow the applicable organizational authority and incident process

### Typical Communication
- Threat, data-handling, and design reviews with Developers and the Technical Lead
- Findings, mitigation status, and residual-risk evidence to the PM, with the PdM consulted on product impact
- Security incident escalation through the security incident runbook and Security on-call route

---

## Support/Customer Success

### Role Summary
Support/Customer Success prepares customer-facing guidance and brings customer impact and inquiry patterns into project decisions.

### Responsibilities
- Prepare FAQs, known-issue information, customer communications, and support handoff materials.
- Share inquiry patterns and customer impact with the PdM; provide Developers and QA/Testing with actionable reproduction information.
- Coordinate communication timing with the PM and incident status with Release/Operations.
- Hand off support materials and known issues to the receiving support team; the PdM retains final backlog prioritization.

### Goals
- Improve consistency of customer responses
- Reduce customer confusion after release
- Ensure customer feedback informs product decisions without bypassing PdM prioritization

### Typical Communication
- Release briefings, FAQs, and known issues with the PM and support recipients
- Inquiry trends and customer impact to the PdM
- Reproduction details to Developers and QA/Testing, and incident status coordination with Release/Operations

---

## Common Role Operating Guidance

These personas describe project responsibilities, not mandatory new job positions or finalized organizational policy. Roles may be combined, but at initiation/planning record named owners, backups, consultation contacts, and the required approvals and reviews. Confirm that each named decision-maker has the appropriate organizational authority; do not infer approval authority from a role title.

Use this allocation template to record project-specific assignments. Fill in names or roles for every cell rather than assuming the assignments below:

| Activity / decision | Execution owner | Final decision-maker | Consultees | Informed recipients |
| --- | --- | --- | --- | --- |
| Initiation approval | To be assigned | To be assigned under delegated authority | To be assigned | To be assigned |
| Acceptance criteria | To be assigned | To be assigned | To be assigned | To be assigned |
| Technical design | To be assigned | To be assigned | To be assigned | To be assigned |
| Quality verification | To be assigned | To be assigned | To be assigned | To be assigned |
| Release go/no-go | To be assigned | To be assigned under organizational authority | To be assigned | To be assigned |
| Incident response | To be assigned | To be assigned under the applicable incident procedure | To be assigned | To be assigned |

Confirm and record during initiation/planning whether the Product Lead named in other process docs and the PdM in this document are the same or distinct roles, and document the authority and responsibilities of each. Do not assume they are synonymous.

Maintain the existing escalation path of Team -> PM -> Product Lead -> Sponsor. For security incidents, use the separate security incident runbook and Security on-call route; this role guidance does not replace either process.

Review the role allocation with stakeholders before adoption; stakeholder review is pending and no organizational policy is established by this proposal. In retrospectives, consider tracking unassigned work, approval lead time, handoff omissions, post-release defects, and time for new teammates to understand role allocation. Establish no baseline or target in advance; use project evidence to decide whether and how to improve.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
