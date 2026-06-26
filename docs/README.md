# OctoAcme Project Management Docs

This folder collects OctoAcme's project management process documents and provides a concise overview of how OctoAcme runs cross-functional projects. The goal is to make process guidance discoverable and easy to reference during planning, execution, reviews, and retrospectives.

OctoAcme follows a lightweight, iterative lifecycle: Initiation, Planning, Execution, Release, and Close. Projects begin with a Project One‑pager to capture the problem, objective, success metrics, stakeholders, and a high‑level timeline; a decision gate confirms readiness before planning. Planning breaks approved work into prioritized, shippable backlog items with acceptance criteria and estimates, defines the Definition of Done, captures dependencies and risks, and produces a release/milestone plan.

During execution, the team uses a visible project board (Backlog → Ready → In Progress → In Review → QA → Done) and follows a disciplined pull request workflow emphasizing small PRs, linked issues and acceptance criteria, and passing CI before review. Communication cadence includes daily standups for tactical sync, weekly delivery syncs to surface progress and risks, and scheduled demos/reviews at the end of sprints or milestones. Stakeholders are kept informed with a single source of truth (project README or release doc) and weekly status templates.

Quality gates combine automated and manual checks: unit, integration, and end‑to‑end smoke tests; security scanning in CI; and manual QA where needed. Pre-release checks require passing CI and security scans, written release notes, and a rollback/mitigation plan. Retrospectives after sprints and releases capture action items with owners and due dates and feed continuous improvement back into the backlog. Risk management is operationalized via a Risk Register and a tiered escalation path (team → PM → Product Lead → Sponsor).

## Process documents

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risks & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

## How to use

To propose additions or updates to any process document, open an issue using the "Add Content to Project Management Process Docs" template in .github/ISSUE_TEMPLATE/ (select the document to update, provide a summary and rationale, and include suggested content). Use the issue to discuss changes, then submit a PR that references the issue.

## Contact / Ownership

Each project should name a Project Manager and Product Lead. For questions about these process docs or how to apply them to a specific project, contact the project PM or create an issue in this repository.

## Acceptance Criteria (for this README)
- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)
