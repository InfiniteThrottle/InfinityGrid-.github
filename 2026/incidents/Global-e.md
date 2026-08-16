Ledger / Global-e — Third-Party Data Breach

InfinityGrid ID: IG-2026-003
Status: Confirmed
Sector: Crypto / E-commerce
Region: Global
Third Party: Global-e
Incident Type: Third-party cloud data breach
Disclosure Date: January 5, 2026
Last Reviewed: August 2026

Summary

Ledger customers were affected by unauthorized access to a cloud-based information system operated by Global-e, a third-party e-commerce provider used in connection with Ledger.com purchases. The affected system contained shopper order data. The incident did not compromise Ledger devices, Ledger software, private keys, recovery phrases, wallet balances, or payment information. The primary security consequence was exposure of customer identity, contact, shipping, and order information that could be used for targeted phishing, impersonation, and other social-engineering attacks.

What Happened

Global-e identified unauthorized access to a cloud-based information system containing shopper order information associated with multiple brands. Some of the affected data belonged to Ledger customers who purchased products through Ledger.com using Global-e-supported commerce services. Global-e began notifying affected Ledger customers on January 5, 2026. Ledger confirmed that the affected environment belonged to Global-e and that Ledger’s hardware-wallet infrastructure and cryptographic security systems were not compromised.

Timeline

Before January 5, 2026: Global-e identified unauthorized access affecting shopper order information stored in its cloud environment.
January 5, 2026: Global-e began notifying affected Ledger customers.
January 5–6, 2026: Ledger publicly confirmed that customer information had been exposed through Global-e and warned users about phishing and impersonation attempts.
After disclosure: Security reporting documented phishing activity attempting to exploit the incident and the credibility created by possession of legitimate Ledger customer information.

Data Affected

Confirmed affected information included names, postal addresses, email addresses, telephone numbers, order details, products purchased, and product prices.

Data Not Affected

Public disclosures state that the incident did not expose Ledger recovery phrases, private keys, wallet balances, PINs, Ledger hardware devices, Ledger software, or payment information.

Technical Details

Affected environment: Global-e cloud-based information system
System purpose: E-commerce and shopper order processing
Direct Ledger infrastructure compromise: Not established
Data exfiltration / unauthorized access: Confirmed
Known CVE: None publicly confirmed
Initial access method: Not publicly disclosed
Credential compromise: Unknown
MFA failure: Unknown
Cloud misconfiguration: Unknown
API compromise: Unknown
Malware involvement: Unknown
Multi-brand exposure: Confirmed

Security Impact

The incident is notable because the exposed data connected identifiable individuals with purchases of cryptocurrency hardware wallets. Even without access to private keys or recovery phrases, attackers could use the exposed information to create more convincing phishing and impersonation campaigns. A malicious actor with a customer’s name, phone number, address, email address, and exact Ledger order details can construct highly contextual social-engineering attempts designed to trick the victim into revealing wallet secrets later.

Current Status

The incident is confirmed. The exact technical method used to gain unauthorized access to Global-e’s cloud environment has not been publicly established. No CVE has been credibly connected to the breach. The final number of affected Ledger customers has not been publicly confirmed.

Evidence Status

E4 — Established: Global-e experienced unauthorized access. Ledger customer data was affected. Names, addresses, emails, phone numbers, and order information were exposed. Ledger wallet secrets, devices, software, and payment information were not compromised.
E0 — Unknown: Initial access method, specific vulnerability, attacker identity, credential path, MFA status, exact access duration, and final Ledger-specific affected-person count.

Why This Matters

The incident demonstrates that the security boundary around a high-value security product extends beyond the product itself. Ledger’s hardware security controls remained intact, but customer identity and purchase context stored by a third-party commerce provider created a separate attack surface. The exposure did not directly compromise cryptocurrency assets, but it increased the effectiveness of downstream attempts to steal them through phishing, impersonation, and social engineering.

Public Safety Note

InfinityGrid does not publish stolen customer data, credentials, recovery phrases, personal records, or direct links to stolen datasets. This record documents publicly available incident information only.

Sources
Ledger customer/security notice regarding the Global-e incident
Global-e breach notifications
Independent cybersecurity reporting
Regulatory or legal filings as they become available
InfinityGrid Classification

Primary: TP — Third-Party Data Incident
Secondary: SC — Supply-Chain Incident
Secondary: SE — Social Engineering Risk
Impact dimensions: Privacy, Identity, Financial Risk, Third-Party Risk

InfinityGrid Note

InfinityGrid separates compromise of customer-supporting business systems from compromise of the security product itself. In this incident, public evidence supports exposure of Ledger customer identity and order data through Global-e. Public evidence does not support a compromise of Ledger private keys, recovery phrases, hardware wallets, or wallet balances.
