
# Technology Risk Assessment, Control Assurance & Remediation Program

Conducted an end-to-end technology risk and control assurance assessment for MapleCare Health Services, a simulated Canadian healthcare organization.

The engagement covered 15 technology and cybersecurity risks across Microsoft 365, patient records, identity and access management, third-party vendors, backups, endpoints, business continuity, and governance.

The work included business and technology scoping, asset and process identification, risk assessment, control design, framework mapping, control testing, evidence review, findings analysis, remediation planning, and executive reporting.

The project demonstrates practical capability in translating technical control weaknesses into clear business risks, testing whether controls are working, and presenting management with prioritized actions and accountable next steps.

> **Portfolio notice:** MapleCare Health Services is fictional. All information, risks, controls, test results, findings, and records in this repository are simulated for professional portfolio demonstration. No real patient, employee, client, or company data is used.

---

## Engagement Objective

The objective of the engagement is to provide management with a structured view of MapleCare’s key technology risks, existing controls, control gaps, ownership, and remediation priorities.

The assessment covers areas including:

* Identity and access management
* Microsoft 365 and SharePoint security
* Patient-record access
* Employee offboarding
* Third-party and vendor risk
* Backup and recovery
* Incident response
* Security awareness
* Patch and vulnerability management
* Data classification
* Endpoint security
* Business continuity
* Risk governance
* Audit evidence management

---

## Business Scenario

MapleCare Health Services is a fictional Canadian healthcare organization with approximately 150 employees.

The organization relies on Microsoft 365, SharePoint, a patient records system, an HR management platform, endpoint devices, backup services, and a third-party billing portal.

Because these systems support important healthcare and business operations, management requires a clearer understanding of:

* Critical technology risks
* Existing control coverage
* Control design gaps
* Third-party exposure
* Risk ownership
* Remediation priorities
* Audit and assurance readiness

---

## Engagement Approach

The work follows a practical technology risk lifecycle:

1. Define the engagement scope and objectives
2. Understand the business and technology environment
3. Identify critical assets and business processes
4. Identify and assess technology risks
5. Document existing controls and control gaps
6. Design and map recommended controls
7. Define testing procedures and evidence requirements
8. Assess control effectiveness
9. Track remediation actions
10. Report results to management

---

## Engagement Role

In this portfolio engagement, I perform the responsibilities of a **Technology Risk and GRC Analyst**.

My responsibilities include:

* Defining the assessment scope, stakeholders, and deliverables
* Reviewing the business and technology environment
* Identifying critical systems, processes, data, and owners
* Developing technology and cybersecurity risk statements
* Assessing likelihood, impact, and business consequences
* Documenting existing controls and control gaps
* Designing recommended control activities
* Mapping controls to NIST and ISO frameworks
* Preparing control-testing procedures
* Defining evidence requirements
* Supporting remediation planning and executive reporting

---

## Project Deliverables

| # | Deliverable                                                | Description                                                                                                                                                        | Status     |
| - | ---------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- |
| 1 | [Project Charter](01_Project_Charter/)                     | Defines the engagement objective, scope, stakeholders, frameworks, exclusions, and expected outputs.                                                               | Completed  |
| 2 | [Company Profile](02_Company_Profile/)                     | Documents MapleCare’s services, technology environment, sensitive data, business processes, and risk context.                                                      | Completed  |
| 3 | [Asset and Process Inventory](03_Asset_Process_Inventory/) | Identifies important systems and processes, including ownership, business purpose, data sensitivity, criticality, and key concerns.                                | Completed  |
| 4 | [Risk Register](04_Risk_Register/)                         | Documents 15 technology, cybersecurity, privacy, vendor, resilience, and governance risks, including scores, impacts, controls, gaps, owners, and treatment plans. | Completed  |
| 5 | [Risk and Control Matrix](05_Risk_Control_Matrix/)         | Links identified risks to control objectives, recommended controls, owners, frequencies, framework references, testing procedures, and evidence requirements.      | Completed  |
| 6 | Control Testing and Evidence                               | Will assess control design and operating effectiveness through evidence review, sampling, exception analysis, and documented conclusions.                          | Next Phase |
| 7 | Remediation Tracker                                        | Will track findings, action owners, target dates, status, closure evidence, and validation.                                                                        | Planned    |
| 8 | Executive Dashboard and Report                             | Will summarize risk exposure, control effectiveness, remediation progress, and management priorities.                                                              | Planned    |

