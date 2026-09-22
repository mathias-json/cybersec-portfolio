## Controls Assessment & Compliance Checklist

Below is an evaluation of Botium Toys existing safeguards and security postures assessed against industry standard baselines - **NIST CSF**, **PCI-DSS** & **GDPR**

---

## 🔎 Audit Findings / Risk Exposure

**Administrative - Least Privilege Policy, Separation of Duties:** | Missing | All employees have access to internally stored data and ability to access customers' personal and financial information\
**Administrative - Disaster Policy Plans, Backups:** | Missing | The company does not have any backups of critical data, not procedures for that\
**Administrative, Technical - Password Policies, Password Management System:** | Missing | All user passwords do not have any complexity requirements and for inclusion of special characters. There is no password management system enforcing policy requirement\
**Technical - Intrusion Detection System:** | Missing | There is no use of an IDS within the company to reveal any potential threats across their network\
**Technical - Encryption:** | Missing | Use of encryption is not present where customers' financial information is stored in the company's internal database making it prone to theft\
**Physical - Fire Detection/Prevention:** | Partial | Though the site does implement use of CCTV and locks to protect assets, the are no precautions against potential fires\

---

**Regulatory Fines - PCI DSS:** Lack of separation of duties is causing all personnel to have access to customers' card information; there is no password management system that enables special charaters from user and complexity of passwords; there is a encryption of critical data concerning customers primarily at transaction end endpoints and PII data\
**Lack of Redundancy:** The company is operating from a single location where there is no disaster plans and backups to benefit business continuity\
**Regulatory Fines - GDPR:** The company has indeed included a plan to notify customers in a time window in regards to data breaches; they ensure data is classified and inventoried and enforce privacy policies, procedures and processes to properly document and maintain data however all of this is fulfilled whilst not keeping customer data private or in a secure location\

---

## ➕ Recommendations for Changes and Improvement

**Employing tighter privileges**
**Harden GDPR and PCI DSS data protection**
**Create Backups and Create disaster plan** - (potentially try to expand to more than one site)
**Enforce stricter password requirements and policies**
**Implement fire safety anti measures**