# OctoAcme Project Management Processes

Welcome to OctoAcme's centralized project management documentation. This README provides a concise overview of our approach and links to the detailed process guides stored in this folder.

OctoAcme runs projects through a lightweight, stage-gated lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Initiation captures the problem, success metrics, stakeholders, and a high-level timeline (Project One-pager). Planning breaks approved initiatives into shippable backlog items with acceptance criteria, identifies dependencies and risks, and defines the Definition of Done. Execution uses a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a Pull Request workflow that encourages small PRs, links issues and acceptance criteria, runs CI and security checks, and requires at least one approval before merging. Releases follow a checklist with pre-release checks, staging smoke tests, automated deployment pipelines when possible, and post-deploy verifications; rollback and incident playbooks are included for failures.

Roles and responsibilities are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate delivery, schedules, risks, and communications; Developers implement features and tests; QA validates acceptance criteria and runs manual verification when needed; Stakeholders provide inputs and approvals. Communication is structured — short daily standups for blockers and progress, weekly delivery syncs to surface risks, sprint demos/reviews, regular PM/PdM syncs, and cadence-driven stakeholder updates. A simple Risk Register and templates for weekly status and incident communications support consistent, traceable reporting and escalation.

Process documentation
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)
