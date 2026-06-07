# OctoAcme Project Management Docs

## Overview

This README introduces the core project management lifecycle, roles, and principles used by OctoAcme, and provides links to detailed process documentation. It serves as a single, accessible starting point for team members and stakeholders to understand how OctoAcme manages projects and to access all process documentation.

## Summary of Project Management Processes

OctoAcme employs a comprehensive, lifecycle-driven project management approach centered on five key phases: **Initiation, Planning, Execution, Release, and Retrospective**. The methodology prioritizes customer value, iterative delivery, and data-informed decision-making.

**Initiation & Planning:** Projects begin with a lightweight initiation phase where stakeholders validate business need and define success metrics through a Project One-pager, ensuring clear alignment before committing resources. This gates entry into the planning phase, where work is broken into shippable increments with acceptance criteria, dependencies are mapped, and a Definition of Done is established to maintain quality standards throughout delivery.

**Execution & Tracking:** Execution and tracking rely on a structured team rhythm and transparent project boards. Daily standups (15 minutes) focus on progress and blockers, while weekly delivery syncs with the Product Manager and Project Manager review burndown, metrics, and flagged risks. The workflow emphasizes small, reviewable pull requests (≤400 lines), automated CI/CD testing and linting, and at least one approval before merging. Quality is embedded through unit and integration testing, end-to-end smoke tests for critical flows, and security scanning in CI.

**Release & Continuous Improvement:** Release and deployment follow a standardized, risk-reducing process with pre-release requirements including passing CI, completed acceptance criteria, drafted release notes, and documented rollback plans. Retrospectives after each sprint or milestone capture learnings and convert them into prioritized action items, fostering a culture of continuous improvement.

**Core Principles:**
- Customer-first focus on delivering value and usability
- Iterative, evidence-based delivery with small, testable increments
- Clear accountability with named Project Managers, Product Managers, and team ownership
- Data-informed decisions and impact measurement
- Psychological safety encouraging feedback and learning

**Core Roles:**
- **Project Manager (PM):** Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM):** Defines outcomes, prioritizes backlog, and measures success
- **Developers:** Implement features, collaborate on design and testability
- **QA/Testing:** Validate quality and acceptance criteria
- **Stakeholders:** Provide inputs and approvals

**Risk & Communication:** Risk management is central throughout all phases—risks are identified, assessed for impact and likelihood, mitigated through documented plans, and monitored weekly. A single source of truth (project README, risk register, and decision log) enables stakeholders across engineering, sales, and support to stay aligned through weekly status updates and ad-hoc escalations.

---

## Process Documentation

Click any link below to access detailed process guidance:

| Phase | Document |
|-------|----------|
| **Overview & Principles** | [Project Management Overview](./octoacme-project-management-overview.md) |
| **Initiation** | [Project Initiation Guide](./octoacme-project-initiation.md) |
| **Planning** | [Project Planning](./octoacme-project-planning.md) |
| **Execution & Tracking** | [Execution & Tracking](./octoacme-execution-and-tracking.md) |
| **Risk & Communication** | [Risk Management & Communication](./octoacme-risks-and-communication.md) |
| **Release & Deployment** | [Release & Deployment Guide](./octoacme-release-and-deployment.md) |
| **Retrospectives** | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) |
| **Roles & Personas** | [Roles & Personas](./octoacme-roles-and-personas.md) |

---

## How to Use These Docs

- **New team members:** Start here to understand OctoAcme's project approach, then review role-specific docs.
- **Project leads:** Use the Initiation and Planning guides when kicking off a new project.
- **Delivery teams:** Reference Execution & Tracking and Risk Management during sprints.
- **Release managers:** Follow the Release & Deployment guide when preparing production deployments.
- **Retrospective facilitators:** Use the Retrospective & Continuous Improvement guide to run effective post-project reviews.

Keep the Project Charter updated in your project repo and add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context for AI-assisted guidance.
