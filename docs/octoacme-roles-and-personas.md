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

## QA/Testing Lead

### Role Summary
QA/Testing Leads ensure product quality, validate acceptance criteria, and manage the testing strategy across all phases of delivery. They collaborate with Developers, Product Managers, and Project Managers to define testability requirements and maintain quality standards.

### Responsibilities
- Create and maintain test plans aligned with acceptance criteria
- Execute manual and automated testing across unit, integration, and end-to-end scenarios
- Validate features meet quality standards before release
- Report defects and track quality metrics
- Participate in sprint planning and Definition of Done refinement
- Conduct smoke testing prior to production deployment

### Goals
- Ensure features meet acceptance criteria and business requirements
- Minimize production incidents through thorough testing
- Establish and maintain high quality standards

### Typical Communication
- Sprint planning and backlog refinement sessions
- Quality metrics reports and defect tracking
- Test plans and acceptance sign-offs
- Pre-release quality gates and smoke test results

### Interaction with Other Roles
- Works with Developers to identify gaps in coverage and validate fixes
- Coordinates with Product Managers on acceptance criteria and release readiness
- Shares quality signals and risk findings with Project Managers for scheduling and escalation

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors are business or executive leaders who provide business context, prioritization input, and approval authority. They align projects with organizational strategy and ensure resources are allocated to high-impact work.

### Responsibilities
- Approve project initiation and major scope changes
- Provide business context and success metrics
- Participate in decision gates and milestone reviews
- Remove organizational blockers and secure resources
- Review and approve release communications and announcements

### Goals
- Ensure projects align with business strategy
- Maximize ROI and business impact
- Maintain executive visibility and accountability

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Decision gate reviews and approval meetings
- Ad-hoc escalations for business-impacting blockers
- Release announcements and executive summaries

### Interaction with Other Roles
- Provides strategic direction to Product Managers and Project Managers
- Approves major trade-offs and escalations when scope or priority changes
- Receives updates from PMs and Product Leads on milestones, risks, and outcomes

---

## Scrum Master / Team Facilitator

### Role Summary
Scrum Masters or Team Facilitators help teams operate effectively by guiding agile ceremonies, removing blockers, and supporting healthy team dynamics. They enable consistent delivery while keeping the team focused on outcomes and collaboration.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Remove or escalate blockers affecting delivery
- Support team health, communication, and continuous improvement
- Help maintain process adherence and sustainable delivery cadence
- Coordinate with Project Managers to surface risks and dependencies

### Goals
- Improve team flow and delivery predictability
- Support a healthy, collaborative, and accountable working environment
- Reduce friction caused by process, communication, or dependency issues

### Typical Communication
- Daily standups and sprint ceremonies
- Team health check-ins and retrospectives
- Dependency and blocker coordination with Project Managers and leads
- Coaching conversations around agile practices and workflow improvements

### Interaction with Other Roles
- Partners with Project Managers on planning cadence and team coordination
- Helps Developers and Product Managers maintain focus on agreed priorities and effective ceremonies
- Escalates structural issues to leadership when process or team health requires intervention

---

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects provide technical direction, guide architectural decisions, and help the team balance delivery speed with maintainability and long-term system health.

### Responsibilities
- Define or guide technical direction and architectural standards
- Review design trade-offs and major technical decisions
- Identify technical risks, dependencies, and integration concerns
- Support implementation quality through design guidance and code review
- Partner with engineering leaders on platform and scalability decisions

### Goals
- Deliver solutions that are maintainable, reliable, and scalable
- Reduce avoidable technical debt and architectural drift
- Support the team in making sound technical decisions under delivery pressure

### Typical Communication
- Technical design discussions and architecture reviews
- Design docs, system-level trade-off discussions, and risk reviews
- Collaboration with Developers during implementation and troubleshooting

### Interaction with Other Roles
- Works with Product Managers and Stakeholders on feasibility and trade-offs for roadmap items
- Advises Project Managers and Scrum Masters on technical dependencies and sequencing
- Supports Developers with design clarity and risk reduction

---

## Release Manager

### Role Summary
Release Managers coordinate delivery and deployment activities, manage release schedules, and ensure pre-release and post-release activities are completed consistently and with minimal disruption.

### Responsibilities
- Coordinate release windows, sequencing, and readiness reviews
- Ensure release checklists and deployment requirements are met
- Manage communication with stakeholders during deployment events
- Track rollback readiness and post-deployment verification
- Align release activities with project milestones and operational constraints

### Goals
- Reduce release risk and operational disruption
- Ensure consistent deployment readiness across environments
- Support predictable delivery with clear ownership and communication

### Typical Communication
- Release readiness meetings and deployment check-ins
- Stakeholder updates before and after deployment
- Coordination with engineering, QA, and support teams during release windows

### Interaction with Other Roles
- Works closely with QA/Testing Leads to confirm quality gates before production release
- Coordinates with Project Managers and Product Managers on milestone timing and stakeholder messaging
- Partners with Technical Leads to validate deployment plans and rollback readiness

---

## Security Lead

### Role Summary
Security Leads ensure secure engineering practices, compliance readiness, and incident response coordination are embedded in project work and release practices.

### Responsibilities
- Ensure security requirements and compliance controls are considered in planning and delivery
- Review security scanning, code review findings, and risk exposure
- Support security triage during incidents or escalations
- Partner with release, technical, and project teams on secure deployment practices
- Help define mitigation strategies for security-related risks

### Goals
- Reduce security risk in software delivery and operations
- Ensure teams follow established security controls and incident procedures
- Support a secure, resilient product environment

### Typical Communication
- Security review meetings and risk assessments
- Security incident notification and response coordination
- Security guidance for engineering and release readiness discussions

### Interaction with Other Roles
- Works with Developers and Technical Leads to validate secure architecture and implementation choices
- Supports Release Managers and QA leads with pre-release security checks and post-deployment monitoring
- Escalates high-risk issues to Stakeholders or Sponsors when business impact or compliance concerns require action

---

## How these personas work together
- Product Managers and Stakeholders define priorities and business outcomes.
- Project Managers and Scrum Masters coordinate delivery flow, dependencies, and team health.
- Developers and Technical Leads deliver implementation and technical quality.
- QA/Testing Leads validate readiness against acceptance criteria and release criteria.
- Release Managers and Security Leads ensure deployments are safe, observable, and compliant.
- Sponsor and stakeholder involvement provides business context, approvals, and escalation paths when major decisions are required.

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These roles help clarify ownership boundaries and communication patterns across the project lifecycle.

