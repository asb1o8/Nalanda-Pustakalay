# Key Stakeholders Under the Digital Personal Data Protection (DPDP) Framework

The Digital Personal Data Protection (DPDP) framework involves four key stakeholders:

## 1. Data Principal

A **Data Principal** is the individual to whom the personal data relates.

**Responsibilities:**
- Provide authentic and accurate information where required.
- Avoid filing frivolous complaints.
- Exercise rights available under the DPDP framework.

**Example:** A student whose personal information is collected by a university is the Data Principal.

## 2. Data Fiduciary

A **Data Fiduciary** is the person or organization that determines the purpose and means of processing personal data.

**Examples:**
- Banks
- Hospitals
- E-commerce platforms
- Educational institutions
- Mobile applications

**Key responsibilities:**
- Obtain valid consent wherever required.
- Implement reasonable security safeguards to protect personal data.
- Respond to Data Principal requests as required by law.
- Notify data breaches in accordance with applicable legal requirements.
- Ensure compliance with applicable DPDP obligations.

**Important:** Even when data processing is outsourced to a third party, the Data Fiduciary retains its legal responsibilities under the DPDP framework.

## 3. Data Processor

A **Data Processor** is a person or entity that processes personal data on behalf of a Data Fiduciary.

**Examples:**
- Cloud service providers
- Payroll service companies
- Managed IT service providers
- Third-party analytics platforms

**Key characteristics:**
- Processes personal data on behalf of the Data Fiduciary.
- Operates according to the Data Fiduciary's instructions and applicable legal requirements.
- Must not independently use personal data for its own purposes unless legally permitted.
- Supports the Data Fiduciary's data processing activities.

**Important:** The Data Fiduciary remains responsible for its obligations under the DPDP framework, even when a Data Processor performs the actual processing.

## 4. Consent Manager

A **Consent Manager** is a registered entity that enables Data Principals to give, manage, review, and withdraw their consent through an accessible, transparent, and interoperable platform.

**Key characteristics:**
- Enables individuals to manage their consent.
- Provides greater transparency and control over consent.
- Acts in the interests of the Data Principal.
- Facilitates consent management between the Data Principal and Data Fiduciary.

## How the Four Stakeholders Interact

1. **Data Principal:** The individual whose personal data is involved.
2. **Data Fiduciary:** Determines why and how the personal data will be processed.
3. **Data Processor:** Processes personal data on behalf of the Data Fiduciary.
4. **Consent Manager:** Enables the Data Principal to manage consent through a registered platform.

### Simplified Relationship

```text
             DATA PRINCIPAL
          (Individual / User)
                   |
                   | Personal Data
                   v
             DATA FIDUCIARY
        (Determines Purpose and Means)
                   |
                   | Processing Instructions
                   v
             DATA PROCESSOR
        (Processes Data on Its Behalf)


             CONSENT MANAGER
                   |
                   | Consent Management
                   v
             DATA PRINCIPAL
        (Give, Review, Manage,
             or Withdraw Consent)
```

## Quick Revision

| Stakeholder | Primary Role |
|---|---|
| Data Principal | Individual to whom the personal data relates |
| Data Fiduciary | Determines the purpose and means of processing personal data |
| Data Processor | Processes personal data on behalf of the Data Fiduciary |
| Consent Manager | Enables the Data Principal to manage consent |

**Key takeaway:** The Data Principal is at the center of the framework. The Data Fiduciary determines the purpose and means of processing and remains responsible for its legal obligations. The Data Processor supports processing activities, while the Consent Manager empowers individuals to manage their consent.




# DPDP Compliance: Integrating Legal Requirements with Cybersecurity Controls

Under the Digital Personal Data Protection (DPDP) framework, organizations must do more than define privacy policies. They must also possess the technical capabilities to protect personal data, detect cyber incidents, respond rapidly, and manage the entire data lifecycle.

Every applicable legal requirement should be supported by corresponding technical controls, operational processes, and documented evidence.

## 1. Mapping Legal Requirements to Technical Controls

For example, the requirement to implement reasonable security safeguards translates into practical cybersecurity measures, including:

- **Defense in Depth:** Implement multiple layers of security to reduce the risk of unauthorized access and data compromise.
- **Access Control:** Enforce strong authentication, authorization, and the principle of least privilege.
- **Encryption:** Protect personal data both at rest and in transit.
- **Vulnerability Management:** Identify, assess, prioritize, and remediate security vulnerabilities.
- **Penetration Testing:** Assess the security of applications, APIs, infrastructure, and other in-scope assets.
- **Zero Trust Architecture:** Continuously verify access based on identity, device posture, context, and applicable security policies.
- **Role-Based Access Control (RBAC):** Restrict access according to defined organizational roles and responsibilities.
- **Security Monitoring:** Continuously monitor systems, networks, and applications for suspicious activities through a Security Operations Center (SOC).

The objective is to ensure that privacy obligations are supported by measurable and verifiable security controls.

## 2. Personal Data Breach Response: Integrating SOC, DFIR, and Legal Teams

