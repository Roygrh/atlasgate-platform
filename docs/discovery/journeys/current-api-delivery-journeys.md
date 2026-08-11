# Current API Delivery Journeys

These ordered-text journeys derive from the fictional simulated [SES-002 transcript](../sessions/SES-002-platform-product-discovery/01-simulated-transcript.md). They are not universal or validated workflows. Journeys describe broader consumer/delivery paths; the [domain workflow register](../domains/domain-workflows.md) adds scenario-level change behavior and is not a target process.

## JRN-001 - Commerce external partner launch

- **Actors:** Commerce producer and operator, external partner developer, partner integration lead, reviewers, platform operator/support.
- **Trigger:** A dated commercial partner launch.
- **Intended outcome:** The partner can use the commerce integration in operation with an understood support route.
- **Ordered stages:** 1. Clarify commercial exchange. 2. Draft interface notes. 3. Identify contacts and required context. 4. Seek applicable review. 5. Request non-production access. 6. Coordinate partner tests and returned inputs. 7. Schedule release. 8. Transition to operational support.
- **Handoffs and reported friction:** Commerce-to-partner contact, review, platform access, test feedback, exception, and support; incomplete person, organization, service, ownership, environment, purpose, classification, expiry, or closure context; external readiness; returned requests; unclear waiting attribution.
- **Alternatives:** Direct messages, local tracker, and temporary shared test credential. The credential can accelerate local testing but weakens attribution, rotation, cleanup, and support.
- **Known and conflicting evidence:** Aisha recalled the sequence (STMT-026) and an unverified mixed review interval (STMT-053); Sofia challenged total and security-delay attribution (STMT-027, STMT-052); Elena required reason-coded stages (STMT-054); exception and support authority remain unknown (STMT-062 through STMT-072).
- **Estimates:** Six to eight weeks for one recalled journey; unverified and includes unknown partner waiting (STMT-026).
- **Missing evidence:** Stage timestamps, pause reasons, access returns, review path, partner feedback, operational incidents, and prevalence.
- **Related statements:** STMT-021, STMT-026 through STMT-030, STMT-047 through STMT-056, STMT-062 through STMT-072.
- **Related outcomes or questions:** OUT-001, OUT-002, OUT-003; OQ-003, OQ-011, OQ-013.
- **Owner:** Aisha Bello
- **Status:** Under validation

## JRN-002 - Loyalty API change for internal product teams

- **Actors:** Loyalty producer/support, internal product-team consumers, platform support, and reviewers when applicable.
- **Trigger:** A loyalty product or rule change.
- **Intended outcome:** Internal consumers adopt compatible behavior on workable release schedules.
- **Ordered stages:** 1. Clarify product need. 2. Identify known consumers. 3. Circulate semantics and examples. 4. Implement locally. 5. Arrange consumer testing. 6. Negotiate independent release timing. 7. Observe support channels and change effects.
- **Handoffs and reported friction:** Producer-to-consumer interpretation, incomplete consumer and service-actor inventory, incompatible test windows, repeated questions, copied assumptions/access, unclear downstream purpose, and missing revocation triggers.
- **Alternatives:** Internal directories, direct team channels, cloned prior configuration, and informal expert help.
- **Known and conflicting evidence:** Lucas reported consumer and cadence uncertainty (STMT-031); Aisha rejected synchronized releases and a partner approval route by default (STMT-032, STMT-057); Elena challenged internal trust assumptions (STMT-058); Jordan described risky cloned access (STMT-059).
- **Estimates:** Roughly three engineer-days of repeated questions across two teams for one change; unverified and possibly mixed with implementation discussion (STMT-033).
- **Missing evidence:** Consumer inventory, version/change records, release dates, question categories, rework, incidents, and consumer-team testimony.
- **Related statements:** STMT-022, STMT-031 through STMT-035, STMT-057 through STMT-061.
- **Related outcomes or questions:** OUT-001, OUT-002; OQ-007, OQ-011, OQ-014.
- **Owner:** Lucas Pereira
- **Status:** Under validation

## JRN-003 - External partner API onboarding

- **Actors:** External partner developer, business contact, partner integration lead, eligibility and identity reviewers, platform operator/support, domain producer.
- **Trigger:** A prospective eligible partner seeks an API integration.
- **Intended outcome:** The partner discovers an appropriate API, obtains access, completes a successful test, and knows production and support routes.
- **Ordered stages:** 1. Ask a business contact what exists. 2. Receive selected documentation. 3. Confirm commercial eligibility. 4. Identify technical contacts. 5. Gather identity and access information. 6. Arrange test environment. 7. Exchange test results. 8. Explain production access, change notice, and support.
- **Handoffs and reported friction:** Business-to-technical introduction, emailed document versions, organization/person/service identity dependencies, environment visibility, access review and removal, external waiting, and support routing without sufficient but minimized context.
- **Alternatives:** Email documents, partner-specific calls, integration-coordinator mediation, and platform tickets.
- **Known and conflicting evidence:** Sofia described partner variation (STMT-036) and challenged login metrics (STMT-038); Jordan reported document and context gaps (STMT-037); Aisha warned that a new destination can add transition work (STMT-039).
- **Estimates:** No elapsed-time estimate was offered.
- **Missing evidence:** Direct partner perspective, partner categories, funnel starts and pauses, document versions, access records, time to first successful call, and support contacts.
- **Related statements:** STMT-023, STMT-036 through STMT-040, STMT-045, STMT-049 through STMT-055, STMT-061, STMT-069 through STMT-074.
- **Related outcomes or questions:** OUT-001, OUT-002; OQ-008, OQ-013, OQ-015.
- **Owner:** Sofia Novak
- **Status:** Preliminary

## SES-004 operational evidence

JRN-001 now has a launch-degradation scenario and hidden direct-chat support cost (STMT-083 through STMT-089). JRN-002 has semantic-change, consumer-detection, and restoration-evidence questions (STMT-090 through STMT-096). JRN-003 includes partner-visible symptoms, communication, and external-wait separation (STMT-079, STMT-084, STMT-088, STMT-099). No journey is validated.

## SES-005 domain-workflow refinement

- **JRN-001:** DWF-001 distinguishes Commerce behavior authority, partner implementation/readiness, review and platform coordination, and completion beyond deployment (STMT-118 through STMT-124). The seven-to-ten-day estimate is unverified.
- **JRN-002:** DWF-003 and DWF-004 distinguish semantic change from migration. Loyalty retains semantics; consumers retain impact, test, schedule, and use responsibility; deployment does not force adoption (STMT-131 through STMT-144).
- **JRN-003:** External partner onboarding remains broader than a dated partner change and still requires direct external evidence. SES-005 adds readiness, responsibility, and support-boundary questions, not validation (STMT-120, STMT-122).
- **Additional case:** DWF-002 records a tenant-specific Commerce change separately; it is not promoted to a universal journey or mechanism (STMT-125 through STMT-130).

Every journey remains `Preliminary` or `Under validation`; none is validated.
