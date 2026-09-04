# OctoAcme Project Management Docs

## Overview

OctoAcme uses a structured, customer-first approach to project management that emphasizes iterative delivery, clear ownership, and data-informed decisions. All projects follow a consistent lifecycle: Initiation → Planning → Execution → Release → Close & Retrospective.

## Project Management Processes Summary

**Project Lifecycle & Workflows**

OctoAcme follows a structured five-phase project lifecycle designed to deliver customer value through iterative, measurable increments. Projects progress through Initiation (where problems are validated and stakeholders aligned), Planning (where work is broken into shippable backlog items with clear acceptance criteria), Execution (day-to-day delivery with standups and pull request reviews), Release (deployment to production with pre-flight checks and rollback plans), and Close & Retrospective (capturing learnings and continuous improvements). The framework emphasizes breaking work into small, testable increments (PRs ≤ 400 lines when possible) and maintaining a prioritized backlog managed through project boards with consistent workflow columns: Backlog, Ready, In Progress, In Review, QA, and Done.

**Clear Ownership & Roles**

Three core personas drive OctoAcme projects: Project Managers coordinate delivery schedules, manage risks, and maintain stakeholder communication; Product Managers define outcomes, prioritize the backlog, and measure success against data-driven metrics; and Developers implement features while contributing to design, testing, and risk identification. Each project has named ownership for both PM and Product Lead roles, with a commitment to psychological safety and collaborative decision-making. Supporting roles include QA/Testing teams responsible for validating quality and acceptance criteria, and designated Stakeholders who provide inputs and approvals at key gates.

**Communication & Risk Management**

OctoAcme maintains a structured communication cadence including daily standups (15 minutes focused on progress and blockers), weekly syncs between PM and Product Manager, twice-weekly delivery team standups, and monthly stakeholder updates. A three-level escalation path—from team-level triage in standups, to PM escalation to Product Lead, to sponsor-level escalation—ensures risks are surfaced and managed transparently. Risk registers are maintained throughout projects with Impact, Likelihood, Owner, and Mitigation tracked, and key dependencies are marked on project boards. Weekly status updates follow a consistent template covering progress, next steps, risks/blockers, and decisions needed.

**Quality Assurance & Continuous Improvement**

Quality is built into every stage: during Execution, teams run automated CI tests, linting, and security scanning before requesting PR review (requiring at least one approval). Testing includes unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, and manual QA for feature acceptance when needed. After each sprint, release, or milestone, OctoAcme conducts retrospectives (45–75 minutes) to capture what went well, identify improvements, and assign 2–3 prioritized action items with clear owners and due dates. This continuous improvement culture measures impact of changes and iterates based on evidence, feeding validated improvements back into process documentation and team practices.

## Quick Start

New to OctoAcme projects? Start here:

1. Read the [Project Management Overview](octoacme-project-management-overview.md) for key principles and roles
2. Follow the [Project Initiation Guide](octoacme-project-initiation.md) to kick off a new project
3. Use the [Project Planning](octoacme-project-planning.md) guide to create your backlog and timeline
4. Refer to [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day workflows

## Process Documentation

### Core Documents

- **[Project Management Overview](octoacme-project-management-overview.md)** — Introduction to OctoAcme principles, roles, and key artifacts
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Definitions of Project Manager, Product Manager, Developer, and other roles

### Project Lifecycle Phases

- **[Project Initiation](octoacme-project-initiation.md)** — Validate ideas, align stakeholders, create project charter
- **[Project Planning](octoacme-project-planning.md)** — Break work into backlog items, estimate, define DoD, identify dependencies
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day workflows, standups, PR process, quality standards
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Pre-release checks, deployment process, rollback procedures
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, drive improvements

### Cross-cutting Guides

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk registers, escalation paths, stakeholder communication templates

## Document Navigation by Phase

| Phase | Primary Documents |
|-------|------------------|
| **Initiation** | Project Initiation, Project Management Overview |
| **Planning** | Project Planning, Risk Management & Communication |
| **Execution** | Execution & Tracking, Roles & Personas |
| **Release** | Release & Deployment, Risk Management & Communication |
| **Close & Learn** | Retrospective & Continuous Improvement |

## Contributing to Process Docs

To suggest updates or add new content to these process documents, please create an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
