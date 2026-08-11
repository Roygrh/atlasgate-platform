# Initial Glossary

These definitions support discovery and do not imply that the described behavior is implemented.

| Term | Definition |
| --- | --- |
| API product | An API or related set of APIs managed for defined consumers and outcomes across a lifecycle. |
| API consumer | A person, team, partner, or software system that uses an API. |
| Consumer segment | A preliminary grouping of consumers with similar jobs and constraints, maintained as a validation subject rather than approved scope. |
| Current-state journey | An evidence-linked ordered description of how actors currently attempt an outcome, including handoffs, alternatives, friction, and uncertainty. |
| Product hypothesis | A falsifiable proposition connecting a segment or journey to an expected observable effect and rejection signal. |
| Workaround | An alternative used to bypass or accelerate part of a current journey that may shift cost or risk elsewhere. |
| Adoption | Use of a path or practice by an eligible consumer; it is not sufficient evidence of value without a related outcome. |
| Candidate measure | A proposed observation for evaluating an outcome whose feasibility, baseline, attribution, and target are not yet established. |
| Control plane | The concern responsible for configuring, governing, and managing runtime behavior; its exact AtlasGate scope is undecided. |
| Data plane | The concern that handles API traffic according to effective runtime configuration; it is not yet implemented. |
| Gateway runtime | A prospective data-plane component that would process API traffic; its capabilities and technology are undecided. |
| Policy | A stated rule or constraint that may be evaluated or enforced through people, process, or technology. |
| Tenant | A logically identified organizational or consumer boundary; the need and isolation semantics remain open. |
| Revision | A distinguishable state of an artifact over time, without implying a particular storage or versioning mechanism. |
| Publication | The act of making an approved revision available to a defined audience or environment; workflow details are undecided. |
| Stakeholder statement | An attributed assertion made by a participant during a discovery activity. |
| Finding | A synthesized conclusion supported by cited discovery evidence and accompanied by conflicts or confidence where relevant. |
| Assumption | A proposition treated as plausible pending validation. |
| Requirement | A traceable, testable need that becomes authoritative only through an explicit approval process. |
| Decision | An authorized selection among alternatives, with rationale and consequences recorded. |
| SLI | Service level indicator: a quantitative measure of an aspect of service behavior. |
| SLO | Service level objective: a target value or range for an SLI over a defined period. |
| Error budget | The permitted amount of behavior outside an SLO over its defined period. |
| Asset | Something potentially valuable or sensitive that may need protection. |
| Trust boundary | A point where trust, responsibility, actor, organization, system, or environment changes. |
| Obligation candidate | A possible duty whose source and applicability require authoritative interpretation. |
| Threat scenario | A plausible adverse sequence used as input to later threat analysis, not an assessed risk. |
| Control objective | A technology-neutral desired security outcome, distinct from an approved requirement or selected control. |
| Exception | A requested deviation from an expected condition, with unresolved authority, scope, duration, monitoring, and closure unless approved elsewhere. |
| Evidence requirement | A candidate need for information supporting a defined decision, review, or audit purpose. |
| Audit evidence | Information intended to support a reviewable conclusion about a decision, obligation, or control; sufficiency and retention require validation. |
| Operational telemetry | Logs, metrics, traces, or related signals produced primarily to understand operation and diagnose behavior. |
| Revocation | Removal or invalidation of access when authorization, purpose, ownership, or duration no longer supports it. |
| Evidence minimization | Limiting collected and retained evidence to what is necessary for a stated purpose while preserving required integrity and context. |
| Critical journey | A consumer or business outcome whose consequence and critical periods require validation. |
| Incident scenario | A hypothetical service-impact situation used to test signals and responsibilities. |
| Operational ownership | Responsibility for operating or responding within a defined boundary. |
| Support boundary | A point where diagnostic, communication, or assistance responsibility changes. |
| Detection | Recognition of possible impact; it does not establish cause. |
| Diagnosis | Evidence-based identification of likely cause and accountable boundary. |
| Restoration | Verified return of the selected consumer outcome, distinct from mitigation or closure. |
| Telemetry candidate | A possible operational signal whose existence and fitness require validation. |
| Service-level indicator | A defined measurement of a service or user outcome; it is not a target. |
| Service-level objective | A desired indicator level over a period; none is approved for AtlasGate. |
| Service-level agreement | A service commitment and associated consequences; none is approved for AtlasGate. |
| Error budget | Allowable unreliability derived from an approved objective; none exists for AtlasGate. |
| False positive | A signal that indicates actionable impact when the defined condition is absent. |
| Alert fatigue | Reduced responder effectiveness caused by excessive or low-value signals. |
| Recovery evidence | Purpose-appropriate information showing mitigation and verified restoration events. |
| Domain workflow | A scenario-specific discovery record of how domain and other actors currently attempt an outcome; it is not a target process. |
| Workflow step | A bounded activity within a workflow, without implying a global sequence or gate. |
| Dependency | Readiness, information, action, or decision controlled by one party that affects another actor or workflow. |
| Handoff | Movement of information, coordination, or responsibility; authority transfers only when evidence establishes it. |
| Producer responsibility | Responsibility for producer-side domain behavior, change context, compatibility reasoning, and operation within a stated boundary. |
| Consumer responsibility | Responsibility for assessing impact, testing, scheduling, and using a change within the consumer's product boundary. |
| Semantic ownership | Authority and responsibility for authoritative domain meaning; platform carriage or coordination does not establish it. |
| Completion criteria | Evidence and conditions used to determine whether a scenario is complete, potentially beyond deployment. |
| Domain-specific variation | A workflow difference plausibly caused by domain meaning, actors, consequence, or business context. |
| Accidental inconsistency | A potentially avoidable difference not yet shown necessary by business, risk, authority, or consumer context. |
