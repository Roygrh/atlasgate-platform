# Architecture Alignment Discovery

This synthesis derives from fictional simulated [SES-007](sessions/SES-007-architecture-alignment-discovery/02-session-record.md) and earlier SES-001–SES-005 evidence. It is preliminary discovery analysis, not a target architecture or Architecture Baseline. SES-006 external-consumer discovery is incomplete.

## Drivers and candidate responsibility boundaries

The [driver register](architecture/architecture-drivers.md) frames domain authority, runtime continuity, bounded traceability, outcome-aware diagnosis, operating cost, and missing partner evidence. The [boundary register](architecture/candidate-boundaries.md) tests platform versus domain, management versus request processing, policy definition/evaluation versus enforcement, publication authority versus execution, telemetry production versus outcome interpretation, and incident coordination versus consequence acceptance. Shared governance may provide consistent context; it does not confer ownership of Loyalty or Commerce semantics. A management/control-plane versus runtime/data-plane distinction is a candidate responsibility and failure boundary, not a selected topology.

## Alternatives and trade-offs

The [alternatives](architecture/architecture-alternatives.md) compare a more centralized platform, a modular control-plane candidate, and a more distributed control-plane candidate. Centralization may simplify coordination while concentrating queues and outages. Modular boundaries may contain conceptual coupling but could still hide a central process bottleneck. Distribution might isolate independently proven concerns while adding consistency, security, telemetry, and on-call cost. No workload, failure, cost, or authority evidence supports preference. Synchronous propagation is simpler to inspect but may block on dependency failure; asynchronous propagation can reduce that coupling while adding lag and reconciliation. Neither implies consumer adoption.

## Scenario implications

- **Commerce partner launch/change:** Domain meaning, partner readiness, shared context, publication timing, and approval waiting may have separate owners. External notice and onboarding architecture await SES-006.
- **Loyalty semantic change:** The producer's publication and each consumer's adoption are distinct. Domain semantic authority and shared metadata authorship need source-backed mapping.
- **Urgent tenant policy/exception:** Definition, advice, risk acceptance, evaluation, activation, and enforcement may be different responsibilities. Traceability must be scoped to purpose and authority.
- **Cross-boundary incident:** Request and configuration signals can be produced by Platform while domain or partner outcome interpretation remains elsewhere. Coordination does not automatically transfer consequence acceptance.

## Rejected conclusions and explicit non-decisions

The workshop rejected the inference that asynchronous adoption requires distributed event architecture. It did not select a modular monolith, distributed services, gateway extension model, ports/adapters, outbox, immutable store, policy mechanism, publication implementation, technology, target, requirement, diagram, or baseline. The [future ADR candidates](architecture/adr-candidates.md) identify consequential topics; the [deferred questions](architecture/deferred-decisions.md) retain unresolved authority, stale-state, partner, metadata, and change-lifecycle choices. None is an accepted ADR.

## Evidence before Architecture Baseline

Obtain representative inventory, dependency, approval and change records; configuration activation and outage behavior; domain metadata and consumer adoption samples; policy/exception authority and purpose-limited evidence; incident timelines, telemetry coverage, and actual consequence; capacity and operating-cost comparison; an architecture decision authority source; and direct SES-006 partner evidence. Then compare candidate directions with recorded criteria and conflicting evidence. I01-P08 Discovery Synthesis and Baseline Review remains planned and incomplete.
