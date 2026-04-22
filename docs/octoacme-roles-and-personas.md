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

## Quality Assurance / Testing Lead

### Role Summary
Quality Assurance and Testing Leads define and execute quality strategies, ensuring products meet acceptance criteria and quality standards before release.

### Responsibilities
- Define test strategy, automation frameworks, and test coverage goals
- Validate acceptance criteria with Product Managers and Developers
- Conduct manual and automated testing, including smoke tests
- Identify quality gaps and work with team to resolve defects
- Participate in release readiness reviews
- Document test plans and results

### Goals
- Ensure quality gates are met before release
- Reduce defect escape rate to production
- Improve test coverage and automation
- Enable fast, confident releases

### Typical Communication
- Weekly QA status in execution sync
- Test plans and acceptance criteria reviews
- Release readiness checklists
- Defect triage and severity assessment

### Interactions with Other Roles
- **Developers:** Collaborate on test design, automation frameworks, and reproduction of defects
- **Product Managers:** Clarify acceptance criteria, prioritize test scenarios
- **Project Managers:** Coordinate QA scheduling, resource allocation, test environment setup
- **Security Owner:** Participate in security testing and vulnerability validation

---

## Tech Lead / Architecture Lead

### Role Summary
Tech Leads provide technical direction, conduct design reviews, and identify architectural risks to ensure systems remain scalable, maintainable, and aligned with long-term vision.

### Responsibilities
- Make technical direction decisions and propose architectural approaches
- Conduct design reviews and provide technical mentorship
- Identify technical debt and propose mitigation strategies
- Assess technical feasibility of features
- Escalate architectural risks and dependencies
- Foster technical excellence and best practices

### Goals
- Maintain system health and reduce technical debt
- Ensure scalability and performance
- Enable rapid, confident feature delivery
- Build a learning culture within the engineering team

### Typical Communication
- Technical design reviews before implementation
- Architecture decision records (ADRs) and design docs
- Weekly engineering syncs
- Escalations to Product Lead for complex trade-offs

### Interactions with Other Roles
- **Developers:** Mentor on technical decisions, design patterns, code quality
- **Product Managers:** Collaborate on feasibility and trade-offs between features
- **Project Managers:** Identify and escalate technical dependencies and risks
- **Product Lead / Director:** Escalate strategic architectural concerns

---

## Product Lead / Director

### Role Summary
Product Leads provide strategic oversight of product initiatives, align cross-functional priorities, and make go/no-go decisions on behalf of the business and product vision.

### Responsibilities
- Approve and align Project One-pagers with business strategy
- Review and prioritize competing initiatives
- Make strategic go/no-go decisions on projects
- Escalate to Sponsors for business-impacting decisions
- Ensure cross-project alignment and resource allocation
- Serve as final escalation point for product trade-offs

### Goals
- Ensure product strategy alignment across initiatives
- Maximize organizational impact and customer value
- Manage competing priorities and resource constraints
- Enable informed, timely decision-making

### Typical Communication
- Monthly strategic planning sessions
- Project approval and go/no-go gates
- Escalation point for PM and Tech Lead concerns
- Stakeholder and Sponsor updates

### Interactions with Other Roles
- **Product Managers:** Review One-pagers, approve roadmap priorities
- **Project Managers:** Escalation point for resource and schedule conflicts
- **Tech Leads:** Review architectural concerns and technical trade-offs
- **Stakeholders / Sponsors:** Align with business priorities and budget

---

## Security Owner / Security Lead

### Role Summary
Security Owners assess security risks, ensure compliance, coordinate incident response, and drive security best practices across projects.

### Responsibilities
- Conduct security risk assessments during planning
- Review code and PRs for security concerns
- Participate in risk registers and mitigation planning
- Lead security incident response and post-incident reviews
- Ensure compliance with security policies and standards
- Provide security guidance and training to the team

### Goals
- Minimize security risks and vulnerabilities
- Ensure rapid incident detection and response
- Maintain compliance with security standards
- Build security awareness across the organization

### Typical Communication
- Security risk reviews in planning phase
- Code review comments and security findings
- Incident response coordination
- Security incident playbook execution
- Monthly security updates

### Interactions with Other Roles
- **Developers:** Review PRs, guide secure coding practices
- **Project Managers:** Participate in risk registers, escalate security incidents
- **QA/Testing Lead:** Coordinate security testing and vulnerability validation
- **Tech Leads:** Review architectural security implications
- **Support / Operations Lead:** Coordinate incident response and runbooks

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors represent business interests, provide approval authority, and ensure projects deliver value aligned with organizational goals.

### Responsibilities
- Provide business context and success metrics
- Approve project scope, budget, and timeline
- Serve as escalation point for business-impacting decisions
- Participate in project approvals and go/no-go gates
- Receive and review project status updates
- Make final decisions on trade-offs and priorities

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment between projects and business strategy
- Enable timely, informed decision-making
- Ensure stakeholder confidence and transparency

### Typical Communication
- Monthly stakeholder status updates
- Project initiation and approval meetings
- Escalation point for critical issues
- Go/no-go decision gates
- Release announcements

### Interactions with Other Roles
- **Product Managers:** Align on business needs and success metrics
- **Project Managers:** Receive status updates and escalations
- **Product Lead / Director:** Coordinate strategic decisions and budget
- **Support / Operations Lead:** Receive operational status and incident updates

---

## Support / Operations Lead

### Role Summary
Support and Operations Leads ensure operational readiness, drive production monitoring, and coordinate rapid incident response to maintain service quality and customer satisfaction.

### Responsibilities
- Ensure operational readiness before releases
- Monitor production systems and customer impact
- Coordinate incident triage and response
- Develop and maintain runbooks and deployment procedures
- Participate in release planning and deployment coordination
- Lead post-incident reviews and action items
- Coordinate with customer support on status communication

### Goals
- Minimize production incidents and downtime
- Enable rapid incident detection and resolution
- Maintain excellent customer experience
- Continuously improve operational procedures

### Typical Communication
- Release readiness reviews
- Production monitoring and alerts
- Incident coordination and status updates
- Runbook and procedure documentation
- Monthly operational metrics review

### Interactions with Other Roles
- **Project Managers:** Coordinate release planning and deployment windows
- **Developers:** Debug production issues, provide system context
- **Security Owner:** Coordinate security incident response
- **QA/Testing Lead:** Smoke test verification and release validation
- **Stakeholders / Sponsors:** Communicate service status and incidents

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

