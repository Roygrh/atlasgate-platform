# 02 - Discovery Artifacts

## Purpose and structure

## SES-005 typed domain records

SES-005 adds workflow (`DWF`), dependency (`DEP`), handoff (`HOF`), and adoption-need (`ADN`) registers under [`docs/discovery/domains/`](../discovery/domains/README.md). Derive each record from stakeholder statements, preserve controlling party and authority uncertainty, keep shared concern separate from identical process, and propagate evidence without changing non-terminal status. The detailed procedure is in [chapter 07](07-domain-workflow-discovery.md).

The [discovery index](../discovery/README.md) defines evidence types and traceability. Reconstruct the foundation by reviewing the [fictional company profile](../discovery/01-company-profile.md), [stakeholder map](../discovery/02-stakeholder-map.md), [engagement plan](../discovery/03-discovery-plan.md), [assumption and open-question registers](../discovery/04-assumptions-and-open-questions.md), and [glossary](../discovery/05-glossary.md). Project-level uncertainty is maintained in the [risk register](../project-management/risk-register.md); consequential choices follow [decision governance](../architecture/decisions/README.md).

The company profile bounds the fictional scenario, the stakeholder map defines planned contributors and tensions, the plan sequences evidence collection, the registers preserve uncertainty, and the glossary prevents terms from silently acquiring implementation meaning.

## Adding future evidence

1. Create a record for the planned simulated activity and label the organization and participants fictional.
2. Preserve stakeholder statements with attribution and session context.
3. Synthesize findings separately, citing supporting and conflicting statements.
4. Update assumptions and open questions only when the new evidence is relevant; do not resolve them by inference alone.
5. Record hypotheses and proposed requirements separately. Approval requires an explicit future baseline review.
6. Link consequential architecture choices to discovery evidence through an ADR; do not use an ADR to manufacture evidence.
7. Update this reconstruction record and the iteration ledger in the same iteration.

## Identifier conventions

Use `SES-NNN` for sessions, `STMT-NNN` for stakeholder statements, `FND-NNN` for findings, `SEG-NNN` for consumer segments, `JRN-NNN` for journeys, `HYP-NNN` for hypotheses, `OUT-NNN` for outcome candidates, `ASM-NNN` for assumptions, `OQ-NNN` for open questions, `RSK-NNN` for risks, `AST-NNN` for assets, `BND-NNN` for boundaries, `OBL-NNN` for obligation candidates, `THR-NNN` for threat scenarios, `EXC-NNN` for exception cases, `EVR-NNN` for evidence requirements, and `ADR-NNNN` for architecture decisions. Identifiers are never renumbered or reused; closed and superseded records remain traceable. See [03 - Executive Kickoff](03-executive-kickoff.md), [04 - Platform Product Discovery](04-platform-product-discovery.md), and [05 - Security and Compliance Discovery](05-security-and-compliance-discovery.md) for their derivation workflows.

## Validation

SES-004 additionally uses immutable `CRJ-NNN`, `INC-NNN`, `OWN-NNN`, `TEL-NNN`, and `SLI-NNN` sequences for critical journeys, incident scenarios, ownership boundaries, telemetry candidates, and SLI candidates respectively; see [06](06-reliability-and-operations-discovery.md).

- Confirm every Markdown link resolves to an existing repository file.
- Confirm statements, findings, assumptions, hypotheses, requirements, and decisions remain distinguishable.
- Confirm only sessions actually simulated for the portfolio are described as completed and no proposal is described as approved.
- Confirm fictional labels appear in the company profile, stakeholder model, and activity records.
- Run `git diff --check`, inspect `git diff --name-only`, and verify no executable or infrastructure artifact entered scope.
- Verify the private plan is still ignored and untracked and that nothing is staged.

## Current limitation

This chapter reconstructs the discovery foundation. SES-001 through SES-004 now provide fictional simulated sessions and preliminary synthesis; see [06](06-reliability-and-operations-discovery.md). There are no validated findings, segments, journeys, assets, or boundaries; no supported hypotheses; no confirmed obligations; no assessed threats; no approved exceptions, requirements, targets, commitments, or controls; no final architecture baseline; and no implemented capabilities.
