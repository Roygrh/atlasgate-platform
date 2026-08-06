# 02 - Discovery Artifacts

## Purpose and structure

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

Use `ASM-NNN` for assumptions, `OQ-NNN` for open questions, `RSK-NNN` for risks, and `ADR-NNNN` for architecture decisions. Future evidence types must define their own stable convention before first use. Identifiers are never renumbered or reused; closed and superseded records remain traceable.

## Validation

- Confirm every Markdown link resolves to an existing repository file.
- Confirm statements, findings, assumptions, hypotheses, requirements, and decisions remain distinguishable.
- Confirm no planned interview is described as completed and no proposal is described as approved.
- Confirm fictional labels appear in the company profile, stakeholder model, and activity records.
- Run `git diff --check`, inspect `git diff --name-only`, and verify no executable or infrastructure artifact entered scope.
- Verify the private plan is still ignored and untracked and that nothing is staged.

## Current limitation

This chapter reconstructs the discovery foundation only. There are no simulated session records, synthesized findings, approved requirements, final architecture baseline, or implemented capabilities.
