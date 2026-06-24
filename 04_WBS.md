# Work Breakdown Structure (WBS)

**Project Name:** Greenfield Connect — Coimbatore Branch Network & Infrastructure Build
**Document Owner:** Prachi Sharma, IT Infrastructure Project Manager
**Status:** Approved
**Version:** 1.0
**Date:** [Insert Approval Date]

---

## 1. WBS Overview

The project is decomposed into **7 stages** (1.0–7.0), aligned to the Waterfall-based stage-gate structure used to govern site readiness, procurement, security, and operational handover. Stage 4 (Build) overlaps physical and technical workstreams across roughly six weeks; Stage 6 (Cutover) is tracked separately on a lightweight Kanban board given its compressed, minute-by-minute nature.

**Total duration:** 14 weeks design-to-go-live, plus a 4-week stabilization and handover period.

## 2. WBS Hierarchy

```
0.0 Greenfield Connect — Coimbatore Branch Network & Infrastructure Build
├── 1.0 Discovery & Business Case
│   ├── 1.1 Structured discovery session (Head of IT Infrastructure, Operations Director, Facilities, COO)
│   ├── 1.2 Physical site walkthrough against landlord handover documents
│   ├── 1.3 Headcount & seating plan sizing exercise (HR, Operations)
│   ├── 1.4 Working-calendar reconciliation (certification timeline vs. 14-week assumption)
│   ├── 1.5 Site-readiness checklist co-authored with Facilities
│   ├── 1.6 Draft Project Charter & Business Case
│   └── 1.7 Sponsor approval gate
│
├── 2.0 Requirements & Vendor Selection
│   ├── 2.1 Translate charter objectives into detailed requirements (functional/non-functional)
│   ├── 2.2 Bill of materials development with Network & Systems Engineers
│   ├── 2.3 Certified site survey commissioned from cabling contractor
│   ├── 2.4 Parallel vendor evaluation — WAN provider, hardware vendor, cabling contractor
│   ├── 2.5 Security baseline requirements gathering
│   ├── 2.6 Purchase orders issued for longest-lead-time items (WAN circuit, core switching)
│   └── 2.7 Requirements & vendor comparison sign-off
│
├── 3.0 Solution Design & Architecture
│   ├── 3.1 Server room layout design review against real room dimensions/power
│   ├── 3.2 Network topology & security design walkthrough (pre-hardware)
│   ├── 3.3 Emergency-calling (E911-equivalent) compliance verification
│   ├── 3.4 Architecture deviation logging (24U rack, guest Wi-Fi isolation fix)
│   └── 3.5 Network Design Document & ADR sign-off
│
├── 4.0 Build & Delivery Coordination
│   ├── 4.1 Week 1–2: Structured cabling first pass
│   ├── 4.2 Week 3: Electrical & UPS install (permit-delay contingency executed)
│   ├── 4.3 Week 3–4: Cabling completion & end-to-end certification
│   ├── 4.4 Week 4–5: Rack build, switch & firewall install
│   ├── 4.5 Week 5–6: Wi-Fi AP install & telephony provisioning
│   ├── 4.6 Week 6: Endpoint imaging & deployment (85/85)
│   ├── 4.7 Twice-weekly site coordination meetings (ongoing across all weeks)
│   ├── 4.8 RAID log maintenance & weekly sponsor review (ongoing)
│   ├── 4.9 Personal on-site progress walkthroughs (ongoing, triggered by reporting discrepancy)
│   └── 4.10 Change-request management (e.g., additional conference room)
│
├── 5.0 Testing & Pre-Go-Live Validation
│   ├── 5.1 Structured test plan execution (network failover, Wi-Fi, telephony, endpoints)
│   ├── 5.2 Mock opening day with early-arriving staff
│   ├── 5.3 Failover test, fix, and independent retest
│   ├── 5.4 Wi-Fi dead-zone remediation (additional AP + re-survey)
│   ├── 5.5 UPS live load test (held as non-negotiable despite schedule pressure)
│   └── 5.6 Go/no-go review with sponsor and all workstream owners
│
├── 6.0 Go-Live & Cutover
│   ├── 6.1 Minute-by-minute cutover-weekend runbook authored
│   ├── 6.2 On-site war room staffing (network, systems, telephony)
│   ├── 6.3 Sat AM — final network/firewall config push
│   ├── 6.4 Sat PM — endpoint deployment (85/85)
│   ├── 6.5 Sun AM — telephony cutover and emergency-routing verification
│   ├── 6.6 Sun PM — full site walkthrough (patch panel fix)
│   ├── 6.7 Mon Day 1 — on-site war room, hourly status checks
│   └── 6.8 First-week hypercare (daily 8am check-ins with branch lead)
│
└── 7.0 Post-Go-Live Stabilization & Handover
    ├── 7.1 Handover package & live walkthrough to regional helpdesk
    ├── 7.2 Design-decisions-and-known-deviations documentation (added on PM's requirement)
    ├── 7.3 On-call coverage gap remediation (telephony platform training)
    ├── 7.4 Operational thresholds defined (uptime, ticket volume, capacity triggers)
    ├── 7.5 Ticket-volume root-cause review (onboarding gap vs. infrastructure fault)
    ├── 7.6 30-day post-go-live review against Stage 1 success metrics
    ├── 7.7 Formal project closure & signed handover acceptance
    └── 7.8 Deferred/future scope logged (18-month capacity review, secondary fiber path, VoIP rollout to next 2 branches)
```

