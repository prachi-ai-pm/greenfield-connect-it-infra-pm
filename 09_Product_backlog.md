# Product Backlog — Cutover & Hypercare Kanban
### Greenfield Connect — Coimbatore Branch Network & Infrastructure Build

> *Self-directed case study artifact. See repository [README](../README.md) for context.*

This backlog covers only the cutover-weekend and hypercare-week Kanban board referenced in the [Sprint Plan](./13-sprint-plan.md) — the one part of Greenfield Connect run iteratively. Priority follows MoSCoW (Must / Should / Could / Won't-this-sprint).

## Backlog

| ID | Item | Priority | Sprint | Owner | Status |
|---|---|---|---|---|---|
| B-01 | Final network/firewall config push verified against Stage 3 baseline | Must | Sprint 1 | Network Engineer | Done |
| B-02 | Image and domain-join all 85 endpoints, verify connectivity | Must | Sprint 1 | Systems Engineer | Done |
| B-03 | Activate telephony numbers; test inbound/outbound calling | Must | Sprint 1 | Telephony Specialist | Done |
| B-04 | Verify emergency-call routing from at least 3 physical locations | Must | Sprint 1 | Telephony Specialist | Done |
| B-05 | Full physical site walkthrough — every desk, port, AP | Must | Sprint 1 | PM + full team | Done |
| B-06 | Diagnose and fix patch-panel connectivity gap (Corner office) | Must | Sprint 1 | Network Engineer | Done — 20 min resolution |
| B-07 | Staff and run on-site war room with hourly status checks | Must | Sprint 1 | PM | Done |
| B-08 | Run daily 8am check-in with branch lead | Must | Sprint 2 | PM | Done (Day 1–7) |
| B-09 | Investigate Day-3 "slow network" report | Must | Sprint 2 | Network Engineer | Done — traced to legacy server |
| B-10 | Redistribute VoIP quick-reference card to departments that missed it | Should | Sprint 2 | PM | Done |
| B-11 | Monitor and follow up on VoIP adoption normalization | Should | Sprint 2 | PM | Done — normalized within 3 days |
| B-12 | Prepare handover package draft (topology, as-built schedule, escalation paths) | Should | Sprint 2 | Network/Systems Engineers | Carried to Stage 7 |
| B-13 | Identify and log helpdesk on-call coverage gap for new telephony platform | Could | Sprint 2 | Helpdesk Manager | Carried to Stage 7 (became D-04 dependency) |
| B-14 | Capacity-review flag for 18-month server room growth point | Won't this sprint | — | PM | Logged as deferred scope (Stage 7) |

## Backlog Health at Sprint Close

| Metric | Sprint 1 | Sprint 2 |
|---|---|---|
| Items committed | 7 | 7 |
| Items completed within sprint | 7 | 5 |
| Items carried forward | 0 | 2 (B-12, B-13 — intentionally, as Stage 7 inputs) |
| Unplanned items added mid-sprint | 1 (B-06, discovered Sunday) | 1 (B-09, discovered Day 3) |

---

## Notes on This Backlog
- Items B-12 and B-13 were **deliberately** carried forward rather than force-closed within the sprint — both needed sponsor/helpdesk-manager-level sign-off that belonged to the Stage 7 handover gate, not a Kanban board. Forcing them closed early would have meant a shallow handover.
- Two backlog items (B-06, B-09) were unplanned discoveries, not pre-identified scope — consistent with why this window used a Kanban board rather than a fixed sprint backlog locked a week in advance.
