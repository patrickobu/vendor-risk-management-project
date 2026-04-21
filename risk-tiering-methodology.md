# Risk Tiering Methodology

**Organisation:** SecureSupply Corp
**Document:** Vendor Risk Tiering Methodology
**Framework:** NIST SP 800-161 Supply Chain Risk Management
**Version:** 1.0
**Date:** 2025

---

## Purpose

This document explains exactly how SecureSupply Corp decides which
risk tier to assign to each vendor. Every vendor must be assigned
a tier before they can be onboarded. The tier determines how much
due diligence is required and how frequently the vendor is reviewed.

---

## The Three Tiers Explained

### Tier 1 — Critical Vendors

A vendor is Tier 1 if ANY of the following are true:

- The vendor stores, processes, or transmits client financial data
- The vendor has direct access to SecureSupply's core banking or
  trading systems
- Loss of the vendor's service would cause SecureSupply to be
  unable to serve clients for more than 4 hours
- The vendor has privileged access to SecureSupply's IT infrastructure
- A security incident at the vendor could directly cause a
  regulatory breach for SecureSupply
- The vendor processes personally identifiable information (PII)
  for more than 1,000 clients

**Assessment required:** Full due diligence questionnaire plus
evidence review. Annual reassessment. Right-to-audit clause mandatory
in contract. Senior management sign-off required for onboarding.

---

### Tier 2 — Important Vendors

A vendor is Tier 2 if ANY of the following are true AND they do
not qualify as Tier 1:

- The vendor has access to SecureSupply's internal systems or
  networks but not to client data directly
- The vendor processes employee personal data
- Loss of the vendor's service would cause significant operational
  disruption for SecureSupply
- The vendor stores internal SecureSupply documents or communications
- The vendor has remote access to SecureSupply systems for support

**Assessment required:** Standard due diligence questionnaire.
Biennial reassessment. Security addendum required in contract.
IT Security team sign-off required for onboarding.

---

### Tier 3 — Standard Vendors

A vendor is Tier 3 if ALL of the following are true:

- The vendor has no access to SecureSupply IT systems
- The vendor does not handle any client or employee personal data
- Loss of the vendor's service would not affect SecureSupply's
  ability to serve clients
- The vendor provides purely physical or commodity services

**Assessment required:** Basic contract review only. No questionnaire.
No regular reassessment unless vendor scope changes. Procurement
team sign-off sufficient for onboarding.

---

## Tiering Decision Flowchart

Use the following questions in order to assign a tier:

```
Question 1: Does the vendor access client financial data or PII?
YES → TIER 1

Question 2: Does the vendor have access to core systems or
            privileged IT access?
YES → TIER 1

Question 3: Would losing this vendor stop us serving clients
            for more than 4 hours?
YES → TIER 1

Question 4: Does the vendor access any internal SecureSupply
            systems or employee data?
YES → TIER 2

Question 5: Would losing this vendor cause significant internal
            operational disruption?
YES → TIER 2

If none of the above → TIER 3
```

---

## Tiering Review Triggers

A vendor's tier must be reviewed immediately when any of the
following occur:

| Trigger | Action |
|---------|--------|
| Vendor expands scope of services | Re-run tiering assessment — may move up a tier |
| Vendor reduces scope of services | Re-run tiering assessment — may move down a tier |
| Vendor is acquired by another company | Reassess immediately — new parent company ownership risk |
| Vendor suffers a security breach | Reassess tier and increase monitoring frequency |
| Vendor loses a key security certification | Reassess tier and require corrective action |
| New regulation affects data vendor handles | Reassess tier against new regulatory requirements |

---

## Tiering Approval Process

| Tier | Who Assigns | Who Approves |
|------|------------|-------------|
| Tier 1 | Vendor Risk Manager | CISO and CFO |
| Tier 2 | Vendor Risk Manager | CISO |
| Tier 3 | Procurement Team | Procurement Manager |

All tier assignments must be recorded in the vendor inventory
within 5 business days of the decision.

---

## Current Tier Distribution

| Tier | Count | Percentage |
|------|-------|-----------|
| Tier 1 — Critical | 8 | 20% |
| Tier 2 — Important | 18 | 45% |
| Tier 3 — Standard | 14 | 35% |
| Total | 40 | 100% |

---

*This document is part of a GRC portfolio project. All names,
data, and scenarios are fictional and used for learning and
career development purposes only.*

