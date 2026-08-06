# Assumptions and Open Questions

These registers are deliberately separate. An assumption is a provisional proposition; an open question identifies missing knowledge. Neither is a finding, approved requirement, or decision. Status values are `Open`, `Validation planned`, `Validated`, or `Invalidated`; only evidence may move an item to either terminal status.

## Assumptions

| ID | Statement | Rationale | Risk if false | Validation source | Owner | Status |
| --- | --- | --- | --- | --- | --- | --- |
| ASM-001 | Multiple domain teams experience materially different API delivery workflows. | The fictional organization is described as decentralized. | A uniform discovery and adoption approach could misrepresent actual needs. | Commerce and loyalty interviews; workflow artifacts | API platform product manager | Open |
| ASM-002 | External partner onboarding creates recurring coordination cost. | Partner connectivity is a stated business context. | Discovery could over-prioritize a low-frequency problem. | Partner lead and external consumer interview; support records if simulated | External partner integration lead | Open |
| ASM-003 | Cross-cutting API governance is inconsistent across teams. | Initial scenario themes mention varied practices. | A centralized solution could solve a problem that is local or already controlled. | Security, compliance, and domain sessions; policy sources | Security architect | Open |
| ASM-004 | Operational ownership is unclear at some API lifecycle stages. | Incident and runtime responsibilities are not documented. | Proposed governance could duplicate an effective ownership model. | Reliability workshop; responsibility and incident artifacts | SRE and observability lead | Open |
| ASM-005 | Domain teams value autonomy and will resist unnecessary central approval. | The organizational model assigns business outcomes to domains. | Adoption risks may be misstated and governance designed incorrectly. | Domain interviews and platform product discovery | API platform product manager | Open |
| ASM-006 | Reliable API inventory and traffic evidence are not yet available in one place. | Repository context contains no operational evidence. | Discovery planning may underestimate available data or duplicate existing analysis. | Architect and SRE workshop; inventory sources | Platform architect | Open |
| ASM-007 | Control-plane and data-plane separation remains useful as an architectural direction. | It is current project direction, not an assessed decision. | Premature structuring could constrain better options. | Architecture alignment workshop and future option assessment | Platform architect | Open |
| ASM-008 | A modular-monolith control plane and component-oriented gateway runtime warrant evaluation. | These are stated directions in project guidance. | Treating directions as conclusions could cause speculative architecture. | Validated requirements, quality attributes, prototypes, and ADR assessment | Platform architect | Open |

## Open questions

| ID | Question | Why it matters | Target stakeholder | Expected decision impact | Status |
| --- | --- | --- | --- | --- | --- |
| OQ-001 | Which business outcomes justify investment in AtlasGate, and how will they be measured? | Establishes prioritization and prevents output-only success claims. | Executive sponsor | Product scope, sequencing, and continuation criteria | Open |
| OQ-002 | Who has authority to approve discovery baselines, requirements, exceptions, and architecture decisions? | Traceable governance requires explicit decision rights. | Executive sponsor and platform product manager | Review and approval model | Open |
| OQ-003 | Which consumer segments and journeys are most important? | Value and usability depend on known consumers and jobs. | Product manager, domain leads, and partner lead | Discovery priority and proposed capabilities | Open |
| OQ-004 | What API inventory, ownership, lifecycle, and traffic evidence exists? | Scope and migration reasoning need current-state evidence. | Platform architect and SRE lead | Baseline, migration options, and validation approach | Open |
| OQ-005 | Which security, privacy, compliance, and audit obligations apply to which flows? | Controls cannot be assessed without applicable obligations and assets. | Security architect and compliance representative | Security requirements and risk treatment | Open |
| OQ-006 | Which journeys require service objectives, and what evidence supports their targets? | Prevents arbitrary reliability and performance commitments. | SRE lead and business leads | SLI/SLO selection and operational readiness | Open |
| OQ-007 | How do commerce and loyalty API delivery workflows differ? | Determines where shared practices help or hinder. | Commerce and loyalty domain leads | Platform boundaries and adoption model | Open |
| OQ-008 | What does an external consumer need for onboarding, change, and support? | Partner experience may drive product and operating-model choices. | External consumer and partner integration lead | Consumer experience proposals | Open |
| OQ-009 | What existing platforms, contracts, skills, and delivery capacity constrain change? | Feasibility and migration depend on real constraints. | Platform engineering and executive sponsor | Option assessment, sequencing, and cost | Open |
| OQ-010 | What evidence would justify changing or rejecting the current architectural directions? | Keeps architecture adaptive and falsifiable. | Architecture alignment participants | ADR drivers and validation plans | Open |
