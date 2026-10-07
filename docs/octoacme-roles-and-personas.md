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

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate team ceremonies, coach teams in agile practices, and help remove impediments to steady delivery.

### Responsibilities
- Facilitate standups, sprint planning, reviews, and retrospectives
- Identify impediments and coordinate their resolution or escalation
- Coach the team in self-organization and continuous improvement
- Help protect planned work from avoidable interruptions and scope changes

### Goals
- Enable a collaborative, sustainable delivery pace
- Make blockers visible and resolve them quickly
- Help the team improve its practices and take ownership of commitments

### Typical Communication
- Daily standups and facilitated sprint ceremonies
- Impediment follow-ups with owners and escalation contacts
- Retrospective notes and progress on improvement actions
- Coaching conversations and process guidance

### Interactions with Other Roles
- **Project Managers:** Coordinates delivery ceremonies and raises impediments, dependencies, or schedule risks.
- **Product Managers:** Supports backlog refinement and helps the team understand sprint priorities without taking over product decisions.
- **Developers:** Facilitates collaboration, removes process blockers, and supports self-organization.
- **Technical Leads:** Coordinates technical discussion and helps surface engineering impediments.

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide technical strategy and architecture, helping ensure that solutions are maintainable, scalable, secure, and consistent with quality standards.

### Responsibilities
- Define and document architecture, design patterns, and technical trade-offs
- Guide implementation and review important technical decisions
- Establish code quality practices and support their adoption
- Identify technical risks, dependencies, and technical debt
- Mentor developers and collaborate on mitigation plans

### Goals
- Deliver reliable and maintainable solutions that meet product needs
- Keep technical risks and debt visible and manageable
- Enable developers to make consistent, well-informed design decisions

### Typical Communication
- Architecture and design reviews, including written decision records
- Code review guidance and technical mentoring
- Technical risk, dependency, and feasibility updates
- Collaboration with security and QA on design and testability

### Interactions with Other Roles
- **Developers:** Provides technical direction, reviews designs, and mentors on engineering practices.
- **Product Managers:** Evaluates feasibility and trade-offs against product outcomes and priorities.
- **Project Managers:** Communicates technical risks, dependencies, and estimates that affect delivery plans.
- **QA Leads:** Aligns on testability, quality standards, and technical approaches to validation.
- **Security / Compliance Officers:** Incorporates security requirements into architecture and design decisions.

---

## Designer / UX Lead

### Role Summary
Designers and UX Leads shape user experiences through research, interaction and visual design, and validation with users.

### Responsibilities
- Research user needs and translate findings into experience requirements
- Create and maintain flows, prototypes, and design specifications
- Test concepts and designs with users and incorporate feedback
- Collaborate on feature acceptance criteria and usability expectations
- Communicate accessibility and design-system requirements

### Goals
- Make products useful, understandable, and accessible to customers
- Validate design decisions with evidence and user feedback
- Keep the implemented experience coherent across features

### Typical Communication
- Research plans, findings, and usability test summaries
- Design reviews, prototypes, and implementation specifications
- Collaboration during feature discovery and acceptance-criteria refinement
- Feedback on usability issues discovered during delivery

### Interactions with Other Roles
- **Product Managers:** Connects user research and product outcomes to feature scope and priorities.
- **Developers:** Clarifies design intent, supports implementation, and reviews the delivered experience.
- **Project Managers:** Shares research and design dependencies that affect sequencing and milestones.
- **QA Leads:** Defines usability and accessibility checks that can be included in validation.
- **Business Analysts:** Aligns user needs and workflows with documented requirements.

---

## QA Lead / Test Manager

### Role Summary
QA Leads own the quality strategy and coordinate testing so that delivered work meets acceptance criteria and the Definition of Done.

### Responsibilities
- Define the testing approach, coverage, and quality checkpoints
- Coordinate functional, integration, regression, and exploratory testing
- Identify test data, environment, and automation needs
- Collaborate on clear, verifiable acceptance criteria
- Report defects, quality risks, and release readiness

### Goals
- Find important defects early and reduce preventable production issues
- Make quality expectations clear and consistently validated
- Provide evidence that releases meet agreed acceptance criteria

### Typical Communication
- Test plans, test results, and defect reports
- Quality and release-readiness updates during delivery
- Coordination with Developers on reproduction and remediation
- Agreement on acceptance criteria and Definition of Done

### Interactions with Other Roles
- **Developers:** Coordinates testability, defect triage, and fixes; supports a shared responsibility for quality.
- **Product Managers:** Confirms that acceptance criteria cover intended outcomes and customer needs.
- **Project Managers:** Reports quality risks and testing dependencies that may affect schedules or release decisions.
- **Technical Leads:** Aligns testing coverage with architecture, integration points, and technical risks.
- **Business Analysts:** Reviews requirements and acceptance criteria for clarity and verifiability.

---

## Business Analyst

