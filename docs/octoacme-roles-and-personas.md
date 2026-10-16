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

## Technical Program Manager (TPM)

### Role Summary
The TPM owns cross-team technical coordination for complex initiatives, aligning engineering roadmaps, tracking technical dependencies, and facilitating architecture and design decisions.

### Responsibilities
- Identify and track cross-team technical dependencies and risks
- Coordinate architecture/design discussions and trade-offs
- Maintain a consolidated technical timeline and dependency map
- Facilitate decisions between engineering teams and product stakeholders

### Decision Authority
- Can escalate technical conflicts and propose sequencing options; final architecture/technical decisions remain with the appropriate Tech Lead or architecture board.

### Typical Deliverables
- Dependency maps, technical milestones, meeting notes, and decision logs

### Primary Handoffs / Interactions
- Receives high-level objectives from PM/PdM; works with Tech Leads, EMs, Release Manager to sequence work and deconflict dependencies.

---

## Engineering Manager (EM) / Tech Lead (EM / Tech Lead)

### Role Summary
Clarified split: EM focuses on people management, staffing, and capacity; Tech Lead owns solution design, technical decisions, and code-level acceptance.

### Responsibilities (EM)
- Manage team staffing, growth, and performance
- Coordinate capacity planning and hiring needs
- Remove organizational or resource blockers

### Responsibilities (Tech Lead)
- Own solution design, technical approaches, and design reviews
- Ensure code quality and architectural coherence
- Mentor team members on design and implementation

### Decision Authority
- EM: staffing and people-related decisions; Tech Lead: technical solution decisions within the scope of the project.

### Typical Deliverables
- Team capacity plans (EM), technical designs and design reviews (Tech Lead)

### Primary Handoffs / Interactions
- EM interacts with PM for capacity and delivery commitments; Tech Lead interacts with Developers, QA, and TPM for design acceptance and implementation feasibility.

---

## Delivery Lead

### Role Summary
Focused on day-to-day delivery coordination: sprint-to-sprint planning, task-level coordination, and blocking removal.

### Responsibilities
- Manage sprint execution and ensure stories meet DoD
- Track and remove blockers, smooth capacity distribution
- Maintain sprint board health and readiness of work items

### Decision Authority
- Prioritize day-to-day task sequencing within the sprint in collaboration with the team.

### Typical Deliverables
- Sprint plan, daily status updates, impediment logs

### Primary Handoffs / Interactions
- Works closely with PM, Scrum Master (if present), Developers, and QA to keep deliverables on track.

---

## Product Designer / UX Researcher

### Role Summary
Owns user experience decisions, prototypes, and acceptance of design criteria; ensures solutions are usable and validated.

### Responsibilities
- Run user research, create prototypes, and define UX acceptance criteria
- Provide design specifications and collaborate on implementation
- Validate usability post-release and iterate on designs

### Decision Authority
- Decision authority on UX direction and acceptance related to user experience; coordinates with PdM on priority.

### Typical Deliverables
- Wireframes, prototypes, design specs, research summaries

### Primary Handoffs / Interactions
- Collaborates with PdM during planning, hands off designs to Developers and Tech Leads, and reviews implementations with QA.

---

## Data Analyst / Measurement Owner

### Role Summary
Defines success metrics, instrumentation needs, and validates release impact through analytics and dashboards.

### Responsibilities
- Define measurement strategy and acceptance criteria for success metrics
- Specify instrumentation and tracking requirements
- Validate post-release data and produce impact analysis

### Decision Authority
- Owns the correctness and interpretation of measurement definitions and reporting.

### Typical Deliverables
- Metrics definitions, instrumentation specs, dashboards, post-release analysis

### Primary Handoffs / Interactions
- Works with PdM to define metrics, Engineers to implement instrumentation, and PM to confirm release readiness.

---

## Release Manager / SRE Liaison

### Role Summary
Owns deploy readiness, runbooks, rollback plans, and post-deploy verification; liaises with SRE/Platform teams.

### Responsibilities
- Validate deployment readiness and runbook completeness
- Coordinate staging and production deployments and verification steps
- Own rollback procedures and post-deploy verification

### Decision Authority
- Can hold a release if pre-release checks fail; works with PM and PdM to reschedule if needed.

### Typical Deliverables
- Deployment runbooks, rollback plans, post-deploy checklists

### Primary Handoffs / Interactions
- Coordinates with DevOps/Platform Engineers, QA, PM, and Support before and after deployment.

---

## Security & Compliance Owner

### Role Summary
Reviews changes for security or regulatory impact, owns security sign-offs, and coordinates scans and remediations.

### Responsibilities
- Review designs and code for security and compliance implications
- Define and track remediation for security findings
- Coordinate security sign-off before production deployment

### Decision Authority
- Can require security remediation or additional review before release for compliance-sensitive work.

### Typical Deliverables
- Security review notes, compliance checklists, remediation plans

### Primary Handoffs / Interactions
- Works with PM, EM, Tech Leads, and SRE to address and close security issues.

---

## Customer Success / Support Representative

### Role Summary
Represents customer operational needs and feedback, informs rollout planning, and helps craft communication and runbooks.

### Responsibilities
- Provide customer impact context and operational constraints
- Help create support runbooks and customer communications
- Raise known customer issues or special cases to the team

### Decision Authority
- Provides customer-facing guidance and approves support communications.

### Typical Deliverables
- Support runbooks, release communications, customer impact summaries

### Primary Handoffs / Interactions
- Works with PM and Release Manager to prepare customer-facing materials and with Support/Engineering for operational concerns.

---

## Knowledge Manager / Documentation Owner

### Role Summary
Ensures process docs, runbooks, and handoff notes are authored, maintained, and discoverable; coordinates updates to docs/ and .copilot/ for Copilot Spaces.

### Responsibilities
- Maintain and curate process documentation and runbooks
- Ensure documentation is discoverable and up-to-date
- Coordinate documentation updates tied to releases and retrospectives

### Decision Authority
- Sets documentation standards and determines readiness of docs for handoffs and onboarding.

### Typical Deliverables
- Updated process docs, runbooks, onboarding notes, and documentation checklists

### Primary Handoffs / Interactions
- Works with PMs, TPMs, Release Manager, and Developers to capture decisions, runbooks, and how-to guides.

---
