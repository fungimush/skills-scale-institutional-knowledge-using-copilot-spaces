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

## Release Manager

### Role Summary
Release Managers coordinate and execute the release process from code freeze through production deployment. They ensure release quality, manage release schedules, and coordinate cross-team activities during release windows.

### Responsibilities
- Plan and schedule release windows and deployment activities
- Coordinate release readiness reviews with QA, DevOps, and stakeholders
- Manage release documentation including release notes and deployment guides
- Track and communicate release status to stakeholders
- Coordinate rollback procedures if issues arise post-deployment
- Maintain release calendars and coordinate with dependent teams

### Key Interactions with Existing Roles
- **With Developers**: Review code completion status, coordinate merge schedules, and validate pre-release testing
- **With Product Managers**: Align on feature inclusion, validate acceptance criteria completion, and communicate release scope
- **With Project Managers**: Synchronize on timelines, dependencies, and resource allocation during release periods
- **With Quality Manager**: Coordinate final quality gates, sign-off procedures, and validation testing

### Sample Communications and Decision Points
- **Release Readiness Meeting**: "All P0 bugs have been addressed. QA sign-off received. Proposing go-live for Thursday 2pm with on-call coverage through Friday."
- **Release Delay Decision**: "Blocker issue discovered in staging. Recommending 48-hour delay to properly validate fix. Will update stakeholders and reschedule deployment window."
- **Post-Release Communication**: "Release 2.5 deployed successfully. All smoke tests passing. Monitoring dashboards showing normal metrics. Support team briefed on new features."

---

## Quality Manager

### Role Summary
Quality Managers define and enforce quality standards across the software development lifecycle. They establish testing strategies, oversee QA processes, and ensure products meet defined quality criteria before release.

### Responsibilities
- Define quality standards, testing strategies, and acceptance criteria
- Coordinate testing activities across unit, integration, and end-to-end levels
- Manage QA resources and prioritize testing efforts
- Track quality metrics (defect rates, test coverage, regression trends)
- Review and approve release candidates from a quality perspective
- Drive continuous improvement of testing processes and tools

### Key Interactions with Existing Roles
- **With Developers**: Collaborate on test coverage requirements, review test plans, and triage defects
- **With Product Managers**: Validate acceptance criteria, assess quality trade-offs, and prioritize defect fixes
- **With Project Managers**: Report quality status, flag quality risks, and coordinate testing resource needs
- **With Release Manager**: Provide quality sign-off for releases and coordinate final validation testing

### Sample Communications and Decision Points
- **Quality Gate Review**: "Feature X meets all acceptance criteria. Test coverage at 87%. Two minor issues logged for future sprint. Recommend approval for release."
- **Risk Assessment**: "Regression test failures in payment flow. High severity, recommend holding release until root cause identified and resolved."
- **Quality Improvement Proposal**: "Analysis shows 40% of bugs originate in API layer. Proposing enhanced integration test suite and contract testing framework."

---

## Communications Lead

### Role Summary
Communications Leads develop and execute communication strategies to keep stakeholders informed, aligned, and engaged throughout the project lifecycle. They craft messaging, coordinate announcements, and ensure consistent information flow.

### Responsibilities
- Develop project communication plans identifying audiences, channels, and frequency
- Draft and distribute status updates, announcements, and change communications
- Coordinate with marketing, support, and customer success on external communications
- Manage stakeholder engagement and feedback collection
- Create and maintain project documentation for broader audiences
- Facilitate town halls, demos, and stakeholder briefings

### Key Interactions with Existing Roles
- **With Product Managers**: Translate product vision and roadmap into stakeholder-friendly communications
- **With Project Managers**: Gather status updates, risks, and milestones for regular reporting
- **With Release Manager**: Coordinate release announcements, user documentation, and support briefings
- **With Developers**: Gather technical details for change logs and technical documentation

### Sample Communications and Decision Points
- **Launch Communication Plan**: "Proposing three-tier communication approach: internal team announcement (D-7), support/sales enablement (D-3), customer announcement (D-day). Draft materials ready for review."
- **Stakeholder Update**: "Q3 roadmap progress: Feature A delivered, Feature B on track for next sprint, Feature C delayed due to infrastructure dependencies—mitigation plan attached."
- **Change Management**: "Breaking change in API v3 requires customer migration. Prepared: migration guide, FAQ, support scripts, and 60-day notice communication."

---

## UX Specialist

### Role Summary
UX Specialists ensure products are user-centered, accessible, and deliver excellent user experiences. They conduct user research, create designs, and validate solutions through testing and feedback.

### Responsibilities
- Conduct user research and usability testing to inform design decisions
- Create wireframes, prototypes, and design specifications
- Ensure accessibility standards (WCAG) are met
- Collaborate with developers on implementation and design validation
- Track user experience metrics and satisfaction scores
- Advocate for user needs in product and technical discussions

### Key Interactions with Existing Roles
- **With Product Managers**: Collaborate on user stories, validate problem statements with research, and define success metrics
- **With Developers**: Review implementation for design fidelity, provide UI/UX guidance, and conduct design reviews
- **With Project Managers**: Communicate design timelines, dependencies, and resource needs
- **With Quality Manager**: Define usability test criteria and participate in acceptance testing

### Sample Communications and Decision Points
- **Design Review**: "Usability testing with 12 users shows 85% task completion rate. Main friction point: navigation structure. Proposing revised IA with breadcrumb navigation."
- **Accessibility Assessment**: "Current design fails WCAG 2.1 Level AA for color contrast and keyboard navigation. Required changes documented with recommended fixes."
- **Feature Trade-off Discussion**: "Removing this UI element reduces implementation complexity but increases user steps from 3 to 5. User research suggests this impacts 70% of workflows—recommend keeping original design."

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They elicit requirements, analyze processes, and ensure solutions deliver measurable business value.

### Responsibilities
- Gather and document business requirements and use cases
- Analyze current processes and identify improvement opportunities
- Translate business needs into technical requirements and user stories
- Validate solutions against business objectives and success criteria
- Conduct impact analysis for proposed changes
- Support data analysis and reporting to measure business outcomes

### Key Interactions with Existing Roles
- **With Product Managers**: Collaborate on requirement definition, validate market needs, and analyze competitive landscape
- **With Developers**: Clarify requirements, answer business logic questions, and validate implementation against needs
- **With Project Managers**: Estimate effort for requirements gathering, track requirement changes, and assess scope impacts
- **With Stakeholders**: Elicit needs, demonstrate solutions, and gather feedback on business value

### Sample Communications and Decision Points
- **Requirements Clarification**: "Business rule analysis reveals three edge cases not covered in original spec: bulk operations, recurring schedules, and system-initiated triggers. Proposing expanded requirements with priority ranking."
- **Impact Analysis**: "Proposed feature change affects 3 downstream systems and requires 4 data migration scripts. Estimated business impact: 500 customers, moderate risk, 6-week implementation timeline."
- **Value Assessment**: "Post-launch analysis shows feature adoption at 34% (target: 50%). User interviews indicate onboarding friction. Recommending enhanced documentation and in-app guidance."

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

