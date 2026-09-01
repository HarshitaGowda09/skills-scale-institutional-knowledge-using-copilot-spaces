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

## Technical Architect

### Role Summary
Technical Architects design system architecture, evaluate technology choices, and ensure technical feasibility. They provide strategic guidance on technical solutions and help teams navigate complex technical decisions.

### Responsibilities
- Design system architecture and technology stack decisions
- Assess technical feasibility of proposed features
- Conduct technical due diligence on major initiatives
- Establish technical standards and best practices
- Provide technical mentorship to development teams
- Review and validate technical proposals

### Interactions with Existing Roles
- **With Developers**: Provides architectural guidance, reviews technical designs, and mentors on implementation patterns
- **With Project Managers**: Advises on technical risks, feasibility, and resource needs; helps set realistic technical timelines
- **With Product Managers**: Collaborates on feature requirements to ensure technical viability and optimal solutions

### Goals
- Ensure scalable, maintainable system design
- Reduce technical debt and architectural risks
- Enable teams to make informed technical decisions
- Align technology choices with business objectives

### Typical Communication
- Technical design reviews and architecture discussions
- Technical documentation and decision records
- One-on-ones with development leads and project managers

---

## Release Manager

### Role Summary
Release Managers oversee deployment coordination, release planning, and post-deployment validation. They ensure smooth transitions from development to production and coordinate all activities related to releases.

### Responsibilities
- Plan and coordinate release schedules
- Manage deployment processes and rollback procedures
- Validate production readiness and configuration
- Coordinate with QA on release testing and sign-off
- Manage release notes and deployment documentation
- Monitor post-deployment health and support incident response

### Interactions with Existing Roles
- **With Developers**: Coordinates code freeze schedules, collects deployment requirements, and communicates deployment timelines
- **With Project Managers**: Provides release status updates and escalates deployment blockers
- **With QA Lead**: Aligns on testing criteria, deployment validation, and post-release testing activities
- **With Operations/Support Lead**: Ensures production readiness and coordinates support during and after deployments

### Goals
- Execute reliable, predictable releases
- Minimize deployment-related incidents and rollbacks
- Ensure clear communication throughout release cycles
- Reduce time-to-production while maintaining quality

### Typical Communication
- Release planning meetings and deployment coordination calls
- Release notes and deployment checklists
- Post-deployment status reports and retrospectives

---

## Risk Officer / Risk Manager

### Role Summary
Risk Officers proactively identify, assess, monitor, and mitigate project risks. They provide early warning of potential issues and help teams develop mitigation strategies.

### Responsibilities
- Identify and document project risks
- Assess risk probability and impact
- Develop and track mitigation plans
- Escalate high-priority risks to Project Manager and stakeholders
- Conduct regular risk reviews and updates
- Maintain risk registers and dashboards

### Interactions with Existing Roles
- **With Project Managers**: Escalates risks, supports risk response planning, and ensures risk tracking in project governance
- **With Developers**: Identifies technical risks and collaborates on mitigation strategies
- **With Product Managers**: Highlights risks related to scope, requirements, and market factors
- **With Stakeholders**: Provides risk visibility and recommends mitigation approaches

### Goals
- Prevent or minimize project disruptions
- Enable informed decision-making through risk visibility
- Foster proactive risk culture within the team
- Improve project predictability and outcomes

### Typical Communication
- Weekly risk register reviews and updates
- Risk escalation emails and risk assessment meetings
- Risk mitigation plan discussions and progress tracking

---

## Communications Lead

### Role Summary
Communications Leads manage stakeholder communications, ensure consistent messaging, and maintain comprehensive documentation. They serve as the hub for information flow across the project and organization.

### Responsibilities
- Develop and execute stakeholder communication plans
- Create and distribute project status updates and reports
- Maintain project documentation and knowledge repositories
- Coordinate messaging across teams and stakeholders
- Manage escalations and address communication gaps
- Archive and organize project artifacts for future reference

### Interactions with Existing Roles
- **With Project Managers**: Supports status reporting and stakeholder communication
- **With All Roles**: Gathers information for updates and documentation; ensures consistent messaging across teams
- **With Stakeholders**: Delivers tailored communications based on audience needs and preferences

### Goals
- Ensure transparent, timely project communication
- Reduce information silos and miscommunication
- Maintain accessible project documentation
- Build stakeholder confidence through clear updates

### Typical Communication
- Weekly status updates and newsletters
- Stakeholder briefings and presentation decks
- Project documentation and knowledge base maintenance

---

## Product Owner

### Role Summary
Product Owners represent business requirements, prioritize work items, and make feature decisions. They bridge the gap between business needs and technical delivery.

### Responsibilities
- Define and articulate product requirements and user stories
- Prioritize backlog based on business value and customer impact
- Make feature decisions and trade-off calls
- Accept completed work and validate requirements
- Collaborate with stakeholders on roadmap alignment
- Measure and communicate feature adoption and impact

### Interactions with Existing Roles
- **With Developers**: Clarifies requirements, accepts completed work, and provides feedback on implementations
- **With Product Managers**: Collaborates on prioritization strategy and outcome measurement
- **With Project Managers**: Communicates priorities and deadline impacts on feature delivery
- **With Business Analysts**: Works closely on requirements definition and user acceptance

### Goals
- Maximize business value delivered per sprint
- Ensure clear, well-understood requirements reduce rework
- Maintain alignment between business and technical teams
- Enable fast feedback loops and course corrections

### Typical Communication
- Sprint planning and grooming sessions
- User story definitions and acceptance criteria
- Product review meetings and stakeholder updates

---

## Operations / Support Lead

### Role Summary
Operations and Support Leads ensure operational readiness for deployments and support production systems. They bridge development and production, ensuring smooth operations and rapid incident response.

### Responsibilities
- Ensure production environment readiness for deployments
- Monitor production systems and application health
- Respond to and resolve production incidents
- Maintain runbooks and operational documentation
- Coordinate with development teams on troubleshooting
- Provide operational feedback for system improvements
- Plan and execute infrastructure updates and maintenance

### Interactions with Existing Roles
- **With Release Managers**: Coordinates pre-deployment validation and production readiness checks
- **With Developers**: Provides operational feedback and collaborates on incident resolution
- **With Project Managers**: Reports on system availability and operational constraints
- **With Technical Architects**: Advises on operational implications of architecture decisions

### Goals
- Maintain high system availability and performance
- Minimize incident duration and impact
- Provide rapid, effective incident response
- Enable continuous improvement through operational insights

### Typical Communication
- Deployment coordination and readiness reviews
- Incident response calls and post-mortems
- Operational metrics and performance dashboards
- Runbook and documentation updates

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
