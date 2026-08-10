# Reliability Discovery

This directory contains preliminary fictional discovery analysis, not approved operational requirements, target reliability architecture, service commitments, or implemented observability.

## Distinctions

- A **critical journey candidate** is a consumer or business outcome proposed for consequence-based validation.
- An **incident scenario** is a hypothetical service-impact situation used to test signals and responsibilities; it is not proof of a real incident.
- **Operational ownership** concerns responsibility for operating or responding within a boundary.
- A **support boundary** marks where diagnostic, communication, or assistance responsibility changes.
- A **telemetry candidate** is a possible signal or evidence source whose existence and fitness require validation.
- A **service-level indicator candidate** is a proposed measurement definition, not a target.
- A **service-level objective** would set a desired indicator level over a period; none is approved.
- A **service-level agreement** would create a service commitment and consequences; none is approved.
- An **error budget** would derive allowable unreliability from an approved objective; none exists.
- An **approved requirement** has passed future authorization and baselining; discovery records are not requirements.
- An **operational decision** is an authorized choice about operating behavior; none is made here.
- **Implemented observability** means deployed, verified collection and use; no such capability is claimed.

## Identifiers and lifecycle

Use immutable sequential `CRJ-NNN`, `INC-NNN`, `OWN-NNN`, `TEL-NNN`, and `SLI-NNN` identifiers. Never reuse or renumber an ID. Preserve rejected records for traceability. Status changes require cited validation evidence and authorized review. SES-004 creates only non-terminal states allowed in each register.

Registers: [critical journeys](critical-journey-candidates.md), [incident scenarios](incident-scenarios.md), [ownership/support boundaries](ownership-and-support-boundaries.md), [telemetry candidates](telemetry-candidates.md), and [SLI candidates](sli-candidates.md).
