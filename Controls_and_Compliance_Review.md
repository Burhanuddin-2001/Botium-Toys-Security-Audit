# <a name="_87tykp1u0l36"></a>Controls and compliance checklist

**Controls assessment checklist**

|**Yes**|**No**|**Control**|
| -: | :-: | :- |
||❌|Least Privilege|
||❌|Disaster recovery plans|
||❌|Password policies|
||❌|Separation of duties|
|✅||Firewall|
||❌|Intrusion detection system (IDS)|
||❌|Backups|
|✅||Antivirus software|
||❌|Manual monitoring, maintenance, and intervention for legacy systems|
||❌|Encryption|
||❌|Password management system|
|✅||Locks (offices, storefront, warehouse)|
|✅||Closed-circuit television (CCTV) surveillance|
|✅||Fire detection/prevention (fire alarm, sprinkler system, etc.)|

-----
**Compliance checklist**

Payment Card Industry Data Security Standard (PCI DSS)

|**Yes**|**No**|**Best practice**|
| -: | :-: | :- |
||❌|Only authorized users have access to customers’ credit card information. |
||❌|Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment.|
||❌|Implement data encryption procedures to better secure credit card transaction touchpoints and data. |
||❌|Adopt secure password management policies.|


General Data Protection Regulation (GDPR)

|**Yes**|**No**|**Best practice**|
| -: | :-: | :- |
||❌|E.U. customers’ data is kept private/secured.|
|✅||There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach.|
||❌|Ensure data is properly classified and inventoried.|
|✅||Enforce privacy policies, procedures, and processes to properly document and maintain data.|


System and Organizations Controls (SOC type 1, SOC type 2) 

|**Yes**|**No**|**Best practice**|
| -: | :-: | :- |
||❌|User access policies are established.|
||❌|Sensitive data (PII/SPII) is confidential/private.|
|✅||Data integrity ensures the data is consistent, complete, accurate, and has been validated.|
||❌|Data is available to individuals authorized to access it.|

-----

**Recommendations (optional):** In this section, provide recommendations, related to controls and/or compliance needs, that your IT manager could communicate to stakeholders to reduce risks to assets and improve Botium Toys’ security posture.

Security Audit Recommendations for Botium Toys

### 1. Issue: Non-compliance with PCI DSS

Description:

- Specific Issue: The organization has not implemented the PCI DSS (Payment Card Industry Data Security Standard) framework.

- Impact: Non-compliance with PCI DSS can lead to significant fines from governing bodies, increased risk of data breaches, and potential loss of customer trust.

Current Control:

- No current controls or measures are in place to comply with PCI DSS.

Recommendation:

- Embed PCI DSS regulations into the system to ensure proper management and protection of credit card information.

### 2. Issue: Lack of Access Control Policies

Description:

- Specific Issue: There are no access control policies to protect and limit employee access to customer private data.

- Impact: This poses a high risk of insider threats and unauthorized data access.

Current Control:

- No access control policies are currently in place.

Recommendation:

- Develop and implement comprehensive access control policies to restrict employee access based on roles and responsibilities.

### 3. Issue: Lack of Data Encryption

Description:

- Specific Issue: There is no encryption to safeguard customers' Personally Identifiable Information (PII) and Sensitive Personal Identifiable Information (SPII).

- Impact: Lack of encryption increases the risk of data breaches and unauthorized access to sensitive customer information.

Current Control:

- No data encryption measures are currently in place.

Recommendation:

- Implement encryption protocols to protect PII and SPII both at rest and in transit.

### 4. Issue: Inadequate Implementation of Security Principles

Description:

- Specific Issue: The system lacks implementation of security principles like separation of duties and least privilege.

- Impact: This can lead to increased risk of errors and malicious activities due to excessive access privileges.

Current Control:

- No effective implementation of separation of duties and least privilege.

Recommendation:

- Adopt and enforce the principles of separation of duties and least privilege to minimize access to only what is necessary for employees to perform their job functions.

### 5. Issue: Absence of Disaster Recovery and Backup Policy

Description:

- Specific Issue: There is no disaster recovery plan or backup policy in place.

- Impact: This can lead to significant data loss and operational disruptions during outages or system failures.

Current Control:

- No disaster recovery plan or backup policy is currently in place.

Recommendation:

- Develop and implement a robust disaster recovery plan and backup policy to ensure data integrity and business continuity during unexpected events.

### 6. Issue: Non-compliance with E.U. GDPR Regulation

Description:

- Specific Issue: The system does not meet all the requirements of the E.U. General Data Protection Regulation (GDPR).

- Impact: Non-compliance can result in substantial fines and legal penalties in the EU jurisdiction.

Current Control:

- Partial or non-existent GDPR compliance measures.

Recommendation:

- Ensure full compliance with GDPR by implementing all required policies and procedures to protect personal data and uphold data subject rights.

### 7. Issue: Absence of Password Management System

Description:

- Specific Issue: There is no password management system in place.

- Impact: This causes inefficiencies and increased workload for employees and the IT department in managing password-related issues.

Current Control:

- Manual password management processes.

Recommendation:

- Implement an automated password management system to streamline password creation, update, and reset processes.

### 8. Issue: Outdated Password Policy

Description:

- Specific Issue: The current password policy is outdated.

- Impact: An outdated password policy poses a significant security risk to the organization.

Current Control:

- Existing but outdated password policy.

Recommendation:

- Update the password policy to align with current best practices and security standards, including requirements for password complexity (e.g., at least eight characters, a combination of letters and at least one number; special characters).

### 9. Issue: Lack of Intrusion Detection System

Description:

- Specific Issue: There is no intrusion detection system in place.

- Impact: This leaves the organization vulnerable to undetected cyber attacks and unauthorized access.

Current Control:

- No intrusion detection measures.

Recommendation:

- Implement an intrusion detection system (IDS) to monitor network traffic and detect suspicious activities and potential security breaches.

### 10. Issue: Inconsistent Monitoring and Maintenance of Legacy Systems

Description:

- Specific Issue: Monitoring and maintenance of legacy systems are inconsistent.

- Impact: This may pose a security threat to the organization due to potential vulnerabilities in outdated systems.

Current Control:

- Inconsistent monitoring and maintenance practices.

Recommendation:

- Establish regular and consistent monitoring and maintenance schedules for all legacy systems to ensure they are secure and up-to-date.
