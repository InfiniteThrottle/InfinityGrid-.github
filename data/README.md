# InfinityGrid Cyber Incident Dataset

The InfinityGrid data directory contains structured, machine-readable records derived from InfinityGrid's public cyber incident research.

The purpose of this dataset is to make significant cyber incidents easier to search, compare, analyze, correlate, and preserve beyond the news cycle.

InfinityGrid does not treat raw record counts, threat-actor claims, media reports, and confirmed findings as equivalent evidence.

Every published record should distinguish between:

- confirmed facts
- corroborated findings
- reported information
- threat-actor claims
- unknown or unresolved information

## Dataset Files

### `incidents-2026.csv`

Flat, analysis-friendly representation of InfinityGrid's 2026 cyber incident records.

Recommended for:

- spreadsheets
- data analysis
- filtering
- dashboards
- research
- importing into SIEM or BI systems
- public cyber incident comparisons

### `incidents-2026.json`

Structured machine-readable representation of the same incident intelligence.

Recommended for:

- APIs
- applications
- automation
- security research
- correlation engines
- data pipelines
- future InfinityGrid tooling

## Data Philosophy

InfinityGrid separates:

`RAW RECORD COUNT`

from

`UNIQUE AFFECTED IDENTITIES`

from

`CONFIRMED VICTIMS`

from

`THREAT-ACTOR CLAIMS`

A breach involving 40 million database rows does not automatically mean 40 million individuals were affected.

Likewise, a threat actor claiming possession of data does not establish that every claimed record, system, or victim is genuine.

## Evidence Model

InfinityGrid uses the InfinityGrid Evidence Confidence Model.

### E4 — Established
Supported by authoritative primary evidence.

Examples:

- regulatory records
- court records
- SEC filings
- official breach notifications
- vendor forensic findings
- direct technical evidence

### E3 — Corroborated
Supported by multiple credible independent sources or strong technical evidence.

### E2 — Reported
Credibly reported but not independently established.

### E1 — Claimed
A material claim exists but remains unverified.

Examples:

- threat-actor claim
- leak-site claim
- unverified record count

### E0 — Unknown
Public evidence is insufficient to reach a defensible conclusion.

## Core Dataset Principles

### Evidence Before Narrative

InfinityGrid records what the evidence supports.

Technical details are not inferred simply because they appear likely.

### Unknown Means Unknown

When public evidence does not establish:

- initial access
- CVE
- threat actor
- credential path
- MFA status
- exfiltration volume
- affected-person count

the field should remain unknown.

### Claims Are Preserved, Not Promoted

Threat-actor statements and disputed claims may be recorded because they are historically relevant.

They are never automatically promoted to confirmed fact.

### Living Records

Incident records may change as:

- organizations issue new disclosures
- regulators publish findings
- technical investigations mature
- lawsuits reveal additional evidence
- threat-actor claims are validated or disproven

The structured dataset should be updated alongside the corresponding InfinityGrid incident record.

## Dataset Scope

The initial public dataset covers significant cyber incidents occurring, disclosed, or materially developing during 2026.

Not every cybersecurity event is included.

InfinityGrid prioritizes incidents with significant:

- technical impact
- data exposure
- operational disruption
- supply-chain consequences
- critical infrastructure implications
- vulnerability exploitation
- identity compromise
- disclosure changes
- defensive lessons

## Public Safety

InfinityGrid does not publish:

- stolen personal records
- credentials
- private keys
- recovery phrases
- passwords
- authentication tokens
- raw victim datasets
- exploit-ready victim infrastructure
- unnecessary personally identifiable information

The dataset describes incidents.

It does not redistribute stolen data.

## Corrections

Corrections should be reflected in both:

- the human-readable incident record
- the machine-readable dataset

Material corrections should follow the InfinityGrid Public Record Correction Protocol.

See:

`../methodology/corrections-policy.md`

## Methodology

See:

`../methodology/README.md`

`../methodology/evidence-levels.md`

`../methodology/source-policy.md`

`../methodology/incident-classification.md`

## Intellectual Property

© 2026 InfinityGrid LLC.

The InfinityGrid incident dataset, classification structures, terminology, research organization, analytical models, and associated methodology are developed and maintained by InfinityGrid.

Public availability of this dataset does not transfer ownership of InfinityGrid trademarks, proprietary scoring systems, analytical methods, or internal research processes.

## Disclaimer

InfinityGrid provides independent cybersecurity research based on publicly available information.

Incident records may evolve as additional evidence becomes available.

Users should review the underlying sources before relying on the dataset for legal, regulatory, investment, or other high-impact decisions.
