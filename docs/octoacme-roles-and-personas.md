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
- **QA/Testing Lead**: Collaborate on test automation strategies and acceptance criteria; receive quality feedback on PRs
- **Technical Architect/Tech Lead**: Receive design guidance and mentoring on best practices; discuss technical debt and refactoring
- **Product Managers**: Clarify requirements and acceptance criteria; provide implementation feedback
- **Project Managers**: Report progress and blockers in standups; assist with effort estimation

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
- **Developers**: Define acceptance criteria; validate implementations against user needs
- **QA/Testing Lead**: Review test coverage for feature completeness; validate user-facing quality
- **Technical Architect/Tech Lead**: Discuss technical feasibility and trade-offs; understand scalability implications
- **Project Managers**: Align on priorities and timelines; communicate roadmap to stakeholders

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
- **All Roles**: Facilitate planning, retrospectives, and status updates; escalate blockers and risks
- **Scrum Master/Agile Coach**: Coordinate on ceremonies and team health; collaborate on process improvements
- **DevOps/Infrastructure Engineer**: Coordinate deployment schedules; align on infrastructure dependencies
- **Product Managers**: Align on milestone timelines and roadmap; communicate status to stakeholders

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads ensure product quality by defining testing strategies, coordinating QA activities, and validating acceptance criteria. They work closely with developers and product managers to establish quality standards and testing scope.

### Responsibilities
- Define and maintain test plans and test cases
- Coordinate manual and automated testing efforts
- Escalate quality issues and track defect resolution
- Collaborate on acceptance criteria clarity
- Review Definition of Done compliance before merging
- Advise on test automation strategy and tooling

### Goals
- Deliver high-quality, defect-free software
- Reduce time to quality feedback in the development cycle
- Build team confidence in feature readiness

### Typical Communication
- Daily standups and sprint planning
- QA sign-off discussions on PRs and features
- Quality metrics reporting

### Interactions with Other Roles
- **Developers**: Review code for testability; provide quality feedback on PRs; collaborate on test automation
- **Product Managers**: Validate acceptance criteria completeness; confirm user-facing quality standards
- **Technical Architect/Tech Lead**: Understand system design for comprehensive test coverage planning
- **DevOps/Infrastructure Engineer**: Coordinate smoke tests for deployments; align on staging environment requirements

---

## Technical Architect / Tech Lead

### Role Summary
Technical Architects and Tech Leads provide technical direction and design oversight. They guide implementation decisions, manage technical debt, and ensure scalability and maintainability of the system.

### Responsibilities
- Design system architecture and major components
- Review design decisions for scalability and maintainability
- Guide technology and framework choices
- Mentor developers on best practices
- Identify and prioritize technical debt
- Participate in design and code reviews

### Goals
- Maintain a robust, scalable technical foundation
- Reduce rework and technical debt accumulation
- Foster a culture of technical excellence

### Typical Communication
- Technical design reviews and architecture discussions
- Code review comments and guidance
- Technical spike planning and estimation

### Interactions with Other Roles
- **Developers**: Provide architectural guidance; mentor on best practices; review complex designs
- **QA/Testing Lead**: Discuss testability implications of designs; guide test coverage strategies
- **Product Managers**: Advise on technical feasibility; highlight constraints and scalability concerns
- **DevOps/Infrastructure Engineer**: Collaborate on deployment architecture; plan for operational requirements

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate agile ceremonies, remove impediments, and coach the team on process improvements. They serve the team and help the organization adopt lean and agile practices.

### Responsibilities
- Facilitate standups, planning, retrospectives, and reviews
- Track and help resolve blockers and dependencies
- Protect the team from external distractions
- Coach the team on agile practices and continuous improvement
- Maintain sprint boards and health metrics
- Escalate process issues to leadership

### Goals
- Maximize team velocity and predictability
- Improve team cohesion and psychological safety
- Embed continuous improvement into team culture

### Typical Communication
- Agile ceremonies facilitation
- 1:1 coaching conversations
- Sprint health and velocity tracking

### Interactions with Other Roles
- **Project Managers**: Collaborate on planning and retrospectives; coordinate escalations and dependency management
- **All Team Members**: Facilitate ceremonies; remove impediments; coach on agile practices
- **Developers, QA, Technical Leads**: Monitor team health; identify and help resolve blockers

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps and Infrastructure Engineers manage deployment pipelines, infrastructure, and operational reliability. They enable fast, safe releases and ensure systems remain available and performant.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure and cloud resources
- Implement monitoring and logging
- Coordinate deployments and rollbacks
- Respond to infrastructure incidents
- Advise on operational requirements in planning

### Goals
- Enable fast, reliable deployments
- Minimize downtime and operational toil
- Maintain system performance and security

### Typical Communication
- Deployment planning and coordination
- Infrastructure design discussions
- Post-incident reviews
- Operational metrics and alerts

### Interactions with Other Roles
- **Developers**: Provide CI/CD pipeline support; advise on deployment and operational requirements
- **Technical Architect/Tech Lead**: Collaborate on deployment architecture and scalability planning
- **QA/Testing Lead**: Coordinate staging environments; run smoke tests before production deployment
- **Project Managers**: Coordinate deployment windows; manage release schedules
- **Security/Compliance Officer**: Implement security controls in pipelines; coordinate security patches and deployments

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure products and processes meet security standards and regulatory requirements. They identify risks, advise on secure design, and coordinate incident response.

### Responsibilities
- Review designs for security risks
- Conduct security testing and audits
- Manage security vulnerabilities and patch cycles
- Advise on compliance requirements
- Participate in incident response for security issues
- Maintain security policies and standards documentation

### Goals
- Protect customer data and system integrity
- Maintain compliance with regulatory requirements
- Build customer trust through security and transparency

### Typical Communication
- Security design reviews
- Vulnerability and incident reporting
- Compliance and audit coordination
- Security training and awareness

### Interactions with Other Roles
- **Developers**: Review code for security vulnerabilities; provide secure coding guidance; coordinate patch deployment
- **Technical Architect/Tech Lead**: Review architecture for security design; advise on secure technology choices
- **DevOps/Infrastructure Engineer**: Implement security controls; coordinate security patches; manage incident response
- **Product Managers**: Advise on security features and compliance requirements affecting product roadmap
- **Project Managers**: Escalate security risks; coordinate incident response communication

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the **Interactions with Other Roles** sections to understand cross-functional dependencies and collaboration points.
