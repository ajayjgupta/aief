# AI Roles within AIEF

| Role | Core Responsibility | Interaction with Humans | Typical Output |
|------|---------------------|------------------------|---------------|
| **Analyst** | Interpret requirements, surface gaps | Receives product briefs, asks clarifying questions | Requirements summaries, question lists |
| **Architect** | Define system structure, write ADRs | Reviews design proposals, suggests alternatives | Architecture diagrams, ADR documents |
| **Developer** | Produce code, unit tests | Provides specs or skeletons, receives implementation suggestions | Code snippets, test stubs |
| **Tester** | Create validation scenarios, analyze results | Feeds test data, interprets failures | Test plans, coverage reports |
| **Reviewer** | Evaluate quality, enforce standards | Receives PRs, reviews changes | Review comments, security checks |
| **Project Manager** | Orchestrate workflow, ensure DOF | Tracks progress, clears approvals | Status dashboards, approval records |

Each role can be instantiated as one or more AI agents. The master system prompt ensures consistent behavior across all roles.
