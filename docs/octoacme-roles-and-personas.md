# OctoAcme Personas

This document defines the typical roles, responsibilities, boundaries, artifacts, and collaboration patterns used across OctoAcme project docs and exercises.

## Lifecycle phases referenced in this document
- Initiation
- Planning
- Execution & Tracking
- Risk & Communication Management
- Release & Deployment
- Retrospectives & Continuous Improvement

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and technical documentation
- Participate in design, security, and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Decision Rights and Boundaries
- Decide implementation details, test approach, and day-to-day technical execution within agreed scope
- Raise trade-offs that affect timeline, architecture, security, or user experience
- Do not unilaterally change business priorities, release gates, or acceptance criteria

### Required Artifacts
- Pull requests linked to backlog items or issues
- Test evidence and implementation notes
- Technical design notes when changes are complex or cross-cutting

### Lifecycle Involvement
- Primary: Planning, Execution & Tracking, Release & Deployment, Retrospectives & Continuous Improvement
- Supporting: Initiation, Risk & Communication Management

### Interactions and Handoffs
- Work with Product Managers to clarify requirements and acceptance criteria
- Work with Project Managers to estimate effort, flag blockers, and update delivery status
- Hand off completed work and test evidence to QA/Test Lead for verification when applicable
- Partner with Technical Lead/Architect, Security/Privacy Representative, and Operations/SRE or Release Manager on readiness and risk reduction

### Escalation Expectations
- Escalate blockers, dependency risks, or production-impacting defects through the team lead and Project Manager
- Immediately surface security, privacy, or reliability concerns to the relevant specialists and PM

### Measures of Effective Contribution
- Reliable delivery against acceptance criteria
- Maintainable code with appropriate tests and observability
- Early identification of risks, trade-offs, and dependencies

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements, outcomes, and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Decision Rights and Boundaries
- Decide product priorities, scope sequencing, and acceptance intent
- Approve requirement changes that preserve strategy and stakeholder commitments
- Do not independently approve material budget changes, delivery date commitments, or technical exceptions without the appropriate partners

### Required Artifacts
- Project one-pager inputs for problem, goal, and success metrics
- Prioritized backlog and feature requirements
- Acceptance criteria and release outcome expectations

### Lifecycle Involvement
- Primary: Initiation, Planning, Execution & Tracking, Retrospectives & Continuous Improvement
- Supporting: Risk & Communication Management, Release & Deployment

### Interactions and Handoffs
- Translate stakeholder needs into prioritized work for Developers
- Partner with Project Managers on milestones, delivery trade-offs, and escalations
- Work with Business Analyst, UX/Product Designer, Data/Analytics Partner, and Customer Support/Enablement Representative to refine customer value and outcomes

### Escalation Expectations
- Escalate priority conflicts, unresolved scope trade-offs, or business-impact concerns through the Project Manager and Executive Sponsor as needed

### Measures of Effective Contribution
- Clear prioritization and acceptance criteria
- Measurable customer and business outcomes
- Timely product decisions that unblock delivery

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings such as kickoff, planning, reviews, and retrospectives
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Decision Rights and Boundaries
- Decide delivery coordination methods, meeting cadence, reporting structure, and escalation timing
- Re-sequence work and drive mitigation planning with input from role owners
- Do not redefine product goals, approve technical exceptions, or waive release controls on behalf of specialists

### Required Artifacts
- Project plan, milestones, and release timeline
- Risk register and decision log
- Stakeholder status updates and action-item tracking

### Lifecycle Involvement
- Primary: Initiation, Planning, Execution & Tracking, Risk & Communication Management, Release & Deployment, Retrospectives & Continuous Improvement

### Interactions and Handoffs
- Coordinate planning and execution across Developers and Product Managers
- Bring in Executive Sponsor for decision gates, funding, or business-impact escalations
- Coordinate cross-functional handoffs among QA/Test Lead, Security/Privacy Representative, Operations/SRE or Release Manager, and Customer Support/Enablement Representative

### Escalation Expectations
- Own the default escalation path from team-level blockers to Product Lead and Sponsor
- Raise schedule, dependency, or governance risks early and keep owners accountable for follow-through

### Measures of Effective Contribution
- Predictable execution against milestones
- Current risk, dependency, and status visibility
- Fast resolution of blockers and decision bottlenecks

---

## Executive Sponsor

### Role Summary
The Executive Sponsor provides strategic sponsorship, funding alignment, and senior decision-making support for the initiative. This role partners with the Project Manager and Product Manager at key decision gates and owns business-impact escalation.

### Responsibilities
- Confirm strategic alignment, expected business value, and investment rationale
- Resolve major trade-offs involving scope, timeline, funding, or business risk
- Champion the initiative with senior stakeholders and dependent teams
- Support major go/no-go decisions at initiation, milestone, and release gates

