# Fictional Company Profile: Northstar Digital Group

> **Fictional-scenario disclaimer:** Northstar Digital Group, its operating context, and all associated people and groups are fictional. They exist only to support a realistic simulated discovery exercise.

## Company overview

Northstar Digital Group is a multi-business digital enterprise operating customer-facing products and partner integrations across several markets. Its teams depend on APIs to connect channels, domain systems, shared capabilities, and external organizations. Exact scale, geography, financial profile, and regulatory obligations remain subjects for discovery.

## Business domains

The initial scenario includes commerce, customer loyalty, identity-related shared services, payments integration, and partner connectivity. These labels establish interview coverage, not finalized platform boundaries or approved domain models.

## Organizational model

Autonomous domain teams own business outcomes and delivery within their areas. A central platform engineering team provides shared technical foundations, while architecture, security, reliability, compliance, and product-management functions provide cross-cutting governance. Decision rights and escalation paths are not yet verified.

## Platform and domain-team relationship

The platform team is expected to enable domain teams rather than take ownership of their business logic. Domain teams currently vary in delivery practices and platform adoption. The appropriate balance among self-service, guardrails, central review, and local autonomy must be discovered rather than assumed.

## External partner context

Northstar exchanges APIs with fictional commercial partners and other external consumers. Their onboarding paths, identity models, support expectations, contractual service commitments, and technical constraints are unknown. Proposed partner-facing capabilities are not approved requirements.

## Current operating model

API work is initiated and delivered through a mix of domain roadmaps and cross-team requests. Reviews, publication practices, runtime ownership, incident response, and lifecycle management appear inconsistent, but their exact form and severity require evidence from planned sessions.

## Current-state API delivery problems

The discovery will examine reported themes: slow or unpredictable onboarding, duplicated gateway and policy work, uneven documentation, unclear ownership, inconsistent change management, fragmented operational visibility, and difficulty demonstrating governance. These are initial problem statements, not verified findings.

## Business drivers

- Reduce avoidable delay in delivering and consuming APIs.
- Improve consistency of security, lifecycle, and operational governance.
- Make ownership and accountability clearer across platform and domain teams.
- Support external partnerships without creating bespoke processes for every consumer.
- Produce evidence that platform investment improves measurable business and engineering outcomes.

The relative priority and success measures for these drivers remain open.

## High-level constraints

- Existing domain ownership and delivery autonomy must be considered.
- Security, compliance, and audit expectations may vary by business flow and market.
- Migration must coexist with current API traffic and team commitments.
- Platform capacity, funding, skills, and delivery timelines are not yet established.
- AtlasGate is directionally an enterprise API platform with control-plane and data-plane concerns. A modular monolith with hexagonal module boundaries is the current control-plane direction, and a component-oriented gateway runtime is the current data-plane direction. These directions remain subject to discovery evidence and future decisions.

## Intentionally unknown

Discovery has not established user volumes, API inventory, traffic patterns, critical journeys, team counts, regulatory scope, tenant model, service levels, budget, migration constraints, identity providers, existing vendors, deployment environments, data classifications, or approved success metrics. No proposed platform capability should be treated as a requirement until evidence and approval are recorded.

## Kickoff evidence

The fictional [SES-001 executive kickoff](sessions/SES-001-executive-kickoff/02-session-record.md) supports only preliminary context:

- **Supported simulated evidence:** Participants perceive delivery coordination, adoption, security-review timing, cross-team ownership, cost, and decision rights as investigation areas. Executive sponsorship covers discovery and funding priority. Technology selection, architecture approval, migration commitment, and numeric targets were excluded from the session.
- **Challenged statements:** Commerce challenged the breadth and attribution of delivery-delay claims; Security challenged attribution of delay to security; Commerce challenged broad operational-ownership claims.
- **Still unknown:** Enterprise prevalence and root causes, consumer and journey priority, inventory completeness, obligations, criticality, telemetry, total cost, capacity, formal decision rights, and any approved outcome or target.

This evidence does not validate the initial business-driver list or any architecture direction.

## Platform product discovery evidence

The fictional [SES-002 platform product discovery](sessions/SES-002-platform-product-discovery/02-session-record.md) adds bounded simulated evidence:

- **Supported observations within the simulation:** Participants described three distinct journeys and differentiated domain producers, internal consumers, partner developers, reviewers, and platform operator/support needs. They reported handoffs, missing context, informal alternatives, external dependencies, and weak outcome attribution.
- **Challenged interpretations:** A total partner-launch duration was challenged because partner waiting was mixed with Northstar work; a universal workflow was challenged by different triggers and release cadences; API counts and portal logins were challenged as value measures.
- **Unknown facts:** Prevalence, source-backed timelines, applicable obligations, direct consumer experience, workaround frequency and harm, inventory coverage, costs, authority, feasible baselines, and targets remain unknown.

SES-002 does not establish an enterprise operating model, approved product scope, or architecture direction.

## Security and compliance evidence

The fictional [SES-003 security and compliance discovery](sessions/SES-003-security-and-compliance-discovery/02-session-record.md) adds bounded simulated evidence, separate from objective company facts:

- **Observed simulated evidence:** Four scenarios exposed possible customer, order, transaction, loyalty, identity, access, decision-record, and telemetry assets plus partner, environment, domain/platform, actor, consumer, and evidence-purpose boundaries.
- **Challenged interpretations:** Participants challenged security review as the primary delay, a universal checklist, one identity or approval model, Security-only exception authority, centralized enforcement by default, and full telemetry retention for audit.
- **Still unknown:** Classifications, applicable obligations, authoritative sources, access lifecycle coverage, review causes, exception authority, evidence sufficiency, retention, current support access, threat likelihood, and implemented controls.

This evidence makes no legal conclusion, compliance claim, approved requirement, control selection, or architecture decision.

## Reliability and operations evidence (fictional SES-004)

Simulated evidence suggests criticality varies by outcome and period; infrastructure health may not represent consumer outcomes; and ownership uncertainty may concentrate at domain, platform, partner, consumer, and access boundaries. Telemetry existence, reliability performance, incident frequency, service commitments, and implemented operational controls remain unknown. No target, operating model, or observability architecture is approved.

## SES-005 observed simulated evidence

- **Supported simulated observations:** Commerce cases emphasize partner/date and tenant-treatment dependencies; Loyalty cases emphasize semantic interpretation and asynchronous internal adoption. Both report missing context, boundary coordination, support, compatibility, and completion concerns (STMT-118 through STMT-145).
- **Challenged interpretations:** Shared concerns do not establish one workflow; Platform coordination does not transfer domain semantic authority; producer deployment does not control consumer adoption; existing variation is not automatically necessary (STMT-113 through STMT-116, STMT-128, STMT-136, STMT-139).
- **Unknown facts:** Workflow prevalence, consumer inventory, partner readiness, delay attribution, authority, handoff acceptance, adoption state, compatibility outcomes, completion definitions, incidents, and source-backed necessary versus accidental variation.

No workflow, requirement, ownership model, or architecture is approved.
