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

### Standard Escalation
1. **Team Level**: Identified in daily standup by Project Manager, Developers, QA Lead, or Tech Lead
2. **Product Level**: Project Manager escalates to Product Manager and Product Lead
3. **Executive Level**: Product Lead escalates to Sponsor for business-impacting decisions

### Security Escalations
- Any security concern identified during development or review → **Security Owner immediately**
- Security Owner conducts risk assessment and coordinates response
- Critical security incidents → Follow security incident runbook; notify Sponsor and Support/Ops Lead

### Operational / Production Escalations
- Production issues → **Support/Ops Lead coordinates triage**
- Critical incidents → Notify Project Manager, Tech Lead, and Sponsor
- Post-incident review led by Support/Ops Lead with retrospective