### Decision Rights and Boundaries
- Approves strategic sponsorship, major investment changes, and material business trade-offs
- Decides when business-impacting risks require executive intervention
- Does not manage day-to-day backlog decisions, implementation details, or routine project coordination

### Required Artifacts
- Approved project one-pager or charter
- Funding or staffing approval record when applicable
- Decision log entries for major trade-offs and escalations

### Lifecycle Involvement
- Primary: Initiation, Risk & Communication Management, Release & Deployment
- Supporting: Planning, Execution & Tracking

### Interactions and Handoffs
- Reviews initiative framing and success metrics with Product Managers
- Works with Project Managers on milestone reviews, escalations, and stakeholder alignment
- Provides directional decisions that unblock Developers when scope, funding, or cross-organization priorities conflict

### Escalation Expectations
- Engages when Project Managers or Product Managers cannot resolve business-impacting risks, trade-offs, or stakeholder conflicts at the working-team level

### Measures of Effective Contribution
- Timely strategic decisions
- Clear sponsorship and stakeholder alignment
- Reduced delay on high-impact escalations

---

## Business Analyst

### Role Summary
The Business Analyst elicits, structures, and documents business needs so the team can convert them into clear requirements and acceptance criteria. This role reduces ambiguity between stakeholders, Product Managers, Developers, and QA.

### Responsibilities
- Gather business requirements, workflow details, and operational constraints
- Translate business needs into structured requirements, user stories, and acceptance criteria
- Trace requirements through implementation and validation
- Clarify edge cases, assumptions, and terminology for the delivery team

### Decision Rights and Boundaries
- Recommends requirement structure, traceability, and clarification needs
- Can refine wording and detail level for documented requirements with Product Manager alignment
- Does not independently set roadmap priority, commit delivery dates, or approve implemented behavior

### Required Artifacts
- Requirements notes and process maps
- User stories or backlog refinement inputs
- Acceptance criteria and traceability references

### Lifecycle Involvement
- Primary: Initiation, Planning, Execution & Tracking
- Supporting: Retrospectives & Continuous Improvement

### Interactions and Handoffs
- Partners with Product Managers to turn business goals into actionable backlog items
- Hands clarified requirements and acceptance criteria to Developers for implementation
- Supports Project Managers by documenting assumptions, dependencies, and requirement changes
- Works with QA/Test Lead to ensure acceptance coverage reflects business rules

### Escalation Expectations
- Escalates unresolved requirement ambiguity, stakeholder disagreement, or missing acceptance criteria to the Product Manager and Project Manager before implementation proceeds

### Measures of Effective Contribution
- Reduced requirement ambiguity and rework
- Traceable acceptance criteria and business rules
- Faster handoffs from discovery to planning and testing

---

## UX/Product Designer

### Role Summary
The UX/Product Designer defines the user flow, interaction model, and usability outcomes needed to deliver a coherent experience. This role partners with Product Managers on user value and with Developers on feasible implementation options.

### Responsibilities
- Define user journeys, interaction flows, and interface behavior
- Produce design concepts, annotated mockups, or lightweight prototypes as needed
- Identify usability risks, accessibility concerns, and design trade-offs
- Support acceptance discussions for user-facing behaviors

### Decision Rights and Boundaries
- Recommends and approves detailed interaction patterns and usability expectations within agreed product goals
- Can require clarification when feasibility or accessibility concerns are unresolved
- Does not independently reprioritize the roadmap or commit engineering implementation dates

### Required Artifacts
- User flows, wireframes, mockups, or prototypes
- Design acceptance notes and usability considerations
- Accessibility or interaction guidance tied to backlog items

### Lifecycle Involvement
- Primary: Initiation, Planning, Execution & Tracking
- Supporting: Release & Deployment, Retrospectives & Continuous Improvement

### Interactions and Handoffs
- Works with Product Managers to align proposed experiences to customer value
- Hands design intent and interaction guidance to Developers for implementation
- Supports Project Managers by surfacing design dependencies and review checkpoints
- Collaborates with QA/Test Lead on usability and accessibility acceptance expectations

### Escalation Expectations
- Escalates unresolved user experience risks, accessibility concerns, or experience trade-offs to the Product Manager and Project Manager when they affect scope or release readiness

### Measures of Effective Contribution
- Clear user flows and reduced design ambiguity
- Improved usability and accessibility outcomes
- Fewer late-stage experience defects or rework requests

---

## Technical Lead/Architect

### Role Summary
The Technical Lead/Architect guides technical design, engineering standards, dependencies, and technical risk mitigation. This role helps Developers make sound implementation choices and helps Project Managers understand technical delivery risk.

