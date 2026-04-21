# SecureSupply Corp — Vendor Risk Management Project

![Framework](https://img.shields.io/badge/Framework-Vendor%20Risk%20Management-blue)
![Standard](https://img.shields.io/badge/Standard-NIST%20800--161%20%7C%20ISO%2027001-purple)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Organisation](https://img.shields.io/badge/Organisation-SecureSupply%20Corp-orange)
![Sector](https://img.shields.io/badge/Sector-Financial%20Services-teal)

---

## About This Project

This project demonstrates a comprehensive **Vendor Risk Management
(VRM) programme** for SecureSupply Corp — a fictional financial
services company that relies on 40 third-party vendors for critical
business operations.

The project covers the full vendor risk lifecycle: vendor inventory,
risk tiering, due diligence questionnaires, contract requirements,
ongoing monitoring, and off-boarding. It references NIST SP 800-161
(Supply Chain Risk Management) and ISO 27001:2022 Annex A controls
5.19 through 5.22.

> All names, data, and scenarios are fictional. Created for portfolio
> and learning purposes only.

---

## About SecureSupply Corp

SecureSupply Corp is a fictional mid-sized financial services company
providing investment management and financial advisory services to
retail and institutional clients. It processes sensitive financial
data and personally identifiable information for approximately
50,000 clients.

| Field | Value |
|-------|-------|
| Organisation | SecureSupply Corp |
| Sector | Financial services — investment management |
| Location | New York, NY (fictional) |
| Employees | 300 |
| Clients | 50,000 retail and institutional |
| Data | Financial records, PII, investment portfolios |
| Regulation | SEC, FINRA, GLBA, SOX (US financial services) |
| Total Vendors | 40 third-party suppliers |
| Critical Vendors | 8 tier-1 vendors |

---

## Why Vendor Risk Management Matters

Most major security breaches in recent years originated through
a third-party vendor rather than a direct attack. Examples include:

- A payroll vendor being compromised giving attackers access to
  employee data
- A cloud storage vendor misconfiguring a bucket exposing client files
- A software vendor pushing a malicious update through the supply chain

SecureSupply Corp cannot fully control how its vendors protect the
data they handle. But it can assess vendor security posture, require
contractual security obligations, and monitor for changes in risk.

---

## Project Documents

| File | Description |
|------|-------------|
| `README.md` | This file — programme overview |
| `vendor-inventory.md` | Complete inventory of all 40 vendors with risk tiers |
| `risk-tiering-methodology.md` | How vendors are classified into tiers 1-3 |
| `due-diligence-questionnaire.md` | Security questionnaire sent to all vendors |
| `tier1-assessments/README.md` | Detailed assessments for the 8 critical vendors |
| `contract-security-requirements.md` | Minimum security clauses for all vendor contracts |
| `ongoing-monitoring-programme.md` | How vendor risk is tracked continuously |
| `vendor-incident-response.md` | What to do when a vendor has a security incident |
| `offboarding-checklist.md` | Secure vendor off-boarding process |

---

## Vendor Risk Tiering

SecureSupply Corp classifies all vendors into three risk tiers
based on their access to systems and data.

| Tier | Label | Definition | Examples | Assessment Required |
|------|-------|-----------|----------|---------------------|
| Tier 1 | Critical | Has direct access to client financial data or core systems | Cloud hosting, core banking system, data analytics platform | Full due diligence + annual reassessment |
| Tier 2 | Important | Has access to internal systems but not directly to client data | HR system, email provider, legal software | Standard questionnaire + biennial review |
| Tier 3 | Standard | No access to sensitive data or systems | Office supplies, catering, general contractors | Basic contract review only |

---

## Vendor Inventory Summary

| Tier | Count | Examples |
|------|-------|---------|
| Tier 1 — Critical | 8 | CloudBase (hosting), DataStream (analytics), PaySecure (payments) |
| Tier 2 — Important | 18 | HR platform, email provider, legal research tool, video conferencing |
| Tier 3 — Standard | 14 | Office supplies, facilities management, cleaning services |
| **Total** | **40** | |

---

## Due Diligence Assessment Summary

All Tier 1 and Tier 2 vendors complete a security questionnaire.
Results from the most recent assessment cycle:

| Vendor | Tier | Risk Score | Finding | Action Required |
|--------|------|-----------|---------|----------------|
| CloudBase Inc | 1 | 88/100 | Strong controls. Minor gap in DR testing. | Request DR test evidence |
| DataStream Analytics | 1 | 74/100 | No formal pen test conducted in 18 months | Require pen test within 90 days |
| PaySecure Ltd | 1 | 91/100 | PCI DSS certified. Strong controls. | No action — annual review |
| TalentHub HR | 2 | 65/100 | MFA not enforced for all staff | Require MFA within 60 days |
| GlobalMail Pro | 2 | 79/100 | SPF/DKIM configured. DMARC missing | Require DMARC within 30 days |
| LegalResearch Co | 2 | 82/100 | Strong access controls. Minor logging gaps | Recommend logging improvement |
| ConnectMeet Video | 2 | 71/100 | End-to-end encryption not enabled by default | Require E2E encryption for financial calls |
| InfraWatch Monitor | 1 | 85/100 | SOC 2 Type II certified. Good controls. | No action — annual review |

---

## Key Programme Metrics — Year One

| Metric | Value |
|--------|-------|
| Total vendors inventoried | 40 |
| Tier 1 vendors assessed | 8 of 8 (100%) |
| Tier 2 vendors assessed | 15 of 18 (83%) |
| Vendors with findings | 6 |
| Critical findings resolved | 4 of 4 (100%) |
| Vendors with signed security addendum | 26 of 26 Tier 1 and 2 (100%) |
| New vendors onboarded with VRM process | 5 |
| Vendors off-boarded securely | 3 |

---

## Interview Talking Points

When asked about vendor risk management in interviews, this project
lets you say:

- You built a vendor inventory and classified 40 vendors into three
  risk tiers based on data access and criticality
- You designed a due diligence questionnaire and conducted assessments
  of all critical and important vendors
- You identified vendors with security gaps and tracked remediation
- You wrote contract security requirements including right-to-audit
  clauses and breach notification obligations
- You designed an ongoing monitoring programme including annual
  reassessments and event-triggered reviews

---

## Document Version History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | 2025 | Portfolio Author | Initial VRM programme completed |

---

*This document is part of a GRC portfolio project. All names,
data, and scenarios are fictional and used for learning and
career development purposes only.*


