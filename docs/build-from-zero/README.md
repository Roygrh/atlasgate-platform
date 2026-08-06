# Build from Zero

## Purpose

Build from Zero is the reproducible reconstruction record for AtlasGate. It explains how to recreate the repository and verify each capability from an empty starting point without relying on undocumented local state.

## Chapter conventions

Chapters use ordered filenames, state their prerequisites, describe only completed work, list commands and expected observations, and include validation and known limitations. Planned work is labeled explicitly and is not presented as available behavior.

## Update rules

Every iteration must update the relevant reconstruction chapter and the iteration ledger. Commands, versions, paths, and outcomes must be based on observed results. When behavior changes, the affected chapter must change in the same iteration. Validation must be proportional to risk, include negative paths when applicable, and extend beyond compilation.

## Current state

- [00 - Prerequisites](00-prerequisites.md): complete for the governance bootstrap environment snapshot.
- [01 - Repository Bootstrap](01-repository-bootstrap.md): reconstruction of the committed governance baseline.
- [02 - Discovery Artifacts](02-discovery-artifacts.md): reconstruction and extension rules for the discovery and decision-governance foundation.
- Repository governance and documentation entry points: complete for `I00-P01`.
- Discovery planning, stakeholder modeling, risk governance, and architecture decision governance: complete for `I00-P02`; no discovery session has occurred.
- Application, build, runtime, and deployment reconstruction: deferred; none has been implemented.
