# Project Charter

**Project Name:** Greenfield Connect — Coimbatore Branch Network & Infrastructure Build
**Document Owner:** Prachi Sharma, IT Infrastructure Project Manager
**Status:** Approved
**Version:** 1.0
**Date:** [Insert Approval Date]

> **Note on this document:** This is a self-directed case study built to demonstrate IT infrastructure project management methodology end to end, independent of any AI/ML tooling. The company, stakeholders, and figures are illustrative, modeled on realistic mid-market network and branch-infrastructure rollouts. It is not a claimed client engagement.

---

## 1. Purpose

This charter formally authorizes the Greenfield Connect project and grants the Project Manager the authority to apply organizational resources to project activities. It converts a fixed customer go-live date and an empty shell-and-core building into a bounded, fundable, technically grounded delivery plan — before any vendor contract is signed or any switch ordered.

## 2. Project Sponsor & Authority

| Role | Name / Title |
|---|---|
| **Executive Sponsor** | COO (given the fixed, contractually committed customer go-live date) |
| **Delivery Sponsor** | Head of IT Infrastructure |
| **Project Manager** | Prachi Sharma — IT Infrastructure Project Manager (sole PM, cross-functional and vendor-facing lead) |
| **Approval Authority** | COO, with conditions (see Section 9) |

## 3. Business Need / Problem Statement

Bridgeline Logistics, a 600-employee regional freight and distribution company, won a contract requiring it to open a new 85-person regional distribution and operations branch in Coimbatore within a fixed 14-week window — driven by a customer go-live commitment, not an internal preference. The building's shell-and-core was handed over by the landlord but otherwise empty: no cabling, no network, no phones, no Wi-Fi, no server room.

A new 85-person branch must be fully operational — network, telephony, Wi-Fi, and endpoints — in time for this contractually committed customer go-live date, in a building with no existing IT infrastructure of any kind.

## 4. Project Description

Greenfield Connect designs, procures, builds, and stabilizes the full network and IT infrastructure for the branch: structured cabling, LAN/WAN, firewall and security, Wi-Fi, telephony, server room and rack build-out, endpoint deployment, and a 24/7 support handover — all before the branch's committed open date.

The project follows a **Waterfall-based stage-gate delivery** model (site, procurement, and construction-linked work does not suit iterative sprints), with a lightweight Kanban board used only for cutover-week task tracking.

## 5. Project Objectives

| # | Objective |
|---|---|
| 1 | Branch network, telephony, and Wi-Fi live and tested at least 5 business days before the committed go-live date |
| 2 | Zero customer-facing slippage on the go-live date itself |
| 3 | Infrastructure built to the company's standard branch reference architecture, with deviations documented and approved |
| 4 | A fully documented handover to the regional support helpdesk before the project team stands down |

## 6. Success Metrics

| Metric | Target |
|---|---|
| Go-live date slippage | Zero |
| Network uptime (first 30 days) | ≥ 99.5% |
| Endpoints provisioned before day one | 85 / 85 |
| Support handover sign-off | Obtained from the helpdesk manager |

## 7. High-Level Scope

**In Scope:** Structured cabling, core/access switching, firewall and WAN connectivity, Wi-Fi, server room build-out (rack, UPS, basic cooling), VoIP telephony, endpoint imaging and deployment, support documentation and handover.

**Out of Scope:** Building electrical and HVAC base build (Facilities-owned); furniture and physical office fit-out; any application-layer or business-system configuration beyond network connectivity; CCTV and physical access control (tracked as a parallel Facilities-led workstream with an IT dependency only).

*(See the Scope Statement for full detail.)*

## 8. Project Team & Resources

| Role | Allocation |
|---|---|
| Project Manager | 1, full-time (sole PM, cross-functional and vendor-facing lead) |
| Network Engineer | 1 |
| Systems / Server Engineer | 1 |
| Telephony Specialist | 1 |
| External Contractors | 2 (structured cabling, electrical) |
| Vendor Account Manager (hardware) | 1 |
| Security, Procurement | Part-time partners |

**Duration:** 14 weeks design-to-go-live, plus a 4-week stabilization and handover period.

## 9. Budget & Funding

| Item | Amount |
|---|---|
| One-time build cost | ₹38.5 lakh (hardware, cabling, contractor labor) |
| Projected recurring cost | ~₹62,000/month (WAN circuit, telephony licensing, warranty support) |

## 10. Key Assumptions

- Landlord delivers electrical and fire-safety certification on the committed date
- Primary WAN circuit provider can deliver within the standard 6–8 week lead time if ordered immediately
- Hardware vendor can meet the project's delivery window at standard (not expedited) pricing

## 11. Key Constraints

- Go-live date is contractually fixed with a customer penalty clause — not internally negotiable
- All infrastructure must meet the company's existing security baseline — no exceptions for "new site, fast timeline"
- Server room has real physical space and power constraints that cap how much hardware can be installed

## 12. High-Level Risks

| Risk | Notes |
|---|---|
| Compressed working calendar | The "14 weeks" was not 14 working weeks — 9 days were consumed by mandatory landlord electrical and fire-safety inspections before any cabling contractor could legally start. Surfaced in the charter as a revised internal working calendar of 12 weeks for IT-controlled work |
| Server room scope gap | Site walkthrough revealed no dedicated server room — just an empty utility closet with a single 15A outlet, no cooling, no raised flooring. A materially more expensive scope than the charter's first draft assumed; flagged as a budget risk before the business case went to the sponsor |
| Facilities/IT definition-of-done mismatch | Facilities considered their job finished once power and HVAC were live; IT needed structured cabling, rack power, and network connectivity verified end to end. Resolved via a jointly signed-off "site readiness" checklist written into the charter |

## 13. Approval

| Decision | Detail |
|---|---|
| **Outcome** | Approved by COO |
| **Conditions** | Any risk to the go-live date must be escalated within 24 hours of identification, not batched into a weekly report |

| Approver | Title | Signature | Date |
|---|---|---|---|
| | COO (Executive Sponsor) | | |
| | Head of IT Infrastructure (Delivery Sponsor) | | |
| | IT Infrastructure Project Manager | | |
| | Facilities Lead | | |

---
*Prepared by Prachi Sharma — IT Infrastructure Project Manager · Technical PM · Service Delivery Lead*