## 3. WBS Dictionary (Summary)

| WBS ID | Work Package | Primary Owner | Key Output |
|---|---|---|---|
| 1.4 | Working-calendar reconciliation | PM | Revised internal 12-working-week schedule, surfaced in the charter |
| 2.6 | PO issuance for long-lead items | PM | WAN circuit and core switching ordered same week requirements finalized |
| 3.1 | Server room layout redesign | Systems Engineer / PM | 24U high-density rack design approved as a documented exception |
| 4.9 | On-site progress walkthrough | PM | Cabling contractor re-baselined from a reported 70% to an actual 45% completion |
| 5.3 | Failover test, fix, retest | Network Engineer | Misconfigured routing priority found and fixed before go-live |
| 5.5 | UPS live load test | Systems Engineer | 18-minute hold at full load verified (target: ≥ 15 min) |
| 6.6 | Full site walkthrough (cutover) | PM + full team | Mislabeled patch panel port fixed within 20 minutes |
| 7.3 | On-call coverage remediation | Helpdesk Manager | Two helpdesk engineers trained before handover formally closed |

## 4. Milestones

| Milestone | WBS Reference | Gate Type |
|---|---|---|
| Charter & Business Case approved | 1.7 | Sponsor approval gate |
| Requirements & vendor comparison signed off | 2.7 | Procurement / stakeholder alignment gate |
| Architecture & Security approved | 3.5 | Security gate |
| Core network live on internal test VLAN | 4.4 | Engineering readiness checkpoint |
| Go/no-go review passed | 5.6 | Sponsor + workstream owner gate (non-negotiable on UPS test) |
| Branch opened on committed date | 6.7 | Customer-contract milestone |
| Handover accepted by helpdesk manager | 7.7 | Formal project closure gate |

## 5. Notes on Decomposition Choices

- **Stage 4 is organized by build week, not by trade**, reflecting how cabling, electrical, and hardware install genuinely overlapped in the same building during the same weeks — the dependency-aware schedule (cabling → rack install → switch configuration → endpoint imaging) is the actual sequencing logic, not an artifact of this WBS.
- **Stage 6 is intentionally fine-grained at the half-day level**, reflecting that cutover weekend was run from a minute-by-minute runbook rather than a sprint-style backlog — this is the lowest level of formal decomposition for that stage; the full runbook lives in the Cutover Runbook document, not repeated here.
- Deferred items (7.8) are recorded as the decision to defer, not as open project work — they belong to a future business case, not this WBS's remaining scope.

---
*Prepared by Prachi Sharma — IT Infrastructure Project Manager · Technical PM · Service Delivery Lead*
