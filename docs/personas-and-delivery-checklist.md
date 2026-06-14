# Personas & Delivery Checklist

Purpose:
- Provide a minimal, actionable checklist teams can use to ensure role handoffs, dependencies, and acceptance signals are clear at key moments: planning, sprint start, implementation, and release.

How to use:
- Attach this checklist as a template to planning tickets or releases.
- Assign owners for each checklist item; clear ownership prevents implicit assumptions.

Checklist

## Pre-Planning / Kickoff
- [ ] Project One-pager exists (Problem, Goal, Success Metrics) — Owner: PM
- [ ] Stakeholders and champions identified — Owner: PM
- [ ] Initial success metrics & instrumentation needs noted — Owner: PM / Data Analyst
- [ ] Security/privacy needs flagged — Owner: PM

## Sprint / Iteration Start
- [ ] Delivery Lead confirms backlog items are "Ready" and dependencies assigned — Owner: Delivery Lead
- [ ] Engineering Lead approves technical approach for scoped work items — Owner: Engineering Lead
- [ ] UX handoff: designs + acceptance criteria attached — Owner: UX Designer
- [ ] Data instrumentation tasks created for required events — Owner: Data Analyst
- [ ] SRE/operational concerns raised and runbooks updated as needed — Owner: SRE

## Implementation / PRs
- [ ] PR includes issue link, acceptance criteria, and test plan — Owner: Author
- [ ] Engineering Lead or designee performed code/design review for major changes — Owner: Engineering Lead
- [ ] Security checklist run for changes touching sensitive systems — Owner: Security Engineer
- [ ] Accessibility checks included where applicable — Owner: Accessibility Advocate / QA

## Pre-release / Deploy
- [ ] CI and security scans green — Owner: Dev / CI
- [ ] Runbook and post-deploy checks documented — Owner: SRE
- [ ] Support/CS pre-release notes prepared — Owner: Customer Success Liaison
- [ ] Legal/privacy approvals obtained (if applicable) — Owner: Legal Liaison
- [ ] PM confirms go/no-go based on acceptance criteria and risk register — Owner: PM

## Post-release / Verification
- [ ] Smoke tests and data validation executed — Owner: QA / Data Analyst
- [ ] Monitoring/alerts verified and incidents triaged — Owner: SRE
- [ ] Customer feedback loop initiated (if applicable) — Owner: Customer Success
- [ ] Retrospective item created for any process gaps — Owner: PM / Delivery Lead

Notes:
- This checklist is intentionally lightweight — adapt as needed for project size and risk.
- For cross-team dependencies, add explicit due dates and contact persons on the project board.
