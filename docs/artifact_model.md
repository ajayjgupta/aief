# Artifact Model

AIEF treats every deliverable as an **artifact** with explicit relationships.

| Artifact | Role | Owner | Dependencies |
|----------|------|-------|--------------|
| Requirements | Business intent | Product owner | – |
| Design Document | Architectural blueprint | Architect | Requirements |
| ADRs | Decision record | Engineering team | Design Document |
| Code | Implemented behavior | Developers | Design Document, ADRs |
| Unit Tests | Validation of code | Developers | Code |
| Integration Tests | System‑level validation | QA / DevOps | Code, External Services |
| Build Scripts | Packaging & deployment | DevOps | Code |
| Documentation | Knowledge base | Technical writer | Requirements, Design Doc |
| CI/CD Pipelines | Automation | DevOps | Build Scripts |

*Key relationships*:  
- **Code** depends on **Design Document** and any relevant **ADRs**.  
- **Tests** depend on the code they validate.  
- **Build scripts** consume compiled artifacts.  
- **Documentation** should be updated whenever a related artifact changes.

Artifacts are version‑controlled, tagged, and stored in a central repository to enable traceability from user stories back to production code.
