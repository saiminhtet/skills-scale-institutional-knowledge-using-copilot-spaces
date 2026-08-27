# OctoAcme Project Management Documentation

## Overview
OctoAcme follows a lightweight, outcome-focused project management approach that emphasizes customer value, iterative delivery, and clear ownership. Every initiative begins with a concise one-pager that defines the problem, measurable success criteria, stakeholders, and an initial timeline. Projects move through a simple lifecycle—Initiation → Planning → Execution → Release → Retrospective—with minimum artifacts and decision gates to reduce ambiguity and speed alignment.

## Key workflows
Planning turns approved initiatives into a prioritized, estimated backlog with acceptance criteria and a Definition of Done. Execution uses a project board with columns (Backlog, Ready, In Progress, In Review, QA, Done) and a Pull Request workflow that favors small PRs, automated CI checks, and at least one approval before merge. Releases are classified (patch, minor, major) and require pre-release checks, smoke tests, rollback plans, and post-deploy verifications.

## Personas & communication
Core roles are defined so responsibilities and handoffs are explicit: Project Manager (delivery coordination, risk, communications), Product Manager (vision, prioritization, success metrics), Developers (implementation and tests), QA (validation), and Stakeholders (inputs and approvals). Team rhythm includes daily standups to surface blockers, weekly delivery syncs for progress and risks, regular demos, and monthly stakeholder updates. Escalation paths and incident communication templates are documented to ensure timely, clear notifications for outages or business-impacting issues.

## Quality & continuous improvement
Quality is enforced through automated testing (unit, integration, and security scans) in CI, manual QA where needed, and end-to-end smoke tests for critical flows. Risk management uses a simple risk register tracked during weekly syncs with clear mitigation owners. Retrospectives after sprints, releases, and incidents capture action items that are added to the backlog and tracked to completion to drive continuous improvement.

## Documentation index
- Getting started / overview
  - [Project Management Overview](./octoacme-project-management-overview.md) — High-level approach, principles, and key artifacts
  - [Roles and Personas](./octoacme-roles-and-personas.md) — Detailed role responsibilities and communication patterns
- Project lifecycle
  - [Project Initiation](./octoacme-project-initiation.md) — One-pager, decision gate, and initiation checklist
  - [Project Planning](./octoacme-project-planning.md) — Backlog, estimates, and release planning
  - [Execution & Tracking](./octoacme-execution-and-tracking.md) — Team rhythm, PR workflow, and execution checklist
  - [Release & Deployment](./octoacme-release-and-deployment.md) — Release types, pre-release checks, and rollback playbook
  - [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure and action item tracking
- Cross-cutting
  - [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk register, escalation, and stakeholder templates

## Getting started
1. Start with the Project Management Overview to understand principles and lifecycle.
2. Use the lifecycle docs in sequence as your project progresses.
3. Keep the Project One-pager and Project Charter updated in your project repo.
4. Add action items from retrospectives to the backlog and review them in weekly PM syncs.
