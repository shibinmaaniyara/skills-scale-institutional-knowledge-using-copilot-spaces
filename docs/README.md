# OctoAcme Project Management Process Documentation

Welcome to the OctoAcme project management process library. This README provides a central entrypoint to all project management processes and guides used across OctoAcme projects.

## Overview

OctoAcme follows a **structured lifecycle approach** to project delivery that encompasses five core phases: Initiation, Planning, Execution, Release, and Close & Retrospective. The methodology is grounded in clear ownership, iterative delivery, and data-informed decision-making.

### Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

### 1. **Initiation**
Projects begin with a lightweight One-pager that establishes the business need, success metrics, stakeholder alignment, and a go/no-go decision. This phase ensures we only move forward on initiatives with clear value and stakeholder buy-in.
- **Key deliverable**: Project One-pager (Problem, Goal, Success Metrics)
- **Outcome**: Decision to proceed to planning
- [Full guide →](./octoacme-project-initiation.md)

### 2. **Planning**
Once approved, the team breaks work into shippable increments with defined acceptance criteria, dependency mapping, and a prioritized backlog. This foundation ensures execution is focused and measurable from the start.
- **Key deliverables**: Prioritized backlog, release plan, risk register, Definition of Done
- **Activities**: Kickoff, estimation, dependency mapping, risk identification
- [Full guide →](./octoacme-project-planning.md)

### 3. **Execution & Tracking**
The team executes daily standups, maintains a GitHub Projects board, manages small pull requests with automated CI/CD checks, and tracks progress toward milestones. Quality is enforced through tests, linting, security scanning, and code reviews.
- **Key practices**: Daily standups, project board management, small PR workflow, CI-driven quality
- **Rhythm**: Daily standups, weekly delivery sync, sprint/milestone demos
- [Full guide →](./octoacme-execution-and-tracking.md)

### 4. **Release & Deployment**
Releases follow a structured checklist that includes smoke tests, rollback plans, and post-deploy verification. Pre-release requirements ensure all acceptance criteria are met and risks are mitigated before production deployment.
- **Key activities**: Pre-release checks, automated deployment, smoke testing, rollback preparation
- **Artifacts**: Release notes, deployment checklist, incident playbooks
- [Full guide →](./octoacme-release-and-deployment.md)

### 5. **Retrospective & Continuous Improvement**
After each sprint or milestone, the team retrospects to capture learnings and convert them into actionable improvements. Action items are tracked as backlog issues with clear owners and timelines.
- **Key activity**: Structured retrospectives (45–75 minutes)
- **Outcomes**: Action items, process improvements, celebration of wins
- [Full guide →](./octoacme-retrospective-and-continuous-improvement.md)

## Key Roles & Personas

OctoAcme projects involve **four primary roles**:

| Role | Responsibility | Key Activities |
|------|---|---|
| **Project Manager (PM)** | Coordinates delivery, manages schedules, risks, and communications | Planning, risk tracking, stakeholder updates, escalation |
| **Product Manager (PdM)** | Defines outcomes, prioritizes backlog, measures success | Acceptance criteria, roadmap, success metrics, feature prioritization |
| **Developers** | Design, build, test, and deliver software components | Implementation, code review, testing, estimation |
| **QA/Testing** | Validate quality and acceptance criteria | Test planning, manual QA, acceptance verification |

[Full personas guide →](./octoacme-roles-and-personas.md)

## Communication & Risk Management

### Communication Cadence
- **Daily**: Team standups (15 minutes)
- **Twice-weekly**: Delivery team standups
- **Weekly**: PM + PdM alignment sync
- **Weekly**: Risk register review
- **Monthly**: Stakeholder updates
- **Ad-hoc**: Escalations and incident communication

### Risk & Dependency Management
OctoAcme maintains a **Risk Register** that tracks:
- Risk ID, Description, Impact, Likelihood, Owner, Mitigation plan, Status

Risks are reviewed weekly, assessed for escalation, and mitigated proactively. Dependencies are mapped during planning and coordinated across teams.

**Escalation Path**: Team-level → PM → Product Lead → Sponsor

[Full risk & communication guide →](./octoacme-risks-and-communication.md)

## Project Management Overview

For a high-level introduction to OctoAcme's project management approach, roles, key artifacts, and how they all work together, see:

[Full management overview →](./octoacme-project-management-overview.md)

## How to Use These Docs

1. **For new team members**: Start with this README and [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) to understand our approach
2. **For project initiation**: Follow [octoacme-project-initiation.md](./octoacme-project-initiation.md)
3. **For detailed process guidance**: Refer to the specific phase document based on where your project is in the lifecycle
4. **For role-specific guidance**: Consult [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) to understand your responsibilities
5. **For continuous improvement**: Use [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) to capture learnings

## Complete Process Document Index

| Document | Purpose | Use When |
|----------|---------|----------|
| [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme approach, roles, and artifacts | You need an overview of how OctoAcme runs projects |
| [octoacme-project-initiation.md](./octoacme-project-initiation.md) | Validate and authorize new work, align stakeholders | A new project idea or feature proposal is ready to explore |
| [octoacme-project-planning.md](./octoacme-project-planning.md) | Turn approved initiatives into actionable plans | You need to scope work, break it into increments, and plan releases |
| [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) | Manage day-to-day execution and track progress | You're executing on deliverables and tracking toward milestones |
| [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies | You need to manage project risks or communicate status/issues |
| [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) | Standardize releases and deployments | You're preparing a release or deploying to production |
| [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and drive improvements | You've completed a sprint/milestone or want to improve processes |
| [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) | Define roles and responsibilities | You need clarity on what PM, PdM, Developer, or QA should own |

## Contributing to Process Documentation

To propose updates or add content to these process documents, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.

---

**Last updated**: June 2026  
**Maintained by**: OctoAcme Project Management team
