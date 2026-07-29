# Release Readiness Checklist

Purpose: Short, actionable checklist to ensure production releases are well coordinated and low-risk.

Pre-release (all items must be confirmed)
- [ ] Acceptance criteria met and sign-offs complete (owner: Feature owner + QA Lead)
- [ ] CI green and all security scans passed (owner: Tech Lead)
- [ ] Release runbook and rollback plan documented (owner: Release Manager)
- [ ] Monitoring & alerts configured and verified (owner: SRE/Platform)
- [ ] Migration steps and data considerations documented (owner: Tech Lead / Data)
- [ ] Stakeholders and support teams notified of release window (owner: Project Manager)
- [ ] UX acceptance and accessibility checks complete (owner: UX Researcher)

Staging
- [ ] Deploy to staging and run smoke tests (owner: Release Manager + QA)
- [ ] Confirm telemetry and dashboards are receiving correct signals (owner: Data/Analytics)
- [ ] Perform standard load/soak checks if applicable (owner: SRE/Platform)

Production rollout
- [ ] Execute deployment plan and monitor key metrics (owner: Release Manager + SRE)
- [ ] Verify feature toggles or gradual rollout if needed (owner: Tech Lead)
- [ ] Confirm no critical errors within defined window (owner: SRE/Platform)

Post-release
- [ ] Run post-deploy verification checklist (owner: QA/Release)
- [ ] Collect and review initial metrics against success criteria (owner: Product Manager + Data)
- [ ] Capture any incidents and assign follow-ups (owner: Project Manager)
- [ ] Close release notes and update project README (owner: Project Manager)

Notes
- Include links to runbooks, dashboards, and incident contacts in the release checklist entry on the project board or milestone.
