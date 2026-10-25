# Build from Zero

**I01 closure:** [Chapter 10](10-discovery-synthesis-and-baseline-review.md) reconstructs SES-008 evidence reconciliation and the accepted [Business Discovery Baseline](../discovery/baseline/README.md). I01 Business Discovery is complete; Requirements and Architecture Baselines and implementation remain future work.

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
- [03 - Executive Kickoff](03-executive-kickoff.md): reconstruction of the first fictional simulated session and its traceable evidence chain.
- [04 - Platform Product Discovery](04-platform-product-discovery.md): reconstruction of the second fictional simulation, consumer segments, current-state journeys, product hypotheses, and evidence propagation.
- [05 - Security and Compliance Discovery](05-security-and-compliance-discovery.md): reconstruction of the third fictional simulation and its preliminary assets, boundaries, obligations, threats, exceptions, and evidence requirements.
- [06 - Reliability and Operations Discovery](06-reliability-and-operations-discovery.md): reconstruction of the fourth fictional simulation and target-free operational candidates.
- [07 - Domain Workflow Discovery](07-domain-workflow-discovery.md): reconstruction of the fifth fictional simulation and Commerce/Loyalty comparison.
- [08 - Architecture Alignment Discovery](08-architecture-alignment-discovery.md): fictional simulated SES-007 and preliminary driver, boundary, alternative, and ADR-topic derivation.
- [09 - External Consumer Discovery](09-external-consumer-discovery.md): fictional simulated SES-006 direct consumer account and preliminary external-consumer registers.
- [10 - Discovery Synthesis and Baseline Review](10-discovery-synthesis-and-baseline-review.md): fictional SES-008 and accepted Business Discovery Baseline; I01 complete.
- Repository governance and documentation entry points: complete for `I00-P01`.
- Discovery planning, stakeholder modeling, risk governance, and architecture decision governance: complete for `I00-P02`.
- Fictional SES-001 executive-kickoff simulation, evidence, preliminary findings, and outcome candidates: complete for `I01-P01`; none is an approved requirement or validated enterprise conclusion.
- Fictional SES-002 product-discovery simulation, segments, journeys, hypotheses, findings, and synthesis: complete for `I01-P02`; all remain preliminary or under validation.
- Fictional SES-003 security/compliance simulation and preliminary security records: complete for `I01-P03`; no legal applicability, requirement, control objective, control, exception, or architecture is approved.
- Fictional SES-004 reliability/operations simulation and target-free registers: complete for `I01-P04`; no target, commitment, tooling, or observability is approved or implemented. See [06](06-reliability-and-operations-discovery.md).
- Fictional SES-005 domain workflow comparison and typed registers: complete for `I01-P05`; no universal workflow, requirement, ownership model, or implementation is approved. See [07](07-domain-workflow-discovery.md).
- Fictional SES-007 architecture alignment and candidate registers: complete for `I01-P07`; P07 preceded P06 and no architecture baseline or ADR is approved. See [08](08-architecture-alignment-discovery.md).
- Fictional SES-006 external-consumer discovery and preliminary registers: complete for `I01-P06`. Fictional SES-008 synthesis and Business Discovery Baseline: complete for `I01-P08`; see [10](10-discovery-synthesis-and-baseline-review.md).
- Application, build, runtime, and deployment reconstruction: deferred; none has been implemented.
