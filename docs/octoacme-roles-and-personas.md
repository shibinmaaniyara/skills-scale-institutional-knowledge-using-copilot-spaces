# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Key Interactions
- Works with Engineering Lead on technical direction and architecture
- Collaborates with Product Manager and Designer on acceptance criteria
- Partners with DevOps/SRE on deployment and monitoring
- Engaged by QA during testing phases

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Own post-release impact measurement

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Key Interactions
- Partners with Project Manager on timelines and delivery
- Works with Designer on user experience and research inputs
- Collaborates with Data Analyst on success metrics definition
- Engages with Stakeholder Liaison on requirements surfacing
- Reviews release readiness with Release Manager

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Key Interactions
- Works closely with Scrum Master on ceremony facilitation and impediment removal
- Collaborates with Release Manager on deployment scheduling
- Partners with Product Manager on roadmap and backlog prioritization
- Escalates risks and blockers to Product Lead and Stakeholder Liaison

---

## Engineering Lead / Tech Lead

### Role Summary
Engineering Leads provide technical direction and make architecture decisions. They mentor developers, guide design reviews, and ensure technical excellence while balancing delivery needs.

### Responsibilities
- Define technical architecture and major design decisions
- Review and approve technical designs and significant pull requests
- Mentor developers and guide technical problem-solving
- Identify and mitigate technical risks
- Ensure code quality, testing standards, and maintainability
- Represent engineering perspective in trade-off discussions

### Goals
- Deliver technically sound, scalable solutions
- Build team technical capability
- Reduce technical debt while maintaining velocity

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and mentoring sessions
- Technical risk assessments in planning meetings
- Architecture decision records (ADRs)

### Key Interactions
- Mentors and guides Developers on technical decisions
- Collaborates with Product Manager on feasibility and trade-offs
- Partners with Security Owner on architectural security reviews
- Works with DevOps/SRE on deployability and operational requirements
- Engages with Data Analyst on instrumentation design

---

## Product Designer (UX)

### Role Summary
Product Designers lead user research, design interfaces, and create acceptance criteria for usability. They ensure solutions are intuitive and meet user needs.

### Responsibilities
- Conduct user research and gather usability requirements
- Design interfaces and user experiences
- Create design specs and acceptance criteria for usability
- Validate designs with users and stakeholders
- Review implemented features for design fidelity
- Advocate for user needs in trade-off discussions

### Goals
- Deliver intuitive, user-friendly solutions
- Reduce support burden through good design
- Maximize user adoption and satisfaction

### Typical Communication
- Design specs and prototypes
- Usability testing sessions and reports
- Design review feedback in planning and execution
- Wireframes and user journey documentation

### Key Interactions
- Works with Product Manager to define user requirements and success metrics
- Collaborates with Developers on design feasibility and implementation
- Engages with QA on usability acceptance criteria verification
- Partners with Stakeholder Liaison to validate designs with stakeholders

---

## Data Analyst / Analytics Owner

### Role Summary
Data Analysts define measurable success metrics, ensure telemetry is instrumented, and analyze post-release impact. They provide data-driven insights to inform prioritization.

### Responsibilities
- Define and instrument success metrics with engineering
- Set up dashboards and monitoring for key signals
- Analyze post-release impact and user behavior
- Provide data-driven insights for prioritization
- Track velocity, burndown, and team health metrics
- Identify trends and anomalies that warrant action

### Goals
- Ensure decisions are informed by data
- Reduce time to insight on feature impact
- Maintain observability into product and team health

### Typical Communication
- Success metric definitions and instrumentation specs
- Post-release impact reports and dashboards
- Weekly metrics reviews in sync meetings
- Data-driven insights and trend analysis

### Key Interactions
- Partners with Product Manager to define success metrics
- Works with Developers to instrument telemetry and logging
- Engages with DevOps/SRE on monitoring and alerting setup
- Supports Release Manager with pre/post-release data analysis

---

## DevOps / SRE (Platform Engineer)

### Role Summary
DevOps and Site Reliability Engineers maintain deployment pipelines, monitor production health, and automate operational tasks. They ensure systems are reliable, scalable, and observable.

### Responsibilities
- Design, build, and maintain CI/CD pipelines
- Monitor production systems and respond to incidents
- Automate operational tasks and infrastructure provisioning
- Define and enforce operational standards and runbooks
- Manage infrastructure capacity and costs
- Conduct post-incident reviews and implement preventative measures

### Goals
- Maximize system reliability and uptime
- Enable fast, safe deployments
- Reduce manual operational toil
- Maintain security and compliance posture

