<p align="center">
  <img src="https://i.imgur.com/ElWjENc.png" alt="Google Logo" width="200" height="200" />
</p>

# Botium Toys: Scope, Goals, and Risk Assessment Report

## Scope and Goals of the Audit

**Scope:** The scope is defined as the entire security program at Botium Toys. This means all assets need to be assessed alongside internal processes and procedures related to the implementation of controls and compliance best practices.

**Goals:** Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices need to be implemented to improve Botium Toys’ security posture.

### Current Assets

Assets managed by the IT Department include:
- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring

## Risk Assessment and Description

Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.

**Control Best Practices:** The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

**Risk Score:** On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

**Additional Comments:** The potential impact from the loss of an asset is rated as medium because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:

- Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
- Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database.
- Access controls pertaining to least privilege and separation of duties have not been implemented.
- The IT department has ensured availability and integrated controls to ensure data integrity.
- The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
- Antivirus software is installed and monitored regularly by the IT department.
- The IT department has not installed an intrusion detection system (IDS).
- There are no disaster recovery plans currently in place, and the company does not have backups of critical data.
- The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among

# Controls and Compliance Checklist - Botium Toys

## Controls Assessment Checklist

- [ ] Least Privilege: Currently, all employees have access to customer data; privileges need to be limited to reduce the risk of a breach.
- [ ] Disaster Recovery Plans: There are no disaster recovery plans in place. These need to be implemented to ensure business continuity.
- [ ] Password Policies: Employee password requirements are minimal, which could allow a threat actor to more easily access secure data/other assets via employee work equipment/the internal network.
- [ ] Separation of Duties: Needs to be implemented to reduce the possibility of fraud/access to critical data, since the company CEO currently runs day-to-day operations and manages the payroll.
- [X] Firewall: The existing firewall blocks traffic based on an appropriately defined set of security rules.
- [ ] Intrusion Detection System (IDS): The IT department needs an IDS in place to help identify possible intrusions by threat actors.
- [ ] Backups: The IT department needs to have backups of critical data, in the case of a breach, to ensure business continuity.
- [X] Antivirus Software: Antivirus software is installed and monitored regularly by the IT department.
- [ ] Manual Monitoring, Maintenance, and Intervention for Legacy Systems: The list of assets notes the use of legacy systems. The risk assessment indicates that these systems are monitored and maintained, but there is not a regular schedule in place for this task and procedures/policies related to intervention are unclear, which could place these systems at risk of a breach.
- [ ] Encryption: Encryption is not currently used; implementing it would provide greater confidentiality of sensitive information.
- [ ] Password Management System: There is no password management system currently in place; implementing this control would improve IT department/other employee productivity in the case of password issues.
- [X] Locks (Offices, Storefront, Warehouse): The store’s physical location, which includes the company’s main offices, store front, and warehouse of products, has sufficient locks.
- [X] Closed-Circuit Television (CCTV) Surveillance: CCTV is installed/functioning at the store’s physical location.
- [X] Fire Detection/Prevention (Fire Alarm, Sprinkler System, etc.): Botium Toys’ physical location has a functioning fire detection and prevention system.

### Payment Card Industry Data Security Standard (PCI DSS)

- [ ] Only authorized users have access to customers’ credit card information: Currently, all employees have access to the company’s internal data.
- [ ] Credit card information is accepted, processed, transmitted, and stored internally, in a secure environment: Credit card information is not encrypted, and all employees currently have access to internal data, including customers’ credit card information.
- [ ] Implement data encryption procedures to better secure credit card transaction touchpoints and data: The company does not currently use encryption to better ensure the confidentiality of customers’ financial information.
- [ ] Adopt secure password management policies: Password policies are nominal, and no password management system is currently in place.

### General Data Protection Regulation (GDPR)