### Responsibilities
- Define or review solution architecture and major design decisions
- Establish engineering standards, integration patterns, and non-functional expectations
- Identify technical dependencies, constraints, and risk mitigations
- Support estimation and sequencing for technically complex work

### Decision Rights and Boundaries
- Decides architectural direction, technical standards, and exception handling within the approved product scope
- Can block unsafe or unsound technical approaches until risk is addressed
- Does not unilaterally change business priorities or release dates without Product Manager and Project Manager alignment

### Required Artifacts
- Architecture or technical design notes
- Dependency and risk assessments
- Standards, decision records, or implementation guidance

### Lifecycle Involvement
- Primary: Planning, Execution & Tracking, Risk & Communication Management
- Supporting: Initiation, Release & Deployment, Retrospectives & Continuous Improvement

### Interactions and Handoffs
- Guides Developers on design decisions, standards, and implementation risks
- Partners with Product Managers on technical trade-offs that affect scope or value
- Works with Project Managers to surface dependencies, sequencing impacts, and mitigation plans
- Coordinates with Security/Privacy Representative and Operations/SRE or Release Manager on readiness controls

### Escalation Expectations
- Escalates architectural risks, dependency conflicts, or non-functional gaps when they threaten delivery, reliability, or compliance

### Measures of Effective Contribution
- Sound, scalable technical decisions
- Early visibility into technical risk and dependencies
- Consistent engineering standards across delivery work

---

## QA/Test Lead

### Role Summary
The QA/Test Lead owns the test strategy, quality risk assessment, coverage expectations, and release-readiness evidence for the initiative. This role ensures that acceptance and quality signals are visible before release decisions are made.

### Responsibilities
- Define the test approach across unit, integration, end-to-end, and manual validation
- Identify quality risks, coverage gaps, and exit criteria
- Review acceptance criteria for testability and completeness
- Consolidate quality evidence for release readiness

### Decision Rights and Boundaries
- Decides the test strategy, quality gates, and release-readiness recommendation from a QA perspective
- Can require additional validation when coverage or defect risk is inadequate
- Does not independently override product acceptance, business priority, or deployment ownership decisions

### Required Artifacts
- Test plan or QA approach
- Test cases or test coverage references
- Defect tracking and release-readiness evidence

### Lifecycle Involvement
- Primary: Planning, Execution & Tracking, Release & Deployment
- Supporting: Retrospectives & Continuous Improvement

### Interactions and Handoffs
- Works with Developers to improve testability and defect prevention
- Supports Product Managers by validating that implemented behavior matches acceptance intent
- Provides Project Managers with visibility into quality risks, exit criteria, and release readiness
- Coordinates with UX/Product Designer on usability acceptance and with Security/Privacy Representative on validation of required controls

### Escalation Expectations
- Escalates unresolved critical defects, inadequate coverage, or unmet exit criteria before release decisions are finalized

### Measures of Effective Contribution
- Risk-based test coverage aligned to scope
- Clear release-readiness evidence
- Reduced escaped defects and faster defect triage

---

## Security/Privacy Representative

### Role Summary
The Security/Privacy Representative advises on security, privacy, threat modeling, compliance expectations, and incident readiness. This role helps the team integrate controls into planning, implementation, testing, and release workflows.

### Responsibilities
- Identify security and privacy requirements, risks, and required controls
- Support threat modeling, data handling reviews, and compliance checks when applicable
- Review incident readiness, access considerations, and remediation expectations
- Advise on secure release criteria and post-release monitoring needs

### Decision Rights and Boundaries
- Recommends required controls, remediation priorities, and security/privacy sign-off conditions
- Can block release progression when material security or privacy risks are not adequately addressed
- Does not own day-to-day engineering implementation, delivery scheduling, or product prioritization

### Required Artifacts
- Threat model or risk assessment notes
- Security and privacy requirements or control checklist
- Evidence of remediation, approvals, or incident-readiness expectations

### Lifecycle Involvement
- Primary: Planning, Execution & Tracking, Risk & Communication Management, Release & Deployment
- Supporting: Initiation, Retrospectives & Continuous Improvement

### Interactions and Handoffs
- Advises Developers and Technical Lead/Architect on secure implementation patterns
- Helps Product Managers understand security/privacy trade-offs that affect scope or user value
- Works with Project Managers to track security risks, approvals, and escalation timing
- Partners with QA/Test Lead and Operations/SRE or Release Manager on validation and release safeguards

### Escalation Expectations
- Escalates material security, privacy, or compliance risks immediately through the Project Manager and appropriate incident or sponsor channels

### Measures of Effective Contribution
- Early integration of controls into planning
- Fewer late security surprises at release time
- Clear remediation priorities and incident readiness

---

## Operations/SRE or Release Manager

### Role Summary
The Operations/SRE or Release Manager coordinates deployment readiness, observability, rollback planning, operational support, and post-release verification. This role helps the team deliver changes safely into live environments.

