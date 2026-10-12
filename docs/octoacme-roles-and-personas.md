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

## Delivery Managers

### Role Summary
Delivery Managers coordinate day-to-day execution and remove blockers so work can move steadily through planning, delivery, and review stages. They align the engineering team with project priorities and escalate issues that require broader decision-making.

### Responsibilities
- Coordinate day-to-day delivery across the project or workstream
- Manage sprint-level dependencies and remove execution blockers
- Track progress against milestones and communicate status to project leadership
- Work with Product Owners and Technical Leads to resolve scope and implementation trade-offs
- Escalate unresolved risks, resource constraints, or cross-team dependencies

### Goals
- Keep delivery moving with minimal disruption
- Improve predictability and transparency across workstreams
- Ensure decisions are made quickly when dependencies or conflicts arise

### Typical Communication
- Daily standups and sprint reviews
- Status updates to Project Managers and stakeholders
- Dependency and escalation discussions with technical and product leads

### Interaction with Existing Roles
- Works closely with Developers and Technical Leads to unblock delivery
- Coordinates with Product Managers and Project Managers on prioritization and project health
- Escalates risks and constraints to Project Managers or sponsors when broader intervention is required

---

## Release Managers

### Role Summary
Release Managers ensure that software changes are prepared, tested, communicated, and deployed in a controlled and predictable manner. They support a safe and repeatable release process across environments.

### Responsibilities
- Own the release readiness checklist and deployment schedule
- Coordinate release communications and rollback planning
- Work with technical and QA roles to confirm production readiness
- Manage timing, dependencies, and stakeholder notifications for release events
- Support post-release follow-up and lessons learned

### Goals
- Reduce release risk and avoid unplanned outages
- Improve release consistency and operational readiness
- Increase confidence in deployment quality

### Typical Communication
- Release planning meetings
- Readiness reviews and deployment approvals
- Release notes and stakeholder updates

### Interaction with Existing Roles
- Works with Technical Leads to confirm technical soundness before deployment
- Collaborates with QA Leads to verify release criteria and test evidence
- Coordinates with Project Managers and stakeholder leads to communicate timing and business impact

---

## QA Leads / Test Owners

### Role Summary
QA Leads define quality standards, testing strategies, and acceptance criteria for project work. They help ensure that solutions meet business intent and are ready for release.

### Responsibilities
- Define test strategy, quality gates, and validation checkpoints
- Review acceptance criteria and align them with realistic test coverage
- Coordinate testing efforts across functional and regression scenarios
- Track defects, identify trends, and assess release readiness
- Work with delivery and technical teams on remediation priorities

### Goals
- Improve confidence in product quality
- Reduce defects escaping into production
- Ensure test evidence supports delivery decisions

### Typical Communication
- Test planning and sign-off reviews
- Defect triage and quality metrics updates
- Release readiness discussions with technical and release leads

### Interaction with Existing Roles
- Aligns with Product Managers on acceptance criteria and user value
- Works with Developers and Technical Leads to validate fixes and root causes
- Provides release readiness input to Release Managers and Project Managers

---

## Stakeholder Liaison / Communications Lead

### Role Summary
This role keeps key project stakeholders informed and aligned by managing status communication, decision visibility, and meeting cadence. It translates technical delivery progress into clear business language.

### Responsibilities
- Coordinate stakeholder updates and reporting rhythms
- Maintain communications plans and meeting agendas
- Summarize status, milestones, risks, and decisions for non-technical audiences
- Ensure key stakeholder concerns are surfaced to the right project roles
- Support executive visibility and decision-making needs

### Goals
- Maintain stakeholder confidence and alignment
- Reduce confusion caused by incomplete or inconsistent updates
- Improve decision-making through clear communication

### Typical Communication
- Weekly/project status summaries
- Stakeholder briefings and governance updates
- Messaging around milestones, risks, and change impacts

### Interaction with Existing Roles
- Pulls information from Project Managers, Product Managers, and Delivery Managers
- Works with Release Managers to communicate deployment impact
- Escalates unresolved stakeholder concerns to project leadership or sponsors

---

## Security and Compliance Reviewers

### Role Summary
Security and Compliance Reviewers assess whether project work meets required standards for confidentiality, integrity, and operational safety. They ensure that delivery decisions account for policy and risk requirements.

### Responsibilities
- Review project changes for security and compliance impact
- Validate controls, authorization flows, and sensitive data handling
- Confirm required checks are completed before release
- Identify security or compliance risks and recommend mitigations
- Support governance reviews and approval gates

### Goals
- Reduce business and technical risk
- Ensure projects meet required standards and controls
- Improve trust in the solution and release process

### Typical Communication
- Security review meetings and approval checkpoints
- Risk and control assessments
- Release and governance recommendations

### Interaction with Existing Roles
- Partner with Technical Leads on secure design decisions
- Works with Release Managers to confirm risk controls before deployment
- Informs Project Managers and stakeholders of security-related impacts or gating

---

## Data Owners / Privacy Leads

### Role Summary
Data Owners and Privacy Leads ensure that project decisions respect data stewardship, retention policies, and regulatory obligations. They help define how information is collected, used, stored, and protected.

### Responsibilities
- Approve data handling approaches and ownership boundaries
- Ensure privacy and compliance requirements are considered in design decisions
- Review sensitive data usage and retention obligations
- Support data governance and consent considerations
- Help resolve issues related to access, classification, or compliance

### Goals
- Protect data integrity and privacy
- Reduce compliance risk and downstream governance issues
- Support responsible and transparent use of information

### Typical Communication
- Data governance reviews
- Privacy and compliance check-ins
- Design discussions with technical and product roles

### Interaction with Existing Roles
- Works with Technical Leads to validate safe data design and controls
- Collaborates with Product Managers to ensure user and business needs align with policy
- Supports Security and Compliance Reviewers as part of broader governance requirements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These roles clarify ownership, accountability, and decision flows across planning, execution, quality, and release activities.

