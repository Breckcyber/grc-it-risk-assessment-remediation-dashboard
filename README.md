# Technology Risk Assessment, Control Assurance and Remediation Review

This repository documents an end-to-end technology risk and control assurance review completed for **MapleCare Health Services**, a simulated Canadian healthcare organization.

The review assessed **15 technology and cybersecurity risks** and **15 related controls** across identity and access management, Microsoft 365, patient records, third-party risk, backup and recovery, endpoint security, business continuity, and technology governance.

The work included:

* Engagement scoping
* Business and technology analysis
* Asset and process identification
* Technology risk assessment
* Control design evaluation
* NIST and ISO framework alignment
* Control testing and evidence review
* Findings analysis
* Remediation tracking
* Executive risk reporting

The review demonstrates a practical approach to translating technical control weaknesses into clear business risks, assessing whether controls are designed and operating effectively, and presenting management with prioritized actions, accountable ownership, and defined closure requirements.

> **Engagement notice:** MapleCare Health Services is fictional. All risks, controls, evidence, testing results, findings, management actions, and records are simulated for professional portfolio demonstration. No real patient, employee, client, or company data is used.

---

## Engagement Summary

| Area                                        | Scope |
| ------------------------------------------- | ----: |
| Technology and cybersecurity risks assessed |    15 |
| Controls evaluated                          |    15 |
| Control-testing workpapers completed        |    15 |
| Frameworks referenced                       |     3 |
| Findings documented                         |    15 |
| Remediation actions tracked                 |    15 |

---

## Engagement Objective

The objective of the review is to provide management with a clear and structured view of MapleCare’s key technology risks, existing controls, control gaps, accountable owners, and remediation priorities.

The assessment supports risk-based decision-making by identifying where control weaknesses could affect:

* Sensitive patient, employee, billing, and business information
* Daily clinical and administrative operations
* Privacy and regulatory obligations
* Third-party service delivery
* Business continuity and recovery
* Audit and assurance readiness

The review covers:

* Identity and access management
* Microsoft 365 and SharePoint security
* Patient-record access
* Employee onboarding and offboarding
* Privileged access management
* Third-party and vendor risk
* Backup and recovery
* Incident response
* Security awareness and training
* Patch and vulnerability management
* Data classification and handling
* Endpoint security
* Business continuity
* Technology risk governance
* Audit evidence management

---

## Business Scenario

MapleCare Health Services is a fictional Canadian healthcare organization with approximately 150 employees.

The organization depends on Microsoft 365, SharePoint, a patient records system, an HR management platform, employee endpoint devices, backup services, and a third-party billing portal to support clinical, administrative, and financial operations.

Because these systems process sensitive information and support important services, management requires a clearer understanding of:

* Material technology and cybersecurity risks
* Existing control coverage and ownership
* Control design and operating gaps
* Third-party and vendor exposure
* Remediation priorities
* Risk acceptance and escalation needs
* Audit and assurance readiness
* The potential effect of control weaknesses on privacy, service continuity, and business operations

---

## Review Approach

The work follows a practical technology risk lifecycle:

1. Define the review scope, objectives, stakeholders, and deliverables
2. Understand the business and technology environment
3. Identify critical assets, processes, data, and dependencies
4. Identify and assess technology and cybersecurity risks
5. Document existing controls and control gaps
6. Define and map recommended controls
7. Establish testing procedures and evidence requirements
8. Assess control design and operating effectiveness
9. Document findings and management actions
10. Track remediation, closure evidence, and retesting
11. Report material risks and priorities to management

---

## Analyst Responsibilities

As the Technology Risk and GRC Analyst for this review, I was responsible for:

* Defining the review scope and assessment boundaries
* Identifying key stakeholders and control owners
* Reviewing the business and technology environment
* Developing the asset and process inventory
* Writing technology and cybersecurity risk statements
* Assessing likelihood, impact, and business consequences
* Documenting existing controls and control gaps
* Defining control objectives and recommended activities
* Mapping controls to NIST and ISO references
* Preparing and executing control-testing procedures
* Reviewing evidence and documenting exceptions
* Assessing design and operating effectiveness
* Developing findings and remediation actions
* Defining closure evidence and retesting requirements
* Preparing management-level risk reporting

---

## Project Deliverables

| # | Deliverable                                                  | Description                                                                                                                                                                | Status      |
| - | ------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- |
| 1 | [Project Charter](01_Project_Charter/Project_Charter.pdf) | Defines the engagement objective, scope, stakeholders, governance, assessment approach, assumptions, limitations, and expected outputs. | Completed |
| 2 | [Company Profile](02_Company_Profile/)                       | Documents MapleCare’s services, technology environment, sensitive data, business processes, systems, and key risk concerns.                                                | Completed   |
| 3 | [Asset and Process Inventory](03_Asset_Process_Inventory/)   | Identifies important systems and processes, including ownership, business purpose, data sensitivity, criticality, dependencies, and key concerns.                          | Completed   |
| 4 | [Risk Register](04_Risk_Register/)                           | Documents 15 technology, cybersecurity, privacy, vendor, resilience, and governance risks, including ratings, impacts, controls, gaps, owners, and treatment plans.        | Completed   |
| 5 | [Risk and Control Matrix](05_Risk_Control_Matrix/)           | Links identified risks to control objectives, recommended controls, owners, frequencies, testing procedures, evidence requirements, and framework references.              | Completed   |
| 6 | [Control Testing and Evidence](06_Control_Testing_Evidence/) | Assesses control design and operating effectiveness through population analysis, risk-based sampling, evidence review, exception analysis, and documented conclusions.     | Completed   |
| 7 | [Remediation Tracker](07_Remediation_Tracker/)               | Tracks findings, root causes, management actions, accountable owners, target dates, progress, closure evidence, validation, and retesting requirements.                    | Completed   |
| 8 | Executive Risk Reporting and Management Summary              | Consolidates risk exposure, control effectiveness, significant findings, remediation progress, overdue actions, and management priorities into decision-focused reporting. | In Progress |

