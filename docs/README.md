# OctoAcme Project Management Documentation

## Overview

OctoAcme is a customer-first, iterative project management methodology that emphasizes clear ownership, data-informed decisions, and psychological safety. Our approach follows a structured lifecycle from project initiation through retrospective and continuous improvement.

OctoAcme operates through five core phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with acceptance criteria), **Execution** (daily standups, sprint-based delivery, and risk management), **Release** (standardized deployment with rollback safeguards), and **Close & Retrospective** (capturing learnings for continuous improvement). This phased approach is enabled by a lightweight but rigorous set of artifacts—including project one-pagers, risk registers, release plans, and retrospective notes—that serve as the single source of truth for each initiative.

The organization emphasizes **clear role definition and accountability**. Three primary personas drive projects: **Product Managers** (PdM) define outcomes, prioritize backlogs, and measure success; **Project Managers** (PM) coordinate schedules, risks, and cross-team communication; and **Developers** implement features, collaborate on design, and help identify technical risks. This separation of concerns enables each discipline to focus on its core contribution while maintaining alignment through a consistent communication cadence: weekly PM-PdM syncs, twice-weekly standups for delivery teams, and monthly stakeholder updates.

Quality and risk management are woven throughout OctoAcme's execution model. The team maintains a **project board** (e.g., GitHub Projects) with defined columns and enforces a rigorous Definition of Done that includes unit tests, integration tests, CI validation, and security scanning before merge. **Risk registers** are actively maintained and reviewed weekly, with a three-level escalation path for blockers. Continuous improvement is built into the cadence through structured retrospectives held after sprints, releases, or significant milestones, creating a feedback loop that drives iterative refinement of both product and process.

## Quick Navigation

### Project Lifecycle Phases
- **[Project Initiation](octoacme-project-initiation.md)** — Validate business need, align stakeholders, and authorize work
- **[Project Planning](octoacme-project-planning.md)** — Break work into shippable increments and create actionable backlog
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day delivery and track progress
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize how we release features to production
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive improvements

### Cross-Cutting Guides
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme roles, principles, and artifacts
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Definitions of key roles (PM, PdM, Developers, QA)

## Key Principles
- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has named owners
- **Data-informed:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

## Getting Started
1. **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md)
2. **Starting a new project?** Follow [Project Initiation](octoacme-project-initiation.md)
3. **Planning execution?** See [Project Planning](octoacme-project-planning.md)
4. **Need clarity on roles?** Check [Roles and Personas](octoacme-roles-and-personas.md)
5. **Managing risks or communicating status?** Review [Risk Management & Communication](octoacme-risks-and-communication.md)
6. **Ready to release?** Follow [Release & Deployment](octoacme-release-and-deployment.md)
7. **Conducting a retrospective?** See [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## How to Use These Docs

- **Keep process charters and one-pagers updated** in your project repository
- **Add process-specific docs** to `.copilot/` if you want Copilot Spaces to use them as context
- **Link to these docs** in project communications, kickoff materials, and team wikis
- **Contribute improvements** via the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
