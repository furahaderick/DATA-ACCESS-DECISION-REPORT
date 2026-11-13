# DATA ACCESS DECISION REPORT

**Organization:** EduConnect Ghana  
**Name & Role:** Furaha Yves Derick Dukundane, DevOps Engineer  
**Legal Framework:** Rwanda Data Protection and Privacy Law, Law No. 058/2021

---

# REQUEST 1: MARKETING CAMPAIGN

**Requester:** Sarah Owusu, Marketing Manager

### Decision
**CONDITIONAL APPROVAL**

### Lifecycle Stage
**USE** – The request involves using existing student information for a marketing campaign.

### Justification
Sarah currently has INTERNAL access, but email addresses are classified as CONFIDENTIAL. Granting her unrestricted access to the entire student database would violate the principle of least privilege.

Access should be limited to the information necessary for the campaign. Additionally, personal data must be processed for legitimate purposes, and applicable student privacy rights must be respected under Rwanda's Data Protection and Privacy Law.

### Action Steps
1. Reject unrestricted access to the full student database.
2. Ask Sarah to identify the specific information required for the campaign.
3. Consult the Data Protection Officer (DPO) to establish a valid legal basis for processing the information.
4. Verify that students have been appropriately informed about the marketing activities and can exercise applicable opt-out rights.
5. Provide only the necessary data through a secure, restricted-access system.
6. Enable access logging and set an appropriate access expiration date.

---

# REQUEST 2: ANALYTICS PARTNERSHIP

**Requester:** David Mensah, Head of Product

### Decision
**DENY--PENDING COMPLIANCE CHECKS**

### Lifecycle Stage
**SHARE** – The request involves sharing student information with an external analytics company.

### Justification
Student profiles are classified as CONFIDENTIAL, making unrestricted third-party database access inappropriate.

The request also presents international data transfer concerns because DataInsights Inc. is based in the United States.

Under Rwanda's Data Protection and Privacy Law, international transfers and third-party processing must satisfy applicable legal requirements and security safeguards. The principle of least privilege also requires restricting external access to the minimum necessary information.

Sharing login credentials through a ticketing system creates an additional security risk.

### Action Steps
1. Deny direct AWS database access in its current form.
2. Revoke or rotate the credentials attached to the request.
3. Consult the DPO, Legal Team, and IT/Security Team.
4. Verify the legal basis for processing and applicable international data transfer requirements.
5. Establish a written data processing and transfer agreement.
6. Conduct a Data Protection Impact Assessment (DPIA) if required.
7. If approved, provide only the necessary data, preferably anonymized where feasible.
8. Implement secure, monitored, and restricted access.

---

# REQUEST 3: ARCHIVE AND DELETION

**Requester:** Comfort Asante, Customer Support Lead

### Decision
**CONDITIONAL APPROVAL**

### Lifecycle Stage
**DESTROY** – The request involves securely deleting a student's personal information.

### Justification
Rwanda's Data Protection and Privacy Law recognizes individuals' right to request the erasure of their personal data under applicable conditions.

James has completed his course, has an inactive account, and has no outstanding payments. Therefore, the original purposes for processing some of his information may have been fulfilled.

However, certain records, such as financial or accounting information, may need to be retained to satisfy legal obligations. Such information should only be retained where a valid legal basis exists.

### Action Steps
1. Verify James's identity and record his deletion request.
2. Consult the DPO and relevant departments to identify legal retention requirements.
3. Identify all personal data associated with James, including account, contact, enrollment, learning activity, and payment information.
4. Identify records that must legally be retained and document the reasons.
5. Securely delete all information that is no longer necessary and is not subject to a valid retention exception.
6. Restrict access to any information that must be retained.
7. Notify relevant third parties of the erasure request where required.
8. Address deleted information in backup systems according to applicable retention procedures.
9. Document the deletion process and communicate the outcome to James.

---

**Legal Reference:** Republic of Rwanda. (2021). *Law No. 058/2021 of 13/10/2021 relating to the Protection of Personal Data and Privacy.*

https://www.risa.gov.rw/data-protection-and-privacy-law