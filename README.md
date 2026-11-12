# Third-Party Risk Management (TPRM) & GRC Portfolio

End-to-end vendor risk assessments, control gap analyses, and remediation workflows executed in **ServiceNow Vendor Risk Management (VRM)** and aligned with **ISO/IEC 27001**, **SOC 2 Type II**, **HIPAA**, and **UK GDPR**.

---

## Featured Case Studies

### 1. Ridgeline Care — Ambient AI Clinical Documentation Onboarding
* **Workpaper:** [`Ridgeline Care Rapid Onboarding.pdf`](./Ridgeline%20Care%20Rapid%20Onboarding.pdf)
* **Scope & Criticality:** Tier 1 (Very High) SaaS/AI vendor processing ~240,000 patient records with bidirectional FHIR write access into production EHR ($410,000/year).
* **Key Risk Findings & Mitigations:**
  * Logged High-priority issue (`VRI0003008`) for missing Multi-Factor Authentication (MFA) on vendor administrator accounts.
  * Enforced pre-go-live remediation gating (`VRT0003002`), restricted Phase 1 rollout to 2 outpatient clinics (40 clinicians), and secured $10M cyber liability indemnification.
  * Executed formal residual risk override (`3 - Moderate`) on assessment `VRA0003005` with CMIO, DPO, and CSO sign-offs, and scheduled 12-month recurring oversight (`VRR0002001`).

### 2. Acme Cloud Inc. — Global Cloud Payroll Migration
* **Workpaper:** [`Acme Cloud Payroll Review.pdf`](./Acme%20Cloud%20Payroll%20Review.pdf)
* **Scope & Criticality:** Tier 1 (Very High) payroll platform handling PII, Tax IDs, and direct deposit banking details for 3,200 US/UK employees ($432,000 TCV).
* **Key Risk Findings & Mitigations:**
  * Remediated Critical finding (`VRI0003002`) for unenforced MFA across 14 privileged admin accounts via conditional access verification (`VRT0003001`) and internal dual-approval controls.
  * Contractually enforced delivery of an updated CREST-accredited penetration test within 30 days post-cutover (`VRI0003004`) and redlined DPA subprocessor notice from 14 to 30 days (`VRI0003005`).
  * Closed master assessment (`VRA0003002`) at `3 - Moderate` residual risk under Conditional Approval.

---

## Core Tools & Frameworks Demonstrated
* **GRC Platform:** ServiceNow VRM (`core_company`, `sn_vdr_risk_asmt_engagement`, `sn_vdr_risk_asmt`, `sn_vdr_risk_asmt_issue`, `sn_vdr_risk_asmt_task`, repeating assessment rules)
* **Standards & Regulations:** ISO/IEC 27001:2022, SOC 1 & SOC 2 Type II, HIPAA BAA, UK GDPR Article 9, NIST TPRM Lifecycle
