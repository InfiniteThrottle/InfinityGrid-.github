# InfinityGrid Incident Classification Standard (IG-ICS)

An InfinityGrid incident may contain multiple classifications.

## Primary Incident Classes

### DB — Data Breach
Unauthorized access to or acquisition of protected, confidential, personal, or proprietary information.

### DE — Data Exposure
Information became accessible without sufficient authorization controls, whether or not malicious acquisition is established.

### RX — Ransomware / Extortion
Ransomware deployment, encryption, data-theft extortion, or related coercive activity.

### CI — Cyber Intrusion
Unauthorized access to systems or networks without sufficient evidence of data theft.

### DS — Destructive Attack
Cyber activity intentionally disrupting, wiping, corrupting, or destroying systems or data.

### SC — Supply-Chain Incident
Compromise propagated through or materially involved a supplier, service provider, software provider, contractor, or shared dependency.

### TP — Third-Party Data Incident
An organization's information was affected through infrastructure operated by another entity.

### VC — Vulnerability-Driven Compromise
A specific vulnerability is credibly connected to exploitation in the incident.

### IC — Identity Compromise
Credential theft, token theft, session theft, authentication bypass, OAuth abuse, MFA compromise, or misuse of valid accounts.

### CE — Credential Exposure
Credentials become publicly available, stolen, or aggregated independently of a single conventional breach.

### SE — Social Engineering
Phishing, vishing, smishing, impersonation, help-desk manipulation, or other human-targeted compromise.

### IS — Insider Incident
Authorized access is misused intentionally or negligently.

### OT — Operational Technology Incident
Industrial, manufacturing, infrastructure, medical-device, utility, transportation, or other cyber-physical systems are materially affected.

### GS — Government / National Security Incident
Government systems, national-security capabilities, intelligence systems, defense environments, or public administration are materially affected.

## Impact Dimensions

Every incident should also be evaluated independently across:

- Confidentiality
- Integrity
- Availability
- Identity
- Privacy
- Financial harm
- Operational disruption
- Safety
- Supply-chain impact
- Regulatory impact
- National-security impact
- Long-term victim risk

## Scale Is Not Severity

A breach involving 20 million email addresses is not automatically more severe than an intrusion exposing 10 highly sensitive intelligence records.

InfinityGrid separates:

`Volume`

from

`Sensitivity`

from

`Operational Impact`

from

`Strategic Impact`.
