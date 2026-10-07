# OctoAcme Project Management Docs

OctoAcme uses a structured, customer-first approach to project management that emphasizes iterative delivery, clear ownership, data-informed decisions, and psychological safety. These guides help teams deliver customer value in small increments, stay aligned, and learn from every project.

## How OctoAcme manages projects

OctoAcme follows a five-phase lifecycle. **Initiation** validates an idea with a lightweight Project One-pager that confirms the business need, identifies stakeholders, and defines success metrics. Approved initiatives move into **Planning**, where teams break work into shippable increments, prioritize the backlog, define acceptance criteria and the Definition of Done, and identify milestones and dependencies. During **Execution & Tracking**, teams coordinate daily work on a project board with Backlog, Ready, In Progress, In Review, QA, and Done columns, supported by daily standups and weekly delivery syncs. **Release & Deployment** establishes pre-release requirements, smoke tests, production verification, and rollback plans. Finally, **Retrospective & Continuous Improvement** turns lessons from each sprint, release, or milestone into prioritized actions tracked in the backlog.

The process shares accountability across clearly defined roles. The **Product Manager (PdM)** sets outcomes, prioritizes work, and measures results; the **Project Manager (PM)** coordinates schedules, delivery, risks, and communications; **Developers** design and implement features while maintaining code quality; **QA/Testing** validates acceptance criteria and quality standards; and **Stakeholders** provide input and approvals. Communication follows a consistent cadence: 15-minute daily standups focus on progress and blockers, PM–PdM alignment happens weekly, delivery teams meet twice weekly, and stakeholders receive monthly updates. Teams escalate issues through the path **Team → PM → Product Lead → Sponsor**, with ad-hoc escalation as needed.

Quality is built into delivery through unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, CI security scanning, and manual QA when needed. Pull requests should be small (≤400 lines when possible), include issue links and acceptance criteria, and receive at least one approval before merging. Risks are identified throughout planning and execution, assessed by impact and likelihood, and tracked in a Risk Register with mitigation plans and owners. Teams mark dependencies and cross-team integrations on the project board and review or escalate them during weekly syncs.

OctoAcme uses evidence and transparent communication to guide decisions. Teams track velocity, burndown, and Project One-pager success metrics, and use dashboards to monitor errors, latency, and usage. Weekly status updates cover progress, next steps, risks and blockers, and decisions needed; incident communication is timely and transparent. Each project keeps a central set of artifacts—including its charter, roadmap, sprint backlog, acceptance criteria, risk register, and retrospective notes—as a single source of truth. Retrospectives last 45–75 minutes and capture 2–3 prioritized actions with owners and due dates, so teams can measure outcomes and improve their processes over time.

## Process documentation

| Guide | Purpose |
| --- | --- |
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, lifecycle, core roles, and key project artifacts |
| [Project Initiation](octoacme-project-initiation.md) | Validate an idea, align stakeholders, and decide whether to proceed |
| [Project Planning](octoacme-project-planning.md) | Shape an approved initiative into a prioritized, actionable delivery plan |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Coordinate day-to-day work, progress, quality, and blockers |
| [Risks & Communication](octoacme-risks-and-communication.md) | Maintain the Risk Register, communicate status, and escalate issues |
| [Release & Deployment](octoacme-release-and-deployment.md) | Prepare, deploy, verify, and if necessary roll back a release |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and track improvement actions |
| [Roles & Personas](octoacme-roles-and-personas.md) | Understand the responsibilities and communication needs of each role |

## Quick navigation

- **Starting a new idea?** Begin with [Project Initiation](octoacme-project-initiation.md).
- **Turning an approved idea into delivery work?** Use [Project Planning](octoacme-project-planning.md).
- **Managing active work, blockers, or testing?** See [Execution & Tracking](octoacme-execution-and-tracking.md).
- **Handling risks, dependencies, or stakeholder updates?** Go to [Risks & Communication](octoacme-risks-and-communication.md).
- **Preparing a production release?** Follow [Release & Deployment](octoacme-release-and-deployment.md).
- **Capturing lessons or improving team practices?** Use [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).
- **Clarifying responsibilities or project-wide principles?** Read [Roles & Personas](octoacme-roles-and-personas.md) or the [Project Management Overview](octoacme-project-management-overview.md).
