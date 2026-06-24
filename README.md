# 🏥 CareShield: NHS Nursing Staff Cybersecurity Awareness Campaign

![Python](https://img.shields.io/badge/Domain-Usable_Security-blue?style=for-the-badge)
![ISO 27001](https://img.shields.io/badge/ISO%2FIEC_27001%3A2022-Annex_A.6.3-0052CC?style=for-the-badge)
![NIST](https://img.shields.io/badge/NIST_SP_800--50_Rev.1-Tier_2_Training-009688?style=for-the-badge)
![WCAG](https://img.shields.io/badge/WCAG_2.1-AA_Compliant-4CAF50?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📌 Project Overview

CareShield is a **mobile-optimised, branching scenario e-learning campaign** designed specifically for nursing staff at a fictional Royal Hospital (RH). It addresses the structural gap between clinical workflow demands and security control design, which is the root cause of security workarounds in healthcare environments.

- ✅ **User group analysis** grounded in usable security literature (Sasse, Koppel, Beautement)
- ✅ **Four-episode branching scenario module** built in Twine/Harlowe, exportable as standalone HTML
- ✅ **Root cause mapping** aligned to the NCSC/ENISA Cyber Security Culture Framework
- ✅ **Measurable outcomes framework** following NIST SP 800-50 Rev. 1 programme lifecycle
- ✅ **Report Friction pathway,** a two-way mechanism letting nurses log usability barriers to IT
- ✅ **Critical reflection** covering trade-off decisions, design alternatives, and ethical considerations

> 📄 **[Download the full project portfolio document →](./CareShield_Personal_Project_Toochukwu_Praise_Ajoku.pdf)**

---

## 🧠 Problem Statement

Nurses represent one of the highest-risk user groups in healthcare cybersecurity, not because of indifference, but because of **structural incompatibility** between clinical workflow and security control design. Three convergent risk factors drive this:

1. **Breadth of system access** — multiple independent clinical systems requiring separate authentication
2. **Operational time pressure** — session timeouts and MFA steps interrupt patient care
3. **Compliance budget exhaustion** — repeated demands cause behavioural disengagement, not malice (Beautement et al., 2008)

The WannaCry attack (2017), which disabled 80 NHS trusts — originated from poor access hygiene, not sophisticated exploitation. Generic annual e-learning does not meet ISO/IEC 27001:2022 Annex A.6.3 or NIST SP 800-50 Rev. 1 Tier 2 requirements for high-risk operational staff.

---

## 🗂️ Project Structure

```
careshield-awareness-campaign/
│
├── README.md
├── CareShield_Personal_Project_Toochukwu_Praise_Ajoku.pdf   ← Full portfolio document
│
└── screenshots/
    ├── 01_careshield_start_screen.png
    ├── 02_episode1_handover_decision.png
    ├── 03_episode1_consequence_shared_credentials.png
    ├── 04_episode1_correct_emergency_override.png
    ├── 05_episode2_nhs_email_decision.png
    └── 06_completion_screen_report_friction.png
```

---

## ⚙️ Framework & Standards Applied

| Standard / Framework | Application |
|---|---|
| **ISO/IEC 27001:2022 Annex A.6.3** | Mandatory role-based awareness training |
| **NIST SP 800-50 Rev. 1** | Tier 2 role-based training programme lifecycle |
| **NIST SP 800-53 Rev. 5 (AT-2, AT-3)** | Frequency and role alignment for training controls |
| **NCSC/ENISA Cyber Security Culture Framework** | Root cause mapping to campaign components |
| **UK GDPR / DPA 2018** | Data minimisation, episode 3 scenario content |
| **WCAG 2.1 AA** | Accessibility compliance for NHS module deployment |

---

## 🎯 Part 1: User Group Analysis & Security Challenges

### Security Controls, Friction & Workarounds

| Security Control | Usability Friction | Workaround | Organisational Risk |
|---|---|---|---|
| Session timeout | Re-auth during emergencies | Shared login; persistent sessions | Non-repudiation failure; GDPR breach |
| Password rotation | Multiple systems; frequent resets | Reuse; sticky notes | Credential compromise; lateral movement |
| MFA | Extra step during urgent tasks | Shared OTPs; bypass requests | Control weakened |
| RBAC | Access delays during transfers | Credential borrowing from colleagues | Access policy violation |

### Theoretical Basis

- **Beautement et al. (2008)** — Compliance budget: repeated demands cause fatigue, not wilful non-compliance
- **Sasse & Flechais (2005)** — Security controls designed without operational context predictably produce workarounds
- **Koppel et al. (2015)** — Nurses physically marked workstations to avoid re-authentication between interruptions
- **Malik, Goel & Sinha (2026)** — Security self-efficacy is the strongest predictor of sustained compliance under fatigue

---

## 🎮 Part 2: CareShield Module Design

### Core Design Principle

Nurses are not the weak link — they are expert users working inside poorly aligned systems. CareShield addresses **both individual behaviour and the system conditions** that produce insecure workarounds (Zimmermann et al., 2024).

### Root Cause → Campaign Response Mapping

| Root Cause | Theoretical Basis | Campaign Response |
|---|---|---|
| Workflow-security conflict | Koppel et al.; Sasse & Flechais | 'Report Friction' pathway |
| Compliance budget exhaustion | Beautement et al. | 3–5 min microlearning at shift-change |
| Security treated as secondary | Sasse & Flechais | Teaches safe shortcuts (e.g., emergency override) |
| Low personal relevance | Nifakos et al. (2021) | RH characters, real EHR interfaces, NHS-specific phishing |
| Low psychological safety | Zimmermann et al. (2024) | Module 4 reframes reporting as professional duty |

### Module Structure: Four Episodes

| Episode | Scenario | Root Cause | Security Concept |
|---|---|---|---|
| 1: The Handover | Session timeout during emergency patient transfer | Structural incompatibility | Session management; emergency access protocol |
| 2: The NHS Email | Fake NHS Digital email requesting urgent password verification | Time-pressure exploitation | Phishing recognition; reporting pathway |
| 3: The WhatsApp Photo | Nurse photographs medication chart on personal phone | Compliance budget; BYOD | UK GDPR; data minimisation; secure channels |
| 4: The Near Miss | Shared terminal left logged in; visitor gains access | Psychological safety | Incident reporting; shared accountability |

### Why Branching Scenarios?

The branching format was chosen over:
- **Posters** — awareness-only, no behaviour change
- **Phishing simulations** — diagnostic, not instructional (Malik et al., 2026)
- **Facilitator-led sessions** — incompatible with rotating shift patterns

Branching scenarios place learners in **active decision roles**, directly building security self-efficacy — the strongest predictor of sustained compliance under fatigue.

---

## 📊 Part 3: Measurement Framework

Consistent with the NIST SP 800-50 Rev. 1 programme lifecycle (Plan–Analyse–Design–Develop–Implement–Assess), CareShield defines five measurable outcomes over a six-month post-deployment window:

| Metric | Method | Target | Horizon |
|---|---|---|---|
| Phishing click rate | Simulated NHS phishing campaign | ≤10% by M6 vs Week 0 baseline | Baseline → M3 → M6 |
| Incident reporting rate | Helpdesk ticket categorisation | ≥30% increase from baseline | Monthly |
| Module completion & retention | In-module quiz + M3 reassessment | ≥80% pass; ≤15% knowledge decay | Immediate + M3 |
| Credential-sharing events | SIEM anomaly alerts | 50% reduction in shared-session events | Quarterly |
| Security culture perception | Anonymous ENISA survey | Shift from compliance-as-burden to compliance-as-normal | Annual |

---

## ⚠️ Design Trade-offs & Limitations

| Decision | Benefit | Limitation |
|---|---|---|
| Micro-duration (3–5 min) | Reduces cognitive burden at shift-change | Limits depth; one workaround per episode |
| RH-specific realism | High personal relevance and engagement | Reduces portability to other NHS trusts |
| Report Friction pathway | Creates two-way organisational learning | Requires IT team responsiveness to sustain trust |
| Non-punitive framing | Supports psychological safety and honest reporting | May understate compliance expectations |

---

## 🔒 Ethical & Governance Considerations

- **UK GDPR / DPA 2018** — Episode 3 explicitly addresses data minimisation and the prohibition on photographing patient records on personal devices
- **ISO/IEC 27001:2022 Annex A.5.16** — Non-repudiation obligations form the feedback content for Episode 1's shared-login branch
- **CQC / ICO implications** — Episode 4 demonstrates that near-miss reporting is a regulatory expectation, not optional
- **WCAG 2.1 AA** — Module is screen-reader compatible, in plain NHS English, with non-punitive framing to protect psychological safety

---

## 📚 Key References

| Reference | Relevance |
|---|---|
| Beautement, Sasse & Wonham (2008) | Compliance budget — cognitive overload theory |
| Sasse & Flechais (2005) | Usable security — security vs. workflow alignment |
| Koppel et al. (2015) | Clinical workaround evidence |
| Malik, Goel & Sinha (2026) | Security fatigue and self-efficacy |
| Zimmermann et al. (2024) | Human-centred cybersecurity framework |
| NIST SP 800-50 Rev. 1 (2024) | Training programme lifecycle |
| ISO/IEC 27001:2022 | Annex A.6.3 awareness control |
| ENISA Cybersecurity Culture Guidelines (2018) | Root cause framework |

---

## 👤 Author

**Toochukwu Praise Ajoku**
MSc Cyber Security - Keele University (2026)
Student Member, CIISec

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/toochukwu-praise-ajoku/)

---

*This project was developed as part of the Usable Cyber Security: Analytics and Management module (2025/26). The Royal Hospital is a fictional organisation used for educational purposes.*
