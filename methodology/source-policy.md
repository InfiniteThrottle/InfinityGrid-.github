# InfinityGrid Source Reliability Standard (IG-SRS)

InfinityGrid evaluates sources based on authority, proximity to the event, independence, evidence quality, technical competence, and potential conflicts.

## SR5 — Authoritative Primary Record

Examples:

- Government regulator
- Court record
- SEC filing
- Official breach notification
- Vendor advisory
- Sworn filing
- Published forensic report

## SR4 — Direct Organizational Source

Examples:

- Official company statement
- Incident-response update
- Customer notification
- Named executive statement
- Security bulletin

Direct organizational sources are authoritative regarding what the organization claims, but are not automatically authoritative regarding disputed external facts.

## SR3 — Independent High-Confidence Source

Examples:

- Reuters
- Established technical research organization
- Recognized incident-response firm
- Peer-reviewed research
- Named researcher publishing reproducible evidence

## SR2 — Credible Secondary Source

Examples:

- Established security publication
- Specialist journalist
- Industry analyst
- Researcher commentary supported by evidence

## SR1 — Interested or Unverified Source

Examples:

- Threat actor
- Leak site
- Anonymous source
- Social-media claim
- Forum post
- Unverified screenshot

These sources may provide leads but do not independently establish material claims.

## Threat-Actor Rule

Threat actors are evidence that a claim was made.

They are not automatically evidence that the claim is true.

Example:

Correct:
"Everest claimed possession of approximately 250,000 records."

Incorrect without corroboration:
"Everest stole 250,000 records."

## Source Independence

Ten articles repeating the same original report are not ten independent sources.

InfinityGrid attempts to identify the original evidentiary chain.

## Primary-Source Upgrade Rule

Whenever a stronger primary source becomes available, InfinityGrid should update the record and reduce reliance on secondary reporting.

## Source Preservation

Records should include enough information for another researcher to reconstruct the evidentiary basis of the conclusion.

Where practical:

- source title
- publisher
- publication date
- access date
- relevant filing identifier
- archived reference
- affected claim
