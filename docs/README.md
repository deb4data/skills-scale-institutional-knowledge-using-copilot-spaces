# OctoAcme Project Management Processes

## Overview

This directory contains the core project management documentation for OctoAcme. These processes guide how we initiate, plan, execute, release, and continuously improve our projects while maintaining team alignment and psychological safety.

## Quick Start

- **New to OctoAcme projects?** Start with [octoacme-project-management-overview.md](octoacme-project-management-overview.md)
- **Starting a new project?** Follow [octoacme-project-initiation.md](octoacme-project-initiation.md)
- **Ready to build?** See [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)

## Process Summary

OctoAcme operates on a structured yet iterative approach that progresses through five phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. This framework is guided by five key principles: customer-first prioritization, iterative delivery of testable increments, clear ownership through named Project Managers (PMs) and Product Leads, data-informed decision-making, and psychological safety.

### Core Roles & Responsibilities

The organization defines distinct personas to ensure accountability:

- **Project Managers** coordinate delivery, manage schedules, risks, and cross-functional communications
- **Product Managers** define what to build, prioritize the backlog, and measure outcomes
- **Developers** implement features, write tests, participate in reviews, and identify technical risks
- **QA/Testing Teams** validate quality and acceptance criteria

### Communication Cadence

Teams align through a disciplined rhythm:
- **Daily standups** (15 min): progress, blockers, dependencies
- **Weekly delivery syncs**: PM + Product Lead alignment
- **Twice-weekly standups**: delivery team check-ins
- **Monthly stakeholder updates**: business and status updates
- **Ad-hoc escalation**: three-level process (team → PM → sponsor)

### Execution & Quality Standards

During execution, teams use standardized workflows:
- GitHub Projects or similar boards with: Backlog → Ready → In Progress → In Review → QA → Done
- Pull requests limited to ≤400 lines with clear issue links and acceptance criteria
- Comprehensive testing: unit, integration, end-to-end smoke tests, security scanning, and manual QA
- Weekly risk register reviews with proactive escalation of cross-team dependencies

### Release & Learning Culture

Releases follow a three-type model (Patch, Minor, Major) with pre-release requirements including passing CI, security scans, and documented rollback plans. OctoAcme institutionalizes learning through structured retrospectives held after each sprint or milestone, yielding 2–3 prioritized action items that feed back into the project backlog. This commitment to capturing learnings, combined with transparent risk communication and data-driven metrics, enables consistent, repeatable project execution and accelerates team onboarding.

## Document Index

| Document | Purpose |
|----------|---------|
| [octoacme-project-management-overview.md](octoacme-project-management-overview.md) | Concise introduction to OctoAcme's project approach and key artifacts |
| [octoacme-project-initiation.md](octoacme-project-initiation.md) | Steps to validate ideas and authorize work with stakeholder alignment |
| [octoacme-project-planning.md](octoacme-project-planning.md) | Breaking work into shippable increments with clear dependencies and risks |
| [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) | Day-to-day execution, workflows, quality standards, and blocker escalation |
| [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) | Risk management, stakeholder communication, and escalation paths |
| [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) | Standardized release types, deployment checklists, and rollback procedures |
| [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) | Capturing learnings and converting them into actionable improvements |
| [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) | Definition of typical roles and their responsibilities |

## How to Use These Docs

- **Keep project charters updated** in your project repo
- **Reference role definitions** when creating teams or clarifying responsibilities
- **Add process-specific docs** to `.copilot/` if using Copilot Spaces for context
- **Propose updates** using the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)

---

For questions or process improvements, see [issue #2](https://github.com/deb4data/skills-scale-institutional-knowledge-using-copilot-spaces/issues/2).