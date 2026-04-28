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

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

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

---

## QA Lead

### Role Summary
The QA Lead owns the overall test strategy, coordinates test planning, and acts as the quality gate for releases. They ensure that acceptance criteria are met and that quality standards are consistently applied across the project.

### Responsibilities
- Define and maintain the test strategy, test plans, and quality standards
- Coordinate test execution across unit, integration, and end-to-end testing
- Own the Definition of Done (DoD) quality criteria and acceptance sign-off
- Identify, track, and escalate defects and quality risks
- Collaborate with Developers on testability and coverage requirements
- Act as the final quality gate before release sign-off

### Goals
- Prevent defects from reaching production
- Maintain comprehensive test coverage across all critical flows
- Continuously improve test efficiency and release confidence

### Typical Communication
- Sprint planning and review participation to clarify acceptance criteria
- Defect triage sessions with Developers and Project Manager
- Release readiness sign-off reports to Project Manager and Sponsor

### Interactions with Existing Roles
- **Developers**: Reviews acceptance criteria, collaborates on test coverage, and signs off on defect resolution
- **Product Manager**: Clarifies acceptance criteria and validates that features meet user expectations
- **Project Manager**: Reports quality status and flags risks that may affect release timelines

---

## Scrum Master / Agile Coach

### Role Summary
The Scrum Master facilitates Agile ceremonies, removes impediments blocking the team, and coaches team members on Agile practices. They protect the team's focus and enable continuous improvement across iterations.

### Responsibilities
- Facilitate daily standups, sprint planning, sprint reviews, and retrospectives
- Identify and remove impediments and blockers that prevent team progress
- Shield the team from external interruptions and scope creep
- Coach team members on Agile principles and practices
- Track and communicate team velocity and sprint health
- Drive continuous improvement actions from retrospectives

### Goals
- Enable the team to deliver consistently and predictably
- Foster a culture of continuous improvement and psychological safety
- Reduce friction in team workflows and cross-team dependencies

### Typical Communication
- Daily standup facilitation and blocker summaries
- Sprint retrospective action items and follow-ups
- Impediment escalations to Project Manager when team-level resolution is insufficient

### Interactions with Existing Roles
- **Developers**: Protects focus time, removes blockers, and facilitates team ceremonies
- **Project Manager**: Escalates unresolved impediments and coordinates cross-team dependencies
- **Product Manager**: Ensures backlog is groomed and prioritized ahead of sprint planning

---

## Business Analyst

### Role Summary
The Business Analyst bridges the gap between business stakeholders and the technical team. They gather, document, and translate requirements into actionable user stories and acceptance criteria, ensuring that what gets built aligns with business needs.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Translate stakeholder needs into user stories and acceptance criteria
- Analyze and model business processes to identify gaps and opportunities
- Support backlog refinement by clarifying ambiguities and defining edge cases
- Facilitate requirements workshops and stakeholder interviews
- Maintain traceability between business requirements and delivered features

### Goals
- Ensure delivered features solve real business problems
- Reduce rework caused by misunderstood or incomplete requirements
- Create shared understanding between business stakeholders and the development team

### Typical Communication
- Requirements workshops and stakeholder interviews
- User story reviews and backlog grooming sessions with Product Manager and Developers
- Requirements change logs and impact assessments shared with Project Manager

### Interactions with Existing Roles
- **Product Manager**: Supports roadmap refinement and translates strategic goals into detailed requirements
- **Developers**: Provides detailed acceptance criteria and answers requirement clarification questions
- **Project Manager**: Flags requirements risks and scope changes that may affect timelines

---

## Technical Lead / Architect

### Role Summary
The Technical Lead provides technical direction, owns architectural decisions, and ensures code quality across the project. They guide Developers on implementation approach and are the final authority on technical trade-offs.

### Responsibilities
- Define and communicate the technical architecture and design decisions
- Lead code reviews and enforce coding standards and best practices
- Identify and mitigate technical risks and dependencies
- Guide Developers on implementation approach for complex features
- Evaluate and approve technology choices and integration patterns
- Collaborate with Product Manager on technical feasibility and trade-off analysis

### Goals
- Maintain a coherent, scalable, and maintainable technical architecture
- Reduce technical debt and improve long-term code quality
- Ensure technical decisions align with business goals and timelines

### Typical Communication
- Architecture decision records (ADRs) and technical design documents
- Code review feedback in pull requests
- Weekly technical sync with Developers and Project Manager to surface risks

### Interactions with Existing Roles
- **Developers**: Mentors on technical approach, reviews code, and approves architectural changes
- **Product Manager**: Provides technical feasibility assessments and surfacing trade-offs for product decisions
- **Project Manager**: Flags technical risks and dependency blockers that may affect project timelines

---

## Sponsor / Executive Stakeholder

### Role Summary
The Sponsor is the executive champion for the project, providing strategic direction, securing resources, and making final decisions on escalated issues. They are accountable for the project's business outcomes and organizational alignment.

### Responsibilities
- Champion the project at the executive level and secure necessary resources
- Define or approve the project's strategic objectives and success criteria
- Make final decisions on escalated risks, scope changes, or resource conflicts
- Review and approve major milestones and release decisions
- Ensure organizational alignment and remove executive-level blockers
- Communicate project status and outcomes to senior leadership

### Goals
- Ensure the project delivers measurable business value
- Maintain strategic alignment between the project and organizational priorities
- Enable the team by resolving blockers that cannot be resolved at lower levels

### Typical Communication
- Monthly executive status briefings from Project Manager
- Milestone review and go/no-go sign-off meetings
- Escalation responses when business-impacting risks are raised

### Interactions with Existing Roles
- **Project Manager**: Receives escalations for unresolved business-impacting issues and approves major scope or timeline changes
- **Product Manager**: Aligns on product strategy, business case, and success metrics
- **Developers / Technical Lead**: Rarely interacts directly; communication is typically through Project Manager or Product Manager

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Role Interactions](octoacme-role-interactions.md) for a RACI matrix and cross-functional touchpoints between all personas.

