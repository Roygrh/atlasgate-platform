# Reliability and Operations Discovery Synthesis

This synthesis derives from fictional simulated SES-004 evidence. It is preliminary analysis, not an approved operational requirement, service commitment, target, architecture, ownership model, or implemented observability claim.

## Critical journeys and incidents

Three [critical-journey candidates](reliability/critical-journey-candidates.md) cover selected commerce launch transactions, loyalty behavior after change, and partner production entry/support. They are narrower than the journey inventory. Four [incident scenarios](reliability/incident-scenarios.md) preserve commerce degradation, loyalty semantic/change failure, uncertain cross-boundary accountability, and diagnosis constrained by telemetry or safe-access gaps.

Criticality appears conditional on consumer, outcome, consequence, and period. A universal reliability level is unsupported. No real incident, severity, traffic profile, frequency, or recovery performance was established.

## Ownership, support, and lifecycle

The [ownership register](reliability/ownership-and-support-boundaries.md) distinguishes domain semantics and mitigation, shared-platform operation, partner dependency/communication, consumer integration, coordination/closure/risk acceptance, and safe support access. Reachable platform support does not acquire domain, partner, or business-risk accountability. Centralized operations are not presumed preferable.

Detection, diagnosis, mitigation, restoration, communication, and closure have different evidence needs and may have separate clocks and owners. Informal chat and expert-query workarounds may accelerate local response while hiding demand, waiting, decisions, ownership, and evidence cost.

## Telemetry, evidence, and measurement

The [telemetry register](reliability/telemetry-candidates.md) contains candidates only. Possible request outcomes, latency, dependencies, contacts, lifecycle timestamps, change effects, and correlation/ownership metadata are not claimed to exist. Coverage, semantics, integrity, access, retention, and ownership require validation. Missing signals constrain diagnosis; noisy signals can create false positives and alert fatigue.

Infrastructure health can help diagnosis but cannot alone prove partner transaction completion or correct loyalty semantics. Operational telemetry optimized for diagnosis is distinct from durable decision or audit evidence.

The [SLI register](reliability/sli-candidates.md) proposes target-free definitions around request/transaction success, latency, change success, owner identification, acknowledgement/restoration, and incident-evidence completeness. Northstar-controlled work and external waiting need separate rules. No candidate is demonstrated measurable. Numeric targets, SLOs, SLAs, error budgets, recovery commitments, and support promises would be unsupported until criticality, event definitions, boundaries, exclusions, telemetry quality, baselines, consequences, costs, and authority are validated.

## Security dependency, non-decisions, and evidence needs

SES-003 safe-support questions remain intact: purpose, authorization, attribution, minimization, review, removal, and closure are not displaced by urgency. No access mechanism or control is selected. SES-004 makes no decision on requirements, targets, tiers, severities, ownership model, incident process, observability architecture, alerting, paging, dashboards, ticketing, retention, technology, or implementation.

Required evidence includes sanitized launch/change timelines, affected operations and consumer outcomes, partner contacts/pauses, ownership and escalation sources, accepted/rejected handoffs, incident/support records, telemetry inventories and quality evidence, direct interviews, contract interpretation, and service-commitment/risk authority.