---

## Risk and Control Assessment

The Risk and Control Matrix connects the risks identified in the Risk Register to the control activities required to reduce them.

For each risk, the matrix documents:

* Existing control
* Control gap
* Control objective
* Recommended control
* Control owner
* Control frequency
* Control type and nature
* NIST CSF 2.0 reference
* NIST SP 800-53 reference
* ISO/IEC 27001:2022 alignment
* Testing procedure
* Evidence requirements
* Control-testing status

The matrix served as the foundation for the control-testing work completed in Deliverable 6.

All 15 controls were assessed using defined populations, risk-based sampling, evidence review, exception analysis, and documented conclusions on design and operating effectiveness.

---

## Control-Testing Method

For each control, the testing process included:

1. Confirming the associated risk and control objective
2. Defining the review period
3. Identifying the complete testing population
4. Selecting a risk-based sample
5. Requesting relevant control evidence
6. Comparing expected and actual results
7. Documenting exceptions
8. Assessing design effectiveness
9. Assessing operating effectiveness
10. Recording findings and management actions

Testing methods included:

* Inspection
* Inquiry
* Walkthrough
* Reconciliation
* Sample testing
* Data analysis
* Observation
* Reperformance

---

## Example: Multi-Factor Authentication

Risk R-001 addresses incomplete MFA coverage in Microsoft 365.

The existing control was that MFA had been enabled for selected administrator accounts. The control gap was that MFA was not consistently enforced for all users and exceptions were not formally governed.

The recommended control required MFA for employees, contractors, administrators, and remote users, with documented, approved, time-limited exceptions and monthly reviews.

The test included:

* Reviewing Microsoft 365 authentication requirements
* Obtaining the complete active-user population
* Comparing active accounts with MFA registration records
* Reviewing administrator accounts
* Testing all excluded accounts
* Validating exception approvals, expiry dates, and monthly review evidence

The simulated testing identified:

* Incomplete MFA coverage
* Weak exception governance
* Missing monthly review evidence

The control was assessed as:

* **Design effectiveness:** Partially Effective
* **Operating effectiveness:** Ineffective
* **Overall conclusion:** Needs Improvement

The recommended action was to enforce MFA for all in-scope accounts, formalize the exception process, assign expiry dates, and complete documented monthly reviews.

---

## Findings and Remediation

Control-testing results were converted into formal findings and remediation actions.

Each finding includes:

* Finding ID
* Risk and control reference
* Finding summary
* Severity
* Root cause
* Management action
* Accountable owner
* Target date
* Progress status
* Closure evidence requirements
* Retesting requirements
* Final closure decision

A finding is not treated as closed simply because the action owner reports completion.

Closure requires:

1. Supporting evidence
2. Independent review
3. Successful retesting
4. A documented closure decision

---

## Framework Alignment

The review uses the following frameworks to support risk and control analysis:

* NIST Cybersecurity Framework 2.0
* NIST SP 800-53 Revision 5
* ISO/IEC 27001:2022

Additional references may be used where relevant:

* NIST AI Risk Management Framework
* ISO/IEC 42001

Framework references support the assessment and do not imply certification or formal compliance by MapleCare Health Services.

---

## Core Capabilities Applied

* Technology risk assessment
* Cybersecurity risk analysis
* Risk-register development
* Business-impact analysis
* Asset and process identification
* Control-gap analysis
* Risk and control evaluation
* Control design assessment
* Operating effectiveness testing
* Evidence review and validation
* Risk-based sampling
* Exception and findings analysis
* Third-party risk assessment
* Identity and access management review
* Business continuity and resilience review
* Remediation governance
* NIST and ISO framework alignment
* Executive risk reporting
* Microsoft Excel-based control analysis
* Python-supported GRC workflow automation

---

## Review Status

The following phases have been completed:

* Project Charter
* Business and Technology Profile
* Asset and Process Inventory
* Risk Register
* Risk and Control Matrix
* Control Testing and Evidence
* Remediation Tracker

The current phase focuses on consolidating the review results into executive risk reporting and a management summary.

The final reporting will present:

* Material technology risks
* Control design and operating effectiveness
* High-priority findings
* Remediation progress
* Overdue management actions
* Residual risk
* Decisions requiring management attention

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
├── 06_Control_Testing_Evidence
├── 07_Remediation_Tracker
├── LICENSE
└── README.md
```

The final folder will be added as:

```text
08_Executive_Risk_Reporting
```

---

## Professional Relevance

This review demonstrates practical capability relevant to roles in:

* Technology Risk
* IT Risk
* Cybersecurity GRC
* IT Controls
* Internal Audit
* Third-Party Risk Management
* Cybersecurity Compliance
* Operational Risk
* Risk and Controls Assurance

---

## Author

**Breck Agyekum**
Technology Risk and GRC Analyst
Ottawa, Ontario, Canada
