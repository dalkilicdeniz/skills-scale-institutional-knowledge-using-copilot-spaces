# OctoAcme Role Handoff Checklist

Use this checklist to ensure clean, well-documented handoffs between roles at each stage of the delivery lifecycle. Each section lists the minimum outputs required before work moves to the next stage.

For full role definitions see [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md).
For a full RACI mapping see [octoacme-raci-matrix.md](./octoacme-raci-matrix.md).

---

## Stage 1 → 2: Initiation → Planning

**Handoff: Stakeholder Representative & PdM → Business Analyst**

- [ ] Approved project charter or one-pager is available
- [ ] Business goals and success metrics are documented
- [ ] Key stakeholders and decision-makers are identified
- [ ] High-level constraints (budget, timeline, compliance) are communicated
- [ ] BA requirements-gathering sessions are scheduled

---

## Stage 2a: Requirements → Design

**Handoff: Business Analyst → UX/UI Designer**

- [ ] User stories are written and accepted by PdM
- [ ] Acceptance criteria are documented for each story
- [ ] User workflows and journey maps are drafted
- [ ] Any existing brand/design guidelines are shared
- [ ] Open questions or assumptions are logged and visible
- [ ] BA is available for designer clarification during discovery

---

## Stage 2b: Requirements & Design → Development

**Handoff: BA + UX/UI Designer → Developers**

- [ ] All user stories in the sprint/iteration have accepted acceptance criteria
- [ ] Finalized wireframes or high-fidelity design specs are available in the design tool
- [ ] UI component specifications (spacing, states, interactions) are annotated
- [ ] Design assets (icons, images) are exported and accessible
- [ ] BA and designer are available during the sprint for clarification

---

## Stage 2c: Requirements & Design → QA

**Handoff: BA + UX/UI Designer → QA Lead**

- [ ] Acceptance criteria have been shared with QA Lead
- [ ] Design specifications are accessible for visual regression testing
- [ ] Test environments are identified and access provisioned
- [ ] Edge cases and out-of-scope items are documented

---

## Stage 3: Execution → Quality Assurance

**Handoff: Developers → QA Lead**

- [ ] Feature branch or build is deployed to the agreed test environment
- [ ] Developer has verified the build runs without critical errors
- [ ] Unit and integration test results are passing (or known failures documented)
- [ ] Release notes or feature description is provided for context
- [ ] Developers are available to address defects during the test cycle

---

## Stage 4a: QA Sign-off → Release Engineering

**Handoff: QA Lead → DevOps/Release Engineer**

- [ ] All critical and high-severity defects are resolved or have agreed workarounds
- [ ] QA Lead has issued a formal release-readiness report
- [ ] UAT sign-off has been obtained from Stakeholder Representative (if applicable)
- [ ] Regression test suite has passed in staging
- [ ] PM has confirmed the deployment window and communicated any change-freeze constraints

---

## Stage 4b: Release Engineering → Post-Deployment

**Handoff: DevOps/Release Engineer → PM + Stakeholders**

- [ ] Deployment runbook was followed and any deviations documented
- [ ] Smoke tests in production have passed
- [ ] Monitoring dashboards are active and baselines recorded
- [ ] Rollback plan is tested and ready if needed
- [ ] Post-deployment status summary is sent to PM and Stakeholder Representative

---

## Stage 5: Release → Retrospective

**Handoff: All Roles → Project Manager**

- [ ] Each role has submitted lessons-learned notes (defects, blockers, process gaps)
- [ ] Metrics against success criteria have been collected (velocity, defect rate, deployment success)
- [ ] Unresolved items or follow-on work are captured in the backlog
- [ ] Retrospective meeting is scheduled and all key roles are invited
- [ ] Action items from the retrospective are assigned to named owners with due dates
