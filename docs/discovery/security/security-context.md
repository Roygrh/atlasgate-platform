# Preliminary Security Context

All records derive from fictional simulated evidence. Sensitivity and ownership are hypotheses for validation; no classification or boundary is approved.

## Assets

| ID | Asset | Importance | Possible sensitivity | Evidence | Uncertainty | Owner | Status |
| --- | --- | --- | --- | --- | --- | --- | --- |
| AST-001 | Customer and order identifiers used in commerce partner flows | Could connect access to customer and order activity | Potentially sensitive; classification unverified | STMT-047, STMT-053 | Fields, purpose, jurisdiction, and classification unknown | Aisha Bello | Under validation |
| AST-002 | Transaction-related information exposed through commerce APIs | Could influence financial or business activity | Potentially sensitive; scope unverified | STMT-047, STMT-053 | Exact fields, source obligations, and consumers unknown | Aisha Bello | Preliminary |
| AST-003 | Loyalty customer identifiers, reward balances, and eligibility data | Influences customer benefit and eligibility outcomes | Potentially sensitive or integrity-critical; unverified | STMT-057, STMT-059 | Consumer set, downstream use, and classification unknown | Aisha Bello | Preliminary |
| AST-004 | Human, organization, service, and environment identity context | Supports attribution, authorization, review, and removal | May include sensitive identity and relationship metadata | STMT-050, STMT-052, STMT-055 | Authoritative sources and lifecycle coverage unknown | Jordan Lee | Under validation |
| AST-005 | Credentials and effective access configuration | Enables API and support access | Security-sensitive; actual forms unknown | STMT-055, STMT-060, STMT-069 | Inventory, sharing, expiry, and revocation evidence unknown | Jordan Lee | Preliminary |
| AST-006 | Approval, exception, access, and closure records | May demonstrate accountable decisions | May expose security context or personal metadata | STMT-048, STMT-064, STMT-070 | Required content, integrity, access, and retention unknown | Henry Walsh | Preliminary |
| AST-007 | Operational logs, traces, request identifiers, and diagnostic context | Supports diagnosis and incident reconstruction | May contain partner or customer-related fragments | STMT-061, STMT-071, STMT-072 | Availability, contents, access, and safe minimization unknown | Jordan Lee | Under validation |

## Trust and responsibility boundaries

| ID | Boundary | Separated actors or systems | Why it matters | Evidence | Uncertainty | Owner | Status |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BND-001 | External partner to Northstar | Partner people/services and Northstar domains/platform | Organization identity, responsibility, support, and data use change | STMT-049, STMT-052, STMT-053 | Contract, identity, and responsibility sources not reviewed | Sofia Novak | Under validation |
| BND-002 | Non-production to production | Test actors/data/access and production actors/data/access | Consequence, approval, and removal expectations may differ | STMT-049, STMT-055, STMT-069 | Environment definitions and current transitions unknown | Jordan Lee | Preliminary |
| BND-003 | Domain to platform/support | Domain ownership and shared platform/support responsibilities | Diagnostic action can cross ownership and accountability | STMT-049, STMT-068, STMT-069 | Formal responsibility and support paths unknown | Priya Raman | Under validation |
| BND-004 | Human to service actor | Named people and non-human service identities | Delegation and attribution may be lost | STMT-050, STMT-055 | Actor inventory and delegation model unknown | Jordan Lee | Preliminary |
| BND-005 | Commerce or loyalty producer to consuming team | Data producer and internal consumer services/teams | Purpose, downstream use, change, and revocation differ | STMT-057 through STMT-060 | Consumer inventory and data-use evidence absent | Priya Raman | Preliminary |
| BND-006 | Operational telemetry to durable review evidence | Diagnostic producers/consumers and decision/audit consumers | Purpose, context, integrity, minimization, and retention differ | STMT-061, STMT-070, STMT-072 | Evidence rules and sources not inspected | Henry Walsh | Under validation |
