# OctoAcme Project Management Docs

This README centralizes access to all OctoAcme project management knowledge, workflows, and roles, and provides organized links to every process doc in `docs/`.

---

## Purpose of this Copilot Space

- Centralize scattered project management knowledge in Copilot Spaces
- Convert tacit team insights into searchable, versioned artifacts
- Give all team members equal access to processes, decisions, and rationale
- Connect a repository as a structured knowledge source
- Extract, refine, and standardize workflows collaboratively
- Feed validated improvements back into living documentation
- Accelerate onboarding and reduce single-person dependency risk
- Enable consistent, repeatable project execution

---

## Overview

OctoAcme projects follow a structured, lifecycle-based methodology spanning five stages: Initiation, Planning, Execution, Release, and Retrospective. Each stage produces clear artifacts—project charters, sprint backlogs, risk registers, release notes, and retrospective action items—that are maintained in the repository and serve as the team's single source of truth. Work is tracked on project boards using a PR-based workflow where every feature branch goes through CI checks and peer review before merging, ensuring incremental and testable delivery.

Delivery relies on five core personas: **Project Manager (PM)**, **Product Manager (PdM)**, **Developers**, **QA/Testing**, and **Stakeholders**. The PM coordinates schedules, risks, and cross-team communication; the PdM owns the product vision and backlog prioritization; Developers implement and review code; QA validates acceptance criteria; and Stakeholders provide inputs and approvals. Clear ownership at every stage minimizes ambiguity and reduces single-person dependency risk.

Communication is standardized through defined cadences—twice-weekly standups, weekly PM/PdM syncs, and monthly stakeholder updates—supplemented by templates for weekly status reports and incident communications. All project status is surfaced through a single source of truth (project README or release doc), and escalation paths (team → PM → Product Lead → Sponsor) are documented so blockers are resolved quickly and transparently.

Quality is enforced throughout the lifecycle via continuous integration, mandatory PR approvals, multi-layer testing (unit, integration, smoke), and security scans before any release. The deployment checklist covers staging validation, production rollout, and post-deploy verification, while the rollback and incident playbook ensures the team can respond and recover rapidly. Retrospectives close each project cycle and feed improvements back into these living documents.

---

## Docs Index

| Document | Description |
|----------|-------------|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, lifecycle summary, and communication cadences |
| [Project Initiation Guide](octoacme-project-initiation.md) | Problem statement, stakeholder alignment, success metrics, and charter template |
| [Project Planning](octoacme-project-planning.md) | Scope definition, backlog breakdown, estimation, milestones, and dependencies |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Standups, board management, PR workflow, CI/CD, and demo cadences |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, stakeholder communication, and templates |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Release types, pre-release checklist, deployment steps, rollback, and release notes template |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format, action item tracking, and process improvement loops |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and communication patterns for each role |

---

> _Read each doc above for actionable checklists, templates, and how-to guidance._

---

_Last updated: 2026-03-02_
