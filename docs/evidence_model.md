# Evidence Model

Evidence is any artifact or record that proves an activity or decision meets its stated criteria. In AIEF, evidence is grouped into categories and tied to the artifact lifecycle stages.

## Evidence Categories
- **Requirement Evidence** – User stories, acceptance criteria, mock‑ups.
- **Design Evidence** – Architecture diagrams, interface contracts, ADRs.
- **Implementation Evidence** – Source code commits, unit tests, code coverage reports.
- **Validation Evidence** – Test results, linting output, security scan logs.
- **Deployment Evidence** – Release notes, CI/CD pipeline run summaries, deployment metrics.

## Mapping to Lifecycle
```
Stage            | Primary Evidence Category
-----------------|--------------------------------
Creation          | Requirement / Design / Implementation
Review & Approval | Code review comments, design reviews
Validation        | Test results, linting logs
Deployment         | Release notes, deployment reports
```

Evidence should be stored in the version control system (commits, PR descriptions) or an artifact repository and linked to the corresponding artifact.
