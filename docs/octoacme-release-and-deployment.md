# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (verified by QA Lead)
- Passing CI and security scans (verified by Security Owner)
- Release notes drafted (by Product Manager)
- Rollback / mitigation plan documented (by Tech Lead and Support/Ops Lead)
- Smoke tests prepared and passed (by QA Lead and Support/Ops Lead)
- Release readiness sign-off from Product Lead

## Deployment Checklist
- [ ] Deployment window scheduled by Project Manager (if needed)
- [ ] Backup or snapshot prepared by Support/Ops Lead (if applicable)
- [ ] Deploy to staging and run smoke tests (QA Lead and Support/Ops Lead)
- [ ] Deploy to production via automated pipeline (Support/Ops Lead) or manual (Tech Lead + Support/Ops Lead)
- [ ] Run post-deploy verifications (QA Lead and Support/Ops Lead)
- [ ] Announce release to stakeholders and support (Project Manager and Product Manager)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - **Support/Ops Lead** triggers incident response and notifies Security Owner and on-call
  - **Tech Lead** and **Support/Ops Lead** coordinate rollback to last known-good release if necessary
  - **Project Manager** notifies Sponsor and stakeholders
  - **Security Owner** leads security incident response (if applicable)
  - Team conducts blameless retrospective (led by Project Manager) within 24 hours

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
