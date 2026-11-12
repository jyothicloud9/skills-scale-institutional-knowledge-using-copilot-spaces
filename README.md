# OctoAcme Project Management Docs

OctoAcme manages cross-functional work through a clear lifecycle: initiation, planning, execution, release, and retrospective/continuous improvement. During initiation, the team validates the business need, defines success measures, identifies stakeholders, and creates a lightweight project one-pager with goals, milestones, risks, and resource needs. Once approved, planning breaks the work into prioritized backlog items with clear acceptance criteria, estimates, dependencies, and a release plan.

The operating model emphasizes ownership and communication. The Project Manager coordinates delivery, schedules, risk, and stakeholder updates; the Product Manager owns outcomes and prioritization; developers implement and test features; QA validates acceptance criteria and quality; and stakeholders provide input, approvals, and feedback. The team stays aligned with standups, weekly syncs, demos/reviews, and regular status updates, escalating issues through the PM, Product Lead, and sponsor when necessary.

Execution is tracked in a project board with stages such as Backlog, Ready, In Progress, In Review, QA, and Done. PRs are expected to stay small when possible, include issue links and acceptance criteria, and require review and CI validation before merge. Quality practices include unit tests, integration tests where applicable, security scanning in CI, smoke tests for critical flows, and manual QA when needed. Releases follow a controlled process with pre-deployment checks, smoke testing, post-deploy verification, release notes, and rollback planning.

After each sprint, milestone, or incident, the team captures lessons learned and converts them into action items for continuous improvement. This documentation set provides the core process guidance for running OctoAcme projects consistently and transparently.

## Process documents

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)
