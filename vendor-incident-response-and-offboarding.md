# Vendor Incident Response Procedure

**Organisation:** SecureSupply Corp
**Document:** Vendor Security Incident Response Procedure
**Version:** 1.0
**Date:** 2025

---

## Purpose

This document defines exactly what SecureSupply Corp does when
a vendor suffers a security incident that could affect SecureSupply
data or operations.

---

## Incident Classification

| Level | Definition | Example |
|-------|-----------|---------|
| CRITICAL | Vendor breach confirmed — SecureSupply client data affected | Tier 1 vendor confirms client data exfiltrated |
| HIGH | Vendor breach suspected — SecureSupply data potentially at risk | Tier 1 vendor reports unauthorised access to systems |
| MODERATE | Vendor incident but data impact uncertain | Tier 2 vendor reports ransomware — extent unknown |
| LOW | Vendor incident with no SecureSupply data impact | Tier 3 vendor website defaced — no data access |

---

## Response Procedures by Level

### CRITICAL Incident Response

**Within 1 hour:**
- CISO notified immediately by Vendor Risk Manager
- CEO and Legal counsel notified
- Vendor access to SecureSupply systems suspended
- SecureSupply incident response plan activated

**Within 4 hours:**
- Written demand sent to vendor for full incident report
- Internal assessment of what client data may be affected
- Regulatory notification timeline assessed (GLBA, SEC requirements)
- Board notified

**Within 24 hours:**
- Determine if client notification is required
- Legal review of notification obligations
- Forensic review of vendor access logs requested

**Within 72 hours:**
- Regulatory notifications submitted if required
- Client notifications sent if required
- Alternative vendor activation considered

---

### HIGH Incident Response

**Within 2 hours:**
- CISO notified by Vendor Risk Manager
- Vendor contacted for immediate status update
- Vendor access reviewed — suspension considered

**Within 8 hours:**
- Written request sent to vendor for incident details
- Internal assessment of potential data exposure

**Within 48 hours:**
- Full vendor incident report received and reviewed
- Determine if escalation to CRITICAL is required
- Regulatory notification assessment completed

---

### MODERATE Incident Response

**Within 4 hours:**
- Vendor Risk Manager contacts vendor for status
- IT Security reviews vendor access logs

**Within 5 business days:**
- Vendor provides written incident report
- Impact assessment completed
- Determine if tier review is required

---

### LOW Incident Response

**Within 5 business days:**
- Vendor Risk Manager documents incident in vendor record
- Confirms no SecureSupply data was affected
- No further action required unless facts change

---

## Vendor Communication Templates

### Initial Contact Message

```
Subject: Security Incident Notification — Immediate Response Required

Dear [Vendor Contact Name],

SecureSupply Corp has been notified of / has become aware of a
potential security incident affecting your organisation.

As a vendor with access to SecureSupply systems and/or data we
require an immediate response to the following questions:

1. Please confirm whether this incident has affected any
   SecureSupply data or systems.

2. Please describe the nature and scope of the incident.

3. Please confirm what immediate containment steps have been taken.

4. Please provide a timeline for a full written incident report.

We require your response within [2/4/24] hours of this message.

[Vendor Risk Manager Name]
Vendor Risk Manager — SecureSupply Corp
```

---

## Post-Incident Review

Following every CRITICAL or HIGH incident the Vendor Risk Manager
must conduct a post-incident review within 30 days covering:

- What happened and what data was affected
- How quickly the vendor notified SecureSupply
- Whether contractual notification timelines were met
- Whether the vendor's response was adequate
- Whether the vendor's tier should be reviewed
- Whether the contract should be renewed or terminated
- Lessons learned for the VRM programme

---

---

# Vendor Off-Boarding Checklist

**Organisation:** SecureSupply Corp
**Document:** Secure Vendor Off-Boarding Checklist
**Version:** 1.0
**Date:** 2025

---

## Purpose

When a vendor relationship ends it is critical to ensure that
all access is revoked and all SecureSupply data is returned or
securely destroyed. A poorly managed off-boarding can leave
SecureSupply data in the hands of a former vendor indefinitely.

---

## Off-Boarding Checklist

Complete every item on this checklist before marking a vendor
as off-boarded. Each item must be signed off by the named owner.

### Step 1 — Notify the Vendor (Day 1)

- [ ] Written notice of contract termination sent to vendor
- [ ] Termination date confirmed in writing
- [ ] Vendor reminded of data return and destruction obligations
- [ ] Vendor account manager contact confirmed for off-boarding process
- [ ] Off-boarding timeline agreed with vendor

**Owner:** Vendor Risk Manager

---

### Step 2 — Access Revocation (By termination date)

- [ ] All vendor user accounts in SecureSupply systems identified
- [ ] All vendor user accounts deactivated on termination date
- [ ] All vendor API keys and integration tokens revoked
- [ ] All vendor VPN certificates revoked
- [ ] All vendor SSH keys removed from SecureSupply systems
- [ ] Vendor removed from all mailing lists and communication platforms
- [ ] Multi-factor authentication devices deregistered
- [ ] Vendor admin access to shared systems removed

**Owner:** IT Security Team

---

### Step 3 — Data Return or Destruction (Within 30 days)

- [ ] Formal written request sent to vendor to return or destroy all SecureSupply data
- [ ] Vendor has confirmed which data they hold
- [ ] Data return method agreed (secure file transfer or physical media)
- [ ] Data returned and confirmed received OR
- [ ] Vendor has confirmed secure destruction of all data
- [ ] Written certificate of data destruction received from vendor
- [ ] Certificate filed in vendor record

**Owner:** Vendor Risk Manager + IT Security

---

### Step 4 — Contract Closure

- [ ] Final invoice received and approved
- [ ] Any service credits or penalties settled
- [ ] Contract formally closed in contract management system
- [ ] Any SLAs or warranties confirmed as concluded
- [ ] Legal sign-off on contract closure received

**Owner:** Legal + Finance

---

### Step 5 — Vendor Record Update

- [ ] Vendor status updated to OFFBOARDED in vendor inventory
- [ ] Off-boarding date recorded
- [ ] Reason for off-boarding recorded
- [ ] All assessment records archived
- [ ] Data destruction certificate filed
- [ ] Vendor removed from monitoring schedule

**Owner:** Vendor Risk Manager

---

### Step 6 — Final Confirmation

- [ ] All checklist items above confirmed complete
- [ ] CISO sign-off obtained
- [ ] Off-boarding completion communicated to relevant business teams

**Owner:** CISO

---

## Completed Off-Boardings — Year One

| Vendor | Tier | Off-Boarded | Reason | Data Destroyed |
|--------|------|-------------|--------|----------------|
| OldSystem Legacy | 1 | Q1 2025 | Platform replacement | Confirmed — certificate filed |
| BasicAlert Monitor | 2 | Q2 2025 | Replaced by InfraWatch | Confirmed — certificate filed |
| SlowMail Email | 2 | Q3 2025 | Replaced by GlobalMail Pro | Confirmed — certificate filed |

---

*This document is part of a GRC portfolio project. All names,
data, and scenarios are fictional and used for learning and
career development purposes only.*

