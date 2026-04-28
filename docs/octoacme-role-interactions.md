# OctoAcme — Role Interactions

## Purpose
Provide a reference guide for how all OctoAcme roles interact across project phases. Use this document to clarify accountability, resolve ambiguity, and support onboarding.

---

## RACI Matrix

**Key:** R = Responsible, A = Accountable, C = Consulted, I = Informed

| Decision / Activity | Project Manager | Product Manager | Developers | QA Lead | Technical Lead | Scrum Master | Business Analyst | Sponsor |
|---|---|---|---|---|---|---|---|---|
| Define project objectives | C | C | I | I | C | I | C | A |
| Gather and document requirements | C | A | C | C | C | I | R | I |
| Prioritize backlog | C | A | C | C | C | C | R | I |
| Estimate scope and effort | C | C | R | C | A | C | C | I |
| Define Definition of Done | R | C | C | A | C | R | C | I |
| Design technical architecture | I | C | C | C | A | I | I | I |
| Sprint planning | R | C | R | C | C | A | C | I |
| Daily standup facilitation | I | I | R | I | I | A | I | I |
| Code review and approval | I | I | R | C | A | I | I | I |
| Test strategy and planning | C | C | C | A | C | I | C | I |
| QA sign-off for release | R | C | C | A | C | I | I | I |
| Release go / no-go decision | R | C | C | A | C | I | I | C |
| Risk identification | R | C | C | C | C | C | C | I |
| Risk escalation (business-impacting) | R | C | I | C | C | I | I | A |
| Stakeholder status communication | A | C | I | I | I | I | I | C |
| Retrospective facilitation | C | I | R | I | I | A | I | I |
| Sprint retrospective actions | C | I | R | C | C | A | I | I |
| Resource and budget decisions | C | C | I | I | I | I | I | A |

---

## Cross-Functional Touchpoints by Project Phase

### 1. Initiation
| Activity | Primary Owner | Collaborators |
|---|---|---|
| Define problem statement and objectives | Product Manager | Sponsor, Business Analyst |
| Stakeholder alignment | Project Manager | Sponsor, Product Manager |
| High-level timeline and resource plan | Project Manager | Sponsor, Technical Lead |
| Initial requirements gathering | Business Analyst | Product Manager, Stakeholders |

### 2. Planning
| Activity | Primary Owner | Collaborators |
|---|---|---|
| Backlog creation and prioritization | Product Manager | Business Analyst, Developers |
| Acceptance criteria definition | Business Analyst | Product Manager, QA Lead |
| Technical architecture and design | Technical Lead | Developers, Product Manager |
| Test plan and QA approach | QA Lead | Developers, Project Manager |
| Release plan and milestone map | Project Manager | Technical Lead, Product Manager |
| Risk register setup | Project Manager | All roles |

### 3. Execution
| Activity | Primary Owner | Collaborators |
|---|---|---|
| Daily standup facilitation | Scrum Master | Developers, QA Lead |
| Sprint planning | Scrum Master | Product Manager, Developers, QA Lead |
| Code implementation | Developers | Technical Lead (code reviews) |
| Test execution and defect tracking | QA Lead | Developers, Project Manager |
| Impediment removal | Scrum Master | Project Manager, Team |
| Stakeholder status updates | Project Manager | Product Manager, Sponsor |

### 4. Release
| Activity | Primary Owner | Collaborators |
|---|---|---|
| Release readiness sign-off | QA Lead | Project Manager, Technical Lead |
| Release go / no-go decision | Project Manager | QA Lead, Product Manager, Sponsor |
| Deployment coordination | Technical Lead | Developers, Project Manager |
| Release communications | Project Manager | Product Manager, Sponsor |

### 5. Close & Retrospective
| Activity | Primary Owner | Collaborators |
|---|---|---|
| Sprint / project retrospective | Scrum Master | All roles |
| Lessons learned documentation | Project Manager | All roles |
| Action item follow-up | Scrum Master | Project Manager |
| Executive summary and outcome reporting | Project Manager | Product Manager, Sponsor |

---

## Communication Flow Overview

```
Sponsor
  ↕ (strategic direction, escalations, resource decisions)
Project Manager ←→ Product Manager
  ↕                     ↕
Scrum Master        Business Analyst
  ↕                     ↕
Developers ←→ Technical Lead ←→ QA Lead
```

- **Sponsor** sets strategic direction; receives escalations and milestone reports from Project Manager.
- **Project Manager** coordinates delivery and communicates status upward and across teams.
- **Product Manager** owns the product vision and collaborates with Business Analyst on requirements.
- **Business Analyst** bridges stakeholder needs to the development team.
- **Technical Lead** guides Developers on architecture and reviews code quality.
- **QA Lead** collaborates with Developers on testability and owns release quality gates.
- **Scrum Master** keeps team ceremonies running and removes blockers across the team.

---

## How to Use This Document
- Reference the RACI matrix when there is ambiguity about who owns a decision or activity.
- Use the cross-functional touchpoints table to identify which roles need to be included at each project phase.
- Update this document when new roles are added or responsibilities shift across the team.
