# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

Roles describe responsibilities, not required dedicated positions. Depending on team size and project scope, one person may cover multiple roles. The Project Manager should make sure each responsibility has a clear owner and coordinate handoffs; combining roles does not remove accountability.

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

## Engineering / Technical Leads

### Role Summary
Engineering or Technical Leads guide technical direction and help the team deliver a feasible, maintainable solution. They support technical decisions without replacing the delivery responsibilities of the Developers or the prioritization responsibilities of the Product Manager.

### Responsibilities
- Align technical design and architecture with project requirements and standards
- Assess feasibility, estimate technical work with Developers, and identify technical risks
- Coordinate technical dependencies and design decisions across teams
- Support Developers through implementation and technical reviews

### Interaction with Existing Roles
- Partner with Developers on design, implementation, estimates, and technical risk mitigations
- Advise the Product Manager on technical trade-offs, feasibility, and impact to outcomes
- Keep the Project Manager informed about technical dependencies, risks, and schedule impacts
- Clarify technical decisions and constraints for stakeholders with the Product Manager and Project Manager

---

## UX / Product Designers and Researchers

### Role Summary
UX or Product Designers and Researchers make sure solutions address user needs through research, interaction design, accessibility, and usability validation.

### Responsibilities
- Plan and conduct user research and synthesize findings
- Create and validate user flows, interaction designs, and prototypes
- Incorporate accessibility and usability considerations into design decisions
- Share design rationale and open questions with the delivery team

### Interaction with Existing Roles
- Work with the Product Manager to connect user needs and research findings to product goals and backlog priorities
- Collaborate with Developers and Engineering / Technical Leads to assess feasibility and refine designs
- Coordinate with QA / Test Leads to include usability and accessibility in validation
- Share research insights with the Project Manager to inform dependencies, milestones, and stakeholder updates

---

## QA / Test Leads

### Role Summary
QA or Test Leads coordinate quality practices so that delivery meets acceptance criteria and is ready for release. They work alongside Developers, who remain responsible for building and testing their changes.

### Responsibilities
- Define or coordinate the test strategy, coverage, and test approach for the project
- Help make acceptance criteria testable and identify gaps early
- Coordinate integration, end-to-end, regression, and exploratory testing as appropriate
- Track defects, communicate quality risks, and verify fixes
- Report evidence of readiness and outstanding quality concerns

### Interaction with Existing Roles
- Work with the Product Manager to clarify acceptance criteria and expected behavior
- Coordinate with Developers on testability, defect triage, and verification of fixes
- Align with the Project Manager on test dependencies, progress, and release-readiness risks
- Share quality evidence and open issues with stakeholders before release decisions

---

## Security / Privacy Leads

### Role Summary
Security or Privacy Leads advise the team on security, privacy, and compliance expectations, and help ensure risks are assessed and addressed throughout delivery.

### Responsibilities
- Identify applicable security and privacy requirements early in planning
- Advise on threat, privacy, and compliance risks and proportionate mitigations
- Coordinate or perform security and privacy reviews as needed
- Help verify that mitigations are implemented and record residual risks
- Escalate material risks through the appropriate security or privacy incident process

### Interaction with Existing Roles
- Advise Developers and Engineering / Technical Leads on secure design and implementation
- Coordinate with QA / Test Leads on security and privacy validation
- Work with the Product Manager to balance requirements and product trade-offs without obscuring risk
- Help the Project Manager track mitigations, owners, and escalation needs in project risk reporting
- Coordinate with the Product Lead and relevant security or privacy stakeholders on significant risks

---

## Operations / SRE or Release Owners

### Role Summary
Operations, Site Reliability Engineering (SRE), or Release Owners prepare services and teams for dependable deployment and operation, including monitoring and recovery.

### Responsibilities
- Define operational readiness requirements, including service health and support coverage
- Coordinate deployment plans, release windows, and operational dependencies
- Ensure monitoring, alerting, and rollback or mitigation plans are prepared
- Coordinate post-deployment verification and communicate operational issues
- Capture operational follow-up actions and reliability risks

### Interaction with Existing Roles
- Partner with Developers and Engineering / Technical Leads on operability, deployment, and recovery plans
- Coordinate with QA / Test Leads on smoke tests and release verification
- Work with the Project Manager on timing, cross-team dependencies, readiness status, and communications
- Align with the Product Manager on customer impact and release scope when operational risks affect a launch
- Coordinate launch and support readiness with Customer Support / Success Representatives

---

## Customer Support / Success Representatives

### Role Summary
Customer Support or Success Representatives bring customer-impact knowledge into delivery and prepare customer-facing teams to support changes after release.

### Responsibilities
- Share recurring customer questions, reported issues, and feedback with the project team
- Identify customer-impact risks and support requirements for planned changes
- Prepare or coordinate support guidance, knowledge-base updates, and internal briefings
- Help gather and communicate customer feedback after release

### Interaction with Existing Roles
- Work with the Product Manager to connect customer needs and feedback to product decisions and success measures
- Coordinate with the Project Manager on launch communications, support readiness, and relevant dependencies
- Partner with Operations / SRE or Release Owners on incident routing and operational updates that affect customers
- Provide Developers and QA / Test Leads with customer scenarios and reported issues that can inform implementation and testing
- Escalate significant customer-impact concerns through the agreed project and support channels

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
