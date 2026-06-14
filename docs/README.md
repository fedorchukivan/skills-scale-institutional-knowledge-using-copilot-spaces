# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documents. The goal of these documents is to make project practices discoverable, repeatable, and easy to apply across teams. Use this README as a single place to find process guidance, role definitions, checklists, and links to the full documents stored in this directory.

OctoAcme follows an iterative, customer-first lifecycle that moves work from initiation to planning, execution, release, and continuous improvement. Initiation captures the problem statement, stakeholders, and success metrics using a Project One-pager. Planning turns approved initiatives into a prioritized backlog with estimates, acceptance criteria, and a Definition of Done to ensure clarity before work begins. Execution emphasizes small, reviewable work items, daily standups, and a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) that keeps teams aligned on status and dependencies.

Workflows emphasize quality and predictability. Pull requests should be small, include linked issues and acceptance criteria, and pass CI (tests, lint, and security scans) before review. Quality practices include unit and integration tests, targeted end-to-end smoke tests for critical flows, and manual QA where needed. Releases follow a pre-release checklist (acceptance criteria met, release notes, rollback plan) and a deployment checklist that includes staging verification and post‑deploy checks.

Roles and communication are explicit to reduce ambiguity: Project Managers coordinate delivery and risks; Product Managers define outcomes and prioritize work; developers implement and test; QA validates acceptance criteria; and stakeholders provide approvals and inputs. Communication cadence includes daily standups, weekly delivery syncs, PM–PdM alignment, monthly stakeholder updates, and documented escalation paths for blockers and incidents. Retrospectives and a living risk register ensure continuous improvement and that lessons learned are converted into tracked action items.

## Docs (links)

- [Project Management Overview](docs/octoacme-project-management-overview.md) — concise introduction to approach, roles, and artifacts.  
- [Project Initiation Guide](docs/octoacme-project-initiation.md) — steps to validate and authorize new initiatives.  
- [Project Planning](docs/octoacme-project-planning.md) — turning approved initiatives into actionable plans.  
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md) — day-to-day execution and tracking guidance.  
- [Risks & Communication](docs/octoacme-risks-and-communication.md) — managing risk register and stakeholder communication.  
- [Release & Deployment](docs/octoacme-release-and-deployment.md) — release types, checklists, and playbooks.  
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md) — running retrospectives and tracking improvements.  
- [Roles & Personas](docs/octoacme-roles-and-personas.md) — role definitions and responsibilities used across OctoAcme.

## How to use

- Add this README to docs/ (this file) and keep links up to date when files are added or renamed.  
- Refer to each document for templates, checklists, and step-by-step guidance during project initiation, planning, execution, release, and retrospectives.  
- Use the issue template `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to request updates to these process documents.

## Proposed filename and location

- docs/README.md
