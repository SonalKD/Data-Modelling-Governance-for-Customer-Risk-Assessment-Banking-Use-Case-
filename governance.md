## Governance Framework

To ensure that customer risk assessment is reliable and consistent, it is important to apply governance controls across the data lifecycle.

This includes ensuring data quality, clear ownership, proper usage, and ongoing monitoring.

.

### Data Quality Controls

Data used for risk assessment must be accurate, complete, and consistent.

Key considerations include:

- Validation of data from reliable and approved sources  
  (e.g. external providers such as Dun & Bradstreet, verification of ownership structures through KVK, and transaction data from internal systems such as Siebel)

- Handling missing or incomplete data  
  (e.g. if transaction systems do not capture all relevant account information, there is a risk of missing important transaction patterns and associated risk indicators)

- Identifying and resolving inconsistent data  
  (e.g. discrepancies between client-provided information, such as company websites, and external intelligence sources like Dow Jones should be flagged and investigated)

- Ensuring data is up to date  
  (e.g. new or updated information identified during reviews should be reflected in the customer record to maintain an accurate risk profile)

Poor, missing, or inaccurate data can lead to incorrect risk classification and missed risk indicators.
---

### Data Ownership and Responsibility

Each data component should have a clearly defined owner responsible for its accuracy, completeness, and maintenance.

Ownership is not only about managing data, but also ensuring that the information collected is reliable and meets internal standards.

For example:

- Customer data → owned by onboarding or KYC teams 
  These teams are responsible for validating the accuracy of the information collected.  
  For instance, in high-risk cases, ownership structures should be recent (e.g. not older than one year) and certified by a qualified professional (such as a lawyer or Chartered Accountant), whose credentials can be independently verified in line with internal standards.

- Ownership and UBO data → owned by compliance teams  
  However, the quality of this data depends heavily on the input provided by KYC teams.  
  If the initial documentation (such as ownership structures) is outdated or not properly certified, compliance teams cannot rely on it.  
  This often results in rework, including additional client outreach, leading to delays, increased risk of overdue cases, and potential inconsistencies in data.

- Transaction data → owned by transaction monitoring teams  
  In addition to monitoring actual transactions, there should be mechanisms to capture expected transaction behaviour.  
  For example, if a client informs the KYC team about planned expansion into new countries, this information should be communicated and reflected in the expected transaction profile, so that the transaction monitoring team can assess future activity accurately.

Clear ownership ensures accountability, improves data quality, and enables timely resolution of data issues.
---


### Data Lineage and Traceability

It should be possible to trace how data flows from source systems to the final risk assessment.

This ensures transparency, supports auditability, and allows stakeholders to understand how decisions are made.

This includes:

- Understanding where the data originates  
  (e.g. how information provided by the client is captured by the KYC team, and how it is stored in systems, tools, or structured folders to ensure traceability of the original source)

- Understanding how data is transformed and structured  
  (e.g. when an analyst reviews an annual report and derives key insights such as source of income, profitability, or business profile, the logic and source used for this interpretation should be documented and stored in line with internal standards)

- Understanding how data is used in decision-making  
  (e.g. when combining customer profile, financial data, transaction behaviour, screening results, and ownership structures, the analyst should be able to trace:
  - which sources were used  
  - how the data was processed  
  - how different inputs contributed to the final risk assessment)

A well-structured lineage process ensures that decisions are transparent, reproducible, and supported by verifiable data.

This is critical for audit readiness, regulatory compliance, and stakeholder confidence.


### Access Control, Data Protection, and Data Minimisation

Sensitive customer data must be protected and accessible only to authorised users.  
At the same time, it is equally important to ensure that only relevant data is collected and used for risk assessment.

This principle of data minimisation ensures that unnecessary or excessive information is not processed.

For example, when clients provide financial information for Source of Funds (SoF) or Source of Wealth (SoW), only the data required to establish and validate SoF/SoW should be used.

---

### Key Controls

- Role-based access  
  Access to systems and data should be aligned with user responsibilities.  
  For example, transaction monitoring tools may not be directly accessible to KYC analysts; however, the outputs or reports generated from these systems should be available to support assessment of transaction behaviour.

- Restricted access to sensitive information  
  Certain data may require additional confidentiality controls.  
  For instance, if a client is involved in a confidential transaction (such as an acquisition), access to related documents should be limited to specific roles (e.g. KYC owner, assigned analyst, and quality reviewer).  
  Controlled channels should be used for sharing such information to maintain confidentiality and client trust.

- Compliance with data protection regulations  
  Data handling must align with applicable regulations such as GDPR and evolving regulatory frameworks (e.g. EU AI Act).  
  A structured and coordinated approach can improve compliance, for example:
  - using standardised templates that reflect current regulatory requirements  
  - notifying analysts of regulatory updates in real time  
  - allowing controlled transition periods when standards change  
  - supporting teams through training and workshops to ensure correct implementation  

---

### Key Takeaway

Effective access control and data protection ensure that sensitive information is handled responsibly, while data minimisation ensures that only relevant data is used for decision-making.

Together, these principles help maintain compliance, improve efficiency, and build trust with clients and stakeholders.

