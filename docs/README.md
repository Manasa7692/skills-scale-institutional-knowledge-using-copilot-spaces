# OctoAcme Project Management Processes

## Purpose
This README provides a concise overview of OctoAcme's project management approach to help all team members understand core workflows, roles, communication practices, and quality assurance standards.

## Overview
OctoAcme employs a structured, customer-first project management approach built on five lifecycle phases: Initiation, Planning, Execution, Release, and Close & Retrospective. Projects begin with a Project One‑pager that defines problem, success metrics, stakeholders, and a high‑level timeline. Planning turns approved initiatives into prioritized, estimated backlog items with clear acceptance criteria and a release/milestone map. Execution uses visible boards and regular cadences to track progress and surface risks early. Releases follow standardized checklists and rollback plans. Retrospectives capture learnings and drive continuous improvement.

## Core Roles & Personas
- Project Manager (PM): coordinates delivery, schedules, risk, and stakeholder communications.
- Product Manager (PdM): defines outcomes, prioritizes the roadmap, and validates success.
- Developers: design, build, test, and review code; identify technical risks.
- QA/Testing: validate acceptance criteria and perform manual/automated checks.
- Stakeholders: provide approvals, domain input, and sponsor-level decisions.

## Key Workflows & Communication
- Project board workflow: Backlog → Ready → In Progress → In Review → QA → Done.
- Team rhythm: daily standups (progress/blockers), weekly delivery syncs (risks/deps), demos, and monthly stakeholder updates.
- Escalation: Team-level triage → PM → Product Lead → Sponsor.
- Communication templates: Weekly Status (Progress, Next Steps, Risks/Blockers, Decisions Needed) and Incident Communication (Triage, Actions, Timeline, Post‑incident Retrospective).

## Quality Assurance & Release Practices
- Pull requests: small, referenced to issues, include acceptance criteria, pass CI (tests, linting, security), and require at least one approval.
- Testing: unit tests for new logic, integration tests where applicable, and end‑to‑end smoke tests for critical flows.
- Releases: pre-release checklist (passing CI, release notes, rollback plan), staged smoke tests, automated deployment when possible, and post‑deploy verification.
- Retrospectives: blameless reviews (45–75 minutes) that capture 2–3 actionable improvements with owners and due dates.

## Artifacts & Where to Look
- Project One‑pager / Charter
- Roadmap and Release Plan
- Sprint/Iteration Backlog with Acceptance Criteria
- Risk Register (ID, Description, Impact, Likelihood, Owner, Mitigation)
- Project Board (Backlog → Ready → In Progress → In Review → QA → Done)
- Release Notes and Retrospective notes

## Getting Started
For more detailed guidance see the other docs in this folder:
- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-release-and-deployment.md
- octoacme-risks-and-communication.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-roles-and-personas.md
