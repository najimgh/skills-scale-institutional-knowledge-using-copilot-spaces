# OctoAcme Project Management Docs

This README centralizes OctoAcme's project management process documents and provides a short summary of the practices, key workflows, and where to find more detailed guidance.

OctoAcme uses a lightweight, iterative project management approach that moves validated ideas into delivery with clear artifacts and checkpoints. Initiation begins with a Project One-pager that captures the problem statement, objectives, success metrics, stakeholders, and high-level timeline. Planning translates that one-pager into a prioritized backlog, defines a Definition of Done, and outlines a release/milestone plan with identified risks and dependencies.

During execution, teams follow a predictable rhythm—daily standups for immediate triage, weekly delivery syncs for cross-team coordination and risk review, and end-of-sprint/milestone demos for stakeholder validation. Work is tracked on a project board with stages such as Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept small and include linked issues and acceptance criteria; automated CI runs tests and linters before reviews and merging.

Roles are clearly defined to reduce ambiguity: Product Managers (PdMs) own outcomes and prioritization; Project Managers (PMs) coordinate timelines, risks, and stakeholder communications; Developers implement and test features; and QA/testing roles validate acceptance criteria. Communication is structured with regular PM+PdM alignment, frequent standups, weekly status templates, and monthly stakeholder updates. Escalation paths and incident communication templates are documented to ensure timely responses and clear ownership.

Quality assurance is enforced through layered testing and pipeline hygiene: unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when required for feature acceptance. Pre-release checks include meeting acceptance criteria, passing CI and security scans, drafting release notes, and preparing rollback plans. Retrospectives capture action items with owners and due dates, which feed back into the backlog to ensure continuous improvement.

Docs and links

- Project Management Overview — ./octoacme-project-management-overview.md
- Project Initiation Guide — ./octoacme-project-initiation.md
- Project Planning — ./octoacme-project-planning.md
- Execution & Tracking — ./octoacme-execution-and-tracking.md
- Risk Management & Communication — ./octoacme-risks-and-communication.md
- Release & Deployment Guide — ./octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — ./octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas — ./octoacme-roles-and-personas.md

Suggested usage

- Add this README to docs/ as README.md and link to it from the project root and .copilot/ if desired.
- Keep the short summaries up to date when significant process changes occur.
