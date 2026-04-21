# Ongoing Vendor Monitoring Programme

**Organisation:** SecureSupply Corp
**Document:** Ongoing Vendor Risk Monitoring Programme
**Version:** 1.0
**Date:** 2025

---

## Purpose

Onboarding a vendor and completing the initial due diligence is
not enough. Vendors change over time — they get acquired, suffer
breaches, lose certifications, or change how they handle data.

This document defines how SecureSupply Corp monitors all vendors
on an ongoing basis after they are onboarded.

---

## Monitoring Activities by Frequency

### Daily Monitoring (Automated)

| Activity | Tool | Applies To |
|----------|------|-----------|
| Dark web monitoring for vendor credential leaks | CyberShield MDR | Tier 1 only |
| News alerts for vendor security incidents | Google Alerts (automated) | Tier 1 and 2 |
| Vendor website availability monitoring | InfraWatch Monitor | Tier 1 only |

---

### Monthly Monitoring

| Activity | Owner | Applies To |
|----------|-------|-----------|
| Review any security alerts received about vendors | Vendor Risk Manager | All tiers |
| Check vendor certification status (ISO 27001, SOC 2) | Vendor Risk Manager | Tier 1 only |
| Review open findings from previous assessments | Vendor Risk Manager | Tier 1 and 2 |
| Check vendor has provided any required evidence | Vendor Risk Manager | Tier 1 |

---

### Quarterly Monitoring

| Activity | Owner | Applies To |
|----------|-------|-----------|
| Vendor risk register reviewed and updated | Vendor Risk Manager | All tiers |
| Open findings tracker reviewed with CISO | CISO | Tier 1 and 2 |
| Vendor performance scorecard produced | Vendor Risk Manager | Tier 1 |
| Any new vendors onboarded reviewed for correct tier | Vendor Risk Manager | All tiers |
| Any vendors off-boarded confirmed as complete | IT Security | All tiers |

---

### Annual Monitoring

| Activity | Owner | Applies To |
|----------|-------|-----------|
| Full due diligence reassessment questionnaire | Vendor Risk Manager | Tier 1 |
| Due diligence reassessment questionnaire | Vendor Risk Manager | Tier 2 (every 2 years) |
| Contract review — check security clauses still current | Legal + Vendor Risk | Tier 1 and 2 |
| Certification evidence collected and filed | Vendor Risk Manager | Tier 1 |
| Penetration test evidence collected and reviewed | IT Security | Tier 1 |
| Business continuity test evidence reviewed | IT Security | Tier 1 |
| Full vendor risk report presented to board | CISO | All tiers |

---

## Event-Triggered Monitoring

Some events require immediate review regardless of the
regular schedule:

| Trigger Event | Response Required | Timeframe |
|--------------|------------------|-----------|
| Vendor announces a data breach | Contact vendor for impact assessment. Review what SecureSupply data may be affected. Notify CISO within 2 hours. | Immediate |
| Vendor is acquired by another company | Reassess tier. Review new parent company. Confirm contractual obligations transfer. | Within 5 days |
| Vendor loses ISO 27001 or SOC 2 certification | Require explanation and remediation plan. Consider temporary suspension pending recertification. | Within 2 days |
| Vendor announces major change to service | Assess impact on data and systems. Re-run due diligence if significant change. | Within 5 days |
| Vendor enters financial difficulty | Activate contingency plans. Identify alternative vendors. Accelerate data retrieval. | Immediate |
| SecureSupply suffers an incident linked to a vendor | Suspend vendor access pending investigation. Full forensic review of vendor activity logs. | Immediate |
| Vendor fails to respond to questionnaire by deadline | Issue formal notice. Escalate to CISO. Consider suspension after 30 days. | Within 7 days |

---

## Vendor Performance Scorecard — Tier 1

Every quarter the Vendor Risk Manager produces a performance
scorecard for each Tier 1 vendor using the following metrics:

| Metric | Weight | How Measured |
|--------|--------|-------------|
| Security questionnaire score | 30% | Score from most recent DDQ |
| Outstanding findings | 20% | Number of open findings past due date |
| Incident history | 20% | Number and severity of incidents in past 12 months |
| Certification status | 15% | Valid ISO 27001 or SOC 2 — yes or no |
| Response time to requests | 15% | Average days to respond to Vendor Risk requests |

**Scorecard ratings:**

| Score | Rating | Action |
|-------|--------|--------|
| 85-100 | GREEN | No action required |
| 70-84 | AMBER | Formal improvement plan within 30 days |
| Below 70 | RED | Immediate escalation to CISO. Contract review triggered. |

---

## Current Vendor Monitoring Status

| Vendor | Tier | Scorecard | Open Findings | Next Review |
|--------|------|-----------|--------------|-------------|
| CloudBase Inc | 1 | GREEN (88) | 1 Low | Q1 2026 |
| DataStream Analytics | 1 | AMBER (74) | 1 High | Q4 2025 |
| PaySecure Ltd | 1 | GREEN (91) | 0 | Q1 2026 |
| CoreBank Systems | 1 | GREEN (86) | 0 | Q1 2026 |
| InfraWatch Monitor | 1 | GREEN (85) | 0 | Q2 2026 |
| BackupVault Co | 1 | GREEN (83) | 0 | Q2 2026 |
| CyberShield MDR | 1 | GREEN (89) | 0 | Q2 2026 |
| ComplianceTrack | 1 | GREEN (82) | 0 | Q3 2026 |

---

*This document is part of a GRC portfolio project. All names,
data, and scenarios are fictional and used for learning and
career development purposes only.*