### Typical Communication
- Deployment pipelines and infrastructure documentation
- Incident response and post-mortems
- Infrastructure change notifications
- Operational metrics and health dashboards

### Key Interactions
- Works with Release Manager on pre-release and deployment verification
- Partners with Security Owner on infrastructure security and compliance
- Collaborates with Developers on observability and logging requirements
- Engages with Engineering Lead on scalability and performance concerns

---

## Security & Compliance Owner

### Role Summary
Security & Compliance Owners run security reviews, ensure compliance requirements are met, and own remediation tracking. They protect the organization and customers from security and regulatory risks.

### Responsibilities
- Conduct security reviews on designs and implementations
- Ensure compliance with regulatory and organizational standards
- Manage vulnerability remediation and tracking
- Lead incident response for security events
- Maintain security documentation and policies
- Provide security guidance on architecture and dependency decisions

### Goals
- Prevent security breaches and compliance violations
- Build security into development processes
- Maintain customer and stakeholder trust

### Typical Communication
- Security review feedback and guidance
- Vulnerability assessments and remediation plans
- Compliance checklists and audit reports
- Security incident communication and resolution

### Key Interactions
- Works with Engineering Lead on secure architecture design
- Reviews implementations with Developers
- Partners with DevOps/SRE on infrastructure security
- Engages with Release Manager on security verification pre-release
- Advises Project Manager on security-related risks and escalations

---

## Release Manager / Release Lead

### Role Summary
Release Managers plan and coordinate releases, manage release checklists, and own rollback/mitigation plans. They ensure smooth, low-risk transitions to production.

### Responsibilities
- Plan release windows and coordinate schedules
- Manage release checklists and pre-release verification
- Own deployment process and rollback plans
- Communicate releases to support, marketing, and stakeholders
- Track deployment health and resolve production issues
- Lead incident response for deployment-related problems

### Goals
- Achieve on-time releases with zero unplanned outages
- Reduce deployment risk and time-to-rollback
- Maintain stakeholder confidence in releases

### Typical Communication
- Release calendars and deployment schedules
- Release notes and stakeholder communications
- Pre/post-deployment checklists and sign-offs
- Incident and escalation notifications

### Key Interactions
- Coordinates with Project Manager and Product Manager on release readiness
- Works with Developers and Engineering Lead on pre-release verification
- Partners with DevOps/SRE on deployment execution and monitoring
- Engages with QA on final acceptance testing
- Communicates with Stakeholder Liaison on customer-facing communications

---

## Scrum Master / Delivery Lead

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team impediments, protect focus, and improve team processes. They enable team productivity and continuous improvement.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Identify and help remove blockers and impediments
- Protect team focus and shield from scope creep
- Track and improve team velocity and predictability
- Facilitate retrospectives and track action items
- Coach team on agile practices and continuous improvement

### Goals
- Maximize team productivity and delivery predictability
- Build a high-performing, cohesive team
- Foster a culture of continuous improvement

### Typical Communication
- Sprint planning agendas and outcomes
- Standup summaries and blocker tracking
- Retrospective notes and action items
- Team health and velocity metrics

### Key Interactions
- Closely partners with Project Manager on delivery tracking and risk management
- Facilitates planning with Product Manager and the delivery team
- Supports Engineering Lead in keeping team focused on technical excellence
- Helps identify and escalate impediments to Project Manager

---

## Stakeholder Liaison / Customer Success Representative

### Role Summary
Stakeholder Liaisons represent customer and stakeholder-facing concerns, coordinate communications, and ensure support readiness. They bridge the gap between project delivery and external expectations.

### Responsibilities
- Represent stakeholder and customer needs to the delivery team
- Surface market feedback and customer requirements
- Coordinate release communications and announcements
- Ensure support and documentation readiness
- Manage stakeholder expectations and address concerns
- Provide feedback to Product Manager on customer impact

### Goals
- Ensure customer satisfaction and smooth adoptions
- Reduce support burden through proactive communication and documentation
- Maintain strong relationships with key stakeholders

### Typical Communication
- Stakeholder requirement documentation and feedback
- Release announcement drafts and communication plans
- Support readiness checklists and training materials
- Customer feedback summaries and trends

### Key Interactions
- Works with Product Manager to surface stakeholder requirements and feedback
- Partners with Project Manager on stakeholder communication cadence
- Engages with Release Manager on release communications and timing
- Collaborates with Developers and Designers on feature acceptance from customer perspective
- Supports post-release customer success and adoption

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference persona responsibilities and interactions when establishing accountability for tasks or decisions.
- Use the interaction patterns to identify communication gaps or silos in your project execution.
