# Vendor Inventory

**Organisation:** SecureSupply Corp
**Document:** Complete Vendor Inventory and Risk Tier Assignments
**Version:** 1.0
**Date:** 2025

---

## Purpose

This document records every third-party vendor used by SecureSupply
Corp, assigns a risk tier to each one, and records the last
assessment date and current status.

---

## Tier 1 — Critical Vendors (8)

These vendors have direct access to client financial data, core
systems, or provide services that would cause significant harm
if unavailable.

| # | Vendor | Service | Data Accessed | Last Assessment | Next Due | Status |
|---|--------|---------|--------------|----------------|---------|--------|
| 1 | CloudBase Inc | Cloud infrastructure hosting | All client data, core systems | Q1 2025 | Q1 2026 | ACTIVE |
| 2 | DataStream Analytics | Data analytics platform | Client portfolio data, transaction history | Q1 2025 | Q1 2026 | FINDING — pen test required |
| 3 | PaySecure Ltd | Payment processing | Client payment data, account numbers | Q1 2025 | Q1 2026 | ACTIVE |
| 4 | CoreBank Systems | Core banking platform | All financial transactions | Q1 2025 | Q1 2026 | ACTIVE |
| 5 | InfraWatch Monitor | Infrastructure monitoring | System logs, performance data | Q2 2025 | Q2 2026 | ACTIVE |
| 6 | BackupVault Co | Disaster recovery and backup | Full data backups including client data | Q2 2025 | Q2 2026 | ACTIVE |
| 7 | CyberShield MDR | Managed detection and response | Security logs, network traffic | Q2 2025 | Q2 2026 | ACTIVE |
| 8 | ComplianceTrack | Regulatory reporting platform | Client and transaction data for reports | Q3 2025 | Q3 2026 | ACTIVE |

---

## Tier 2 — Important Vendors (18)

These vendors have access to internal systems but not directly
to client financial data.

| # | Vendor | Service | Data Accessed | Last Assessment | Status |
|---|--------|---------|--------------|----------------|--------|
| 1 | TalentHub HR | HR and payroll system | Employee data | Q1 2025 | FINDING — MFA required |
| 2 | GlobalMail Pro | Email platform | Internal communications | Q1 2025 | FINDING — DMARC required |
| 3 | LegalResearch Co | Legal research platform | Internal legal documents | Q2 2025 | ACTIVE |
| 4 | ConnectMeet Video | Video conferencing | Meeting recordings | Q2 2025 | FINDING — E2E encryption |
| 5 | DocuSign Pro | Electronic signatures | Signed client contracts | Q2 2025 | ACTIVE |
| 6 | TrackIT Asset | IT asset management | Hardware and software inventory | Q2 2025 | ACTIVE |
| 7 | HelpDesk Pro | IT helpdesk ticketing | IT support tickets, some employee data | Q3 2025 | ACTIVE |
| 8 | AuditLog Systems | Audit log storage | Security and system logs | Q3 2025 | ACTIVE |
| 9 | TravelBook Corp | Business travel management | Employee travel and expense data | Q3 2025 | ACTIVE |
| 10 | TrainSmart LMS | Security training platform | Employee training records | Q3 2025 | ACTIVE |
| 11 | PrintSecure | Managed print services | Documents sent to print | Not yet assessed | DUE |
| 12 | OfficeCloud | Productivity suite | Internal documents and emails | Not yet assessed | DUE |
| 13 | PhoneSystem Pro | VoIP phone system | Call logs, voicemails | Not yet assessed | DUE |
| 14 | NetMonitor Co | Network monitoring | Network traffic metadata | Q4 2025 | ACTIVE |
| 15 | PatchMaster | Patch management | Software versions, vulnerabilities | Q4 2025 | ACTIVE |
| 16 | VaultKey PAM | Privileged access management | Admin credentials management | Q1 2025 | ACTIVE |
| 17 | ScanPro Vuln | Vulnerability scanning | System vulnerabilities | Q1 2025 | ACTIVE |
| 18 | DLP Guardian | Data loss prevention | All outbound data flows | Q2 2025 | ACTIVE |

---

## Tier 3 — Standard Vendors (14)

These vendors have no access to sensitive systems or client data.
Only basic contract review required.

| # | Vendor | Service |
|---|--------|---------|
| 1 | OfficeStock | Office supplies |
| 2 | CleanPro Services | Office cleaning |
| 3 | FreshBrew Catering | Office catering |
| 4 | FixIt Maintenance | Building maintenance |
| 5 | CargoSwift | Courier and post |
| 6 | GreenGrow Plants | Office plants |
| 7 | ParkSecure | Car park management |
| 8 | PrintBrand | Business card and stationery printing |
| 9 | ShredDoc | Document shredding |
| 10 | PowerSave Utilities | Electricity and gas |
| 11 | AquaPure | Water and refreshments |
| 12 | SafeGuard Security | Physical security guards |
| 13 | HealthFirst | Employee health and benefits |
| 14 | TravelInsure | Corporate travel insurance |

---

## Vendors with Open Findings

| Vendor | Tier | Finding | Severity | Owner | Due Date | Status |
|--------|------|---------|---------|-------|---------|--------|
| DataStream Analytics | 1 | No penetration test in 18 months | HIGH | Vendor Manager | 90 days | Chasing vendor |
| TalentHub HR | 2 | MFA not enforced for all staff | MODERATE | Vendor Manager | 60 days | Vendor committed |
| GlobalMail Pro | 2 | DMARC not configured | MODERATE | IT Security | 30 days | In progress |
| ConnectMeet Video | 2 | E2E encryption not default | MODERATE | Vendor Manager | 45 days | Vendor committed |

---

## Vendors Not Yet Assessed

Three Tier 2 vendors are overdue for their first assessment:

| Vendor | Tier | Reason for Delay | Target Assessment Date |
|--------|------|-----------------|----------------------|
| PrintSecure | 2 | New vendor added in Q3 | Q4 2025 |
| OfficeCloud | 2 | Assessment scheduled | Q4 2025 |
| PhoneSystem Pro | 2 | Contact made — awaiting response | Q4 2025 |

---

*This document is part of a GRC portfolio project. All names,
data, and scenarios are fictional and used for learning and
career development purposes only.*

