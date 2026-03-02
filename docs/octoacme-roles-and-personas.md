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

## Business Analyst (BA)

### Role Summary
Business Analysts translate business needs into clear, actionable requirements. They bridge product, technology, and stakeholder groups, ensuring that what gets built solves the right problems and meets agreed acceptance criteria.

### Responsibilities
- Gather, document, and refine business and user requirements
- Define and maintain acceptance criteria, user stories, and workflow diagrams
- Facilitate alignment sessions between business stakeholders, Product Managers, and Developers
- Validate delivered solutions against original requirements
- Identify scope changes and communicate impact to the Project Manager

### Goals
- Eliminate ambiguity before work enters development
- Ensure a shared, traceable understanding of requirements across all roles
- Reduce rework caused by unclear or changing requirements

### Typical Communication
- Requirements workshops and discovery sessions with stakeholders and PM/PdM
- User-story write-ups and acceptance-criteria documents shared in the project backlog
- Change-request summaries and impact analyses sent to PM

### Interactions with Existing Roles
| Role | Interaction / Handoff |
|---|---|
| **Product Manager (PdM)** | Receives high-level product goals and success metrics; translates them into detailed requirements and acceptance criteria |
| **Project Manager (PM)** | Reports scope changes and dependency risks; inputs into planning artifacts (backlog, timelines) |
| **Developers** | Provides detailed requirements, wireframes, and acceptance criteria; answers clarification questions during sprints |
| **Stakeholder Representative** | Runs workshops to elicit and validate requirements; confirms sign-off before development begins |
| **UX/UI Designer** | Shares workflow documentation and user-research insights to inform design; reviews wireframes for requirements coverage |
| **QA Lead** | Hands off acceptance criteria to form the basis of test cases; joins QA review to validate coverage |

---

## UX/UI Designer

### Role Summary
UX/UI Designers advocate for end-users by researching needs and crafting intuitive, accessible experiences. They translate requirements into wireframes, prototypes, and detailed UI specifications that guide development.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, interactive prototypes, and visual design assets
- Produce UI specifications (spacing, typography, component behavior) for Developers
- Collaborate with BA and PM on user journeys and information architecture
- Review implemented features against designs and flag discrepancies

### Goals
- Deliver experiences that are usable, accessible, and aligned with brand standards
- Reduce iteration cycles by providing clear, unambiguous design specifications
- Advocate for user needs in every stage of the lifecycle

### Typical Communication
- Design-review sessions with PM, BA, and Developers (at wireframe and high-fidelity stages)
- Design files and annotated specs shared via the project's design tool (e.g., Figma)
- Usability-test findings summarized as actionable recommendations

### Interactions with Existing Roles
| Role | Interaction / Handoff |
|---|---|
| **Product Manager (PdM)** | Aligns on user personas and product vision; incorporates outcome metrics into design decisions |
| **Business Analyst (BA)** | Receives user stories and workflow documentation; feeds usability insights back into requirement refinement |
| **Developers** | Hands off finalized design specs and assets; joins implementation reviews to ensure pixel-accurate delivery |
| **QA Lead** | Provides acceptance criteria for visual and interaction quality; participates in UI test reviews |
| **Stakeholder Representative** | Presents prototypes for early feedback and stakeholder validation before full implementation |

---

## Quality Assurance Lead (QA Lead)

### Role Summary
The QA Lead ensures that each release meets defined quality standards through robust test strategies, coordinated testing activities, and clear quality gates. They own the definition of "done" from a quality perspective.

### Responsibilities
- Define and maintain the overall test strategy (unit, integration, regression, exploratory, performance)
- Coordinate manual and automated testing across sprints and releases
- Maintain test plans, test cases, and defect logs
- Report quality status, coverage metrics, and risks to PM and stakeholders
- Own sign-off criteria and enforce quality gates before releases proceed

### Goals
- Prevent defects from reaching production
- Build confidence in each release through transparent quality reporting
- Continuously improve test coverage and automation ratios

### Typical Communication
- Test-plan reviews with PM and Developers at sprint start
- Daily defect triage and status updates during active testing
- Release-readiness reports shared with PM, DevOps/Release Engineer, and stakeholders before each deployment

### Interactions with Existing Roles
| Role | Interaction / Handoff |
|---|---|
| **Product Manager (PdM)** | Receives feature specifications and success metrics to define acceptance tests |
| **Business Analyst (BA)** | Derives test cases directly from acceptance criteria; flags gaps or ambiguities |
| **Developers** | Collaborates on testability (test hooks, environments); receives builds for test execution; returns defect reports |
| **UX/UI Designer** | Validates UI implementations against design specs; includes visual regression checks |
| **DevOps/Release Engineer** | Provides go/no-go sign-off before deployments; coordinates test execution in staging environments |
| **Stakeholder Representative** | Reports quality status ahead of major milestones; obtains stakeholder acceptance during UAT |

