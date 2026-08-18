
## `templates/receipt-template.md`

This one should be exceptionally strong because **SecurityReceipts can become one of the things people remember InfinityGrid for**.

```markdown
# SecurityReceipts — [Organization / Incident]

**InfinityGrid ID:** IG-2026-XXX  
**Incident:**  
**Organization:**  
**Status:**  
**Last Reviewed:** YYYY-MM-DD  

## Why This Receipt Exists

This record tracks how the publicly documented understanding of an incident changed over time.

SecurityReceipts separates:

- what was originally disclosed
- what was later disclosed
- what threat actors claimed
- what independent evidence established
- what regulators or courts later documented
- what remains unresolved

InfinityGrid does not treat a changed disclosure as evidence of deception by itself.

Incident investigations evolve.

The purpose of SecurityReceipts is to preserve that evolution.

## Receipt Timeline

### YYYY-MM-DD — Initial Disclosure

**Source:**  
**Source Reliability:** SR0–SR5  

**Statement / Position:**

Summarize the original disclosure.

**Evidence Level:** E0–E4

## YYYY-MM-DD — Threat Actor Claim

**Actor:**  
**Source Reliability:** SR1  

**Claim:**

Summarize the claim.

**Evidence Level:** E1 — Claimed

## YYYY-MM-DD — Independent Reporting

**Source:**  

**Finding:**

Summarize what new evidence appeared.

**Evidence Level:** E2 / E3

## YYYY-MM-DD — Updated Company Disclosure

**Source:**  

**Updated Position:**

Summarize what changed.

**Evidence Level:** E4 for the fact that the organization made the statement.

## YYYY-MM-DD — Regulator / Court / Government Finding

**Source:**  

**Finding:**

Summarize authoritative findings.

**Evidence Level:** E4

## Claim Matrix

| Issue | Company | Threat Actor | Independent Evidence | InfinityGrid Status |
|---|---|---|---|---|
| Incident occurred | | | | |
| Initial access | | | | |
| Threat actor | | | | |
| Data stolen | | | | |
| Data type | | | | |
| Affected population | | | | |
| CVE involved | | | | |
| Operational impact | | | | |
| Data published | | | | |

## What Was Initially Known

- 

## What Was Initially Unknown

- 

## What Changed

Document changes such as:

```text
INITIAL
"No malware identified"

        ↓

LATER INVESTIGATION
Malicious command-execution file identified
