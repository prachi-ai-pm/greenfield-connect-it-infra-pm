# Sprint Plan — Cutover & Hypercare
### Greenfield Connect — Coimbatore Branch Network & Infrastructure Build

> *Self-directed case study artifact. See repository [README](../README.md) for context.*

## A Note on Methodology

Greenfield Connect ran as a **Waterfall, stage-gated delivery** for good reason: site readiness, procurement lead times, and construction-linked work (cabling, electrical, rack build) don't suit iterative sprints — you can't "iterate" on a cable run or re-prioritize a WAN circuit order mid-sprint. That's documented in the [Project Charter](./01-project-charter-business-case.md).

The one phase where a lightweight, iterative approach genuinely fit was the **final cutover weekend through first-week hypercare** — fast-moving, high-uncertainty, multi-owner work where daily re-prioritization mattered more than a fixed long-range schedule. This is the "lightweight Kanban board for cutover-week task tracking" referenced in the project snapshot. The sprint plan, backlog, and user stories below cover **only this window** — they are not retrofitted onto the rest of the project.

## Sprint Structure

| Sprint | Duration | Goal |
|---|---|---|
| Sprint 1 — Cutover Weekend | Sat–Mon (3 days) | Execute the cutover runbook end to end with zero customer-facing slippage on the committed go-live morning |
| Sprint 2 — Hypercare Week | Mon–Fri (5 days, Day 1–7 post-go-live) | Catch and resolve adoption, usability, and stability issues before they become unresolved support tickets; hand confidence to the regional helpdesk |

## Sprint 1 — Cutover Weekend

**Sprint Goal:** Branch network, telephony, and endpoints fully live and verified before staff arrive Monday morning, with zero unresolved blocking issues.

| Day | Focus | Team Capacity |
|---|---|---|
| Saturday | Final network/firewall config push; verification against Stage 3 baseline | Network Engineer (full day) |
| Saturday | Endpoint deployment — image, domain join, connectivity verification (85 units) | Systems Engineer (full day) |
| Sunday | Telephony cutover — number activation, inbound/outbound test, emergency routing | Telephony Specialist (full day) |
| Sunday | Full physical site walkthrough — every desk, port, AP | PM + full team (afternoon) |
| Monday | War room staffed; hourly status checks with branch lead | PM (full day) |

**Sprint Review Outcome:** Completed with one defect found and fixed within the sprint (mislabeled patch panel port, resolved in 20 minutes via the runbook's named-owner/response-time structure).

## Sprint 2 — Hypercare Week

**Sprint Goal:** Stabilize day-to-day operations and surface any adoption or technical issue within 24 hours of it occurring, rather than letting it surface later as an unowned support ticket.

| Day | Focus | Ceremony |
|---|---|---|
| Day 1–7 | Daily 8am check-in with branch lead — open-ended question, not a checklist | Daily stand-up equivalent |
| Day 3 | Diagnose "slow network" report | Ad hoc triage |
| Day 3–6 | Redistribute VoIP quick-reference materials to departments that missed them | Ad hoc fix |
| Day 7 | Sprint review — assess readiness to transition from hypercare to standard helpdesk support | Sprint review |

**Sprint Review Outcome:** Both issues raised during the week (legacy server resizing, VoIP adoption gap) were closed within the sprint. Helpdesk handover proceeded on schedule into Stage 7, with one additional week held open separately for telephony-platform training (a Stage 7 item, not part of this sprint).

---

## Notes on This Sprint Plan
- There was no Sprint 3 — once hypercare closed, the branch moved to standard helpdesk support cadence under the operational thresholds defined in the [Handover document](./07-handover-runbook-acceptance-30-day-review.md). Continuing sprint ceremonies past this point would have been process theater on a stabilized site.
- See the [Product Backlog](./14-product-backlog.md) and [User Stories](./15-user-stories.md) for the items worked within these two sprints.
