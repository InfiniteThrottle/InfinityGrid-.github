Frost Bank — Third-Party Data Breach

InfinityGrid ID: IG-2026-021
Status: Confirmed third-party incident / scope continuing to develop
Sector: Banking
Region: United States
Year: 2026
Priority: Critical
Last reviewed: August 2026

Summary

Frost Bank was connected to a 2026 cybersecurity incident involving unauthorized access to systems operated by a third-party vendor. Frost stated that the incident involved a vendor environment rather than a compromise of Frost Bank's internal network. The Everest ransomware group separately claimed possession of approximately 250,000 Frost Bank customer records. The claimed dataset reportedly included highly sensitive financial and identity information.

What Happened

In April 2026, the Everest ransomware group publicly listed Frost Bank and claimed it had obtained customer information. Public reporting subsequently indicated that Frost Bank acknowledged being notified of unauthorized access involving a third-party vendor used in connection with customer information. At this time, public evidence supports a third-party compromise. InfinityGrid has not identified reliable evidence establishing that Frost Bank's internal banking network was directly compromised.

Data Reportedly Affected

Everest claimed the stolen information included full names, Social Security numbers, taxpayer identification numbers, home addresses, mortgage interest information, investment gain information, income information, and taxable amounts. Important: The approximately 250,000-record figure originates from the threat actor's claim and should not be treated as a final independently verified affected-person count.

Technical Path

Organization: Frost Bank
Third-party involvement: Confirmed
Direct Frost network compromise: Not established publicly
Initial access: Not publicly confirmed
Known CVE: None publicly confirmed
Ransomware/extortion actor: Everest
Data theft claim: Yes

Timeline

April 20, 2026: Everest publicly listed Frost Bank and claimed possession of customer data.
April 2026: Reporting emerged that Frost Bank had been notified of unauthorized access involving a third-party vendor.
Following disclosure: Class-action litigation and additional reporting began examining the breach, affected information, vendor relationship, and notification process.
Current status: The incident remains relevant for continued monitoring as affected-person counts, regulatory filings, litigation, and vendor details may develop.

Why This Matters

This incident demonstrates an important security reality: an organization's customer data can be exposed even when the organization's own network is not the system directly compromised. Financial institutions depend on outside providers for document processing, software support, communications, data handling, and other business functions. That makes third-party security part of the institution's effective attack surface.

What Defenders Should Check

Organizations handling sensitive customer data should review which vendors store or process regulated customer information, how vendors authenticate to file-transfer and support systems, whether sensitive files remain available longer than operationally necessary, whether third-party access is continuously monitored, whether contracts require rapid incident notification, whether vendors can identify exactly which customers and records were exposed, and whether high-risk vendor access is protected with phishing-resistant authentication.

Evidence Status

Confirmed: A third-party vendor environment was involved. Frost customer information may have been affected. Frost's internal network has not been publicly established as the compromised environment.
Claimed: Everest claimed approximately 250,000 Frost customer records and claimed specific sensitive financial and identity fields were included.
Not publicly established: Exact initial-access method, confirmed CVE, final affected-person count, complete volume of data obtained, and full technical attack chain.

Sources

Primary and corroborating sources should be maintained here as additional information becomes available, including Frost Bank or official notifications, regulatory breach filings, court filings, independent cybersecurity reporting, and threat-actor claims clearly labeled as claims.

InfinityGrid Note

InfinityGrid separates confirmed facts from threat-actor allegations. A company's presence on an extortion site does not independently establish every claim made by the threat actor. This record will be updated when stronger evidence, regulatory filings, company disclosures, or technical findings become publicly available.
