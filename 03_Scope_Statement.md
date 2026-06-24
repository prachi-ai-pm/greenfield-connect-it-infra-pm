# Project Scope Statement

**Project Name:** Greenfield Connect — Coimbatore Branch Network & Infrastructure Build
**Document Owner:** Prachi Sharma, IT Infrastructure Project Manager
**Status:** Approved
**Version:** 1.0
**Date:** [Insert Approval Date]

---

## 1. Project Scope Description

Greenfield Connect delivers the complete network and IT infrastructure build-out for a new 85-person branch in Coimbatore, within a fixed, contractually committed 14-week (12 IT-working-week) window. The build covers structured cabling, core/access switching, firewall and WAN connectivity, Wi-Fi, server room build-out, VoIP telephony, endpoint deployment, and a documented handover to the regional support helpdesk.

## 2. Project Deliverables

| Stage | Deliverable |
|---|---|
| 1 — Discovery & Business Case | Project Charter & Business Case |
| 2 — Requirements & Vendor Selection | Requirements Document, Bill of Materials & Vendor Comparison |
| 3 — Solution Design & Architecture | Network Design Document & Architecture Decision Record |
| 4 — Build & Delivery Coordination | Build Schedule, RAID Log & Change Request Log |
| 5 — Testing & Pre-Go-Live Validation | Test Plan, Go/No-Go Checklist & UAT Sign-Off |
| 6 — Go-Live & Cutover | Cutover Runbook & Hypercare Log |
| 7 — Post-Go-Live Stabilization & Handover | Handover Runbook, Acceptance Sign-Off & 30-Day Review |

## 3. In Scope

- **Structured cabling:** Cat6A cabling, certified end-to-end test reports for every run
- **Network:** Core/access switching, sized for 85 users plus 18 months of headcount growth
- **WAN & resilience:** Primary fiber circuit plus a documented, tested LTE failover path
- **Wi-Fi:** Controller-managed AP deployment, covering 100% of usable floor space including warehouse-adjacent ops areas, with true VLAN-isolated guest network
- **Security:** Firewall rules and network segmentation matching the company's standard branch baseline, signed off by Security before production deployment
- **Telephony:** VoIP handsets for all 85 staff, auto-attendant, and location-verified emergency-calling compliance
- **Server room:** Rack, UPS, and basic cooling sufficient for the installed hardware load
- **Endpoints:** Imaging and deployment of all 85 endpoints, domain-joined and connectivity-verified
- **Handover:** Fully documented support handover to the regional IT helpdesk, including design-decision history and known deviations

## 4. Out of Scope

- Building electrical and HVAC base build (Facilities-owned)
- Furniture and physical office fit-out
- Any application-layer or business-system configuration beyond network connectivity
- CCTV and physical access control — tracked as a parallel Facilities-led workstream with an IT dependency only, not delivered by this project
- Permanent secondary fiber WAN path (deferred — LTE failover used for go-live; permanent secondary path deferred to a future evaluation once traffic volume justifies the recurring cost)
- Server room capacity expansion beyond the 24U deviation (deferred to an 18-month capacity review)

## 5. Acceptance Criteria

| Requirement | Acceptance Criteria |
|---|---|
| Wired network capacity | ≥ 130 usable ports provisioned; PoE budget covers all APs and phones with 20% headroom |
| WAN resilience | Automatic failover tested and verified before go-live; failover triggers within 60 seconds of primary loss |
| Wi-Fi coverage | No coverage dead zones in post-install signal survey; guest network isolated from corporate VLAN |
| Security baseline | Security sign-off obtained prior to go-live; baseline config matches the approved standard template |
| Telephony | 100% of handsets registered and tested; emergency calling verified to route correctly to local services |
| Server room environment | UPS holds full load for ≥ 15 minutes on test; room temperature stays within hardware spec under load |
| Go-live readiness | Branch network, telephony, and Wi-Fi live and tested at least 5 business days before the committed go-live date |
| Support handover | Documented handover accepted and signed off by the helpdesk manager |

## 6. Project Constraints

- Go-live date is contractually fixed with a customer penalty clause — not internally negotiable
- All infrastructure must meet the company's existing security baseline — no exceptions for "new site, fast timeline"
- Server room has real, fixed physical space and power constraints (utility closet only fits a 24U rack, not the standard 42U)
- Any risk to the go-live date must be escalated within 24 hours of identification

## 7. Project Assumptions

- Landlord delivers electrical and fire-safety certification on the committed date
- Primary WAN circuit provider can deliver within the standard 6–8 week lead time if ordered immediately
- Hardware vendor can meet the project's delivery window at standard (not expedited) pricing

## 8. Scope Exclusions Rationale

| Excluded / Deferred Item | Rationale | Disposition |
|---|---|---|
| Permanent secondary fiber WAN path | LTE failover is sufficient at current traffic volume; a second fiber path carries an unjustified recurring cost at this stage | Deferred — flagged for future evaluation |
| Server room capacity beyond 24U | Room's physical dimensions cannot accommodate the standard 42U rack without a cooling retrofit outside the approved budget | Documented as an approved deviation; flagged for review at the 18-month growth mark |
| CCTV / physical access control | Owned by Facilities as a parallel workstream; this project only carries a dependency, not delivery responsibility | Out of scope by design, not a cut |

## 9. Scope Change Control

All scope changes are managed through a formal change-request process: the requester's ask is logged, a cost and schedule-impact assessment is obtained directly from the relevant contractor or vendor, and the decision is brought to the sponsor for disposition — rather than informally absorbed or rejected. Example: a mid-build request for an additional conference room with network/AV drops was logged, quoted, and approved within the same week with a small budget increase and zero schedule impact, because the contractor could fold it into an already-scheduled site visit.

## 10. Sign-Off

| Approver | Title | Signature | Date |
|---|---|---|---|
| | COO (Executive Sponsor) | | |
| | Head of IT Infrastructure (Delivery Sponsor) | | |
| | IT Infrastructure Project Manager | | |
| | Regional Operations Director | | |
| | Security Lead | | |

---
*Prepared by Prachi Sharma — IT Infrastructure Project Manager · Technical PM · Service Delivery Lead*
