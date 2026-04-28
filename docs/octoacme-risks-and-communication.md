# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

### Stakeholder Personas and Communication Needs
| Stakeholder | Information Needs | Frequency | Channel |
|---|---|---|---|
| Sponsor / Executive | Business outcomes, budget, major risks | Monthly | Executive status briefing |
| Product Manager | Feature progress, acceptance criteria status | Weekly | PM + PdM sync |
| Project Manager | Delivery status, risks, blockers | Daily / Weekly | Standup, status report |
| QA Lead | Defect trends, test coverage, release readiness | Per sprint | QA status report |
| Developers | Sprint goals, blockers, technical decisions | Daily | Standup, PR reviews |
| Business Analyst | Requirements clarity, change requests | As needed | Backlog grooming sessions |
| External Stakeholders (sales, support) | Release dates, known issues | Milestone-based | Release notes, announcements |

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> **Scrum Master** -> **PM** -> **Product Lead** -> **Sponsor**
- For security incidents, follow the security incident runbook and notify Security on-call
- **Sponsor** is the final escalation authority for business-impacting issues, resource conflicts, and strategic decisions
