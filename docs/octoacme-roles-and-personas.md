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

### Interactions with Other Roles
- Collaborate with QA/Testing Engineers on acceptance criteria and test strategies
- Work with Product Leads to refine requirements and prioritize work
- Support Security Engineers in implementing secure coding practices
- Respond to feedback from Incident Commanders during incident response

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

### Interactions with Other Roles
- Partner with Project Managers on timeline and delivery coordination
- Work with Developers and QA/Testing Engineers to define acceptance criteria
- Align with Sponsors on strategic priorities and resource allocation
- Communicate status and outcomes to Stakeholders

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

### Interactions with Other Roles
- Coordinate with Developers on schedule and dependencies
- Work with QA/Testing Engineers to plan testing phases and quality gates
- Report to Product Leads and Sponsors on project health
- Communicate with all Stakeholders on progress and blockers
- Support Incident Commanders during critical incidents

---

## QA/Testing Engineer

### Role Summary
QA/Testing Engineers validate software quality, test acceptance criteria, and ensure features meet quality standards before release. They collaborate with developers and product managers to define test strategies and maintain quality throughout the delivery lifecycle.

### Responsibilities
- Design and execute test cases based on acceptance criteria and Definition of Done
- Perform functional, integration, and end-to-end testing
- Report bugs and track resolution status
- Participate in test automation and CI pipeline development
- Validate features in staging and production environments
- Coordinate smoke tests before releases
- Define test strategies and quality metrics with the team

### Goals
- Ensure high quality deliverables that meet acceptance criteria
- Reduce bugs and regressions in production
- Enable faster feedback loops through automation
- Maintain customer trust through reliable releases

### Typical Communication
- Daily standups focused on testing progress and blockers
- Test case reviews with developers and product managers
- Bug reports in the project tracking system
- Release coordination for smoke testing and verification

### Interactions with Other Roles
- Partner with Developers on test automation and CI integration
- Work with Product Managers and Project Managers to define quality gates
- Validate security requirements with Security Engineers
- Support release coordination with Project Managers
- Participate in post-incident reviews with Incident Commanders

---

## Stakeholder

### Role Summary
Stakeholders are individuals or groups invested in project success, including business leaders, customers, support teams, and dependent teams. They provide inputs, approvals, and feedback at key decision gates throughout the project lifecycle.

### Responsibilities
- Provide business requirements and success criteria
- Approve major decisions and scope changes
- Review status updates and project artifacts
- Escalate concerns and provide feedback
- Ensure alignment with organizational priorities
- Support adoption and communication of releases

### Goals
- Ensure projects deliver business value
- Minimize surprises and maintain transparency
- Enable efficient decision-making through clear communication
- Support project success through active engagement

### Typical Communication
- Monthly stakeholder updates and status reports
- Milestone review meetings and demos
- Async communication via project readme and dashboards
- Ad-hoc escalation for decisions and risks

### Interactions with Other Roles
- Receive status updates and issue escalations from Project Managers
- Provide guidance and priorities to Product Managers
- Approve release communications from Project Managers
- Escalate critical issues to Sponsors as needed
- Participate in release demos and feedback sessions

---

## Product Lead

### Role Summary
The Product Lead (or Product Manager) defines product vision, prioritizes work, and measures outcomes. They ensure projects deliver customer and business value through clear prioritization and data-driven decision-making.

### Responsibilities
- Define product vision and roadmap
- Prioritize and refine the backlog
- Establish success metrics and measure impact
- Collaborate with stakeholders on trade-offs and priorities
- Conduct user research and validate solutions
- Communicate product strategy to the team and stakeholders
- Make go/no-go decisions at key gates

### Goals
- Maximize customer value and product-market fit
- Make clear, evidence-based prioritization decisions
- Ensure features meet user needs and business objectives
- Drive product adoption and customer satisfaction

### Typical Communication
- Weekly alignment meetings with PM and engineering leads
- Backlog refinement and prioritization sessions
- Acceptance criteria definition in issues and PRs
- Roadmap and strategy updates for stakeholders

### Interactions with Other Roles
- Partner with Project Managers on planning and delivery coordination
- Collaborate with Developers on technical feasibility and design
- Work with QA/Testing Engineers on acceptance criteria
- Align with Sponsors on strategy and resource needs
- Communicate vision and priorities to all Stakeholders

---

## Sponsor

### Role Summary
The Sponsor is an executive or senior leader who champions the project, ensures resource allocation, and represents the project at senior levels. They remove barriers and escalate issues that impact project success.

### Responsibilities
- Secure and allocate resources (team, budget, time)
- Champion project at executive level
- Remove organizational blockers
- Escalate critical issues and decisions
- Approve major scope and timeline changes
- Support project visibility and alignment with company strategy

### Goals
- Ensure project receives necessary support and resources
- Minimize organizational barriers to delivery
- Maintain strategic alignment with company priorities
- Support successful project completion

### Typical Communication
- Bi-weekly or monthly executive updates
- Escalation path for critical issues and decisions
- Milestone reviews and approval gates
- Ad-hoc communication for blockers and risks

### Interactions with Other Roles
- Receive project health updates from Project Managers
- Approve strategic direction from Product Leads
- Allocate resources and remove blockers for the delivery team
- Escalate or resolve issues raised by Project Managers and Stakeholders
- Support organizational communication about releases

---

## Security Engineer

### Role Summary
Security Engineers ensure that projects meet security requirements, implement secure coding practices, and protect customer data. They participate in threat assessment, code review, and incident response.

### Responsibilities
- Define security requirements and acceptance criteria
- Perform threat assessments and risk analysis
- Review code for security vulnerabilities
- Configure security scanning in CI/CD pipelines
- Support incident response and security escalations
- Provide security guidance and training to the team
- Participate in release reviews to validate security controls

### Goals
- Protect customer data and system integrity
- Minimize security vulnerabilities in production
- Embed security into the development lifecycle
- Enable rapid incident response and recovery

### Typical Communication
- Security requirements in planning phase
- Code review and PR comments for security issues
- Participation in incident response calls
- Post-incident reviews and action items

### Interactions with Other Roles
- Review code and architecture with Developers
- Define security acceptance criteria with Product Managers
- Validate security testing with QA/Testing Engineers
- Support project planning with Project Managers
- Coordinate with Incident Commanders during security incidents
- Escalate critical security issues to Sponsors

---

## Incident Commander

### Role Summary
The Incident Commander leads the response to production incidents, coordinates across teams, and ensures timely resolution and communication. They manage incident severity assessment, escalation, and post-incident review.

### Responsibilities
- Assess incident severity and impact
- Coordinate incident response across teams
- Ensure timely communication to stakeholders and customers
- Make decisions on rollback or mitigation strategies
- Document incident details and timeline
- Facilitate post-incident blameless retrospectives
- Track action items from incidents

### Goals
- Minimize incident duration and customer impact
- Ensure transparent communication during incidents
- Enable fast recovery through coordinated response
- Drive continuous improvement through blameless reviews

### Typical Communication
- Incident response calls and status updates
- Stakeholder and customer communication templates
- Post-incident retrospectives and action items
- Escalation for critical decisions

### Interactions with Other Roles
- Coordinate response with Developers and QA/Testing Engineers
- Escalate critical issues to Project Managers and Sponsors
- Update Stakeholders on incident status and resolution
- Work with Security Engineers on security-related incidents
- Facilitate post-incident reviews with the full delivery team
- Partner with Project Managers on impact assessment and communication

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
