# OctoAcme Roles Interaction Matrix

This document provides a quick reference for which roles interact at each stage of the project lifecycle and their primary interaction patterns.

## Legend
- **R** = Responsible (owns the activity)
- **A** = Accountable (final authority/approval)
- **C** = Consulted (provides input/expertise)
- **I** = Informed (receives updates)

## Initiation Phase

| Activity | PM | PdM | Product Lead | Sponsor | Tech Lead | Developers | QA Lead | Security | Ops Lead |
|----------|----|----|-------|---------|-----------|-----------|---------|----------|----------|
| Create One-pager | R | R | — | — | C | — | — | — | — |
| Stakeholder alignment | R | C | C | A | — | — | — | — | — |
| Review & approve One-pager | C | — | R | A | C | — | — | C | — |
| Initial risk assessment | R | C | — | — | C | — | — | C | C |
| Go/No-Go decision gate | C | — | R | A | — | — | — | — | — |

## Planning Phase

| Activity | PM | PdM | Product Lead | Sponsor | Tech Lead | Developers | QA Lead | Security | Ops Lead |
|----------|----|----|-------|---------|-----------|-----------|---------|----------|----------|
| Kickoff meeting | R | R | I | I | R | R | R | C | C |
| Backlog creation & prioritization | — | R | — | — | C | C | C | — | — |
| Scope estimation | C | C | — | — | R | R | C | — | — |
| Define Definition of Done | R | C | — | — | C | — | R | C | — |
| Identify dependencies | R | — | — | — | R | C | — | C | C |
| Test strategy & approach | C | — | — | — | — | — | R | C | — |
| Security review | — | — | — | — | C | C | C | R | — |
| Release & deployment planning | R | C | — | — | C | — | — | — | R |

## Execution Phase

| Activity | PM | PdM | Product Lead | Sponsor | Tech Lead | Developers | QA Lead | Security | Ops Lead |
|----------|----|----|-------|---------|-----------|-----------|---------|----------|----------|
| Daily standups | R | I | — | — | I | R | I | — | I |
| Sprint/iteration planning | R | R | — | — | C | R | C | — | — |
| Code review & PR merge | — | — | — | — | R | R | — | C | — |
| Feature acceptance testing | — | C | — | — | — | — | R | — | — |
| Security scanning | — | — | — | — | C | C | — | R | — |
| Risk register updates | R | — | — | — | C | C | — | C | C |
| Weekly execution sync | R | R | C | I | C | C | C | C | C |
| Escalation handling | R | — | R | — | C | — | — | — | C |

## Release & Deployment Phase

| Activity | PM | PdM | Product Lead | Sponsor | Tech Lead | Developers | QA Lead | Security | Ops Lead |
|----------|----|----|-------|---------|-----------|-----------|---------|----------|----------|
| Release planning | R | C | C | — | C | — | — | — | R |
| Pre-release verification | C | — | — | — | — | — | R | C | R |
| Release readiness sign-off | C | C | R | — | C | — | C | C | C |
| Production deployment | — | — | — | — | C | C | — | — | R |
| Smoke testing | — | — | — | — | — | — | R | — | R |
| Release announcement | R | R | I | I | — | — | — | — | I |

## Incident Response Phase

| Activity | PM | PdM | Product Lead | Sponsor | Tech Lead | Developers | QA Lead | Security | Ops Lead |
|----------|----|----|-------|---------|-----------|-----------|---------|----------|----------|
| Incident triage | I | I | I | I | R | C | — | C* | R |
| Mitigation & fix | — | — | — | — | R | R | — | C* | C |
| Stakeholder notification | R | — | C | I | — | — | — | — | C |
| Post-incident review | R | C | C | I | R | R | C | C* | R |

*Security Owner is R for security-related incidents

## Retrospective & Improvement Phase

| Activity | PM | PdM | Product Lead | Sponsor | Tech Lead | Developers | QA Lead | Security | Ops Lead |
|----------|----|----|-------|---------|-----------|-----------|---------|----------|----------|
| Retrospective facilitation | R | — | — | — | — | — | — | — | — |
| Capture action items | R | C | — | — | C | C | C | C | C |
| Assign owners | R | — | — | — | — | — | — | — | — |
| Track progress | R | — | — | — | — | — | — | — | — |

## Cross-Functional Communication Cadence

| Meeting | PM | PdM | Product Lead | Sponsor | Tech Lead | Developers | QA Lead | Security | Ops Lead | Frequency |
|---------|----|----|-------|---------|-----------|-----------|---------|----------|----------|-----------|
| Daily standup | R | I | — | — | I | R | I | — | I | Daily |
| Weekly PM + PdM sync | R | R | — | — | — | — | — | — | — | Weekly |
| Twice-weekly execution sync | R | — | — | — | C | R | C | C | C | 2x weekly |
| Weekly risk review | R | C | — | — | C | — | — | C | C | Weekly |
| Monthly stakeholder update | R | C | C | R | — | — | — | — | — | Monthly |
| Incident coordination | R | — | C | I | R | C | — | R | R | As needed |
| Retrospective | R | C | I | — | C | C | C | C | C | Per sprint/release |

---

## Role-Specific Responsibilities at a Glance

**Project Manager (PM)**
- Responsible for: Timeline, risk escalation, meeting facilitation, stakeholder communication
- Reports to: Product Lead and Sponsor
- Escalates to: Product Lead (planning/delivery issues), Sponsor (business impact)

**Product Manager (PdM)**
- Responsible for: Backlog prioritization, success metrics, acceptance criteria
- Reports to: Product Lead and Sponsor
- Collaborates closely with: Project Manager, Tech Lead, QA Lead

**Product Lead / Director**
- Responsible for: Strategic alignment, go/no-go decisions, trade-off resolution
- Reports to: Sponsor
- Escalation point for: PM, PdM, Tech Lead

**Sponsor / Stakeholder**
- Responsible for: Business approval, budget authority, strategic alignment
- Escalation point for: Product Lead
- Informed by: Monthly updates, go/no-go gates, incidents

**Tech Lead / Architecture Lead**
- Responsible for: Technical direction, design reviews, technical risk assessment
- Collaborates with: Developers, Product Manager, Security Owner, Support/Ops Lead
- Escalates to: Product Lead (architectural concerns)

**Developers**
- Responsible for: Implementation, testing, design collaboration
- Participates in: Planning, code review, standups, retrospectives
- Reports to: Tech Lead for technical guidance

**QA Lead / Testing Lead**
- Responsible for: Test strategy, test execution, acceptance validation
- Participates in: Planning, daily standups, sprint reviews, release readiness
- Collaborates with: Developers, Product Manager, Project Manager, Security Owner

**Security Owner / Security Lead**
- Responsible for: Security risk assessment, incident response, compliance
- Participates in: Planning, risk reviews, PR reviews, incident response
- Escalates to: Product Lead (critical security concerns)

**Support / Operations Lead**
- Responsible for: Operational readiness, production monitoring, incident response
- Participates in: Release planning, post-release verification, incident management
- Collaborates with: Tech Lead, Developers, Security Owner, Project Manager
