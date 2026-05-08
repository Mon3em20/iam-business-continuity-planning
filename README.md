# IAM Business Continuity & Risk Management

## Overview

This project presents a comprehensive Business Continuity, Disaster Recovery, and Risk Management plan for an Identity and Access Management (IAM) environment using the NIST SP 800-30 framework.

The project focuses on securing and maintaining the availability of enterprise authentication infrastructure based on Active Directory and Azure Active Directory concepts.

The assessment includes:
- Risk Assessment
- Business Impact Analysis (BIA)
- Recovery Objectives
- Backup Strategy
- RAID Design
- High Availability Architecture
- Disaster Recovery Planning
- IAM Continuity Strategy

---

# Objectives

- Analyze risks affecting enterprise IAM infrastructure
- Evaluate business impact of IAM service disruption
- Define recovery objectives and continuity requirements
- Design resilient backup and failover strategies
- Build high-availability Active Directory architecture
- Improve organizational resilience against outages and security incidents

---

# Topics Covered

## Risk Management
- NIST SP 800-30
- Risk Register Development
- Likelihood & Impact Analysis
- Risk Classification Matrix
- Risk Treatment Strategies

## Business Continuity
- Business Impact Analysis (BIA)
- Recovery Time Objective (RTO)
- Recovery Point Objective (RPO)
- Work Recovery Time (WRT)
- Maximum Tolerable Downtime (MTD)

## IAM & Infrastructure Security
- Active Directory Architecture
- Azure AD Concepts
- RBAC
- MFA
- PAM Concepts
- Kerberos & LDAP
- Authentication Logging

## Recovery & Resilience
- Backup Strategy
- Incremental vs Full Backups
- RAID 1 & RAID 6
- Multi-Domain Controller Architecture
- Failover & Replication
- Warm Recovery Site Design

---

# Architecture Highlights

The proposed architecture includes:

- Primary and Secondary Domain Controllers
- DNS Round-Robin Distribution
- RAID-Protected Storage
- Backup Server Infrastructure
- Offsite & Cloud Backup Replication
- Warm Recovery Site
- WAN + VPN Recovery Connectivity

Architecture diagrams are included in the repository.

---

# Key Findings

- IAM infrastructure represents a critical single point of failure in enterprise environments.
- Multi-layer recovery strategies significantly improve resilience and availability.
- High availability and failover planning are essential for minimizing operational disruption.
- Backup and RAID serve different but complementary security and continuity purposes.
- Business continuity metrics must align with operational and security priorities.

---

# Skills Demonstrated

- Risk Assessment
- Business Continuity Planning
- Disaster Recovery Planning
- Infrastructure Security
- IAM Architecture
- Active Directory Concepts
- Enterprise Security Design
- Technical Documentation
- Security Governance

---

# Repository Contents

- Full technical report
- Risk assessment framework
- BIA analysis
- Recovery planning documentation
- Architecture diagrams
- Backup and RAID strategy
- Recovery timeline design

---

# Lessons Learned

- IAM systems are mission-critical infrastructure components that require strong continuity planning.
- Recovery objectives must align with operational and business requirements.
- Defense-in-depth strategies improve both resilience and recovery capability.
- Backup, redundancy, and failover mechanisms must work together to reduce organizational risk.

---

# Disclaimer

This project was developed for educational and cybersecurity learning purposes using enterprise IAM architecture concepts and industry-standard security frameworks.