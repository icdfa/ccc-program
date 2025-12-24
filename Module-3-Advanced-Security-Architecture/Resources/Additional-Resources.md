# Module 3: Additional Resources

## Advanced Security Architecture & Solution Design

This document provides additional resources to supplement your learning in Module 3. These resources include architecture frameworks, cloud security tools, vendor management resources, and incident response materials.

---

## 3.1 Enterprise Security Architecture

### Architecture Frameworks

#### TOGAF (The Open Group Architecture Framework)

**Official Resources:**
- **TOGAF Website:** https://www.opengroup.org/togaf
- **TOGAF Standard:** https://pubs.opengroup.org/architecture/togaf9-doc/arch/

**Key Components:**
- Architecture Development Method (ADM)
- Architecture Content Framework
- Enterprise Continuum
- Architecture Capability Framework

#### SABSA (Sherwood Applied Business Security Architecture)

**Official Resources:**
- **SABSA Website:** https://sabsa.org/
- **SABSA White Papers:** https://sabsa.org/sabsa-executive-summary/

**Key Concepts:**
- Business-driven approach to security architecture
- Six-layer model (Contextual, Conceptual, Logical, Physical, Component, Operational)
- Risk-driven architecture

#### NIST Enterprise Architecture Model

**Official Resources:**
- **NIST SP 800-160:** Systems Security Engineering
- **NIST Cybersecurity Framework:** https://www.nist.gov/cyberframework

### Zero Trust Architecture (ZTA)

**Official Resources:**
- **NIST SP 800-207:** Zero Trust Architecture
- **CISA Zero Trust Maturity Model:** https://www.cisa.gov/zero-trust-maturity-model

**Key Principles:**
1. Verify explicitly
2. Use least privilege access
3. Assume breach

**Core Components:**
- Policy Engine
- Policy Administrator
- Policy Enforcement Point

**Implementation Approaches:**
- Enhanced Identity Governance
- Micro-segmentation
- Network Infrastructure and Software Defined Perimeter

### Recommended Reading

- **"Zero Trust Networks" by Evan Gilman and Doug Barth**
- **"The Cybersecurity Architect's Handbook" by Lester Nichols**
- **"Enterprise Security Architecture" by Nicholas A. Sherwood**

---

## 3.2 Cloud Security Strategy

### Cloud Service Models

| Model | Provider Manages | Customer Manages |
|-------|------------------|------------------|
| **IaaS** | Physical infrastructure, virtualization | OS, middleware, runtime, data, applications |
| **PaaS** | Physical infrastructure, virtualization, OS, middleware, runtime | Data, applications |
| **SaaS** | Everything except data | Data (and some configurations) |

### Cloud Security Frameworks

#### AWS Security

**Official Resources:**
- **AWS Security Hub:** https://aws.amazon.com/security-hub/
- **AWS Well-Architected Framework:** https://aws.amazon.com/architecture/well-architected/
- **AWS Security Best Practices:** https://aws.amazon.com/security/best-practices/

**Key Services:**
- IAM (Identity and Access Management)
- GuardDuty (Threat Detection)
- CloudTrail (Logging and Monitoring)
- KMS (Key Management Service)
- Security Groups and NACLs

#### Azure Security

**Official Resources:**
- **Azure Security Center:** https://azure.microsoft.com/en-us/services/security-center/
- **Azure Security Documentation:** https://docs.microsoft.com/en-us/azure/security/

**Key Services:**
- Azure Active Directory
- Azure Security Center
- Azure Sentinel (SIEM)
- Azure Key Vault
- Network Security Groups

#### Google Cloud Security

**Official Resources:**
- **Google Cloud Security:** https://cloud.google.com/security
- **Google Cloud Security Command Center:** https://cloud.google.com/security-command-center

**Key Services:**
- Cloud Identity and Access Management
- Cloud Security Command Center
- Cloud Armor (DDoS Protection)
- Cloud KMS
- VPC Service Controls

### Cloud Security Standards

- **CSA Cloud Controls Matrix (CCM):** https://cloudsecurityalliance.org/
- **ISO 27017:** Cloud Security Controls
- **ISO 27018:** Protection of PII in Public Clouds
- **FedRAMP:** Federal Risk and Authorization Management Program

### Cloud Security Tools

- **CloudSploit:** Open-source cloud security scanning
- **Prowler:** AWS security assessment tool
- **ScoutSuite:** Multi-cloud security auditing tool
- **Cloud Custodian:** Cloud governance tool

### Recommended Reading

- **"Cloud Security and Privacy" by Tim Mather, Subra Kumaraswamy, and Shahed Latif**
- **"Architecting the Cloud" by Michael J. Kavis**

---

## 3.3 Vendor and Technology Management

### Third-Party Risk Assessment (TPRA)

**Key Assessment Areas:**
1. Information Security Policies and Procedures
2. Access Control and Identity Management
3. Data Protection and Encryption
4. Incident Response and Business Continuity
5. Compliance and Regulatory Adherence
6. Physical Security
7. Personnel Security
8. Network Security
9. Application Security
10. Vendor Management

### Vendor Assessment Frameworks

- **SIG (Standardized Information Gathering):** https://sharedassessments.org/
- **CAIQ (Consensus Assessments Initiative Questionnaire):** https://cloudsecurityalliance.org/
- **NIST SP 800-161:** Supply Chain Risk Management

### Vendor Management Tools

