<!--
Sync Impact Report:
- Version change: 0.0.0 → 1.0.0
- Added sections:
  - Core Principles
  - Technical Stack
  - Quality Requirements
  - Governance
- Templates requiring updates:
  - ✅ .specify/templates/plan-template.md
  - ✅ .specify/templates/spec-template.md
  - ✅ .specify/templates/tasks-template.md
-->
# calculator-project Constitution

## Core Principles

### I. Test-Driven Development
TDD is mandatory: Tests are written, user-approved, and failing before implementation begins. The Red-Green-Refactor cycle is strictly enforced.

### II. Code Quality and Style
Use Python 3.12+ with type hints everywhere. Keep code clean, simple, and easy to read, following SOLID, DRY, and KISS principles.

### III. Architectural Documentation
Document important architectural decisions using Architecture Decision Records (ADRs).

## Technical Stack

- **Language and Package Manager**: Python 3.12+ with UV.
- **Testing Framework**: `pytest` for all testing.
- **Version Control**: All project files MUST be stored and managed in `git`.

## Quality Requirements

- **Test Coverage**: All tests MUST pass before any code is merged. A minimum of 80% code coverage is required.
- **Data Structures**: Use `dataclasses` for data structures to ensure immutability and clarity.

## Governance

This constitution supersedes all other practices. Amendments require documentation, approval, and a migration plan. All pull requests and reviews must verify compliance with these principles.

**Version**: 1.0.0 | **Ratified**: 2025-11-21 | **Last Amended**: 2025-11-21