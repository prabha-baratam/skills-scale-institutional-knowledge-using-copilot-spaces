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

## Project Sponsor

### Role Summary
Project Sponsors provide executive sponsorship, funding alignment, and strategic direction for the initiative. They approve major scope, timing, and priority decisions and help resolve organizational dependencies.

### Responsibilities
- Confirm business value, funding, and strategic alignment
- Support go/no-go decisions for major milestones or investments
- Escalate cross-functional blockers and leadership decisions
- Review outcomes against organizational objectives
- Provide executive sponsorship during risk, change, or escalation events

### Goals
- Ensure the project delivers strategic value
- Maintain alignment between business stakeholders and delivery teams
- Support timely decision-making and resource prioritization

### Typical Communication
- Steering committee updates and leadership briefings
- Milestone and portfolio reviews
- Escalation notifications for major risks, decisions, or changes in scope

### Interaction with Existing Roles
- The Sponsor works with the Project Manager on timing, trade-offs, and escalations.
- The Sponsor aligns with the Product Manager on business priorities and success measures.
- The Sponsor supports leaders and stakeholders without replacing day-to-day delivery ownership.

---

## Business Analyst

### Role Summary
Business Analysts clarify business needs, capture requirements, and translate them into clear scope, acceptance criteria, and decision-ready inputs for product and delivery teams.

### Responsibilities
- Gather and document stakeholder requirements and business processes
- Translate stakeholder needs into testable acceptance criteria
- Identify gaps, dependencies, and operational constraints
- Support prioritization and scope trade-offs with product and project leads
- Maintain traceability between requirements, decisions, and outcomes

### Goals
- Improve clarity, consistency, and quality of requirements
- Reduce ambiguity that causes rework or missed expectations
- Support measurable value delivery for stakeholders and users

### Typical Communication
- Requirement workshops and stakeholder interviews
- Backlog refinement and acceptance criteria reviews
- Documentation updates and process clarifications

### Interaction with Existing Roles
- The Business Analyst partners with the Product Manager to define and validate user and business outcomes.
- They help Developers and QA/testing by making requirements concrete and testable.
- They support the Project Manager by documenting dependencies, decision points, and stakeholder impacts.

---

## UX/UI or Product Designer

### Role Summary
UX/UI or Product Designers represent the user experience and ensure that solutions are usable, accessible, and aligned with customer needs.

### Responsibilities
- Define user flows, interaction patterns, and visual design direction
- Validate usability and accessibility considerations
- Partner with product and engineering on design feasibility and trade-offs
- Provide design rationale and review acceptance criteria for usability outcomes
- Help translate customer insights into product experiences

### Goals
- Deliver intuitive, accessible user experiences
- Align product decisions with user needs and business goals
- Improve adoption and customer satisfaction

### Typical Communication
- Design reviews and stakeholder workshops
- Product discovery and user research sessions
- Collaboration during sprint planning and QA acceptance checks

### Interaction with Existing Roles
- The Product Designer works closely with the Product Manager to ensure the product direction matches customer value.
- They collaborate with Developers and QA/testing on implementation, usability validation, and acceptance checks.
- They inform the Project Manager on design dependencies and review needs that may affect timelines.

---

## Technical Lead / Architect

### Role Summary
Technical Leads or Architects guide technical direction, platform decisions, and design quality across the project. They help balance delivery speed with maintainability, scalability, and risk.

### Responsibilities
- Define or guide system architecture and technical standards
- Review design decisions and technical trade-offs
- Identify technical dependencies, risks, and mitigation options
- Support engineering decisions during planning, implementation, and integration
- Help coordinate technical validation and readiness for release

### Goals
- Deliver sustainable technical solutions
- Reduce architecture-related delivery risk
- Maintain system quality, security, and long-term maintainability

### Typical Communication
- Architecture reviews and technical design sessions
- Technical risk updates and dependency reviews
- Alignment with engineering leads and release planning discussions

### Interaction with Existing Roles
- The Technical Lead partners with Developers to ensure implementation matches the target design and standards.
- They provide strategic input to the Product Manager and Project Manager on feasibility, scope, and technical sequencing.
- They work with Security/Privacy and DevOps roles to ensure systems are secure, observable, and release-ready.

---

## DevOps / Release Engineer

### Role Summary
DevOps or Release Engineers support environment readiness, automation, deployment, observability, and rollback activities to help teams deliver reliably and safely.

### Responsibilities
- Support CI/CD pipelines and release automation
- Manage environment configuration, deployment readiness, and rollback planning
- Monitor production health and observability signals
- Coordinate deployment windows and release verification steps
- Support operational readiness for new features or service changes

