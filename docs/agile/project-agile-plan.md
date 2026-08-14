# Agile Scrum and GitHub Plan

## Product Backlog and Epics

Planned epics cover platform foundation, identity/security, core healthcare workflows, agentic AI, supporting services, testing/DevSecOps, observability/cloud, and hackathon documentation. Jira stories will include user value, acceptance criteria, estimates, dependencies, security considerations, and evidence.

## Scrum Events

- Backlog refinement: clarify and prioritize work.
- Sprint planning: select one sprint goal and achievable stories.
- Daily Scrum: inspect progress and blockers.
- Sprint review: demonstrate real integrated functionality.
- Retrospective: adopt measurable team improvements.

## Jira Workflow

```text
Backlog -> Ready -> In Progress -> Code Review -> Testing -> Done
```

## Git Workflow

- `main`: stable, reviewed releases.
- `develop`: integrated upcoming work.
- `feature/MED-<id>-<description>`: Jira-linked work.

Example:

```text
MED-101
feature/MED-101-authentication
feat(MED-101): implement JWT authentication
```

Every member uses their own GitHub identity. Pull requests require review, testing evidence, and documentation updates. Future tags `review-1`, `review-2`, and `final` are created only after the corresponding phase is complete.

## Suggested Initial Jira Backlog

| Key | Item |
|---|---|
| MED-001 | Verify repository naming, access, and protections |
| MED-002 | Approve requirements and architecture baseline |
| MED-101 | Scaffold authentication and JWT/RBAC |
| MED-102 | Scaffold patient and doctor services |
| MED-103 | Scaffold appointment service and gateway/discovery |
| MED-104 | Implement medical-record golden path |
| MED-105 | Implement AI Service and first assistants |
| MED-201 | Configure automated build and tests |
| MED-202 | Configure DevSecOps evidence pipeline |
| MED-203 | Configure observability and deployment evidence |

## Adaptive Practice

Scope and architecture will be adapted using stakeholder reviews, test results, security findings, delivery capacity, and retrospectives. Incomplete supporting services will be documented honestly as future enhancements rather than represented as finished.

