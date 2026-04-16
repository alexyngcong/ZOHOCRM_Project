# MICS International — Zoho Ecosystem Documentation V4

[![Version](https://img.shields.io/badge/version-V4.0-0B2A4A)](./CHANGELOG.md)
[![Status](https://img.shields.io/badge/status-Final-059669)](./docs)
[![Pages](https://img.shields.io/badge/pages-131%20(46%20%2B%2085)-475569)](./docs)
[![License](https://img.shields.io/badge/license-Internal%20Use-94A3B8)](./LICENSE)
[![Effective](https://img.shields.io/badge/effective-15%20Apr%202026-0EA5E9)](./CHANGELOG.md)

> **Comprehensive reference for the MICS International Zoho ecosystem** — covering ownership rules, lead-to-cash flow, service delivery, HR operations, automation logic, and CRM screen designs across two companion documents.

---

## 📚 Documents

This repository contains two companion documents — one covers **what the system does** (rules and workflows), the other covers **what it looks like** (CRM UI designs).

| Document | Pages | Format | View / Download |
|---|---|---|---|
| **📘 Workflow Documentation** | 46 | HTML · PDF | [View HTML](./docs/workflow-documentation.html) · [Download PDF](./docs/workflow-documentation.pdf) |
| **🎨 Visual Design Guide** | 85 | HTML · PDF | [View HTML](./docs/visual-design-guide.html) · [Download PDF](./docs/visual-design-guide.pdf) |

🌐 **Live preview via GitHub Pages:** _enable Pages in repo settings → Source: `main` branch `/` (root)_ — landing page will be served from [`index.html`](./index.html).

---

## 📘 Document 1 · Workflow Documentation

46 pages · 19 sections · business rules, ownership, automation

### Part I · Foundations
1. Executive Summary & System Overview
2. Organizational Structure & Role Hierarchy
3. Employee Code System

### Part II · Lead to Cash
4. Lead Management Workflow
5. Deal & Sales Pipeline Workflow
6. Proposal & Approval Workflow
7. Payment Gate & Invoice Workflow
8. Execution & Service Delivery Workflow
9. Service Frequency & Renewal Management

### Part III · Operations & Governance
10. Sales Targets & Performance Tracking
11. Client Ownership & Attribution Rules
12. External Referral & Commission Tracking
13. HR, Attendance & Leave Workflows
14. Recruitment Pipeline Workflow
15. Marketing & Communication Workflows
16. Document & Credentials Management
17. Automation Rules Reference (50 rules)
18. Access Control & Security Matrix
19. Integration Architecture

---

## 🎨 Document 2 · Visual Design Guide

85 pages · 16 sections · CRM screen mockups

| Section | Pages | Coverage |
|---|---|---|
| B · Zoho CRM Sales | 3–24 | Leads, Accounts, Deals, Proposals, Services, Credentials Vault |
| C · Execution Hub | 25–30 | Work Orders, Tasks, Service Delivery, Calendar |
| D · Notifications & Approvals | 31–32 | Alert center, Approval workflows |
| E · Zoho Books | 33–38 | Invoicing, Payment Gate, External Referral Commission |
| F · Zoho People HR | 39–48 | Attendance, Leave, Onboarding, Performance, Training |
| G · Self-Service Portal | 49–52 | Employee dashboard, tasks, payslips |
| H · Recruitment | 53–55 | Job Orders, Candidate Pipeline, Interview & Offer |
| I · Marketing Hub | 56–60 | Campaigns, Email, Social, ROI |
| J · Communications | 61–63 | WhatsApp Business, SalesIQ, Cliq |
| K · Forms & Sign | 64–67 | Form Builder, Document Signing |
| L · Analytics | 68–71 | Dashboards, Reports, Attribution, Cross-Entity |
| M · Flow & Automation | 72–74 | Flow Builder, Rules Matrix |
| N · Admin | 75–79 | Employee Code Mgmt, Access Control, Settings |
| O · Business Views | 80–85 | Client 360, Retention, Engagement Lifecycle |

---

## 🏛️ Organizational Tier Structure

| Tier | Role | Count |
|------|------|-------|
| **T1** | Founder | 1 |
| **T2** | Partners (×3) + Associate Partner | 4 |
| **T3** | Department Heads (BD · Communications · HR & Admin · Accounts) | 4 |
| **T4** | Managers | 3 |
| **T5** | Executions & Sales | ~23 |
| **T6** | Support | ~7 |
| **T7** | Interns | ~4 |
| | **Total headcount** | **46** |

---

## 🔒 Privacy Notice

Both documents have been **privacy-sanitized** for safe distribution:

- ✅ No personal employee names appear in either document
- ✅ All staff referenced only by Employee Code (e.g. `EMP-001`)
- ✅ All client references use generic descriptors in brackets (e.g. `[Client · Cosmetics Trading]`)
- ✅ Individual salaries, performance scores, and personal data are not disclosed
- ✅ Portal credentials (FTA, DED, MOF, etc.) are conceptually referenced but no actual credentials appear

**Live personal data** remains in Zoho People under HR-controlled access. This repository is safe to share with implementation partners, auditors, consultants, and external reviewers.

---

## 🎯 Key Design Principles

- **Employee Code accountability** — shared departmental logins preserve individual attribution via 3-digit EMP codes
- **Mandatory Payment Gate** — no work order or service delivery begins until deposit is received and reconciled
- **Ownership is set at creation** — the creator of a lead/account becomes the owner; transfers are logged
- **Lead source attribution is permanent** — marketing ROI and referral tracking cannot be altered retroactively
- **Execution team sees everything** — assigned delivery staff have FULL visibility into their client's contract, credentials, and history
- **Every action is audited** — immutable log, 7-year retention, keyed by Employee Code

---

## 📂 Repository Structure

```
mics-zoho-ecosystem-v4/
├── README.md                          ← you are here
├── LICENSE                            ← internal use license
├── CHANGELOG.md                       ← version history
├── index.html                         ← GitHub Pages landing page
├── .gitignore
├── .github/
│   └── workflows/
│       └── deploy-pages.yml           ← auto-deploy to GitHub Pages
├── docs/
│   ├── workflow-documentation.html    ← Document 1 (HTML)
│   ├── workflow-documentation.pdf     ← Document 1 (PDF)
│   ├── visual-design-guide.html       ← Document 2 (HTML)
│   └── visual-design-guide.pdf        ← Document 2 (PDF)
└── assets/
    └── (logos, screenshots — future use)
```

---

## 🛠️ How to Use

### Option 1 · View online (recommended)
Enable GitHub Pages in repository settings, then visit:
- Landing page: `https://<user>.github.io/<repo>/`
- Workflow Doc: `https://<user>.github.io/<repo>/docs/workflow-documentation.html`
- Design Guide: `https://<user>.github.io/<repo>/docs/visual-design-guide.html`

### Option 2 · View locally
```bash
git clone <repo-url>
cd mics-zoho-ecosystem-v4
# Open index.html in any browser, or:
open docs/workflow-documentation.html    # macOS
start docs/workflow-documentation.html   # Windows
xdg-open docs/workflow-documentation.html # Linux
```

### Option 3 · Download PDFs
Click the PDF links in the [Documents table](#-documents) above to download directly.

---

## 🔄 Keeping Documents in Sync

Both documents reference the same underlying system model. When updating:

1. **Workflow changes** → update the `.html` source in `docs/`
2. **Design changes** → update the `.html` source in `docs/`
3. **Re-generate PDFs** using Chrome headless:
   ```bash
   chrome --headless --disable-gpu \
     --print-to-pdf="docs/workflow-documentation.pdf" \
     --print-to-pdf-no-header \
     --virtual-time-budget=15000 \
     "file:///$(pwd)/docs/workflow-documentation.html"
   ```
4. **Bump version** in [`CHANGELOG.md`](./CHANGELOG.md)
5. **Commit** with a descriptive message referencing the change category

---

## 📞 Contact

| Role | Channel |
|------|---------|
| Document owner | Office of the Partners |
| Implementation queries | Head of Accounting & Compliances |
| HR data questions | HR & Admin Manager |
| Technical / Zoho admin | Assistant Manager — IT Support |

**Document references:** `MICS-WF-V4-2026` · `MICS-VDG-V4-2026`

---

## 📄 License

Internal use only — proprietary to MICS International. See [LICENSE](./LICENSE) for terms.

---

<sub>Built with 🧠 by the MICS Operations team · 46 active staff · UAE · India · Remote · April 2026</sub>
