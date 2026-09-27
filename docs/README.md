# OctoAcme Project Management Processes

## Overview

OctoAcme uses a customer-first, iterative project management approach for cross-functional projects that deliver product features, services, or integrations. Projects move through initiation, planning, execution, release, and retrospective, with clear ownership, measurable outcomes, and continuous learning. The process is designed to deliver small, testable increments while maintaining alignment, transparency, and psychological safety.

OctoAcme begins by validating the business need, defining SMART goals and success metrics, identifying stakeholders, and agreeing on whether an initiative should proceed to planning. Approved work is then organized into a prioritized backlog with acceptance criteria, estimates, owners, dependencies, milestones, and a shared Definition of Done. During execution, teams use a project board to track work from Backlog through Done, keep pull requests small, link them to issues, and require automated checks and review before merging.

The core personas are Product Managers, Project Managers, developers, QA/testing contributors, and stakeholders. Product Managers define outcomes and prioritize the backlog; Project Managers coordinate schedules, risks, resources, and communication; developers implement maintainable, tested solutions; QA validates quality and acceptance criteria; and stakeholders provide input and approvals. Communication follows a regular cadence of delivery standups, PM and Product Manager alignment, weekly delivery or status syncs, milestone demos, and stakeholder updates. Risks and dependencies are recorded with owners and mitigation plans, reviewed regularly, and escalated from the team to the PM, Product Lead, and sponsor when needed.

Quality is built into the full lifecycle through unit tests, integration tests where appropriate, end-to-end smoke tests for critical flows, CI linting and test checks, security scanning, manual QA when needed, and post-deployment verification. Releases require completed acceptance criteria, passing CI and security checks, release notes, smoke tests, and a rollback or mitigation plan. After each sprint, release, milestone, or incident, retrospectives capture what went well, what could improve, and a small number of owned action items so that improvements are tracked and measured over time.

## Core Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — Principles, roles, artifacts, lifecycle, and communication cadence.
- [Project Initiation](octoacme-project-initiation.md) — Validate and authorize work, align stakeholders, and establish initial goals and risks.
- [Project Planning](octoacme-project-planning.md) — Build the backlog, estimate work, define the Definition of Done, and map milestones.
- [Execution and Tracking](octoacme-execution-and-tracking.md) — Manage day-to-day delivery, project-board workflow, testing, metrics, and blocker escalation.
- [Risk Management and Communication](octoacme-risks-and-communication.md) — Maintain the risk register and coordinate stakeholder updates and incident communications.
- [Release and Deployment](octoacme-release-and-deployment.md) — Prepare, deploy, verify, and roll back releases safely.
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and track improvement actions.
- [Roles and Personas](octoacme-roles-and-personas.md) — Responsibilities, goals, and communication patterns for key personas.

## Quick Navigation by Role

- **Developers:** Start with the [overview](octoacme-project-management-overview.md), then review [roles](octoacme-roles-and-personas.md), [execution](octoacme-execution-and-tracking.md), and [release](octoacme-release-and-deployment.md).
- **Product Managers:** Use [initiation](octoacme-project-initiation.md) and [planning](octoacme-project-planning.md) to shape work, then use [execution](octoacme-execution-and-tracking.md) and [retrospectives](octoacme-retrospective-and-continuous-improvement.md) to monitor outcomes.
- **Project Managers:** Use the [overview](octoacme-project-management-overview.md) as a foundation, and refer to [risk and communication](octoacme-risks-and-communication.md), [execution](octoacme-execution-and-tracking.md), and [retrospectives](octoacme-retrospective-and-continuous-improvement.md) throughout delivery.

## Using These Docs in Copilot Spaces

Add the `docs/` directory or the specific process documents to a Copilot Space to provide context-specific guidance. The documents can help Copilot answer questions consistently about roles, planning, execution, risk management, release practices, and continuous improvement. Keep process changes versioned through the repository and propose updates using the process-document issue template in `.github/ISSUE_TEMPLATE/`.
