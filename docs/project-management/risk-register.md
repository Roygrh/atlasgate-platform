# Risk Register

## Governance

This register identifies uncertain events or conditions that could harm AtlasGate outcomes. Probability and impact use `Low`, `Medium`, or `High`; they are qualitative until evidence supports a numerical model. Status values are `Open`, `Monitoring`, `Mitigating`, `Realized`, and `Closed`. The named owner coordinates evidence, mitigation, triggers, and review; ownership does not imply sole responsibility.

| ID | Risk | Probability | Impact | Mitigation | Owner | Trigger | Status |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RSK-001 | Excessive scope obscures the smallest valuable outcome. | High | High | Baseline explicit outcomes, exclusions, and incremental acceptance criteria. | API platform product manager | Discovery proposals expand without priority or evidence. | Open |
| RSK-002 | Architectural directions become commitments before requirements and options are assessed. | Medium | High | Label directions, require decision drivers and ADRs, and retain falsifiable assumptions. | Platform architect | A design or diagram is described as final without assessed evidence. | Mitigating |
| RSK-003 | Unnecessary tooling or dependencies increase cost and maintenance. | Medium | Medium | Add tooling only for concrete requirements; prefer repository wrappers and pinned choices. | Platform engineering lead | A tool is proposed without a use case, owner, or validation plan. | Open |
| RSK-004 | Generated artifacts become inconsistent or irreproducible. | Medium | Medium | Record generation sources, commands, versions, and review generated changes. | Platform engineering lead | Generated output differs without an explainable source change. | Open |
| RSK-005 | Documentation becomes stale relative to behavior or decisions. | Medium | High | Update Build from Zero, ledger, and affected documentation in every iteration; validate links and claims. | API platform product manager | A change lands without corresponding documentation review. | Mitigating |
| RSK-006 | Weak traceability allows statements or assumptions to appear as approved requirements. | High | High | Use stable identifiers, explicit evidence types, source links, owners, and approval states. | API platform product manager | A requirement or decision lacks evidence and approval provenance. | Mitigating |
| RSK-007 | An unreliable local environment prevents reproducible validation. | Medium | Medium | Record prerequisites and observed limitations; use pinned repository tooling when introduced. | Platform engineering lead | Required validation differs across supported environments or cannot run locally. | Monitoring |
| RSK-008 | Unsupported performance claims create false confidence. | Medium | High | Define evidence-based targets and reproducible benchmarks before making claims. | SRE and observability lead | Latency, throughput, or scale is claimed without workload and results. | Open |
| RSK-009 | Security is treated superficially or as a checklist. | Medium | High | Derive controls from assets, threats, obligations, negative paths, and verifiable evidence. | Security architect | Security claims lack threat context, ownership, or validation. | Open |
| RSK-010 | Portfolio evidence remains incomplete or overstates delivery. | Medium | Medium | Link only existing, validated artifacts and distinguish planned from implemented evidence. | Project maintainer | The evidence map marks absent behavior as implemented or omits delivered proof. | Mitigating |
