# External Traffic Expectations

**SES-008 carry-forward:** Visibility of expected usage and symptom evidence warrants analysis, but a single fictional consumer gives no representative traffic profile. No quota, rate limit, SLA, SLO, or numeric service target follows.

Fictional, simulated SES-006 analysis. Visibility questions do not choose quota, rate-limit, retry, or traffic-control mechanisms; no numeric target follows.

| ID | Candidate expectation | SES-006 evidence | Uncertainty | Validation needed | Owner | Status |
| --- | --- | --- | --- | --- | --- |
| ETR-001 | Consumer and provider can discuss expected usage shape and planned spikes before launch. | [Exchanges 28-29](../sessions/SES-006-external-consumer-discovery/01-simulated-transcript.md#4-traffic-and-support-incident) | No measured profile or contractual limit. | Sample forecasts and observed traffic with scope. | Jordan Lee | Validation planned |
| ETR-002 | Consumer-visible constraint symptoms can be distinguished from retries, domain behavior, or runtime failure. | [Exchanges 29-31, 35](../sessions/SES-006-external-consumer-discovery/01-simulated-transcript.md#4-traffic-and-support-incident) | Cause, available signals, and safe disclosure unknown. | Compare sanitized request, retry, and outcome timeline. | Jordan Lee | Preliminary |
| ETR-003 | Incident communication and recovery reflect consumer symptoms while minimizing shared diagnostic data. | [Exchanges 32-35](../sessions/SES-006-external-consumer-discovery/01-simulated-transcript.md#4-traffic-and-support-incident) | No SLO, SLA, update commitment, or evidence policy. | Review incident communications and authority sources. | Sofia Novak | Preliminary |
