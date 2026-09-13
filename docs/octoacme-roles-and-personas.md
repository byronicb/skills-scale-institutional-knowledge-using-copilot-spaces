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
- **Product Managers**: Receive feature specifications and acceptance criteria; provide implementation estimates and technical constraints
- **Project Managers**: Report progress and blockers in standups; participate in sprint planning
- **QA / Test Lead**: Collaborate on test plans and acceptance criteria; review test results
- **Technical Architect**: Align on design decisions and technical standards; request architectural guidance
- **UX / Design Lead**: Implement UI designs; provide feedback on feasibility and technical trade-offs

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
- **Developers**: Define feature requirements and acceptance criteria; review implementation against specs
- **Project Managers**: Align on scope, timeline, and priorities; collaborate on release planning
- **Stakeholders / Sponsors**: Present roadmap and gather business requirements; report on metrics and impact
- **UX / Design Lead**: Collaborate on user experience and design validation
- **QA / Test Lead**: Define acceptance criteria and success metrics; review quality against product goals

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
- **Developers**: Track progress and blockers; manage capacity and sprint planning
- **Product Managers**: Align on priorities and timelines; manage scope trade-offs
- **Stakeholders / Sponsors**: Escalate risks and blockers; report status and milestones
- **DevOps / Platform Engineer**: Coordinate deployment schedules and infrastructure readiness
- **Scrum Master / Agile Coach**: Partner on process execution and team health monitoring

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate Agile ceremonies, remove team blockers, and coach the organization on process improvements and continuous learning. They act as servants to the team and help create a psychologically safe, high-performing environment.

### Responsibilities
- Facilitate daily standups, sprint planning, sprint reviews, and retrospectives
- Remove or escalate blockers that impede team progress
- Coach the team on Agile practices and continuous improvement
- Track and report on team health, velocity, and sprint metrics
- Mentor team members on self-organization and collaboration
- Help identify and resolve process bottlenecks

### Goals
- Enable the team to self-organize and deliver incrementally
- Foster psychological safety and open communication
- Maximize team velocity and reduce cycle time
- Drive continuous improvement culture

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-one coaching and mentoring
- Retrospective facilitation and follow-up action tracking
- Team health dashboards and metrics reporting
- Process improvement discussions

### Interactions with Other Roles
- **Developers**: Coach on collaboration and self-organization; remove blockers; track individual and team velocity
- **Project Managers**: Partner on sprint planning and capacity management; escalate risks and dependencies
- **Product Managers**: Facilitate backlog prioritization; ensure team understands acceptance criteria
- **All Roles**: Create psychological safety; facilitate communication and conflict resolution

---

## QA / Test Lead

### Role Summary
QA and Test Leads define testing strategies, develop test plans, and ensure quality standards are met throughout the development lifecycle. They collaborate with Product and Development teams to validate that features meet acceptance criteria and deliver a reliable product experience.

### Responsibilities
- Define testing strategy and test plans for features and releases
- Develop and maintain automated and manual test suites
- Validate acceptance criteria and feature readiness before release
- Identify, triage, and track defects and quality issues
- Report on test coverage and quality metrics
- Collaborate on Definition of Done and quality standards
- Lead QA for critical flows and smoke tests before release

### Goals
- Ensure features meet acceptance criteria and quality standards
- Reduce defects and regressions in production
- Enable fast, confident releases through reliable testing
- Improve test coverage and observability

### Typical Communication
- Sprint planning and backlog refinement
- Test plan reviews and QA status updates
- Defect tracking and escalation
- Pre-release readiness reviews and smoke test execution
- Quality metrics and retrospective discussions

### Interactions with Other Roles
- **Developers**: Collaborate on test plans and acceptance criteria; review test results; triage bugs
- **Product Managers**: Validate that features meet product requirements; define acceptance criteria together
- **Project Managers**: Report on test readiness; identify quality-related risks and timelines
- **Technical Architect**: Align on test infrastructure and automation frameworks
- **DevOps / Platform Engineer**: Coordinate test environment setup and deployment testing

---

## Technical Architect

### Role Summary
Technical Architects provide technical vision, design guidance, and risk mitigation for complex projects. They ensure that solutions are scalable, performant, reliable, and aligned with technical standards and long-term strategy. They bridge product requirements with technical feasibility.

### Responsibilities
- Define technical architecture and design patterns for major features or systems
- Conduct technical design reviews and provide feedback on implementation approaches
- Identify and mitigate technical risks (scalability, performance, security, reliability)
- Ensure solutions align with platform standards and best practices
- Advise on technology choices and trade-offs
- Document architectural decisions and rationale

