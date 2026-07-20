# Artifact Lifecycle

The artifact lifecycle in AIEF is a staged sequence that describes how an artifact originates, evolves, and reaches final state. Each stage defines responsibilities, required evidence, and quality gates.

```
+------------+    +--------------+    +-----------------+    +---------------+
|  Creation | -> |  Review &   | -> |  Validation &   | -> |   Deployment |
|            |    |  Approval   |    |  Sign‑off       |    |               |
+------------+    +--------------+    +-----------------+    +---------------+
```

**Stages**
1. **Creation** – Author writes artifact (requirements, design, code).
2. **Review & Approval** – Peer review ensures correctness and compliance.
3. **Validation & Sign‑off** – Automated tests, static analysis, and security checks are executed.
4. **Deployment** – Artifact is released to production or a release repository.

Artifacts move forward only when all evidence in the current stage meets the corresponding quality gate.
