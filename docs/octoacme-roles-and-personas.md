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

## Additional Personas (proposed additions)

Note: these additional personas are recommended to reduce implicit knowledge and clarify handoffs. For each persona below we provide a concise Role Summary, Responsibilities, Interaction notes, and Suggested Handoff / Acceptance Signals.

### Delivery Lead
Role Summary:
- Owns day-to-day delivery coordination for a project or release cycle.

Responsibilities:
- Facilitate sprint planning, standups, and retrospectives for the delivery stream.
- Track commitments, blockers, and cross-team dependencies.
- Maintain and update the delivery timeline and dependency register.

Interaction:
- Works closely with the PM to translate scope into prioritized delivery plans.
- Coordinates with Engineers, QA, SRE, and external stakeholders to remove impediments.

Suggested Handoff / Acceptance Signals:
- Confirms that all cross-team dependencies are assigned and resolvers are identified before sprint start.
- Marks tasks as "blocked" with an owner and escalation path in the project board.

### Engineering Lead
Role Summary:
- Technical owner for architecture, implementation approach, and engineering quality.

Responsibilities:
- Define and communicate the technical approach and architecture decisions.
- Ensure code quality, testing coverage, and mentoring of engineers.
- Perform or coordinate design reviews and approve major technical changes.

Interaction:
- Works with Product Manager and Delivery Lead to assess technical feasibility and estimates.
- Collaborates with SRE and Security for design reviews when operational or compliance concerns arise.

Suggested Handoff / Acceptance Signals:
- Technical design doc or ADR approved before major implementation begins.
- Engineering Lead sign-off recorded on complex PRs or architecture changes.

### UX Researcher / Designer
Role Summary:
- Drives user research, interaction design, and validates usability.

Responsibilities:
- Conduct user interviews, usability tests, and synthesize findings.
- Produce wireframes, high-fidelity mocks, and accessibility considerations.
- Define UX-related acceptance criteria and handoff artifacts for implementation.

Interaction:
- Works with PM to align on user needs and success criteria.
- Hands off designs and acceptance criteria to Engineers and QA; provides clarifications during implementation.

Suggested Handoff / Acceptance Signals:
- Completed design files and research summaries attached to the ticket before dev work begins.
- UX sign-off on key screens before release.

### Data Analyst
Role Summary:
- Defines measurement strategy and analyzes outcomes against success metrics.

Responsibilities:
- Define key metrics, events, and instrumentation requirements.
- Validate that telemetry and analytics are implemented correctly.
- Provide ongoing analysis to inform product decisions and retrospectives.

Interaction:
- Works with PM to set measurable success criteria.
- Provides engineers with instrumentation specs and verifies data post-release.

Suggested Handoff / Acceptance Signals:
- Instrumentation checklist completed with event names and properties prior to release.
- Data validation report post-deploy confirming metric availability and correctness.

### Site Reliability Engineer (SRE)
Role Summary:
- Ensures operational readiness, reliability, and runbook completeness.

Responsibilities:
- Provide guidance on uptime, scaling, and operational behavior.
- Contribute runbooks, alerting thresholds, and post-deploy monitoring checks.
- Support incident response and production troubleshooting.

Interaction:
- Engages during planning to assess reliability needs.
- Coordinates with Engineering Lead for operability requirements and on-call support.

Suggested Handoff / Acceptance Signals:
- Runbook exists and alerts are defined before production release.
- Load/scale checks in staging complete.

### Security Engineer / Compliance Liaison
Role Summary:
- Ensures security and compliance considerations are integrated into the project.

Responsibilities:
- Conduct threat modeling and security reviews.
- Validate compliance requirements (e.g., data handling, privacy).
- Recommend mitigations for identified risks.

Interaction:
- Works with Engineering Lead and PM during design and prior to release to confirm controls.
- Escalates any security-blocking issues and supports remediation.

Suggested Handoff / Acceptance Signals:
- Security checklist completed and any required approvals recorded.
- Issues with high severity are mitigated or have a documented plan.

### Customer Success / Support Liaison
Role Summary:
- Brings customer context into prioritization and coordinates post-release support.

Responsibilities:
- Provide insights on customer impact and severity of issues.
- Help prioritize production defects and shape release communications.
- Coordinate readiness of knowledge base articles and support runbooks.

Interaction:
- Works with PM to surface customer feedback into backlog prioritization.
- Communicates with Support/CS teams ahead of release to prepare messaging.

Suggested Handoff / Acceptance Signals:
- Support runbooks and release messaging drafted and shared before release.
- Escalation paths for customer-impacting issues are defined.

### Legal / Privacy Liaison
Role Summary:
- Advises on legal, contractual, and privacy implications of features.

Responsibilities:
- Review features for contractual obligations and data privacy requirements.
- Provide approvals or constraints for release language and feature scope.

Interaction:
- Engages for features that introduce new legal or data-privacy considerations.
- Works with PM and Security to ensure compliance before release.

Suggested Handoff / Acceptance Signals:
- Legal review completed for features with contract or privacy impact.
- Approved release wording when required.

### Accessibility Advocate
Role Summary:
- Ensures accessibility considerations are included throughout design and implementation.

Responsibilities:
- Define accessibility acceptance criteria and testing approaches.
- Assist with accessibility testing and remediation guidance.
- Promote inclusive design patterns.

Interaction:
- Works with Designers, Engineers, and QA to validate accessibility.
- Contributes to acceptance criteria and verification steps.

Suggested Handoff / Acceptance Signals:
- Accessibility checklist included in the ticket (WCAG guidelines referenced).
- QA confirms accessibility checks before release.

---

## How to add a persona to this file
- Add a short Role Summary, Responsibilities, Interaction guidance, and Suggested Handoff / Acceptance Signals.
- Keep entries concise and actionable.
- When possible, link to specific procedures (runbooks, instrumentation docs) and include owners.
