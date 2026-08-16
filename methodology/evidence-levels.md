# InfinityGrid Evidence Confidence Model (IG-ECM)

InfinityGrid separates evidence reliability from analytical confidence.

A claim may come from a reliable source but still remain incomplete.

Likewise, several weaker sources may collectively corroborate an event without proving every technical detail.

## E4 — Directly Established

Highest public evidence level.

Examples:

- Regulator finding
- Court-established fact
- SEC filing
- Official breach notification
- Vendor forensic report
- Direct technical artifact
- Organization admission
- Independently verifiable technical evidence

Display:

🟢 E4 — ESTABLISHED

## E3 — Strongly Corroborated

Supported by multiple credible independent sources or strong technical evidence, but lacking authoritative confirmation of every material detail.

Examples:

- Multiple reputable technical researchers independently reaching the same conclusion
- Independent reporting supported by documentary evidence
- Incident facts confirmed across multiple affected organizations

Display:

🔵 E3 — CORROBORATED

## E2 — Credibly Reported

Reported by a credible source with reasonable supporting evidence but not yet independently established.

Examples:

- Reputable investigative reporting
- Named researcher finding
- Company spokesperson statement without supporting technical disclosure
- Litigation allegation supported by exhibits

Display:

🟡 E2 — REPORTED

## E1 — Claimed

A material assertion exists but has not been independently verified.

Examples:

- Threat-actor claim
- Leak-site listing
- Anonymous allegation
- Single-source attribution
- Claimed record count without independent verification

Display:

🟠 E1 — CLAIMED

## E0 — Unknown

Evidence is insufficient to reach a defensible conclusion.

Display:

⚪ E0 — UNKNOWN

## Conflict Rule

When credible sources conflict, InfinityGrid does not arbitrarily select a winner.

The disagreement is recorded.

Example:

Organization:
No internal systems were compromised.

Threat actor:
Internal network access obtained.

InfinityGrid:
Direct internal-network compromise remains disputed.

## Confidence Can Move

Evidence classifications are not permanent.

E1 → E3 may occur when independent technical evidence appears.

E2 → E4 may occur when a regulator publishes findings.

E3 → E1 may occur if the underlying evidence is later disproven.

Every material reclassification should be reflected in the record history.

## Claim Granularity

Evidence ratings apply to individual claims, not entire incidents.

Example:

Incident occurred: E4

250,000 records affected: E1

Vendor environment involved: E4

Specific CVE exploited: E0

Threat actor attribution: E2

This prevents one confirmed aspect of an incident from incorrectly validating every other claim.
