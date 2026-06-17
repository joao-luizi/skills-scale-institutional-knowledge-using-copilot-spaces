# OctoAcme — Project Management Docs

Welcome to the OctoAcme Project Management Process documentation. This folder centralizes our program management knowledge, standardizes delivery practices, and provides guidance for teams at all lifecycle stages—from initiation through retrospectives.

## Quick Links to All Process Docs

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, principles, core roles, and communication cadence.
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and decide go/no-go for planning.
- **[Project Planning](octoacme-project-planning.md)** — How to break work into shippable increments, estimate scope, and map dependencies and release timelines.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Daily team rhythm, pull request workflows, quality assurance, and blocker escalation.
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identifying, assessing, and mitigating risks, plus stakeholder communication strategies.
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Pre-release requirements, deployment checklists, and rollback procedures.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Running retrospectives and converting action items into measurable improvements.
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Definitions of Project Managers, Product Managers, Developers, QA, and stakeholders.

---

## OctoAcme Project Management Approach

### Purpose
OctoAcme's project management processes centralize institutional knowledge, standardize delivery practices, and speed onboarding by making processes searchable and versioned within the repository.

### Core Philosophy
- **Customer-first:** Prioritize customer value and usability in all decisions.
- **Iterative delivery:** Deliver small, testable increments and measure impact.
- **Clear ownership:** Each project has named Project Manager and Product Lead with defined accountability.
- **Data-informed:** Measure outcomes and iterate based on evidence.
- **Psychological safety:** Encourage feedback, learning, and blameless retrospectives.

### Project Lifecycle
OctoAcme operates across five phases:

1. **Initiation** — Validate business need, define success metrics, identify stakeholders, and make a go/no-go decision before investing in planning.
2. **Planning** — Break work into shippable increments, establish acceptance criteria, estimate scope, map dependencies, and create a release timeline.
3. **Execution** — Daily standups, sprint planning, pull request reviews, integrated testing and linting, and continuous risk monitoring.
4. **Release** — Deploy to production following pre-release verification, smoke tests, and rollback planning.
5. **Close & Retrospective** — Capture learnings and convert action items into process improvements.

### Key Practices

**Workflow & Delivery**
- Use GitHub Projects with columns: Backlog, Ready, In Progress, In Review, QA, Done.
- Pull requests stay under 400 lines when possible, include issue links and acceptance criteria, and require at least one approval.
- Automated testing, linting, and security scanning run in CI before review.

**Quality Assurance**
- Unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows.
- Security scanning in CI and manual QA for feature acceptance when needed.
- Definition of Done enforced for all backlog items.

**Communication Cadence**
- Daily standups (15 min) — progress, blockers, dependencies.
- Weekly PM + Product Lead sync — alignment and priority.
- Twice-weekly team standups — delivery coordination.
- Monthly stakeholder updates — high-level progress and risks.

**Risk Management**
- Maintain a Risk Register: ID, Description, Impact, Likelihood, Owner, Mitigation, Status.
- Review risks weekly during syncs.
- Escalate blockers through three levels: Team → PM → Product Lead → Sponsor.

**Roles & Accountability**
- **Project Manager:** Coordinates schedules, risks, communications, and documentation.
- **Product Manager:** Owns outcomes, prioritizes backlog, measures success.
- **Developers:** Implement features, write tests, participate in reviews and estimates.
- **QA/Testing:** Validates acceptance criteria and quality.
- **Stakeholders:** Provide inputs and approvals.

---

## How to Use These Docs

1. **For new projects:** Start with [Project Initiation Guide](octoacme-project-initiation.md) to create your one-pager and decision gate.
2. **For ongoing delivery:** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Project Planning](octoacme-project-planning.md) for sprint guidance and backlog management.
3. **For releases:** Use [Release & Deployment Guide](octoacme-release-and-deployment.md) for pre-release checklists and verification steps.
4. **For risks & escalation:** See [Risk Management & Communication](octoacme-risks-and-communication.md) for escalation paths and stakeholder updates.
5. **For learning & improvement:** Follow [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to capture and act on feedback.

**Tip:** Link your project README back to this folder to help team members navigate processes specific to your project.

---

## Contributing to Process Docs

Have feedback or want to add content? Use the [Add/Update Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose updates. Process improvements are tracked as issues and reviewed for alignment with our principles before merging.
