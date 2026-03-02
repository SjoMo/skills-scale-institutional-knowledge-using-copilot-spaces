# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation hub. This README provides a central entry point for all process guides and serves as a quick orientation for new team members joining any OctoAcme project.

## Summary

OctoAcme projects follow a five-phase lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Continuous Improvement**. Each project begins with a Project One-pager that captures the problem statement, success metrics, stakeholder list, and a high-level timeline. A formal decision gate ensures stakeholder alignment and confirmed team availability before work advances into planning. Clear ownership is established from the start, with a named Project Manager (PM) and Product Lead accountable for every project.

During planning, the team decomposes scope into a prioritized backlog with acceptance criteria and a Definition of Done. A Risk Register is created to track dependencies, impact, likelihood, and mitigation actions. Execution is driven by a GitHub Projects board using the columns **Backlog → Ready → In Progress → In Review → QA → Done**. The team maintains a daily standup cadence (15 minutes), weekly delivery syncs, and sprint demos at the end of each milestone. Pull requests are kept to ≤ 400 lines when possible, must link to an issue and include acceptance criteria, and require at least one approval before merging. Quality is enforced through unit tests, integration tests, end-to-end smoke tests, and automated security scanning in CI. Blockers are resolved through a three-level escalation path: team-level triage → PM escalation to the Product Lead → sponsor-level escalation for business-impacting issues.

OctoAcme recognizes three core personas with distinct responsibilities: **Developers** implement features, write tests, and participate in design and code reviews; **Product Managers (PdM)** own the product vision, prioritize the roadmap, and measure outcomes against success metrics; and **Project Managers (PM)** coordinate delivery, manage schedules and risks, facilitate meetings, and ensure consistent status reporting. Communication follows a structured cadence — weekly PM/PdM syncs, twice-weekly standups, and monthly stakeholder updates — supplemented by ad-hoc escalations as needed. The Risk Register is reviewed at every weekly sync and updated to reflect current status.

Release procedures are standardized by type: **patch** releases address critical production hotfixes, **minor** releases ship incremental features, and **major** releases introduce significant changes or breaking functionality. All releases require passing CI and security scans, merged PRs with met acceptance criteria, drafted release notes, and a documented rollback playbook. After each sprint, release, or significant incident the team holds a retrospective structured around what went well, what could be improved, and a focused set of 2–3 prioritized action items to avoid overload. Improvement actions are tracked in the project backlog, reviewed in the weekly PM sync, and measured over time to foster a culture of continuous improvement.

---

## Quick Reference

- **Project Initiation:** Stakeholder alignment, one-pager with problem statement and success metrics, decision gate before planning begins
- **Planning:** Decomposed and estimated backlog, Risk Register, Definition of Done, release milestone mapping
- **Execution & Tracking:** Board-driven workflow (Backlog → Done), automated quality checks in CI, three-level blocker escalation path
- **Risk Management & Communication:** Ongoing risk review at weekly syncs, structured stakeholder updates, clear escalation routes (Team → PM → Product Lead → Sponsor)
- **Release & Deployment:** Standardized release types (patch/minor/major), CI and security scan requirements, rollback playbook
- **Retrospective & Improvement:** Team learnings after every sprint or release, 2–3 prioritized action items, continuous feedback loop
- **Roles & Personas:** Defined responsibilities for PM, PdM, Developers, and Stakeholders with clear ownership per project

---

## Docs Index

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
