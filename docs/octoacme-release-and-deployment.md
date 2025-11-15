# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Release Management Checklist
Use this comprehensive checklist to ensure smooth releases and minimize risk.

### Planning Phase
- [ ] Release date and deployment window agreed with stakeholders
- [ ] Release Manager assigned and briefed
- [ ] All features scheduled for release have passed QA sign-off
- [ ] Dependent teams notified of release timeline
- [ ] Rollback plan documented and tested
- [ ] On-call coverage confirmed for release window and 24 hours post-deployment

### Preparation Phase
- [ ] Release branch created and feature merges completed
- [ ] Release notes drafted and reviewed (including breaking changes, migration steps, known issues)
- [ ] Deployment runbook updated with current procedures
- [ ] Support team briefed on new features and potential issues
- [ ] Communications Lead prepared announcements for stakeholders
- [ ] Staging environment updated to match production configuration
- [ ] Pre-release smoke test suite prepared and validated

### Deployment Phase
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot created (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Final go/no-go decision from Release Manager and Quality Manager
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications and smoke tests
- [ ] Monitor error rates, latency, and key metrics for first 30 minutes
- [ ] Announce release to stakeholders and support

### Post-Deployment Phase
- [ ] Verify all critical paths are functional
- [ ] Confirm monitoring and alerting working as expected
- [ ] Release notes published and distributed
- [ ] Support documentation updated
- [ ] Customer/user communication sent (if applicable)
- [ ] Retrospective scheduled within 1 week to capture lessons learned

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
