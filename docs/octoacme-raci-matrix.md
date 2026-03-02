# OctoAcme RACI / Collaboration Matrix

This matrix maps key project activities across the delivery lifecycle to each role using the RACI model:

- **R** – Responsible: does the work
- **A** – Accountable: owns the outcome and gives final approval
- **C** – Consulted: provides input before or during the activity
- **I** – Informed: receives updates on progress or outcomes

For full role definitions see [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md).

---

## RACI Matrix

| Activity | PM | PdM | BA | UX/UI | Dev | QA Lead | DevOps | Stakeholder |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Initiation** | | | | | | | | |
| Define problem statement & goals | C | A/R | C | — | — | — | — | C |
| Identify stakeholders & sponsors | A/R | C | C | — | — | — | — | I |
| Draft project charter / one-pager | A/R | C | C | — | — | — | — | I |
| **Planning** | | | | | | | | |
| Gather and document requirements | C | C | A/R | C | C | C | — | C |
| Define acceptance criteria | C | C | A/R | C | C | C | — | C |
| Create wireframes & prototypes | — | C | C | A/R | C | C | — | I |
| Define test strategy | C | I | C | — | C | A/R | I | — |
| Create project plan & milestones | A/R | C | C | C | C | C | C | I |
| Define release & deployment plan | C | I | — | — | C | C | A/R | I |
| **Execution** | | | | | | | | |
| Implement features | C | I | C | C | A/R | I | I | — |
| Design reviews (wireframe/hi-fi) | I | C | C | A/R | C | C | — | C |
| Unit & integration testing | I | — | — | — | A/R | C | — | — |
| Functional & regression testing | I | I | C | C | C | A/R | C | — |
| Defect triage & resolution | C | I | C | C | A/R | C | I | — |
| **Release** | | | | | | | | |
| Release-readiness review | A/R | C | — | — | C | C | C | C |
| User Acceptance Testing (UAT) | C | C | C | C | I | C | I | A/R |
| Production deployment | C | I | — | — | C | C | A/R | I |
| Post-deployment monitoring | I | I | — | — | C | C | A/R | I |
| **Retrospective & Improvement** | | | | | | | | |
| Collect feedback & lessons learned | A/R | C | C | C | C | C | C | C |
| Prioritize process improvements | C | A/R | C | C | C | C | C | I |
| Update documentation | C | C | A/R | C | C | C | C | — |

---

## Key: Abbreviations

| Abbreviation | Role |
|---|---|
| PM | Project Manager |
| PdM | Product Manager |
| BA | Business Analyst |
| UX/UI | UX/UI Designer |
| Dev | Developer |
| QA Lead | Quality Assurance Lead |
| DevOps | DevOps/Release Engineer |
| Stakeholder | Stakeholder Representative |
