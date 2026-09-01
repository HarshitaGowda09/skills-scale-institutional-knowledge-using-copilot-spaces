# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process documentation. This folder contains comprehensive guides for managing projects across all phases of delivery, from initial concept through release and continuous improvement.

## Overview

OctoAcme follows a customer-first, iterative delivery approach built on clear ownership, psychological safety, and data-informed decisions. Our process is designed to help teams deliver value incrementally while maintaining transparency, quality, and alignment across stakeholders.

### Core Philosophy

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments frequently
- **Clear ownership**: Each project has named Project Manager and Product Lead roles
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

### Project Lifecycle

OctoAcme projects progress through five key phases:

1. **Initiation**: Validate business need, identify stakeholders, and confirm alignment
2. **Planning**: Break work into shippable increments with clear acceptance criteria
3. **Execution**: Build, test, and iterate through daily standups and structured reviews
4. **Release**: Deploy to production with standardized procedures and rollback plans
5. **Retrospective**: Capture learnings and drive continuous improvements

## Process Documentation

Each phase of the OctoAcme project lifecycle has detailed guidance:

### [Project Management Overview](./octoacme-project-management-overview.md)
A concise introduction to OctoAcme's approach, core roles, key artifacts, and communication cadence. Start here for a high-level understanding of how projects are structured.

### [Project Initiation Guide](./octoacme-project-initiation.md)
Guidance for validating new project ideas, aligning stakeholders, and preparing for planning. Includes the Project One-pager template and initiation checklist.

### [Project Planning](./octoacme-project-planning.md)
Instructions for turning approved initiatives into actionable plans and prioritized backlogs. Covers backlog creation, estimation, dependency management, and risk identification.

### [Execution & Tracking](./octoacme-execution-and-tracking.md)
Best practices for managing day-to-day delivery, maintaining team rhythm, ensuring quality, and escalating blockers. Includes the pull request workflow and execution checklist.

### [Release & Deployment Guide](./octoacme-release-and-deployment.md)
Standardized procedures for releasing features to production, including pre-release requirements, deployment checklists, and rollback playbooks.

### [Risk Management & Communication](./octoacme-risks-and-communication.md)
Guidance on identifying, assessing, and mitigating risks throughout the project. Includes stakeholder communication templates and escalation paths.

### [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
Framework for capturing learnings, running effective retrospectives, and tracking action items to drive incremental improvements.

### [Roles & Personas](./octoacme-roles-and-personas.md)
Definitions of key roles—Project Manager, Product Manager, and Developers—including responsibilities, goals, and typical communication patterns.

## Key Workflows at a Glance

### Communication Cadence
- **Daily**: Team standups (15 min) focused on progress, blockers, and dependencies
- **Twice weekly**: Delivery team standups (or as agreed)
- **Weekly**: PM + Product Lead sync on strategy and risks
- **Monthly**: Stakeholder updates
- **As needed**: Ad-hoc escalations for critical issues

### Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

### Risk Management
- Maintain a Risk Register tracking ID, description, impact, likelihood, owner, and mitigation
- Review risks at weekly syncs and update status
- Escalate high-impact risks following the escalation path: Team → PM → Product Lead → Sponsor

### Pull Request Workflow
- Keep PRs small (≤ 400 lines when possible)
- Include issue link and acceptance criteria in PR description
- Run automated tests and linting in CI before requesting review
- Require at least one approval before merging

## Getting Started

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our approach and roles.
2. **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md) to validate the idea and align stakeholders.
3. **Planning a project?** See [Project Planning](./octoacme-project-planning.md) to create your backlog and timeline.
4. **Executing a project?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) for daily practices and workflows.
5. **Preparing to release?** Review [Release & Deployment Guide](./octoacme-release-and-deployment.md) for pre-release requirements and deployment procedures.
6. **After a milestone?** Run a retrospective using [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).

## Maintaining This Documentation

Process documentation should evolve as the team learns and improves. To propose updates:

- Use the **"Add Content to Project Management Process Docs"** issue template (located in `.github/ISSUE_TEMPLATE/`)
- Describe the gap, improvement, or new content needed
- Include rationale and proposed changes
- Request review from stakeholders before merging

## Questions or Feedback?

If you have questions about these processes or suggestions for improvement, please:
- Open an issue using the process doc update template
- Reach out to your Project Manager or Product Lead
- Discuss during retrospectives and team syncs
