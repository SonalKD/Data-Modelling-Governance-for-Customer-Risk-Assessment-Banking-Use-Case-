## Use Case Walkthrough

This section demonstrates how the data model, data flow, and governance controls come together to support customer risk assessment.

### Scenario

A company (Customer A) approaches the bank for onboarding.

### Step 1: Data Collection

The following information is collected from various sources:

- Customer profile  
  (e.g. company details from client website and external providers such as Dun & Bradstreet)

- Ownership structure  
  (e.g. organisational chart provided by the client and verified through KVK or certified documents)

- Business activity  
  (e.g. industry type derived from financial reports and company disclosures)

- Transaction expectations  
  (e.g. expected transaction behaviour and countries of operation)

---

### Step 2: Data Validation and Structuring

The collected data is validated using approved and reliable sources.

For example:
- ownership structure is checked for validity (recent and certified if high risk)  
- discrepancies between client-provided data and external sources (e.g. Dow Jones) are identified  
- missing or incomplete data is flagged for follow-up  

The data is then structured into a consolidated view for assessment.

---

### Step 3: Data Integration into Risk View

All validated data is combined to form a complete customer profile:

- customer information  
- ownership and UBO details  
- geographical exposure  
- business activity  
- expected and historical transaction behaviour  

This creates a **Customer Risk Assessment View**, which serves as the basis for evaluation.

---

### Step 4: Risk Assessment

The analyst reviews the structured data and evaluates risk based on multiple factors:

- presence of UBOs in high-risk countries  
- nature of business activity  
- expected transaction patterns  
- any adverse information or inconsistencies  

The analyst uses this combined view to determine an initial risk rating.

---

### Step 5: Governance and Controls

Throughout the process, governance controls are applied:

- data quality checks ensure accuracy and completeness  
- ownership responsibilities ensure accountability  
- data lineage ensures traceability of sources and decisions  
- access controls protect sensitive information  

---

### Step 6: Final Decision and Monitoring

Based on the assessment, the customer is assigned a risk rating (e.g. low, medium, high).

The customer is then subject to:
- ongoing monitoring  
- periodic reviews  
- updates based on new information or changes in behaviour  

---

### Key Takeaway

This use case shows that customer risk assessment is not based on a single factor, but on the combination of multiple data points, structured through a clear data model and supported by strong governance controls.

A well-structured approach ensures that decisions are consistent, explainable, and aligned with regulatory expectations.
