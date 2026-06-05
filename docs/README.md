# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Docs. This repository collects the living documentation for all key project management processes, principles, and best practices used by OctoAcme cross-functional teams.

## Project Management Processes Summary

OctoAcme operates a structured, five-phase project lifecycle designed to balance customer value delivery with clear ownership and data-informed decisions. The lifecycle flows through **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with clear acceptance criteria), **Execution** (iterative build and test cycles), **Release** (standardized deployment to production), and **Close & Retrospective** (capturing learnings for continuous improvement). This approach emphasizes iterative delivery of small, testable increments rather than big-bang releases, allowing teams to measure impact and adjust course based on evidence.

### Core Principles

The framework is grounded in five core principles:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Key Roles

Three primary personas anchor OctoAcme's delivery model:
- **Project Managers** coordinate schedules, risks, and cross-team communication
- **Product Managers** define outcomes, prioritize backlogs, and measure success
- **Developers** implement features while collaborating on design, testing, and risk mitigation

This separation of concerns ensures that execution is coordinated, product direction is clear, and technical quality is maintained.

### Communication Strategy

Communication occurs through a regular cadence:
- Weekly syncs between PM and Product Manager
- Twice-weekly standups for delivery teams
- Monthly stakeholder updates
- Ad-hoc escalations for blockers

Risk escalation follows a structured path: team-level triage in standups → PM escalation with Product Lead and dependent teams → sponsor-level involvement for business-impacting issues.

### Execution, Quality, and Release Discipline

Day-to-day execution centers on GitHub Projects boards with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and a pull request workflow emphasizing small PRs (≤400 lines), automated testing, and required approvals before merging. Quality assurance is built into the process through unit tests, integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance.

Before any release—whether patch, minor, or major—teams must confirm all acceptance criteria are met, CI and security scans pass, release notes are drafted, and rollback plans are documented. This disciplined approach to execution, testing, and release reduces production risk and ensures observability across the delivery process.

### Continuous Learning and Improvement

OctoAcme institutionalizes learning through retrospectives held after each sprint, release, or milestone. Action items are tracked in the project backlog with clear success criteria, reviewed at weekly PM syncs, and measured for impact so improvements compound over time. This commitment to continuous improvement—combined with the principle of psychological safety—creates a culture where feedback is encouraged and small, iterative changes are celebrated.

## Process Documentation Index

Explore the complete OctoAcme project management processes through these detailed guides:

- [**Project Management Overview**](octoacme-project-management-overview.md) — High-level introduction to how OctoAcme runs projects, core roles, key artifacts, and lifecycle overview
- [**Project Initiation Guide**](octoacme-project-initiation.md) — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [**Project Planning**](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog for delivery
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) — Guidance for managing day-to-day execution and tracking progress toward milestones
- [**Risk Management & Communication**](octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies
- [**Release & Deployment Guide**](octoacme-release-and-deployment.md) — Standardized approach to releasing features to production
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements
- [**Key Roles & Personas**](octoacme-roles-and-personas.md) — Detailed definitions of typical roles and responsibilities used in OctoAcme projects

## Getting Started

**For new team members:** Start with [Project Management Overview](octoacme-project-management-overview.md) to understand the big picture, then read [Key Roles & Personas](octoacme-roles-and-personas.md) to find your role.

**For project leads:** Use [Project Initiation Guide](octoacme-project-initiation.md) to kick off a new project, then follow the lifecycle documentation as your project progresses.

**For the delivery team:** Reference [Project Planning](octoacme-project-planning.md) during sprint planning, [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day work, and [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) after each milestone.

## How to Use These Docs

- Keep the Project Charter updated in your project repo
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context
- Use the issue template [Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose updates or new content
- Treat these as living documentation—update them as processes evolve and new learnings emerge