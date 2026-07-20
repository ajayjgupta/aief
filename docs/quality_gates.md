# Quality Gates

Quality gates are threshold criteria that must be met before an artifact can progress to the next lifecycle stage. They enforce consistency, correctness, and readiness.

## Common Gates
| Stage | Gate | Description |
|-------|------|-------------|
| **Creation** | 0% Test Coverage |
| **Review & Approval** | Peer review approval from at least two reviewers |
| **Validation** | All unit tests pass; coverage ≥ 80%; linting errors = 0; security scan no critical findings |
| **Deployment** | Successful CI/CD run; rollback enabled |

## Gate Workflow
1. **Automated gate evaluation** – Continuous integration evaluates gates on every push.
2. **Manual override** – Gates can be bypassed only by explicit approval from a senior engineer.
3. **Gate failure handling** – Failure triggers notification and block merge until resolved.

Gates are defined in `ci.yml` or a gate‑definition file, but the documentation should be maintained in Markdown for visibility to all stakeholders.
