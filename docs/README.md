# OctoAcme Project Management Docs

Welcome — this directory contains the OctoAcme project management process documentation. These guides provide a single entry point to understand how OctoAcme runs projects, defines roles, manages risks, and continuously improves delivery.

OctoAcme follows an iterative, team-centered approach that emphasizes small, measurable deliveries and clear ownership. Work is organized through a prioritized backlog and a project board with standard columns (Backlog, Ready, In Progress, In Review, QA, Done). The lifecycle runs from Initiation (one-pager, stakeholder alignment) through Planning (kickoff, backlog, estimates), Execution (build, test, review) and Release (deploy, verify) to Close & Retrospective. Pull request conventions encourage small, focused changes, link related issues and acceptance criteria, and require CI and at least one approval before merge.

Roles and responsibilities are explicitly defined so handoffs and ownership are clear. Product Managers own problem definition, success metrics, and prioritization; Project Managers coordinate timelines, risks, and stakeholder communication; Developers implement and test; QA validates acceptance criteria and quality. The Personas document provides role definitions and is used to frame scenarios and clarify responsibilities across activities.

Communication is structured around a predictable cadence: daily standups to surface progress and blockers, a weekly delivery sync to review progress and flagged risks, sprint demos/reviews at the end of milestones, and periodic stakeholder updates. Escalation paths are documented (team → PM → Product Lead → Sponsor) to ensure timely resolution of critical blockers. Continuous improvement is supported by retrospectives that produce prioritized action items which feed back into the backlog.

Quality assurance is integrated into the delivery process. Developers add unit and integration tests for new logic, critical flows are covered by end-to-end smoke tests, and CI enforces linting and security scanning before review. Releases follow a checklist (pre-release checks, staging smoke tests, rollback/mitigation plan) and incidents use an incident playbook with defined communication and triage steps.

## Quick Start / Entry Points
- Start here: **[Project Management Overview](octoacme-project-management-overview.md)** — high-level introduction to approach, roles, and artifacts
- For new initiatives: **[Project Initiation Guide](octoacme-project-initiation.md)**
- For planning work: **[Project Planning](octoacme-project-planning.md)**
- For day-to-day execution: **[Execution & Tracking](octoacme-execution-and-tracking.md)**
- For risk & stakeholder comms: **[Risk Management & Communication](octoacme-risks-and-communication.md)**
- For releases: **[Release & Deployment Guide](octoacme-release-and-deployment.md)**
- For continuous improvement: **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)**
- Personas reference: **[Roles & Personas](octoacme-roles-and-personas.md)**

## Project lifecycle (quick reference)
1. Initiation — problem statement, stakeholders, high-level timeline  
2. Planning — scope, resources, milestones, dependencies  
3. Execution — build, test, review, iterate  
4. Release — deploy, verify, announce  
5. Close & Retrospective — capture learnings and next steps

## How to use and contribute
- Keep the Project One-pager and README up to date as the single source of truth for status and links.
- To propose updates to a process document, use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/.
- For process changes that affect multiple teams, capture stakeholder review notes in the issue before merging.
