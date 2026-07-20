# Metadata Schema

The metadata section of a specification MUST be valid YAML and contain the following keys:
- `title` (MUST, string)
- `authors` (SHOULD, array of strings)
- `version` (MUST, semantic version string)
- `date` (MUST, ISO‑8601 date)
- `tags` (OPTIONAL, array of strings)

Example:
```yaml
---
title: "User Authentication Specification"
authors:
  - "Alice Smith"
  - "Bob Jones"
version: "1.0.0"
date: "2026-07-20"
tags:
  - "security"
  - "backend"
---
```
