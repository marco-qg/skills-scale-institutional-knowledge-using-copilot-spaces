# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It covers both core delivery roles and extended cross-functional personas commonly involved in larger or regulated projects. Clear role definitions improve accountability, hand-off clarity, and onboarding effectiveness across teams.

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

## Sponsor

### Role Summary
The Sponsor is the executive-level business champion who owns the project mandate. They secure funding, remove organizational blockers, and provide the escalation authority needed to keep the project moving when cross-functional alignment breaks down.

### Responsibilities
- Approve project charter, scope, and budget
- Remove organizational blockers that the PM cannot resolve
- Serve as the primary escalation point for high-impact decisions
- Communicate project importance and progress to executive leadership
- Ensure the project aligns with organizational strategy

### Goals
- Protect the business investment and ensure expected returns
- Enable the team to operate without bureaucratic friction
- Maintain executive confidence in project outcomes

### Typical Communication
- Bi-weekly or monthly executive briefings from the Project Manager
- Escalation notifications for scope changes, budget overruns, or critical risks
- Sign-off on major milestones and go/no-go decisions

---

## Subject Matter Expert (SME)

### Role Summary
Subject Matter Experts bring specialized domain knowledge that the core delivery team may lack. They advise on technical, regulatory, or business-specific topics to ensure the solution is accurate, feasible, and fit for purpose.

### Responsibilities
- Provide domain expertise during requirements gathering and design
- Review deliverables for correctness and domain accuracy
- Advise on edge cases, constraints, and best practices within their domain
- Participate in validation and acceptance testing as needed
- Transfer knowledge to the team to reduce ongoing dependency

### Goals
- Ensure the solution correctly addresses domain-specific needs
- Reduce errors and rework caused by knowledge gaps
- Enable the core team to operate more independently over time

### Typical Communication
- Scheduled consultations during planning and design phases
- Ad-hoc reviews requested by the Product Manager or Technical Lead
- Written guidance documents or annotated specifications

---

## Technical Lead

### Role Summary
The Technical Lead is the architect and senior engineering mentor for the project. They validate the technical approach, guide design decisions, and support developers in delivering a coherent, maintainable solution.

### Responsibilities
- Define and validate the overall technical architecture
- Make key technology and design decisions in collaboration with the team
- Review technical designs, proposals, and critical pull requests
- Identify and mitigate technical risks early
- Mentor developers and support their growth

### Goals
- Deliver a technically sound and maintainable solution
- Minimize technical debt and architectural inconsistencies
- Enable developers to work efficiently within a clear technical direction

### Typical Communication
- Technical design reviews and architecture decision records (ADRs)
- Code review feedback and pairing sessions with developers
- Regular syncs with the Project Manager and Product Manager on technical trade-offs

---

## UX/UI Designer

### Role Summary
The UX/UI Designer is responsible for the user experience strategy and visual design of the product. They translate user needs and business requirements into intuitive flows and interfaces, working closely with the Product Manager and developers.

### Responsibilities
- Conduct user research and synthesize insights into design requirements
- Create wireframes, prototypes, and high-fidelity designs
- Define user flows and interaction patterns
- Collaborate with developers to ensure accurate implementation of designs
- Participate in usability testing and iterate based on feedback

### Goals
- Create experiences that are intuitive, accessible, and aligned with user needs
- Reduce friction between design intent and implemented output
- Ensure consistent visual and interaction language across the product

### Typical Communication
- Design reviews and prototype walkthroughs with Product Manager and developers
- Handoff documentation and annotated design specs
- Usability test reports and design iteration notes

---

## Operations/Support

### Role Summary
The Operations/Support representative ensures the solution is operationally ready when it reaches production. They advise on infrastructure, monitoring, and supportability concerns throughout the project, and prepare the runbooks and tooling needed for day-to-day operations.

### Responsibilities
- Advise on operational requirements, infrastructure constraints, and monitoring needs
- Review release plans for operational readiness
- Author and maintain runbooks and escalation procedures
- Coordinate go-live readiness checks and post-release support coverage
- Provide feedback on support burden and incident patterns to improve future iterations

### Goals
- Ensure smooth, low-incident deployments and stable production operations
- Reduce time-to-resolution for operational incidents
- Build shared understanding of operational requirements early in the project

### Typical Communication
- Participation in release readiness reviews with the Project Manager and QA
- Runbook reviews shared with the development team before release
- Post-release incident summaries and lessons-learned feedback

---

## Compliance Officer

### Role Summary
The Compliance Officer ensures the project adheres to applicable regulatory, legal, and governance requirements. They engage at key milestones to review documentation, processes, and deliverables for adherence to internal policies and external regulations.

### Responsibilities
- Identify applicable regulatory and compliance requirements for the project
- Review project documentation, processes, and deliverables for compliance gaps
- Advise the team on required controls, data handling policies, and audit trails
- Approve or flag deliverables that must meet specific regulatory standards
- Maintain compliance documentation and support audits as needed

### Goals
- Prevent regulatory violations and associated business risks
- Ensure compliance requirements are understood and addressed early, not retrofitted
- Support a culture of governance awareness across the project team

### Typical Communication
- Structured compliance reviews at project initiation, before release, and at major scope changes
- Written assessments and sign-offs shared with the Project Manager and Sponsor
- Advisory input into risk registers when compliance risks are identified

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Role Interaction Matrix

This matrix summarizes how personas communicate and depend on each other across the project lifecycle. It is intended to clarify hand-offs, reduce gaps, and set expectations for cross-functional coordination.

| Role | Key Interactions | Primary Hand-offs |
|---|---|---|
| **Sponsor** | Project Manager (escalation, milestone approvals), Product Manager (strategic alignment), Compliance Officer (governance sign-off) | Project charter approval → Project Manager; Budget decisions → Project Manager & Product Manager |
| **Product Manager** | Sponsor (strategy), Project Manager (delivery alignment), UX/UI Designer (requirements), Developers (backlog), SME (domain validation) | Prioritized backlog → Project Manager & Developers; Acceptance criteria → QA |
| **Project Manager** | All roles (coordination hub), Sponsor (status, escalation), Compliance Officer (risk register), Operations/Support (release readiness) | Project plan → all; Risk register → Sponsor; Release checklist → Operations/Support |
| **Developers** | Technical Lead (architecture, code review), UX/UI Designer (design handoff), QA (acceptance), Project Manager (planning) | Code & documentation → QA; Technical risks → Technical Lead |
| **Technical Lead** | Developers (mentoring, reviews), Product Manager (trade-offs), Project Manager (technical risk), SME (domain accuracy) | Architecture decisions → Developers; Technical risk items → Project Manager |
| **UX/UI Designer** | Product Manager (requirements), Developers (design handoff), SME (domain accuracy), QA (usability testing) | Design specs & prototypes → Developers; Usability findings → Product Manager |
| **SME** | Product Manager (requirements), Technical Lead (design validation), Compliance Officer (domain regulations), QA (acceptance) | Domain guidance → Product Manager & Technical Lead; Compliance input → Compliance Officer |
| **Operations/Support** | Project Manager (release readiness), Developers (infrastructure requirements), QA (deployment validation) | Runbooks → all; Operational requirements → Developers & Project Manager |
| **Compliance Officer** | Project Manager (risk register), Sponsor (governance sign-off), SME (regulatory domain), Product Manager (requirements) | Compliance assessments → Project Manager & Sponsor; Required controls → Product Manager & Technical Lead |

