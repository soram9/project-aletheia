# Roadmap

This roadmap proposes a sequence of work. It contains no completion claims, delivery dates, or guarantees. A phase should be marked complete only when its acceptance evidence has been reviewed. Public evidence must be sanitized; sensitive test records stay private.

The current public repository provides foundational documentation. It does not verify the state of any private implementation.

## Phase 1 — Define the foundations

Planned work:

- Define system boundaries, intended uses, and data classifications.
- Establish a durable knowledge structure and decision-record format.
- Record constraints, dependencies, and criteria for choosing components.
- Establish a review process for publishing sanitized documentation.

Acceptance evidence: a reviewed scope, knowledge structure, and publication checklist, with private details excluded from public versions.

## Phase 2 — Preserve and recover knowledge

Planned work:

- Define ingestion, provenance, versioning, and export conventions.
- Establish user-controlled storage, backup, and recovery procedures.
- Check that records can be opened without the original assistant or application.

Acceptance evidence: a successful export and restore exercise using synthetic or explicitly approved test material, with documented limitations.

## Phase 3 — Evaluate local intelligence

Planned work:

- Evaluate replaceable local model and retrieval components.
- Test source-backed answers, uncertainty handling, and failure behavior.
- Measure resource requirements before choosing deployment components.
- Define and test the scope of offline operation.

Acceptance evidence: reproducible evaluations with stated inputs, methods, results, and offline limitations. Public examples must use non-sensitive data.

## Phase 4 — Introduce bounded workflows

Planned work:

- Define permissions and approval boundaries for each proposed action.
- Add inspectable action records and practical recovery procedures.
- Evaluate behavior when inputs are misleading or contain embedded instructions.
- Start with limited, reversible workflows.

Acceptance evidence: reviewed workflow tests demonstrating permission boundaries, expected approval behavior, and recovery where supported.

## Phase 5 — Validate durability and migration

Planned work:

- Repeat backup and recovery tests as the system changes.
- Replace a model or service without losing durable knowledge.
- Review access controls, dependencies, and data retention.
- Maintain documentation that another operator or model can understand.

Acceptance evidence: documented recovery and component-replacement exercises, including unresolved risks and maintenance requirements.

## Recording progress

For each milestone, record its status, acceptance criteria, evidence, dependencies, and known limitations. Distinguish proposed, in progress, verified, and deferred work. Changes to established decisions should identify the prior decision and explain the reason for revision.

The phases may be revised as evidence develops. Keep durable decisions in the controlled knowledge base and publish only their privacy-safe summaries.