- **OneTrust:** Vendor risk management platform
- **BitSight:** Security ratings platform
- **SecurityScorecard:** Security ratings and continuous monitoring
- **RiskRecon:** Third-party cyber risk management

### RFP (Request for Proposal) Security Requirements

**Essential Security Requirements:**
1. Data encryption (at rest and in transit)
2. Access control and authentication
3. Audit logging and monitoring
4. Incident response procedures
5. Business continuity and disaster recovery
6. Compliance certifications (ISO 27001, SOC 2, etc.)
7. Data residency and sovereignty
8. Right to audit
9. Breach notification procedures
10. Data deletion and retention policies

### Contract Security Clauses

- **Data Protection Addendum (DPA)**
- **Service Level Agreement (SLA)**
- **Liability and Indemnification**
- **Audit Rights**
- **Termination and Data Return**

---

## 3.4 Incident Response and BCP Consulting

### Incident Response Frameworks

#### NIST SP 800-61: Computer Security Incident Handling Guide

**Incident Response Lifecycle:**
1. Preparation
2. Detection and Analysis
3. Containment, Eradication, and Recovery
4. Post-Incident Activity

**Official Resource:** https://csrc.nist.gov/publications/detail/sp/800-61/rev-2/final

#### SANS Incident Response Process

**Six Steps:**
1. Preparation
2. Identification
3. Containment
4. Eradication
5. Recovery
6. Lessons Learned

**Official Resource:** https://www.sans.org/

### Incident Response Tools

- **TheHive:** Incident response platform
- **MISP (Malware Information Sharing Platform):** Threat intelligence platform
- **GRR (Google Rapid Response):** Incident response framework
- **Velociraptor:** Endpoint visibility and collection tool

### Incident Classification

| Severity | Description | Response Time |
|----------|-------------|---------------|
| **Critical** | Significant business impact, widespread data breach | Immediate (< 1 hour) |
| **High** | Moderate business impact, limited data breach | < 4 hours |
| **Medium** | Minor business impact, no data breach | < 24 hours |
| **Low** | Minimal business impact, informational | < 72 hours |

### Business Continuity Planning (BCP)

#### ISO 22301: Business Continuity Management

**Official Resource:** https://www.iso.org/standard/75106.html

**Key Components:**
- Business Impact Analysis (BIA)
- Risk Assessment
- Business Continuity Strategy
- Business Continuity Plans
- Testing and Exercising
- Maintenance and Review

### Disaster Recovery Planning (DRP)

**Key Metrics:**
- **RTO (Recovery Time Objective):** Maximum acceptable time to restore a system
- **RPO (Recovery Point Objective):** Maximum acceptable amount of data loss
- **MTTR (Mean Time to Repair):** Average time to repair a system
- **MTBF (Mean Time Between Failures):** Average time between system failures

### Tabletop Exercise Scenarios

1. **Ransomware Attack:** Critical systems encrypted, ransom demanded
2. **Data Breach:** Customer data exfiltrated by external attacker
3. **Insider Threat:** Employee intentionally sabotages systems
4. **DDoS Attack:** Website and services unavailable due to distributed attack
5. **Supply Chain Compromise:** Third-party vendor compromised, affecting your systems
6. **Natural Disaster:** Data center destroyed by fire/flood/earthquake

### Recommended Reading

- **"The Cybersecurity Playbook" by Allison Cerra**
- **"Incident Response & Computer Forensics" by Jason T. Luttgens, Matthew Pepe, and Kevin Mandia**
- **"Business Continuity Planning" by Kenneth N. Myers**

---

## Security Architecture Patterns

### Defense in Depth

Multiple layers of security controls to protect assets.

**Layers:**
1. Physical Security
2. Network Security
3. Host Security
4. Application Security
5. Data Security

### Least Privilege

Users and systems should have only the minimum access necessary to perform their functions.

### Separation of Duties

Critical functions should be divided among multiple people to prevent fraud and error.

### Fail Secure

Systems should fail in a secure state rather than an insecure state.

---

## Professional Development

### Certifications

- **CCSP (Certified Cloud Security Professional):** https://www.isc2.org/Certifications/CCSP
- **AWS Certified Security - Specialty:** https://aws.amazon.com/certification/
- **Azure Security Engineer Associate:** https://docs.microsoft.com/en-us/learn/certifications/
- **GCIH (GIAC Certified Incident Handler):** https://www.giac.org/

### Professional Organizations

- **Cloud Security Alliance (CSA):** https://cloudsecurityalliance.org/
- **FIRST (Forum of Incident Response and Security Teams):** https://www.first.org/

---

## Glossary

- **BCP (Business Continuity Plan):** A plan for maintaining business operations during and after a disruption
- **DRP (Disaster Recovery Plan):** A plan for recovering IT systems after a disaster
- **IRP (Incident Response Plan):** A plan for responding to security incidents
- **MTBF (Mean Time Between Failures):** Average time between system failures
- **MTTR (Mean Time to Repair):** Average time to repair a system
- **RPO (Recovery Point Objective):** Maximum acceptable amount of data loss
- **RTO (Recovery Time Objective):** Maximum acceptable time to restore a system
- **TPRA (Third-Party Risk Assessment):** Assessment of risks associated with third-party vendors
- **ZTA (Zero Trust Architecture):** Security model based on "never trust, always verify"

---

**Last Updated:** December 2025

**Version:** 1.0
