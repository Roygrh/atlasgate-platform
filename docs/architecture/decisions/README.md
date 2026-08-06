# Architecture Decision Governance

## Choosing a record

An architecture decision record (ADR) is required when a choice has material, durable, or cross-cutting consequences; changes a system boundary or quality-attribute approach; introduces a significant dependency or technology; affects security, data, operations, or deployment; is difficult to reverse; or needs alternatives and trade-offs preserved.

A lightweight decision entry in an iteration or domain record is sufficient for a local, low-risk, readily reversible choice that does not alter an architecture baseline. If its consequences grow, promote it to an ADR and link the earlier entry.

## Lifecycle and numbering

ADR statuses are `Proposed`, `Accepted`, `Rejected`, `Deprecated`, and `Superseded`. Only an authorized review may move a proposal to `Accepted` or `Rejected`. Use immutable, zero-padded identifiers in creation order: `ADR-0001-title.md`. Never reuse a number, including for deleted or rejected proposals.

Accepted records are historical facts and are not rewritten to conceal later change. A replacement ADR lists the records it supersedes; each superseded record is updated only to set its status and link to the replacement. Deprecation indicates that a decision should no longer guide new work but has no single replacement.

## Review and traceability

Authors identify decision owners and reviewers appropriate to the affected business, architecture, security, reliability, compliance, and delivery concerns. Review checks evidence quality, drivers, credible alternatives, reversibility, consequences, risks, and the validation plan. Urgency does not remove the need to record uncertainty and follow-up validation.

Each ADR links, where applicable, to supporting findings and approved requirements, affected risk identifiers, validation tests or experiments, implementation changes, operational evidence, and superseded records. Missing links must be marked `Not yet available` with an explanation rather than invented. Implementation does not itself prove that a decision was accepted or successful.

Use the [ADR template](adr-template.md). No technology or architecture ADR has been created in this foundation iteration.
