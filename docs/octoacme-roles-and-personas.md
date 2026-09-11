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
- Collaborate with **Technical Lead/Architect** on design review feedback and best practices
- Work with **QA/Testing Specialist** to define test strategies and validate acceptance criteria
- Receive guidance from **Product Managers** on acceptance criteria and priority
- Coordinate with **Release/DevOps Engineer** on deployment requirements and CI/CD pipelines
- Participate in security code reviews led by **Security/Compliance Officer**

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
- Define requirements for **Developers** and translate them into acceptance criteria
- Work with **Project Managers** to align timelines and dependencies
- Brief **Stakeholder/Sponsor** on roadmap and business impact
- Collaborate with **QA/Testing Specialist** to define quality expectations and test coverage
- Consult with **Security/Compliance Officer** on regulatory and security requirements

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
- Facilitate collaboration between **Product Managers**, **Developers**, and **Technical Lead/Architect**
- Track dependencies involving **Release/DevOps Engineer** and deployment timelines
- Escalate security and compliance issues from **Security/Compliance Officer**
- Coordinate with **Stakeholder/Sponsor** on approvals and business constraints
- Work with **QA/Testing Specialist** to ensure quality gates and release readiness

---

## QA/Testing Specialist

### Role Summary
QA and Testing Specialists ensure quality standards are met through systematic testing, validation of acceptance criteria, and defect management. They collaborate with developers and product managers to define test strategies and maintain quality gates.

### Responsibilities
- Design and execute test plans and test cases
- Validate acceptance criteria are met before release
- Perform manual and automated testing (unit, integration, end-to-end)
- Report and triage defects with clear reproduction steps
- Participate in release readiness reviews and smoke testing
- Provide quality metrics and test coverage reports

### Goals
- Ensure features meet quality standards before release
- Reduce production defects and rework
- Improve test coverage and automation

### Typical Communication
- Sprint planning and retrospectives
- Quality gates and release sign-offs
- Defect reports and test status updates

### Interactions with Other Roles
- Partner with **Developers** to understand implementation details and identify test scenarios
- Validate acceptance criteria defined by **Product Managers**
- Work with **Technical Lead/Architect** to plan testing for complex technical changes
- Coordinate with **Release/DevOps Engineer** on smoke tests and deployment verification
- Support **Security/Compliance Officer** in security testing and vulnerability validation
- Report test status and quality metrics to **Project Managers**

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide technical direction, make architectural decisions, and guide the technical implementation of complex features. They ensure solutions are scalable, maintainable, and aligned with system design standards.

### Responsibilities
- Guide technical design and architecture decisions
- Review and approve technical design documents
- Mentor developers on best practices and technical standards
- Identify and mitigate technical risks
- Ensure code quality and system reliability
- Participate in complex problem-solving and performance optimization

### Goals
- Deliver technically sound, scalable solutions
- Build and maintain high code quality standards
- Reduce technical debt and system complexity

### Typical Communication
- Design reviews and architecture discussions
- Technical risk assessment during planning
- Code reviews and mentoring

### Interactions with Other Roles
- Mentor and guide **Developers** on architectural patterns and technical best practices
- Collaborate with **Product Managers** on feasibility and technical trade-offs
- Work with **Project Managers** to identify and mitigate technical risks
- Advise **Release/DevOps Engineer** on infrastructure and deployment architecture requirements
- Support **Security/Compliance Officer** on secure architecture patterns
- Consult with **QA/Testing Specialist** on testability and test strategy for complex systems

---

## Release/DevOps Engineer

### Role Summary
Release and DevOps Engineers manage deployment pipelines, infrastructure, and the release process. They ensure smooth, reliable deployments and maintain system observability and incident response capabilities.

### Responsibilities
- Build and maintain CI/CD pipelines
- Execute deployments and rollbacks
- Manage infrastructure and environment configurations
- Monitor system health and performance metrics
- Participate in incident response and post-incident reviews
- Document deployment procedures and runbooks

### Goals
- Enable frequent, reliable deployments
- Minimize deployment risk and downtime
- Maintain high system availability and observability

### Typical Communication
- Release planning and pre-deployment reviews
- Deployment status and incident updates
- Infrastructure and pipeline improvements

### Interactions with Other Roles
- Support **Developers** with CI/CD pipeline maintenance and deployment guidance
- Work with **Technical Lead/Architect** on infrastructure design and deployment architecture
- Coordinate with **Project Managers** on release timelines and deployment windows
- Participate in release readiness reviews led by **QA/Testing Specialist**
- Support **Security/Compliance Officer** on infrastructure security and compliance controls
- Notify **Product Managers** and **Stakeholder/Sponsor** of deployment status and incidents

---

## Security/Compliance Officer

### Role Summary
Security and Compliance professionals ensure that projects adhere to security standards, regulatory requirements, and organizational policies. They identify security risks and guide secure implementation practices.

### Responsibilities
- Review designs and code for security vulnerabilities
- Ensure compliance with regulatory and organizational standards
- Perform or coordinate security scanning and assessments
- Manage incident response for security-related issues
- Provide security guidance and best practices
- Maintain security documentation and audit trails

### Goals
- Prevent security breaches and data loss
- Ensure regulatory compliance
- Build security into development practices

### Typical Communication
- Security design reviews
- Vulnerability reports and incident response
- Compliance and audit documentation

### Interactions with Other Roles
- Review designs and code with **Developers** and **Technical Lead/Architect** for security vulnerabilities
- Advise **Product Managers** on compliance requirements and security-related features
- Escalate security risks and compliance issues to **Project Managers**
- Coordinate security testing with **QA/Testing Specialist**
- Work with **Release/DevOps Engineer** on infrastructure security and secure deployment practices
- Brief **Stakeholder/Sponsor** on security posture and compliance status

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide strategic direction, business context, and approvals for projects. They ensure projects deliver business value and maintain alignment with organizational priorities.

### Responsibilities
- Define business objectives and success criteria
- Provide approvals and decision-making authority
- Communicate business priorities and constraints
- Monitor project ROI and business outcomes
- Escalate issues and changes through proper governance

### Goals
- Ensure projects deliver business value
- Maintain strategic alignment
- Minimize business risk

### Typical Communication
- Monthly stakeholder updates
- Milestone reviews and approvals
- Executive escalations and decision points

### Interactions with Other Roles
- Provide strategic direction and business context to **Product Managers**
- Review project status and outcomes with **Project Managers**
- Approve scope changes and resource decisions impacting **Developers** and **Technical Lead/Architect**
- Receive compliance and security briefings from **Security/Compliance Officer**
- Review release impact and business results from **Release/DevOps Engineer**
- Approve quality gates and release decisions involving **QA/Testing Specialist**

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the "Interactions with Other Roles" sections to understand cross-functional dependencies and communication patterns.
