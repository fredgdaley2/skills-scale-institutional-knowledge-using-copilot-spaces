# OctoAcme Project Management Docs

Welcome — this folder is the single entry point for OctoAcme's project management processes. It centralizes how we initiate, plan, execute, release, and learn from projects so teammates and contributors can quickly find what they need.

## Project Management Process Summary

OctoAcme uses an iterative, team-oriented approach with clear roles and measurable outcomes. Work moves through a lifecycle of Initiation → Planning → Execution → Release → Retrospective. Key practices include small, shippable increments, acceptance criteria and a Definition of Done, CI‑gated pull requests, and demonstrable success metrics captured up front. Roles and responsibilities are explicit — Product Managers own outcomes and prioritization, Project Managers coordinate delivery and risks, Developers implement and test, QA validates acceptance criteria, and Stakeholders provide inputs and approvals. Communication follows a predictable cadence (daily standups, delivery syncs, demos, and stakeholder updates) with a defined escalation path for blockers and business‑critical risks.

Quality is enforced throughout the process: unit/integration tests and CI gates, end‑to‑end smoke tests on critical flows, security scanning, and manual QA where needed. Progress and health are tracked via velocity/burndown, success metrics from the project one‑pager, and operational dashboards for errors, latency, and usage. Learnings are captured in retrospectives and fed back into living documentation to continuously improve practices.

## Table of Contents (program docs)

- [Project Management Overview](octoacme-project-management-overview.md) — High-level purpose, principles, lifecycle, core roles, and artifacts.
- [Project Initiation Guide](octoacme-project-initiation.md) — One‑pager template, initiation checklist, and decision gate for planning.
- [Project Planning](octoacme-project-planning.md) — Backlog templates, estimation, DoD, release planning, and dependency management.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Team rhythm, project board workflow, PR conventions, QA, and reporting.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register guidance, communication plans, and escalation procedures.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardized release workflow, verification, and announcement checklist.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — How to run retros, capture action items, and track improvements.
- [Roles and Personas](octoacme-roles-and-personas.md) — Role summaries, responsibilities, goals, and typical communication patterns.

## How to use this folder

- Read the Project Management Overview first to understand core principles and cadence.
- Use the templates and checklists in the other documents when creating or running projects.
- Add project-specific artifacts (one‑pager, charter, release plan) into your project repo and keep them updated.
- Put process updates or improvements as PRs to these docs so they can be reviewed and versioned.

## Contributing

- Follow the repository contribution guidelines. Propose doc updates via PR and link to the relevant issue (example: "Closes #2").
- When adding or changing process docs, ensure acceptance criteria and affected roles are noted.