- [ ] E.U. customers’ data is kept private/secured: The company does not currently use encryption to better ensure the confidentiality of customers’ financial information.
- [X] There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach: There is a plan to notify E.U. customers within 72 hours of a data breach.
- [ ] Ensure data is properly classified and inventoried: Current assets have been inventoried/listed, but not classified.
- [X] Enforce privacy policies, procedures, and processes to properly document and maintain data: Privacy policies, procedures, and processes have been developed and enforced among IT team members and other employees, as needed.

### System and Organizations Controls (SOC Type 1, SOC Type 2)

- [ ] User access policies are established: Controls of Least Privilege and separation of duties are not currently in place; all employees have access to internally stored data.
- [X] Sensitive data (PII/SPII) is confidential/private: Encryption is not currently used to better ensure the confidentiality of PII/SPII.
- [X] Data integrity ensures the data is consistent, complete, accurate, and has been validated: Data integrity is in place.
- [ ] Data is available to individuals authorized to access it: While data is available to all employees, authorization needs to be limited to only the individuals who need access to it to do their jobs.

## Recommendations

In order to strengthen Botium Toys' security posture and address compliance gaps, the following recommendations are provided. These recommendations are prioritized based on their significance and potential impact. Assign responsibilities to relevant teams or individuals and consider leveraging external resources or best practices to assist in the implementation process.

### Priority 1: Immediate Action Required

1. **Least Privilege:** Implement strict access control measures to limit employee access to sensitive data. Assign the responsibility to the IT department. [Reference: NIST Access Control Guide](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)

2. **Disaster Recovery Plans:** Develop and document comprehensive disaster recovery plans to ensure business continuity in case of emergencies. The IT department should lead this effort. [Reference: Disaster Recovery Planning Guide](https://www.ready.gov/business/implementation/IT)

3. **Password Policies:** Strengthen password policies to meet current minimum complexity requirements (e.g., eight characters, a combination of letters, numbers, and special characters). IT department to oversee the implementation. [Reference: NIST Password Guidelines](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-63b.pdf)

### Priority 2: High Importance

4. **Separation of Duties:** Implement separation of duties to reduce the risk of fraud and unauthorized access. This should be overseen by both IT and HR departments. [Reference: ISACA Separation of Duties Guidelines](https://www.isaca.org/resources/role-based-separation-of-duties-matrix)

5. **Intrusion Detection System (IDS):** Install and configure an IDS to identify potential security threats and intrusions promptly. The IT department should lead this initiative. [Reference: SANS IDS Implementation Guide](https://www.sans.org/security-resources/idfaq/what-is-an-intrusion-detection-system)

### Priority 3: Important Enhancements

6. **Legacy System Management:** Establish a regular schedule for monitoring and maintaining legacy systems. The IT department should take charge and develop clear intervention procedures. [Reference: Legacy System Management Best Practices](https://www.cio.com/article/3295549/what-is-legacy-systems-management.html)

7. **Encryption:** Implement encryption protocols to ensure the confidentiality of sensitive data, especially customer information. IT department's responsibility. [Reference: Encryption Best Practices](https://www.trendmicro.com/vinfo/us/security/news/security-technology/data-encryption-best-practices)

8. **Password Management System:** Deploy a centralized password management system that enforces password policy requirements. This will improve productivity. IT department and HR can collaborate on this effort. [Reference: Enterprise Password Management Tools](https://www.gartner.com/reviews/market/enterprise-password-management-tools)

### Priority 4: Compliance Focus

9. **Classification of Assets:** Properly classify and inventory all assets to identify additional controls needed for compliance and security. Collaboration between IT and compliance teams is crucial. [Reference: Asset Classification Guidelines](https://www.sans.org/security-resources/policies/general/pdf/asset-classification-policy)

10. **Data Privacy Enforcement:** Enforce privacy policies, procedures, and processes to ensure the proper documentation and maintenance of data, particularly customer data. Involves collaboration between IT and compliance teams. [Reference: GDPR Compliance Guide](https://gdpr.eu/gdpr-compliance/)

By following these recommendations and aligning them with your compliance goals, Botium Toys can enhance its security posture, protect sensitive information, and demonstrate a commitment to regulatory compliance.