---

## DevOps/Release Engineer

### Role Summary
DevOps/Release Engineers own the build, deployment, and operational health of project releases. They design and maintain the automation pipelines and infrastructure that enable teams to ship reliably and safely.

### Responsibilities
- Design, maintain, and improve CI/CD pipelines and release automation
- Coordinate and execute deployments across environments (dev, staging, production)
- Manage rollback plans and incident response procedures
- Monitor reliability, performance, and security metrics post-deployment
- Enforce environment configuration standards and secrets management

### Goals
- Enable frequent, low-risk deployments
- Reduce mean time to recovery (MTTR) for production incidents
- Maintain high deployment-success rates through automation and clear runbooks

### Typical Communication
- Release-planning sessions with PM and QA Lead before each deployment window
- Deployment runbooks and post-deployment status shared with PM and stakeholders
- Incident reports and post-mortems contributed to the retrospective process

### Interactions with Existing Roles
| Role | Interaction / Handoff |
|---|---|
| **Project Manager (PM)** | Aligns on release windows, change-freeze periods, and risk communications |
| **Developers** | Reviews infrastructure-as-code and containerization; provides deployment feedback and environment support |
| **QA Lead** | Provisions staging environments for testing; receives go/no-go signal before production deployments |
| **Product Manager (PdM)** | Communicates deployment timelines and any release constraints that affect roadmap commitments |
| **Stakeholder Representative** | Provides advance notice of planned downtime or breaking changes; shares post-deployment status summaries |

---

## Stakeholder Representative

### Role Summary
Stakeholder Representatives provide the voice of the business and customer within project decisions. They ensure that project outputs remain aligned with organizational goals, regulatory requirements, and end-user needs.

### Responsibilities
- Articulate business goals, constraints, and success metrics to the project team
- Participate in milestone reviews, backlog prioritization, and release approvals
- Provide timely feedback on requirements, designs, and delivered increments
- Escalate or make decisions on priority conflicts within an agreed timeframe
- Champion the project within their business unit to secure resources and adoption

### Goals
- Ensure the project delivers measurable business value
- Minimize disruption to ongoing operations during delivery
- Achieve successful end-user adoption and satisfaction

### Typical Communication
- Milestone review meetings with PM and PdM (at initiation, key checkpoints, and release)
- Written feedback on requirements documents, prototypes, and UAT results
- Executive-level status updates facilitated by PM

### Interactions with Existing Roles
| Role | Interaction / Handoff |
|---|---|
| **Product Manager (PdM)** | Provides business context and priority signals; validates roadmap decisions against strategic goals |
| **Project Manager (PM)** | Receives status updates and escalation requests; approves milestone deliverables and scope changes |
| **Business Analyst (BA)** | Participates in requirements workshops; signs off on acceptance criteria before development begins |
| **UX/UI Designer** | Reviews and provides feedback on prototypes and usability findings |
| **QA Lead** | Conducts or oversees user acceptance testing (UAT) and provides final sign-off before release |
| **DevOps/Release Engineer** | Receives advance notice of deployment schedules and post-release summaries |

---

## Why These Additional Roles Improve Project Outcomes

Adding these five roles closes significant accountability gaps that commonly arise in cross-functional software projects:

| Gap Addressed | Role Responsible | Expected Improvement |
|---|---|---|
| **Unclear requirements** | Business Analyst | Reduces rework and late-stage scope changes by ensuring requirements are documented, agreed, and traceable before development begins |
| **Poor user experience** | UX/UI Designer | Catches usability issues early through research and prototyping, lowering defect rates and increasing adoption |
| **Insufficient quality gates** | QA Lead | Prevents defects from reaching production and provides transparent, data-driven release-readiness decisions |
| **Unreliable releases** | DevOps/Release Engineer | Standardises deployment processes, reduces manual errors, and shortens recovery times when incidents occur |
| **Misaligned stakeholders** | Stakeholder Representative | Keeps business priorities visible throughout delivery and accelerates decision-making at key milestones |

Together, these roles reinforce the **OctoAcme principle of clear ownership**: every major activity in the lifecycle—requirements definition, design, quality assurance, deployment, and stakeholder alignment—has an explicitly named accountable role. This reduces ambiguity, speeds up handoffs, and creates a consistent, repeatable delivery process.

For a full mapping of roles to lifecycle activities, see [octoacme-raci-matrix.md](./octoacme-raci-matrix.md).
For a step-by-step handoff checklist, see [octoacme-role-handoff-checklist.md](./octoacme-role-handoff-checklist.md).

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