### Goals
- Ensure systems are scalable, performant, and maintainable
- Reduce technical debt and prevent architectural regressions
- Enable fast, reliable delivery through sound design
- Build confidence in the technical direction

### Typical Communication
- Technical design reviews and architecture discussions
- RFCs (Request for Comments) and decision documentation
- Risk assessments and mitigation planning
- Mentoring and knowledge sharing on technical practices
- Cross-team architecture alignment

### Interactions with Other Roles
- **Developers**: Provide architectural guidance; review design decisions; mentor on technical standards
- **Project Managers**: Identify technical risks and dependencies; advise on timeline impacts
- **QA / Test Lead**: Align on test infrastructure and quality requirements
- **DevOps / Platform Engineer**: Collaborate on infrastructure and scalability requirements
- **Product Managers**: Advise on technical feasibility and trade-offs

---

## UX / Design Lead

### Role Summary
UX and Design Leads own the user experience and visual design of products and features. They conduct user research, create designs that are both usable and visually compelling, and collaborate with Product and Development teams to ensure design feasibility and quality.

### Responsibilities
- Conduct user research and usability testing to inform design decisions
- Create wireframes, prototypes, and high-fidelity designs
- Define design systems and user experience standards
- Collaborate with Product and Development on design feasibility
- Iterate designs based on user feedback and team input
- Ensure accessibility and inclusive design practices
- Review and approve implementations against design specifications

### Goals
- Maximize user satisfaction and usability
- Create consistent, delightful user experiences
- Enable fast design iteration and validation
- Improve accessibility and inclusive design

### Typical Communication
- User research and usability testing sessions
- Design reviews and feedback with stakeholders
- Design handoff and implementation guidance to developers
- Accessibility and design system discussions
- User feedback synthesis and iteration cycles

### Interactions with Other Roles
- **Product Managers**: Validate user needs and research findings; align on design priorities
- **Developers**: Provide design specifications and implementations; iterate based on feasibility feedback
- **Project Managers**: Coordinate design timelines and dependencies
- **QA / Test Lead**: Ensure visual and usability acceptance criteria are met
- **Stakeholders / Sponsors**: Present design direction and incorporate feedback

---

## DevOps / Platform Engineer

### Role Summary
DevOps and Platform Engineers manage infrastructure, CI/CD pipelines, and deployment processes. They ensure systems are reliable, observable, and secure while enabling fast, confident releases. They provide platforms and tools that allow development teams to build, test, and deploy efficiently.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and automation
- Manage cloud infrastructure, configuration, and deployment
- Ensure system monitoring, observability, and incident response
- Manage security scanning and compliance in deployment pipelines
- Support rollback and disaster recovery processes
- Optimize infrastructure performance and cost
- Provide self-service tools and platforms for development teams

### Goals
- Enable fast, reliable, and secure deployments
- Reduce deployment risk and incident impact
- Maximize system uptime and performance
- Improve team velocity through automation

### Typical Communication
- Deployment planning and release coordination
- Incident response and postmortems
- Infrastructure and pipeline improvements
- Security and compliance discussions
- Performance and observability dashboards

### Interactions with Other Roles
- **Project Managers**: Coordinate deployment schedules and infrastructure readiness
- **Developers**: Provide deployment tools and infrastructure; troubleshoot deployment issues
- **QA / Test Lead**: Set up test environments and deployment testing
- **Technical Architect**: Align on infrastructure architecture and scalability requirements
- **Stakeholders / Sponsors**: Report on system reliability and deployment readiness

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic direction, and approval authority for projects. They represent customer interests, business goals, and organizational priorities. They help teams understand the "why" behind work and provide governance and escalation paths.

### Responsibilities
- Define business requirements and success criteria
- Provide project approval and strategic alignment
- Escalate business-impacting risks and issues
- Communicate project status to leadership and customers
- Ensure alignment between project goals and organizational strategy
- Provide feedback and validate solution value
- Make trade-off decisions when necessary

### Goals
- Ensure projects deliver business value and customer impact
- Minimize business risk and maintain stakeholder alignment
- Enable fast decision-making and unblock teams
- Maximize return on investment

### Typical Communication
- Project approval and kickoff meetings
- Milestone reviews and status updates
- Escalation and decision-making forums
- Stakeholder alignment and leadership briefings
- Post-release retrospectives and value realization reviews

### Interactions with Other Roles
- **Project Managers**: Receive status updates and escalations; approve milestones and scope changes
- **Product Managers**: Provide business context and strategy; validate product roadmap
- **Developers**: Understand business impact and customer context
- **All Roles**: Provide executive visibility and escalation path; unblock decisions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interactions with Other Roles" section to understand cross-functional dependencies and communication patterns.
