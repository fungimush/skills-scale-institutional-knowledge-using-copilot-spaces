# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Cross-Team Coordination
Cross-team dependencies require proactive coordination to avoid delays and misalignment.

### Identifying Dependencies
- Map dependencies during planning and update as work progresses
- Tag cross-team items in project board with team labels
- Document integration points and API contracts early
- Identify handoff points and acceptance criteria for each team

### Coordination Mechanisms
- **Weekly Cross-Team Sync**: 30-minute meeting with leads from dependent teams to review progress, blockers, and upcoming handoffs
- **Dependency Board**: Maintain visibility of cross-team items with clear owners and due dates
- **Handoff Documentation**: Create clear handoff checklists including deliverables, acceptance criteria, and validation steps
- **Communication Protocol**: Establish Slack channels or email threads for quick coordination between teams

### Handoff Best Practices
- Schedule handoff meetings at least 2 days before transfer
- Document what is being handed off, expected outcomes, and success criteria
- Include relevant context: design docs, test results, known issues
- Confirm receiving team has capacity and understands requirements
- Set follow-up checkpoints to verify successful integration

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Cross-team dependencies mapped and tracked
- [ ] Weekly cross-team sync scheduled (if dependencies exist)
- [ ] Handoff procedures documented for key integration points