### Goals
- Improve delivery reliability and deployment safety
- Reduce manual operational friction and incident recovery time
- Enable faster, repeatable releases with clear guardrails

### Typical Communication
- Release planning and deployment readiness meetings
- Incident coordination and rollback reviews
- CI/CD and platform health updates

### Interaction with Existing Roles
- The DevOps/Release Engineer works with Developers on build, deployment, and environment configuration.
- They coordinate with QA/testing and the Project Manager to confirm release readiness and operational checks.
- They support the Product Manager and Sponsor by making release risks visible and measurable.

---

## Security / Privacy Representative

### Role Summary
Security and Privacy Representatives protect the organization and users by ensuring that project work follows security, privacy, and compliance expectations.

### Responsibilities
- Review security and privacy risks for products, services, and data handling
- Support threat modeling, secure design, and control implementation
- Confirm compliance needs and required review checkpoints
- Help define mitigations and incident response considerations
- Validate release readiness from a risk and compliance perspective

### Goals
- Reduce exposure to security and privacy risk
- Ensure appropriate controls are embedded in the design and delivery process
- Protect user trust and organizational compliance

### Typical Communication
- Security review checkpoints and risk assessments
- Privacy and compliance alignment meetings
- Release and incident guidance discussions

### Interaction with Existing Roles
- The Security/Privacy Representative collaborates with the Technical Lead and Developers to review architecture and implementation decisions.
- They advise the Product Manager and Project Manager on required controls, timing, and risk trade-offs.
- They support QA/testing and release activities by validating mitigation and readiness expectations.

---

## Customer / Support Representative

### Role Summary
Customer or Support Representatives translate real-world user and support experience into product and delivery decisions. They provide feedback on customer pain points, operational needs, and service quality.

### Responsibilities
- Share customer feedback, support trends, and service insights
- Help identify user pain points and operational risks
- Contribute to issue triage, release readiness, and customer-facing communication
- Recommend changes based on customer experience and support patterns
- Support stakeholder alignment on user impact and communication needs

### Goals
- Improve customer satisfaction and issue resolution quality
- Ensure customer realities influence product decisions
- Reduce avoidable support burden and rework

### Typical Communication
- Customer feedback reviews and support trend analysis
- Release readiness and issue triage discussions
- Stakeholder updates on customer impact and adoption concerns

### Interaction with Existing Roles
- The Customer/Support Representative informs the Product Manager on customer priorities and pain points.
- They work with the Project Manager to surface customer-impacting risks and communication needs.
- They partner with QA/testing and Developers to validate real-world usability and problem resolution.

---

## Data / Analytics Representative

### Role Summary
Data and Analytics Representatives help teams define metrics, instrumentation, and success measurement so delivery decisions are grounded in evidence.

### Responsibilities
- Define key metrics, instrumentation, and reporting needs
- Support analysis of product or service outcomes
- Translate operational and business data into insights for prioritization
- Validate that a feature or change is producing the intended effects
- Support post-launch analysis and continuous improvement work

### Goals
- Improve decision quality with measurable evidence
- Validate whether outcomes meet business and customer intent
- Support informed iteration and optimization

### Typical Communication
- Metrics reviews and product reporting meetings
- Success criteria validation and dashboard reviews
- Post-release analysis and continuous improvement discussions

### Interaction with Existing Roles
- The Data/Analytics Representative partners with the Product Manager to define measurable outcomes.
- They support the Project Manager and Sponsor by clarifying whether milestones and objectives are being met.
- They work with Developers and QA/testing to ensure instrumentation, test coverage, and validation data are available.

---

## Role Interaction Summary
The personas above are meant to clarify where responsibility, accountability, and collaboration exist across a project. In practice, a single person may cover multiple roles on small teams, while larger teams may split them across distinct functions. The shared goal is clear ownership:

- Product Managers define value and priority.
- Project Managers coordinate schedule, risk, dependencies, and communication.
- Developers build and validate the solution.
- Technical Leads and Architects guide technical quality and feasibility.
- Business Analysts, Designers, and Data/Analytics partners ensure requirements, user experience, and metrics are clear.
- Security, DevOps, and Customer/Support roles contribute specialist input necessary for successful delivery and operational readiness.
- Sponsors provide strategic sponsorship and decision-making support at the leadership level.

A well-defined role model helps teams reduce ambiguity, speed up decision-making, and improve accountability across initiation, planning, execution, release, and retrospective activities.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

