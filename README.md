# NovaCrest Financial Services — Cloud Security Programme

> Multi-cloud GRC and security compliance programme for a self-directed 
> UK financial services firm, covering AWS and Azure security 
> assessment, multi-framework compliance mapping and cloud provider 
> security questionnaire.

---

## What This Project Covers

| Document | Description |
|----------|-------------|
| Multi-Cloud Security Assessment | AWS & Azure assessed against CIS Benchmarks v1.5/v2.0 — 28 findings across IAM, storage, logging and monitoring |
| Cloud Security Policy | NovaCrest's formal cloud governance policy aligned to ISO 27001 Annex A 5.23 and CSA STAR CCM v4 |
| Cloud Compliance Framework Matrix | Cross-mapping of 22 control domains across ISO 27001, CSA STAR CCM v4, CIS AWS and CIS Azure |
| Cloud Security Questionnaire | 44-question CAIQ-style questionnaire across 10 domains for assessing cloud providers |

---

## Key Findings — AWS Assessment (CIS Benchmark v1.5)

- **Critical:** Root account has active access keys — delete immediately
- **Critical:** MFA not enabled on 4 of 7 IAM console users
- **Critical:** S3 bucket containing customer KYC documents has public access enabled — potential GDPR breach
- **High:** CloudTrail disabled in 3 AWS regions — API activity unlogged
- **High:** AWS Config not enabled — no continuous compliance monitoring
- **High:** AWS Security Hub not enabled — no unified security posture assessment

---

## Key Findings — Azure Assessment (CIS Benchmark v2.0)

- **Critical:** MFA not enforced on 3 Global Administrator accounts
- **Critical:** Storage account containing customer PII has public network access enabled
- **High:** 12 guest accounts not reviewed in 6+ months
- **High:** Soft delete not enabled on 3 production storage accounts
- **Partial:** Microsoft Defender for Cloud not enabled on production subscription

---

## Frameworks Applied

- **ISO 27001:2022** — Annex A cloud control mapping for all findings
- **CSA STAR CCM v4** — Cloud Controls Matrix across 10 domains
- **CIS AWS Foundations Benchmark v1.5** — Full IAM, S3, logging and monitoring assessment
- **CIS Azure Foundations Benchmark v2.0** — Full IAM, data protection and monitoring assessment

---

## Cloud Security Questionnaire

The 44-question Cloud Provider Security Questionnaire (CAIQ-style) covers:

- Governance & Risk (5 questions)
- Data Security & Privacy (7 questions)
- Identity & Access Management (6 questions)
- Infrastructure & Network (5 questions)
- Logging & Monitoring (4 questions)
- Incident Response (4 questions)
- Business Continuity (4 questions)
- Supply Chain Security (3 questions)
- Physical Security (3 questions)
- Regulatory Compliance (4 questions — FCA, GDPR, PCI DSS)

---

## Related Projects

- [NovaCrest ISMS Portfolio] — Full ISO 27001:2022 ISMS implementation

---

## About

**Afrid Shaik** — Cyber GRC & Cloud Security Analyst
MSc Cybersecurity (Advanced Research, 2:1) — University of Hertfordshire
CompTIA Security+ | CEH | OneTrust TPRM Expert | ISO 27001 Lead Implementer (in progress)

LinkedIn: [linkedin.com/in/afridshaik-grcuk](https://linkedin.com/in/afridshaik-grcuk)
