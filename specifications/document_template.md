# Document Template

```markdown
---
# {{title}}

**Authors:** {{authors | join(', ')}}
**Version:** {{version}}
**Date:** {{date}}
**Tags:** {{tags | join(', ')}}
---

## Executive Summary
{{executive_summary}}

## Context & Background
{{context_and_background}}

## Requirements
1. ...
2. ...

## Design Decisions
- Reference ADRs: {{adr_references | join(', ')}}

## Milestones
| # | Name | Target Date |
|---|------|-------------|
{{milestones_table}}

## Acceptance Criteria
- ...

## Dependencies & Risks
{{dependencies_and_risks}}

## Appendices
{{appendices}}
```
