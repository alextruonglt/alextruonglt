# <a href="https://www.linkedin.com/in/alex-truong-8a1a8b120/">Alex Truong</a>'s IT and Cybersecurity Project Portfolio 🔐

I'm an Identity & Access Governance Analyst with hands-on experience securing enterprise Microsoft Entra ID environments, building privileged access governance programs, and mapping organizational risk to NIST 800-53, NIST CSF 2.0, ISO 27001, and SOC 2 frameworks. My work spans IAM, PAM, GRC, vulnerability management, and threat detection — all performed in live production environments.

---

## 📋 Governance, Risk, and Compliance (GRC)

- **[GRC Program Portfolio — Live Azure Cloud Environment](https://github.com/alextruonglt/grc-program-portfolio)**
  Built a complete GRC program from scratch on a live Azure shared tenant (~1,000+ users) following a multi-framework gap assessment conducted in March 2026. The assessment confirmed zero active Sentinel analytics rules, 83,600 of 203,906 sign-ins on single-factor authentication, 185 critical vulnerabilities with zero remediated, and an empty ProtectionStatus table for all 126 assets. The program produced 21 documents across 9 folders covering four framework assessments (NIST 800-53, NIST CSF 2.0, ISO 27001:2022, SOC 2 TSC), a GRC Program Charter and System Security Plan, identity governance policies and procedures, vulnerability management program, 29 KQL detection rules with 18 SIEM use cases, configuration baseline standard, TPRM template with completed vendor assessment, POA&M, risk register, information security policy, and incident response plan.

---

## 🪪 Identity & Access Management (IAM / PAM)

- **[Zero Trust Conditional Access Framework — Microsoft Entra ID](https://github.com/alextruonglt/zero-trust)**
  Designed and implemented a 14-policy Zero Trust Conditional Access framework in a live Entra ID tenant. Improved Identity Secure Score from 22% to 55%. Covers legacy auth blocking, risk-based MFA, device compliance via Intune, identity risk response, session controls, and geo-blocking.

- **[Identity Access Review — Microsoft Entra ID](https://github.com/alextruonglt/iam-access-review)**
  Conducted a full identity entitlement review across 2,225 live Entra ID accounts. Identified 13 findings including a Critical-severity external Global Administrator, zero PIM adoption across all 10 privileged role holders, and 1,159+ stale enabled accounts. Mapped findings to NIST SP 800-53 and CIS Controls v8.

- **[Privileged Access Audit — Zero Trust Benchmarks](https://github.com/alextruonglt/privileged-access-audit)**
  Audited 8 privileged identities across 3 tiers against 10 Zero Trust benchmarks. Found 100% of accounts at Critical Risk — including a service principal and an 11-year-old external guest identity holding permanent Global Administrator with no PIM, no MFA evidence, and no CA policy coverage.

---

## ⚠️ Vulnerability Management

- **[Vulnerability Management Program Implementation](https://github.com/alextruonglt/Vulnerability_Policy_Implementation)**
  Built an enterprise vulnerability management program using Tenable. Achieved 98% reduction in vulnerabilities through structured assessments and remediation tracking mapped to NIST 800-53 controls.

- **[Programmatic Vulnerability Remediations (PowerShell and BASH)](https://github.com/alextruonglt/Vulnerability_Management/tree/main/STIGS)**
  Automated STIG remediation using PowerShell and Bash. Achieved 100% elimination of Critical and 90% reduction in High vulnerabilities, validated against NIST 800-53 control families.

---

## 🚨 Threat Hunting and Security Operations

- **[Threat Hunting Scenario — TOR Browser Detection](https://github.com/alextruonglt/threat_hunting_lab)**
  Conducted a threat hunting investigation using Microsoft Defender for Endpoint and KQL to detect TOR usage across endpoints. Built KQL detection rules and Microsoft Sentinel dashboards for ongoing monitoring.

---

## 🎓 Certifications

`AZ-500` · `SC-300` · `SailPoint Identity Security Leader` · `CompTIA Security+` · `CompTIA Network+` · `AWS Cloud Practitioner` · `Azure Fundamentals` · `ITIL`

---

## 🤳 Connect With Me

[<img align="left" alt="Alex Truong | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]

[linkedin]: https://linkedin.com/in/alex-truong-8a1a8b120/