### Role Summary
Business Analysts clarify business needs and translate them into requirements and acceptance criteria that delivery teams can understand and validate.

### Responsibilities
- Elicit and document business requirements, workflows, and constraints
- Analyze gaps, dependencies, and impacts of proposed changes
- Draft and refine acceptance criteria with product and delivery roles
- Maintain traceability between needs, requirements, and delivered outcomes
- Resolve requirement questions with relevant business and technical partners

### Goals
- Ensure the team is solving the right business problem
- Reduce ambiguity and rework through shared understanding
- Make requirements testable and aligned with desired outcomes

### Typical Communication
- Requirements, process maps, and decision records
- Workshops and backlog refinement sessions
- Acceptance-criteria reviews and answers to delivery-team questions
- Updates when business rules or assumptions change

### Interactions with Other Roles
- **Product Managers:** Turns product outcomes and priorities into detailed requirements and supports backlog refinement.
- **Developers:** Clarifies business rules, edge cases, and expected behavior during implementation.
- **Project Managers:** Shares requirements dependencies and decision needs that may affect plans and risks.
- **QA Leads:** Ensures requirements and acceptance criteria can be validated.
- **Stakeholders / Sponsors:** Confirms business needs, constraints, and expected value.

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers help ensure that project decisions and delivered systems meet applicable security, privacy, and regulatory requirements.

### Responsibilities
- Identify applicable security, privacy, and compliance requirements
- Advise on threat assessments, controls, and risk mitigation
- Review designs and delivery plans for security and compliance concerns
- Escalate material risks and coordinate remediation with accountable owners
- Support audit readiness and communicate relevant policy changes

### Goals
- Protect users, systems, and data from avoidable harm
- Meet applicable regulatory and organizational obligations
- Integrate risk reduction into delivery without unnecessary delay

### Typical Communication
- Security requirements and control guidance
- Threat assessment and compliance review findings
- Risk and remediation updates with clear owners
- Timely escalation of incidents or unresolved high-impact risks

### Interactions with Other Roles
- **Developers:** Provides implementation guidance and collaborates on remediation of identified issues.
- **Technical Leads:** Reviews security implications of architecture and design decisions.
- **Product Managers:** Clarifies security and compliance constraints that affect feature scope and priorities.
- **Project Managers:** Communicates risk severity, remediation ownership, and schedule implications.
- **QA Leads:** Coordinates security testing and verification of relevant controls.

---

## Support / Customer Success Lead

### Role Summary
Support and Customer Success Leads represent customer experience after delivery, bringing support trends, usability feedback, and operational needs into project decisions.

### Responsibilities
- Gather and summarize customer feedback, support cases, and recurring issues
- Escalate urgent customer-impacting problems through agreed channels
- Identify product usability and documentation gaps from customer interactions
- Share release readiness, known issues, and support needs with customer-facing teams
- Track feedback themes and follow up on agreed product actions

### Goals
- Improve customer outcomes and reduce recurring customer friction
- Ensure customer-impacting issues are visible and handled promptly
- Close the feedback loop between customers and delivery teams

### Typical Communication
- Customer feedback summaries and support trend reports
- Escalations for incidents or high-impact usability issues
- Release notes, known-issue updates, and support readiness reviews
- Feedback discussions with product and delivery teams

### Interactions with Other Roles
- **Product Managers:** Shares customer feedback and support trends to inform roadmap and backlog priorities.
- **Developers:** Provides reproducible customer issues and validates that fixes address reported problems.
- **Project Managers:** Escalates customer-impacting risks and coordinates communication or support readiness.
- **QA Leads:** Shares real-world scenarios and recurring issues to inform test coverage.
- **Designers / UX Leads:** Connects customer usability feedback to research and design improvements.

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders provide business context and input; a Sponsor is an executive or business owner accountable for strategic alignment, funding, and key decisions.

### Responsibilities
- Explain business objectives, constraints, and expected outcomes
- Provide timely input and decisions within their area of accountability
- Sponsors secure or confirm funding, set strategic priorities, and resolve escalated trade-offs
- Review progress and outcomes against agreed success measures
- Identify affected groups and support organizational readiness for change

### Goals
- Ensure the initiative supports strategic and business objectives
- Make priority and funding decisions using clear evidence
- Realize the expected value and understand material delivery risks

### Typical Communication
- Project kickoff, milestone, and outcome reviews
- Monthly status updates and escalation of significant risks or decisions
- Business-case, funding, priority, and scope discussions
- Product and project updates on progress against success measures

### Interactions with Other Roles
- **Product Managers:** Aligns on strategic outcomes, customer value, and priority decisions.
- **Project Managers:** Receives status and escalations, and helps resolve cross-organizational dependencies.
- **Developers:** Provides business context through product and project leads rather than directing implementation details.
- **Business Analysts:** Confirms business needs, assumptions, and acceptance expectations.
- **Support / Customer Success Leads:** Considers customer feedback and operational impact when evaluating outcomes.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
