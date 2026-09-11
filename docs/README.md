# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management Documentation. This folder contains comprehensive guidance for running projects across OctoAcme, designed to help teams deliver customer value efficiently, consistently, and with psychological safety.

## Purpose

This documentation centralizes OctoAcme's project management knowledge, providing:
- Clear frameworks for each phase of the project lifecycle
- Role definitions and responsibilities
- Templates and checklists for consistent execution
- Risk management and communication strategies
- A common language across teams

## Project Lifecycle Overview

OctoAcme projects follow these key phases:

### 1. **Initiation** – Validate & Authorize
Confirm business need, align stakeholders, and create a lightweight project charter. Output: Project One-pager with problem statement, goals, success metrics, and initial resource estimates.

### 2. **Planning** – Structure & Prepare
Break work into shippable increments, identify dependencies, and build the actionable backlog. Output: Prioritized backlog, release plan, and risk register.

### 3. **Execution & Tracking** – Build & Measure
Manage day-to-day delivery, maintain team rhythm through standups and demos, and track progress against metrics. Output: Completed features, quality assurance, and velocity data.

### 4. **Release & Deployment** – Ship Safely
Standardize how features reach production, manage rollback plans, and announce changes to stakeholders. Output: Deployed feature, release notes, and post-deployment verification.

### 5. **Retrospective & Continuous Improvement** – Learn & Iterate
Capture learnings from the project, identify improvements, and feed action items back into future planning. Output: Retrospective notes and improvement backlog.

## Core Principles

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Ship small, testable increments to reduce risk and enable feedback
- **Clear ownership**: Each project has named Project Manager (PM) and Product Lead accountable for delivery
- **Data-informed**: Measure impact and iterate based on evidence, not assumptions
- **Psychological safety**: Encourage feedback, learning, and honest communication

## Core Roles at a Glance

| Role | Responsibility | Key Outputs |
|------|---|---|
| **Project Manager (PM)** | Coordinates delivery, manages schedules, risks, and stakeholder communication | Project plan, risk register, status updates |
| **Product Manager (PdM)** | Defines outcomes, prioritizes backlog, validates solutions and success metrics | Backlog, success metrics, prioritized roadmap |
| **Developers** | Implement features, write tests and documentation, collaborate on design and quality | Code, pull requests, test coverage |
| **QA/Testing** | Validate quality against acceptance criteria and test plans | Test results, quality reports |
| **Stakeholders** | Provide inputs, approvals, and executive alignment | Feedback, decisions, resource allocation |

See [Roles & Personas](octoacme-roles-and-personas.md) for detailed responsibility definitions.

## Quick Links to Process Docs

### Foundational Guides
- **[Project Management Overview](octoacme-project-management-overview.md)** – Start here for a high-level introduction to OctoAcme's approach, principles, and key artifacts
- **[Roles & Personas](octoacme-roles-and-personas.md)** – Understand team responsibilities and typical communication patterns

### Project Phases
- **[Project Initiation Guide](octoacme-project-initiation.md)** – How to kick off a new project with stakeholder alignment and a one-pager
- **[Project Planning](octoacme-project-planning.md)** – Breaking down work, estimating, and building the delivery roadmap
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** – Daily standups, sprint workflows, quality practices, and metrics
- **[Release & Deployment](octoacme-release-and-deployment.md)** – Pre-release requirements, deployment checklist, and rollback procedures

### Ongoing Practices
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** – Risk registers, escalation paths, and stakeholder updates
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** – Running effective retros and converting learnings into action items

## Communication Cadence

| Frequency | Format | Purpose |
|---|---|---|
| **Daily** | 15-min standup | Report progress, surface blockers, coordinate dependencies |
| **Weekly** | PM + PdM sync | Align on priorities, risks, and decisions |
| **Twice-weekly** | Delivery team standup | Sprint progress and day-to-day coordination |
| **Weekly** | Risk & blocker review | Escalate issues requiring intervention |
| **Sprint/Milestone end** | Demo & Review | Show progress to stakeholders |
| **Monthly** | Stakeholder update | Executive summary and roadmap outlook |
| **Ad-hoc** | Escalation | Critical issues requiring immediate attention |

## Decision Gates

Projects move forward to the next phase when:

### Initiation → Planning
- ✅ One-pager completed and reviewed by Product Lead
- ✅ Stakeholder alignment confirmed
- ✅ Success metrics are clear and measurable
- ✅ Team availability and resource needs confirmed

### Planning → Execution
- ✅ Backlog prioritized with clear acceptance criteria
- ✅ Definition of Done documented
- ✅ Release plan and milestones agreed
- ✅ Initial test plan drafted
- ✅ Dependencies identified and communicated

### Execution → Release
- ✅ All acceptance criteria met and PRs merged
- ✅ Passing CI, security scans, and manual QA
- ✅ Release notes drafted
- ✅ Smoke tests and rollback plan prepared

### Release → Retrospective
- ✅ Feature deployed and post-deployment verifications passed
- ✅ Stakeholders notified
- ✅ Retrospective scheduled

## Key Artifacts Template Reference

Each phase produces key artifacts stored in the project repository:

```
project-repo/
├── README.md                          # Project charter & one-pager
├── docs/
│   ├── REQUIREMENTS.md                # Backlog and acceptance criteria
│   ├── RELEASE_PLAN.md                # Milestones and timeline
│   └── RETROSPECTIVE.md               # Learnings and action items
├── .github/
│   └── ISSUE_TEMPLATE/                # Standardized issue formats
└── [PR descriptions, commit messages] # Traceability to requirements
```

## How to Use This Documentation

1. **New to OctoAcme projects?** Start with [Project Management Overview](octoacme-project-management-overview.md), then review [Roles & Personas](octoacme-roles-and-personas.md)

2. **Kicking off a new project?** Read [Project Initiation Guide](octoacme-project-initiation.md) and use the One-pager template

3. **Planning work?** Follow [Project Planning](octoacme-project-planning.md) for backlog prioritization and risk identification

4. **In execution?** Use [Execution & Tracking](octoacme-execution-and-tracking.md) for daily workflows and [Risk Management & Communication](octoacme-risks-and-communication.md) for status and escalations

5. **Preparing a release?** Review [Release & Deployment](octoacme-release-and-deployment.md) pre-release requirements and deployment checklist

6. **After completion?** Conduct a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Continuous Improvement

These process docs are living documents. If you identify gaps, unclear guidance, or improvements:

1. Create an issue using the "Add Content to Project Management Process Docs" template (`.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`)
2. Propose the update with rationale and suggested content
3. Collaborate with the team to refine and merge improvements

Your feedback helps us scale institutional knowledge across OctoAcme.

---

**Last Updated**: [Project Team]  
**Version**: 1.0  
**Status**: In Use