### Responsibilities
- Define deployment readiness checks and release coordination steps
- Ensure observability, alerting, and support coverage are prepared
- Maintain rollback or mitigation plans and post-release verification expectations
- Coordinate operational communication during release windows or incidents

### Decision Rights and Boundaries
- Decides operational readiness requirements, deployment sequencing, and rollback triggers from an operations perspective
- Can pause or recommend halting a release when operational safeguards are incomplete
- Does not redefine feature scope, acceptance intent, or long-term roadmap priorities

### Required Artifacts
- Release checklist and deployment plan
- Rollback or mitigation playbook
- Observability, monitoring, and post-release verification notes

### Lifecycle Involvement
- Primary: Execution & Tracking, Release & Deployment
- Supporting: Planning, Risk & Communication Management, Retrospectives & Continuous Improvement

### Interactions and Handoffs
- Works with Developers to validate deployment mechanics and observability
- Coordinates with Product Managers on release timing and customer impact considerations
- Keeps Project Managers informed on readiness, windows, and operational dependencies
- Partners with QA/Test Lead and Security/Privacy Representative on release controls and go/no-go input

### Escalation Expectations
- Escalates readiness gaps, rollback risks, incidents, or missing support coverage before and during release activities

### Measures of Effective Contribution
- Predictable, low-risk deployments
- Strong observability and rollback preparedness
- Fast post-release verification and incident response coordination

---

## Customer Support/Enablement Representative

### Role Summary
The Customer Support/Enablement Representative brings customer-impact insight into planning and launch readiness. This role helps the team prepare communications, support workflows, and feedback loops for production issues and recurring user needs.

### Responsibilities
- Share customer pain points, support trends, and readiness concerns
- Prepare support materials, FAQs, or enablement notes for launches when needed
- Capture post-release issues and route them back into the product and delivery process
- Help assess customer communication needs during incidents or major changes

### Decision Rights and Boundaries
- Recommends readiness actions for support content, enablement, and customer communication
- Can require clarification on customer-facing behavior before launch
- Does not approve technical implementation, reprioritize the roadmap, or own incident resolution

### Required Artifacts
- Launch support notes, FAQs, or enablement materials
- Customer-impact summaries and recurring issue themes
- Post-release feedback or incident patterns for backlog input

### Lifecycle Involvement
- Primary: Initiation, Release & Deployment, Retrospectives & Continuous Improvement
- Supporting: Planning, Execution & Tracking, Risk & Communication Management

### Interactions and Handoffs
- Feeds customer insights and recurring support themes to Product Managers
- Helps Project Managers prepare stakeholder and launch communication plans
- Provides Developers with concrete issue patterns and reproduction context after release
- Coordinates with Operations/SRE or Release Manager on incident communication and launch support coverage

### Escalation Expectations
- Escalates high-impact customer issues, repeated confusion, or launch-readiness gaps through the Project Manager and Product Manager

### Measures of Effective Contribution
- Better launch readiness and customer communication
- Faster routing of production issues into the backlog
- Reduced support friction after releases

---

## Data/Analytics Partner

### Role Summary
The Data/Analytics Partner defines measurement plans, instrumentation expectations, dashboards, and outcome reporting so the team can evaluate whether the initiative delivered the intended results.

### Responsibilities
- Define success measures, instrumentation needs, and reporting cadence
- Validate that telemetry and event definitions support intended analysis
- Build or maintain dashboards and outcome reporting views
- Help interpret delivery results and retrospective findings using data

### Decision Rights and Boundaries
- Decides analytics methodology, metric definitions, and reporting structure with Product Manager alignment
- Can require clarification when success metrics or instrumentation are incomplete
- Does not independently approve scope, implementation details, or delivery commitments

### Required Artifacts
- Measurement plan and metric definitions
- Instrumentation requirements or event taxonomy notes
- Dashboards and outcome reporting summaries

### Lifecycle Involvement
- Primary: Initiation, Planning, Execution & Tracking, Retrospectives & Continuous Improvement
- Supporting: Release & Deployment

### Interactions and Handoffs
- Works with Product Managers to define success metrics and outcome reporting
- Hands instrumentation requirements to Developers and validates data capture assumptions
- Helps Project Managers incorporate reporting milestones and adoption signals into status updates
- Supports Executive Sponsor reviews with business-impact evidence when needed

### Escalation Expectations
- Escalates missing instrumentation, unreliable data, or unclear success metrics before release and during outcome reviews

### Measures of Effective Contribution
- Clear, trustworthy success measurement
- Instrumentation aligned to product outcomes
- Actionable dashboards that inform prioritization and retrospectives

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Use the lifecycle involvement, artifacts, and escalation sections to align role prompts with the related project lifecycle documents.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
