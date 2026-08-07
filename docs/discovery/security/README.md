# Preliminary Security Discovery

This directory contains fictional, preliminary discovery analysis. It is not legal advice, a completed threat model, a threat-model diagram, approved requirements, a target security architecture, selected controls, or evidence of implemented controls.

## Record distinctions

| Record | Meaning |
| --- | --- |
| Asset | Something potentially valuable or sensitive that may need protection. |
| Trust boundary | A point where trust, responsibility, actor, organization, system, or environment changes. |
| Obligation candidate | A possible duty whose source and applicability require authoritative interpretation. |
| Threat scenario | A plausible adverse sequence used to guide later analysis, not a measured or accepted risk. |
| Control objective | A technology-neutral desired security outcome; it is neither approved nor a selected control. |
| Exception case | A preliminary request to deviate from an expected condition, including authority, expiry, and closure questions. |
| Evidence requirement | A candidate need for information supporting a decision, review, or audit purpose. |
| Approved requirement | A traceable, testable need made authoritative only by a future explicit approval process. None exists here. |
| Decision | An authorized choice among alternatives with rationale and consequences. None is made here. |
| Implemented control | Verified operating behavior that satisfies an approved objective. None is claimed here. |

## Identifiers and lifecycle

Use immutable, sequential IDs: `AST-NNN`, `BND-NNN`, `OBL-NNN`, `THR-NNN`, `EXC-NNN`, and `EVR-NNN`. Never reuse or renumber an ID. Status changes require cited evidence and the relevant authority; rejection or retirement preserves the record. Cross-references must point to existing statements or records. Preliminary discovery cannot by itself validate, confirm, approve, assess, close, or implement an item.

Current records: [security context](security-context.md), [obligation candidates](obligation-candidates.md), [threat scenarios](threat-scenarios.md), [exception cases](exception-cases.md), and [evidence requirements](evidence-requirements.md).