---

## Risk and Control Matrix

The Risk and Control Matrix connects the risks identified in the Risk Register to the control activities required to reduce them.

For each risk, the matrix documents:

* Existing control
* Control gap
* Control objective
* Recommended control
* Control owner
* Control frequency
* Control type and nature
* NIST CSF 2.0 mapping
* NIST SP 800-53 mapping
* ISO/IEC 27001:2022 alignment
* Planned testing procedure
* Evidence requirements
* Preliminary testing status

All controls are currently marked **Not Tested**. Control design and operating effectiveness will be assessed during the control-testing phase.

### Example: Multi-Factor Authentication

Risk R-001 addresses incomplete MFA coverage in Microsoft 365.

The existing control is that MFA is enabled for selected administrator accounts. The control gap is that MFA is not consistently enforced for all users and exceptions are not formally governed.

The recommended control requires MFA for employees, contractors, administrators, and remote users, with documented, approved, time-limited exceptions and regular exception reviews.

The planned testing approach includes:

* Reviewing Microsoft 365 authentication settings
* Obtaining the complete user population
* Comparing user accounts with MFA registration records
* Sampling different account types
* Reviewing excluded accounts
* Validating exception approvals and review evidence

---

## Framework Alignment

The project uses the following frameworks to support control design and assessment:

* **NIST Cybersecurity Framework 2.0**
* **NIST SP 800-53 Revision 5**
* **ISO/IEC 27001:2022**
* **NIST AI Risk Management Framework**, where applicable
* **ISO/IEC 42001 concepts**, where applicable

Framework references are used to support the risk and control analysis. They do not imply certification or formal compliance by the fictional organization.

---

## Skills Demonstrated

* Technology risk assessment
* Cybersecurity risk analysis
* Risk-register development
* Business-impact analysis
* IT asset and process identification
* Control-gap analysis
* Risk and control matrix development
* Control design
* Control ownership and frequency definition
* Control-testing preparation
* Audit evidence planning
* Third-party risk assessment
* NIST and ISO control mapping
* Remediation planning
* Executive risk reporting
* Microsoft Excel
* Python and AI-assisted GRC workflows

---

## Current Status

**Completed:** Project Charter, Company Profile, Asset and Process Inventory, Risk Register, and Risk and Control Matrix.

**Current phase:** Control Testing and Evidence.

**Next activity:** Assess selected controls for design and operating effectiveness, beginning with multi-factor authentication, employee offboarding, patient-record access, vendor due diligence, and backup restoration.

---

## Repository Structure

```text
grc-it-risk-assessment-remediation-dashboard
│
├── 01_Project_Charter
├── 02_Company_Profile
├── 03_Asset_Process_Inventory
├── 04_Risk_Register
├── 05_Risk_Control_Matrix
├── LICENSE
└── README.md
```

Additional folders will be added as the control-testing, remediation, and executive-reporting phases are completed.

---

## Professional Focus

This project demonstrates practical capability relevant to roles in:

* Technology Risk
* IT Risk
* Cybersecurity GRC
* IT Controls
* Internal Audit
* Third-Party Risk Management
* Cybersecurity Compliance
* Operational Risk
* AI Governance

---

## Author

**Breck Agyekum**
IT Risk & GRC Analyst
Ottawa, Ontario, Canada
[LinkedIn](https://linkedin.com/in/breck-agyekum)
