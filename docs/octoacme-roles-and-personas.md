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

## Scrum Masters

### Role Summary
Scrum Masters enable effective team execution by facilitating agile ceremonies, removing impediments, and coaching teams on healthy delivery habits.

### Responsibilities
- Facilitate standups, planning, reviews, and retrospectives
- Surface and remove blockers with Developers and Project Managers
- Coach teams on sprint focus, flow, and continuous improvement
- Protect team capacity by helping limit unplanned work

### Goals
- Improve predictability and team throughput
- Reduce delivery friction and recurring blockers
- Strengthen team accountability and learning loops

### Typical Communication
- Daily coordination with Developers during standups
- Weekly syncs with Project Managers and Product Managers on blockers and delivery health
- Retrospective action tracking shared with QA/Testing and Stakeholders

### Collaboration and Handoffs
- Works with Product Managers before sprint planning to ensure backlog items are clear enough to start.
- Partners with Project Managers to escalate unresolved blockers and dependency risks.
- Hands retrospective actions to Developers and QA/Testing as owned follow-up tasks for the next iteration.

---

## UX Designers

### Role Summary
UX Designers shape user-centered solutions by translating product goals into usable workflows, interaction patterns, and validated designs.

### Responsibilities
- Run discovery activities and usability evaluations
- Produce wireframes, prototypes, and UX acceptance notes
- Collaborate with Product Managers on problem framing and success criteria
- Support Developers during implementation with design clarifications

### Goals
- Improve usability, adoption, and task success rates
- Reduce rework caused by unclear user flows
- Ensure solutions are accessible and intuitive

### Typical Communication
- Discovery and design review sessions with Product Managers and Stakeholders
- Design handoff walkthroughs with Developers and QA/Testing
- Ongoing feedback loops after demos and usability checks

### Collaboration and Handoffs
- Receives prioritized problem statements from Product Managers and turns them into actionable design artifacts.
- Hands approved designs and UX acceptance notes to Developers and QA/Testing before implementation starts.
- Aligns with Project Managers on scope/timeline trade-offs when design complexity impacts milestones.

---

## Release Managers

### Role Summary
Release Managers coordinate release readiness, deployment sequencing, and release communications so teams can ship safely and predictably.

### Responsibilities
- Build and maintain release calendars and cutover plans
- Coordinate go/no-go readiness checks with QA/Testing and DevOps Engineers
- Ensure release notes, rollout steps, and rollback plans are complete
- Drive release communications to Stakeholders and support teams

### Goals
- Minimize release risk and production disruptions
- Improve release predictability and transparency
- Shorten time from code complete to customer availability

### Typical Communication
- Release readiness reviews with Developers, QA/Testing, and DevOps Engineers
- Schedule and dependency alignment with Project Managers and Product Managers
- Release announcements and post-release summaries for Stakeholders

### Collaboration and Handoffs
- Takes implementation-complete scope from Project Managers/Product Managers and converts it into an executable release plan.
- Confirms QA/Testing sign-off and hands deployment execution to DevOps Engineers.
- Provides release status and outcomes back to Project Managers and Stakeholders for project reporting.

---

## DevOps Engineers

### Role Summary
DevOps Engineers build and operate delivery pipelines, environments, and observability foundations that keep releases reliable and recoverable.

### Responsibilities
- Maintain CI/CD pipelines and deployment automation
- Manage infrastructure configuration, environments, and secrets workflows
- Implement monitoring, alerting, and operational runbooks
- Support incident response, rollback, and reliability improvements

### Goals
- Increase deployment reliability and speed
- Reduce failed changes and recovery time
- Provide clear operational visibility for delivery teams

### Typical Communication
- Pipeline and environment updates with Developers and QA/Testing
- Release execution coordination with Release Managers
- Incident and reliability reporting with Project Managers and Stakeholders

### Collaboration and Handoffs
- Receives deployable artifacts and release plans from Developers and Release Managers.
- Hands environment readiness and deployment verification results to QA/Testing and Release Managers.
- Escalates operational risks to Project Managers when reliability constraints threaten project milestones.

---

## Subject Matter Experts (SMEs)

### Role Summary
Subject Matter Experts provide domain-specific guidance that improves requirement accuracy, feasibility decisions, and compliance with specialized constraints.

### Responsibilities
- Validate domain assumptions, workflows, and edge cases
- Review requirements and acceptance criteria for domain correctness
- Support trade-off decisions where domain risk is high
- Contribute to release readiness for domain-impacting changes

### Goals
- Reduce defects caused by domain misunderstandings
- Improve fit between delivered features and real-world needs
- Increase confidence in high-impact decisions

### Typical Communication
- Requirement and refinement sessions with Product Managers and Developers
- Milestone reviews with Project Managers and Stakeholders
- Domain validation checkpoints during QA/Testing and release preparation

### Collaboration and Handoffs
- Receives early requirements from Product Managers and returns domain-approved constraints and acceptance guidance.
- Works with Developers and QA/Testing to clarify edge cases before implementation and test execution.
- Flags domain risks to Project Managers and Stakeholders for decision or escalation when trade-offs are required.

---

## Cross-role collaboration and handoff points
- **Discovery -> Planning:** Product Managers and UX Designers align on problem framing, then hand prioritized and design-ready backlog items to Developers.
- **Planning -> Execution:** Project Managers and Scrum Masters confirm capacity, dependencies, and sprint goals; Developers and QA/Testing receive committed scope.
- **Execution -> Release Readiness:** Developers complete implementation, QA/Testing provides acceptance sign-off, and Release Managers consolidate go/no-go criteria.
- **Release Readiness -> Deployment:** Release Managers hand approved release plans to DevOps Engineers for deployment execution and post-deploy verification.
- **Deployment -> Outcome Review:** DevOps Engineers and Release Managers report release health; Product Managers, SMEs, and Project Managers assess outcomes and follow-up actions.

## Why these additional personas improve outcomes
- Clear role boundaries reduce ownership gaps and duplicated effort.
- Explicit handoff points reduce delays between planning, build, testing, and release.
- Dedicated release and DevOps ownership improves delivery reliability and recovery speed.
- Embedded UX and SME participation improves usability and domain fit before launch.
- Scrum Master facilitation improves team flow, blocker resolution, and continuous improvement.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
