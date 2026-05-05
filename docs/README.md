# OctoAcme Project Management Docs

This folder contains the program and project process documentation for OctoAcme. It serves as the central reference for how the team initiates, plans, executes, releases, and continuously improves its work. Whether you are a new teammate getting up to speed or a stakeholder looking for a process reference, start here.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a lightweight, repeatable project lifecycle designed to deliver customer value through iterative increments. Work moves through five phases: **Initiation** (clarify the problem statement, identify stakeholders, define success metrics, and make a go/no-go decision), **Planning** (convert the initiative into an actionable backlog and release plan with dependencies and milestones identified), **Execution** (build and track progress through regular delivery rhythms using a project board with columns such as Backlog, Ready, In Progress, In Review, QA, and Done), **Release** (deploy with standard safeguards, release notes, and rollback plans), and **Close & Retrospective** (capture learnings and feed improvements back into the backlog). Key artifacts include a project charter, roadmap and release plan, sprint backlog with acceptance criteria, a risk register, and retrospective action items.

Roles are clearly defined to ensure accountability across the full lifecycle. A **Project Manager (PM)** coordinates delivery, schedules, risks, and stakeholder communications. A **Product Manager (PdM)** defines outcomes, prioritizes the backlog, and measures success against defined metrics. **Developers** design and implement features with appropriate tests and documentation. **QA/Testing** validates quality and acceptance criteria before release. **Stakeholders** provide inputs and approvals at key decision points. These personas are referenced throughout the process docs to clarify responsibilities and expected collaboration patterns, particularly during planning, definition of done, and release readiness reviews.

Day-to-day execution is supported by consistent team rhythms and transparent communication. OctoAcme uses standups and delivery syncs for the team alongside monthly stakeholder updates, with explicit escalation paths for blockers (team triage → PM/Product Lead → sponsor-level escalation when business impact requires it). Risks and dependencies are tracked in a continuously maintained risk register and reviewed during weekly syncs, ensuring a single source of truth. Templates and status-update cadences keep communication clear and predictable.

Quality assurance and release practices are embedded throughout delivery rather than treated as a final gate. New logic is covered by unit tests, with integration and end-to-end smoke tests used for critical flows. CI pipelines run automated tests, linting, and security scans before changes are merged, and releases require passing all checks, drafted release notes, and an approved rollback or mitigation plan. After each sprint, release, or incident, OctoAcme runs retrospectives to identify what worked, what to improve, and to create a small set of owned, trackable action items — reinforcing a culture of continuous improvement.

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's project management principles, core roles, key artifacts, lifecycle stages, and communication cadence. |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps and templates for kicking off a new project, including problem framing, stakeholder identification, and go/no-go criteria. |
| [Project Planning](octoacme-project-planning.md) | Guidance on converting an approved initiative into a scoped backlog, release plan, milestones, and resource plan. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Practices for running sprints, managing the project board, tracking progress, and handling day-to-day delivery decisions. |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register approach, escalation paths, communication templates, and stakeholder update cadences. |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Release readiness checklist, deployment steps, release notes standards, and rollback/incident handling procedures. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective formats, facilitation guidance, action item tracking, and continuous improvement practices. |
| [Roles and Personas](octoacme-roles-and-personas.md) | Definitions of the key personas (Developer, Product Manager, Project Manager) used throughout OctoAcme process docs. |

---

For details, see the individual documents in the [`docs/`](./) folder.