The DPDP framework establishes obligations concerning personal data breaches. Organizations must therefore maintain the technical and operational capabilities to investigate, contain, and respond to such incidents.

When a personal data breach is detected, the technical and incident response teams must:

1. **Contain the Incident:** Limit further unauthorized access, data exposure, or exfiltration.
2. **Preserve Digital Evidence:** Secure relevant logs, system artifacts, network records, and other forensic evidence.
3. **Determine the Scope:** Identify the affected systems, personal data, individuals, and potential extent of data compromise.
4. **Conduct Digital Forensics and Incident Response (DFIR):** Investigate the attack vector, timeline, impact, and potential persistence mechanisms.
5. **Analyze Security Logs:** Correlate relevant events to reconstruct the incident and identify suspicious activity.
6. **Assess Data Exfiltration:** Determine, to the extent possible, whether personal data was accessed, transferred, or exfiltrated.

The legal and compliance teams then use the technical findings to support regulatory notifications and communications to affected Data Principals, in accordance with applicable requirements and prescribed timelines.

### Cross-Functional Incident Response

| Team | Primary Responsibility |
|---|---|
| Security Operations Center (SOC) | Detect, monitor, triage, and escalate security incidents |
| DFIR Team | Investigate incidents, preserve evidence, reconstruct attack timelines, and assess impact |
| Cybersecurity Team | Implement security controls, contain threats, and remediate vulnerabilities |
| Legal Team | Interpret legal obligations and support required regulatory notifications |
| Governance, Risk, and Compliance (GRC) Team | Coordinate compliance requirements, risk assessments, control documentation, and audit evidence |

**Key principle:** SOC, DFIR, cybersecurity, legal, and GRC teams must work together as a coordinated incident response function.

## 3. Right to Erasure: Technical Implementation of Data Lifecycle Management

The DPDP framework provides Data Principals with certain rights concerning their personal data, including erasure, subject to applicable legal requirements and exceptions.

Organizations must implement processes that identify when personal data is no longer required for its specified purpose or when consent is withdrawn, where these events trigger an applicable obligation to erase the data.

Relevant technical measures include:

- **Automated Data Lifecycle Management:** Track data retention periods, processing purposes, and applicable deletion triggers.
- **Data Loss Prevention (DLP):** Help detect and prevent unauthorized transfers or exposure of sensitive data.
- **Automated Deletion Workflows:** Initiate and track deletion processes when applicable requirements are fulfilled.
- **Secure Database Deletion:** Remove personal data from relevant databases and storage systems.
- **Cryptographic Erasure:** Render encrypted data inaccessible by securely destroying the relevant encryption keys, where technically and legally appropriate.
- **Backup and Replica Management:** Account for copies, replicas, and backups when implementing deletion and retention requirements.
- **Audit Logging:** Record deletion requests, approvals, execution status, exceptions, and verification results.

Deletion workflows must account for applicable retention obligations, legal exceptions, and the technical limitations of backup and archival systems.

Audit records should provide evidence that the deletion process was executed appropriately without unnecessarily retaining the personal data that was supposed to be erased.

## 4. Auditability and Evidence of Compliance

Implementing a security control is not sufficient by itself. Organizations should also maintain evidence demonstrating that the control operates as intended.

Examples include:

- Vulnerability assessment and penetration testing reports.
- Access control reviews and access logs.
- Encryption configurations and key management records.
- SOC alerts and incident investigation records.
- DFIR reports and evidence preservation records.
- Personal data breach notification records.
- Data retention schedules and deletion audit logs.
- Documented policies, procedures, and risk assessments.

This evidence helps organizations demonstrate accountability and supports internal audits, regulatory reviews, and continuous compliance improvement.

## 5. Integrating Privacy, Cybersecurity, and GRC

The DPDP framework makes it necessary to coordinate privacy governance with practical cybersecurity capabilities.

The responsibilities can be summarized as follows:

- **Cybersecurity teams** implement and maintain technical safeguards.
- **SOC teams** detect and escalate suspicious activities and potential incidents.
- **DFIR teams** investigate incidents and establish evidence-based findings.
- **Legal teams** interpret regulatory obligations and support legally required notifications.
- **GRC teams** map obligations to controls, manage risk, and maintain compliance evidence.
- **Data governance teams** coordinate data inventories, retention policies, and lifecycle management.

Every applicable privacy obligation should be supported by appropriate cybersecurity controls, governance processes, and operational workflows.

## Conclusion

DPDP compliance is not solely the responsibility of the legal or privacy department. It requires coordinated execution across cybersecurity, SOC, DFIR, legal, GRC, and data governance functions.

By integrating legal requirements with technical controls, incident response capabilities, automated data lifecycle management, and auditable evidence, organizations can strengthen personal data protection, respond effectively to incidents, and demonstrate compliance with the applicable DPDP requirements.

**Core takeaway:** Legal requirements define the obligations; cybersecurity controls help enforce them; SOC and DFIR capabilities support detection and investigation; and legal and GRC functions help ensure that the organization's response and compliance activities meet applicable requirements.
