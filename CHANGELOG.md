# Changelog

All notable changes to the MICS Zoho Ecosystem Documentation are recorded in this file.

The format follows [Keep a Changelog](https://keepachangelog.com/), and this project adheres to semantic versioning.

---

## [V4.0] — 2026-04-15 · Final

### Added
- **Workflow Documentation V4** — 46 pages, 19 sections, paginated for A4 landscape print.
  - Executive summary with seven unbreakable operating rules.
  - Complete tier hierarchy (T1 Founder → T7 Interns) with role responsibilities.
  - Employee Code system documented with full 46-person directory (codes only, no names).
  - Lead management workflow covering 9 sources, BANT scoring, SLAs, ownership fields.
  - Deal pipeline across five parallel tracks (MICS Services · Advisory · Recruitment · KRO · Visa).
  - Proposal &amp; approval chain with dual signing path (online + offline upload).
  - Payment gate rules with mandatory deposit requirements per deal tier.
  - Execution workflow with 6-item handoff checklist and Work Order structure.
  - Service frequency classification (One-time · Monthly · Quarterly · Yearly) with reminder schedules.
  - Sales targets matrix across every role except pure Execution / Support.
  - Client ownership rules with append-only Handler History.
  - External referral commission tiers (Standard 5% · VIP 8% · Strategic 10% · Employee 3%).
  - Complete HR workflows: 9 leave types, 21-step onboarding, quarterly performance reviews.
  - Recruitment pipeline aligned to current open roles.
  - Marketing attribution model (first / last / multi-touch).
  - Document management with Drive folder hierarchy.
  - Client credentials vault (FTA · DED · MOF · GDRFA · ICP · Banking · Insurance).
  - 50 automation rules catalogued (AUTO-001 through AUTO-050).
  - Access control matrix across data objects × tiers.
  - Integration architecture covering 14 Zoho apps + 4 external integrations.

- **Visual Design Guide V4** — 85 pages, 16 sections, A4 landscape.
  - Section B: 22 CRM Sales pages (Leads, Deals, Accounts, Proposals, Services, Credentials).
  - Section C: 6 Execution Hub pages including the core Work Order Detail page.
  - Section D: Notification Center &amp; Approval Center.
  - Section E: 6 Zoho Books pages including the External Referral Commission tracker.
  - Section F: 10 Zoho People HR pages (Attendance, Leave, Onboarding, Performance, Training).
  - Section G: 4 Self-Service Portal pages.
  - Section H: 3 Recruitment pipeline pages.
  - Section I: 5 Marketing Hub pages.
  - Section J: 3 Communication integrations (WhatsApp · SalesIQ · Cliq).
  - Section K: 4 Forms &amp; Sign pages.
  - Section L: 4 Analytics pages.
  - Section M: 3 Flow &amp; Automation pages (Dashboard, Builder, Rules Matrix).
  - Section N: 5 Admin pages including the Access Control Matrix.
  - Section O: 6 Business Views (Client 360 · Retention · Engagement Lifecycle).

- Companion landing page (`index.html`) for GitHub Pages hosting.
- Print-optimised CSS with `@page A4 landscape` for faithful PDF export.
- Pre-generated PDFs for both documents via Chrome headless.

### Changed
- Privacy refactor: removed all personally identifying information from both documents.
  - 46 employees now referenced only by Employee Code + generic role descriptor.
  - Client references replaced with bracketed generic descriptors (e.g. `[Client · Cosmetics Trading]`).
  - External referrer names replaced with `[External Referrer]`.
- Tier structure simplified to match real organization (Founder · Partners · Heads · Managers · Teams).
- Unified theme across both documents: navy (`#0B2A4A`) primary, white backgrounds, zero red color.
- Logo updated to bold navy "MICS" in navy border box.
- Typography standardised on Plus Jakarta Sans (body) + Oswald (logo) + JetBrains Mono (codes).

### Security
- No live credentials, no personal names, no client-identifying data in published documents.
- Live data remains in Zoho People under HR-controlled access.

---

## [V3.x] — 2026-04-13 → 2026-04-15 · Iterations (pre-release)

Internal iterations addressing:
- Removed KRO Real Estate branding (MICS International only).
- Replaced placeholder employee data with real Zoho People roster.
- Rebuilt Proposal Template System with merge-field editor and dual signing path.
- Multiple theme revisions converging on the final all-white, navy-accent design.
- Reverted from editorial letter style to software-tool CRM aesthetic.

_These iterations were not released externally; they are documented here for traceability._

---

## [V2.0] — 2026-04-14 · Archived

- Original 52-page design guide.
- Shared login architecture introduced.
- First draft of ownership attribution rules.

_Superseded by V3 and V4 as the system scope expanded._

---

## Upcoming / Planned

- **V4.1** — Annotations layer for implementation teams (field-level Zoho customization notes).
- **V5.0** — Client-facing extract (sanitized further, for proposal-attachment use).

---

_Document references:  MICS-WF-V4-2026  ·  MICS-VDG-V4-2026_
