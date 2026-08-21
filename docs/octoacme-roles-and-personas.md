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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (proposed additions)

Below are proposed additional personas that commonly participate in cross-functional projects. Each entry includes a role summary, core responsibilities, typical interactions with existing roles, and example decisions they own or contribute to.

### Delivery Lead

Role summary
- A delivery-focused role that coordinates sprint-level execution and optimizes workflow across teams to maintain steady delivery cadence.

Responsibilities
- Coordinate day-to-day sprint execution and board hygiene
- Identify and remove blockers that impede progress
- Monitor team flow and suggest process improvements
- Facilitate backlog refinement and sprint commitments with engineering leads

Interactions with existing roles
- PM / PdM: Translates roadmap priorities into sprint scope and flags scope/priority trade-offs
- Developers: Works closely to unblock technical impediments and align on delivery expectations
- QA: Coordinates testing effort and ensures stories are ready for verification
- Project Manager: Keeps timelines aligned and reports status, risks, and capacity constraints

Example decisions / ownership
- Owns sprint commitments and flow-related process changes
- Decides when to escalate cross-team blockers to PM/Project Manager

---

### UX Researcher / Designer

Role summary
- Focuses on user experience, research, design, and accessibility to ensure delivered features meet user needs and usability standards.

Responsibilities
- Conduct user research (qualitative and quantitative)
- Produce design artifacts, prototypes, and accessibility checks
- Define UX acceptance criteria and success metrics
- Participate in usability testing and capture feedback

Interactions with existing roles
- PdM: Partners on user needs, prioritization, and acceptance criteria
- Developers: Provides designs, component specs, and clarifications during implementation
- QA: Collaborates on usability and accessibility test cases
- Project Manager / Delivery Lead: Aligns on timelines for design work and handoffs

Example decisions / ownership
- Owns UX acceptance criteria and sign-off for usability/accessibility
- Decides when design is ready for development handoff

---

### Security Engineer

Role summary
- Ensures product and delivery meet the organizations security standards; performs threat modeling, code reviews for security, and release gating for security posture.

Responsibilities
- Conduct threat modeling and security risk assessments
- Review architecture and code for security issues
- Define security acceptance criteria and checklist for releases
- Coordinate security-related remediation and validate fixes

Interactions with existing roles
- Developers: Reviews PRs and advises on secure coding practices
- PdM / PM: Advises on security risk and required mitigations affecting scope/timeline
- Release Engineer / SRE: Works with release processes to implement security gates
- QA: Supports security testing (SAST/DAST, penetration testing coordination)

Example decisions / ownership
- Owns security sign-off for releases and security-related mitigations
- Decides acceptable risk levels for features and the need for escalation

---

### Data Analyst / Data Engineer

Role summary
- Defines instrumentation and metrics, ensures data quality, and enables measurement and experimentation to evaluate product outcomes.

Responsibilities
- Define and instrument success metrics and events
- Validate data quality and maintain data schemas
- Create dashboards and analyses to inform product decisions
- Support experiments and interpretation of results

Interactions with existing roles
- PdM: Collaborates to define meaningful success metrics and experiments
- Developers: Provides telemetry requirements and works on instrumentation implementation
- PM: Reports on metric-driven progress and outcomes for stakeholders
- QA: Helps validate that telemetry is firing correctly for tests

Example decisions / ownership
- Owns metric definitions and instrumentation quality
- Decides when data is sufficient to validate a hypothesis or rollout

---

### Release Engineer / Site Reliability Engineer (SRE)

Role summary
- Manages CI/CD, runbooks, deployment automation, and operational reliability to ensure safe and repeatable releases.

Responsibilities
- Maintain and improve CI/CD pipelines and release tooling
- Author runbooks and deployment/rollback procedures
- Coordinate and execute production deployments
- Monitor post-deploy health and respond to incidents

Interactions with existing roles
- PM / Delivery Lead: Aligns deployments with release windows and communication plans
- Developers: Works on build/release pipelines and deployment configurations
- Security Engineer: Implements security gates in the pipeline
- Stakeholder Representative: Communicates release status for client-impacting changes

Example decisions / ownership
- Owns release process and rollback decisions during incidents
- Decides deployment readiness based on pipeline and health checks

---

### Stakeholder Representative (e.g., Sales / Support Lead)

Role summary
- Represents stakeholder groups (sales, support, operations, external partners) to ensure deliverables address stakeholder constraints and downstream needs.

Responsibilities
- Provide stakeholder requirements and priority information
- Review features for stakeholder acceptance and impact
- Surface customer feedback, escalation, and support implications
- Validate release communications and enablement materials

Interactions with existing roles
- PdM / PM: Collaborates on priority, acceptance, and stakeholder sign-off
- Developers / QA: Provides real-world scenarios and acceptance from the stakeholder perspective
- Project Manager: Coordinates communication and rollout plans for stakeholders

Example decisions / ownership
- Owns stakeholder acceptance for features that impact external teams/customers
- Decides when to escalate customer-impacting issues to leadership

---

## How to add these personas to the document

When updating docs/octoacme-roles-and-personas.md, include for each persona:
- Role Summary (one or two sentences)
- Core Responsibilities (bullet list)
- Typical Interactions with existing roles (concise mapping)
- Example Decisions / Ownership (what they approve/own)

These additions are intended to clarify accountability, reduce handoff confusion, and make onboarding easier by setting explicit expectations for who to involve for security, data, UX, release, and stakeholder-related decisions.
