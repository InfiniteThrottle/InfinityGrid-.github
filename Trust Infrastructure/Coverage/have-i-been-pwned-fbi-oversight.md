# Have I Been Pwned / FBI Oversight Review

## When Private Breach Infrastructure Becomes Public Infrastructure: Who Watches the Watcher?

**InfinityGrid Classification:** Trust Infrastructure / Governance / SecurityReceipts / Public-Private Cyber Infrastructure  
**Entity:** Have I Been Pwned (HIBP)  
**Operator:** Superlative Enterprises Pty Ltd  
**Jurisdiction:** Queensland, Australia  
**Government Relationship:** Confirmed FBI / DOJ and other law-enforcement collaboration  
**Primary Issue:** Governance, external data sharing, transparency, concentration risk, accountability  
**Security Failure:** None established  
**Misconduct:** None established  
**Government Data Transfer:** Confirmed  
**Dedicated Public HIBP-Specific Oversight Framework:** Not established from the public materials reviewed  
**InfinityGrid Priority:** CRITICAL RESEARCH TOPIC  
**Last Reviewed:** 2026-08-20

## Executive Finding

Have I Been Pwned should not be described as a rogue, unregulated, insecure, or improperly operated service without evidence.

InfinityGrid has not established evidence that HIBP misused FBI-supplied data, sold government-derived data, failed a government security assessment, suffered a breach involving FBI-provided information, or participated in unlawful data handling.

The more consequential question is different:

> **How did an independently operated Australian breach-notification service become trusted infrastructure for distributing intelligence obtained during major United States federal cybercrime investigations, and what dedicated public governance framework follows that relationship?**

The FBI itself operates within substantial institutional oversight.

Its activities are subject to oversight through mechanisms that include Congress, the Department of Justice, the Attorney General, courts where legal process is involved, and additional oversight structures for intelligence activities.

That establishes oversight of the FBI.

It does not automatically answer:

> **What specific governance follows information after the FBI provides compromised credentials, victim information, or other cybercrime-derived data to an independently operated external service?**

InfinityGrid's review found public evidence confirming repeated government collaboration with HIBP.

The same public record reviewed for this investigation did not establish a comparably detailed, HIBP-specific public framework describing the full set of controls governing that relationship.

This is not evidence that such controls do not exist.

It means InfinityGrid has not established them from the public materials reviewed.

That distinction is central to this investigation.

## Why This Matters

HIBP is no longer merely a consumer-facing website answering:

> Has my email address appeared in a breach?

Its role has expanded.

HIBP now sits within a broader ecosystem involving:

- breach notification
- compromised-password intelligence
- enterprise security workflows
- developer integrations
- victim notification
- law-enforcement remediation
- public-private cybersecurity collaboration

The more useful and widely depended upon such a system becomes, the more significant questions of governance, resilience, provenance, auditability, continuity, and accountability become.

InfinityGrid's position is not:

> Government should not work with private cybersecurity services.

Public-private cyber collaboration is frequently necessary and beneficial.

The stronger position is:

> **The deeper a private service becomes embedded in public cybersecurity operations, the stronger the case for transparent governance, resilience, auditability, and accountability.**

## Confirmed Public-Private Relationship

InfinityGrid identified multiple publicly documented instances in which law-enforcement-derived information was provided to or operationally used through HIBP.

### Receipt 01 — Emotet

In 2021, information obtained during the international Emotet disruption was provided to HIBP.

HIBP recorded approximately 4.3 million affected accounts.

The information was handled as a sensitive breach rather than exposed through unrestricted public search.

**InfinityGrid Finding:**

**E4 — ESTABLISHED**

Law-enforcement-derived information was provided to HIBP.

## Receipt 02 — FBI Password Ingestion

HIBP subsequently developed an ingestion mechanism capable of receiving compromised passwords encountered by law-enforcement agencies.

The publicly described defensive model was:

```text
FBI IDENTIFIES COMPROMISED PASSWORD
        ↓
PASSWORD ENTERS HIBP INGESTION PIPELINE
        ↓
PWNED PASSWORDS CORPUS
        ↓
ORGANIZATIONS CHECK PASSWORD
        ↓
KNOWN-COMPROMISED PASSWORD REJECTED
