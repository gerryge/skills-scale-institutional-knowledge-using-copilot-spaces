# OctoAcme — Project Management Docs

This folder contains OctoAcme's project management process documents. The files here capture how we start, plan, execute, release, and learn from work so teams can move quickly with clear ownership, measurable outcomes, and repeatable practices.

## Summary

OctoAcme uses a lightweight, iterative approach that begins with a focused Project One‑pager to define the problem, SMART objectives, success metrics, stakeholders, and a high‑level timeline. Approved initiatives move into planning where work is broken into shippable increments, prioritized in a backlog, estimated, and scheduled into short iterations with demos and retrospectives.

## Workflows & quality

Teams use a project board with Backlog → Ready → In Progress → In Review → QA → Done to track work. Pull requests are kept small, include issue links and acceptance criteria, and run CI (tests, linting, security scans) before requesting review. Quality is enforced by unit and integration tests, end‑to‑end smoke tests for critical flows, CI‑based security scanning, and manual QA when required. Releases follow a checklist (pre‑release checks, staging smoke tests, rollback plan, and post‑deploy verification) and have documented rollback and incident steps.

## Roles & communication

Roles are defined (Product Managers own outcomes and prioritization, Project Managers coordinate delivery and risks, Developers implement and test, QA validates acceptance criteria). Communication cadence includes daily standups for blockers, weekly delivery syncs for progress and risk, and regular demos and retrospectives. Risks are tracked in a simple register and escalated along documented paths (team → PM → Product Lead → Sponsor).

## Docs (links)

- Project Management Overview — docs/octoacme-project-management-overview.md
- Project Initiation Guide — docs/octoacme-project-initiation.md
- Project Planning — docs/octoacme-project-planning.md
- Execution & Tracking — docs/octoacme-execution-and-tracking.md
- Risks & Communication — docs/octoacme-risks-and-communication.md
- Release & Deployment — docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas — docs/octoacme-roles-and-personas.md
