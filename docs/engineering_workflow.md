# Engineering Workflow in AIEF

AIEF follows a disciplined five‑phase workflow that integrates AI assistance at every stage.

1. **Planning**
   - Gather requirements and define acceptance criteria.
   - Create user stories or task specifications.
   - Prioritize backlog items using business value and technical risk.

2. **Design & Architecture**
   - Draft high‑level architecture diagrams.
   - Identify interfaces, data contracts, and responsibilities.
   - Capture design decisions in an ADR.

3. **Implementation**
   - Write code guided by the master system prompt.
   - Generate unit tests alongside production code.
   - Commit incrementally with descriptive messages.

4. **Verification & Validation**
   - Run automated test suites (unit, integration, performance).
   - Perform static analysis and security scans.
   - Review coverage and linting reports.

5. **Code Review & Retrospective**
   - Conduct peer reviews following the code review prompt.
   - Merge approved changes to the shared branch.
   - Hold a retrospective to surface lessons learned.

The workflow is iterative: each sprint cycles through all phases, refining artifacts until they reach *Definition of Done*.
