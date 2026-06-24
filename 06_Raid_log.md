# RAID Log (Full)
### Greenfield Connect — Coimbatore Branch Network & Infrastructure Build

> *Self-directed case study artifact. See repository [README](../README.md) for context.*

This is the complete RAID log maintained and reviewed weekly with the sponsor throughout delivery. The condensed version in [Stage 4](./04-build-schedule-raid-log-change-request-log.md) shows the entries most relevant to the build coordination narrative; this log captures every Risk, Assumption, Issue, and Dependency raised across all seven stages.

## Risks

| ID | Stage Raised | Description | Owner | Impact if Realized | Status |
|---|---|---|---|---|---|
| R-01 | 1 | "14 weeks" includes non-working time consumed by mandatory building certification | PM | Schedule compression on IT-controlled work | Closed — re-baselined to 12-week working window in charter |
| R-02 | 2 | WAN circuit lead time (7 wks) leaves minimal buffer against 12-week window | PM | Go-live delay if circuit slips | Mitigated — LTE failover router ordered as contingency |
| R-03 | 3 | Standard 42U rack may not physically fit the server room | Systems Engineer | Forced costly cooling retrofit or schedule delay | Closed — resolved via 24U high-density redesign (Stage 3) |
| R-04 | 4 | Electrical permit inspection could slip past planned UPS install date | Electrical Contractor | Delay to rack power-on and all downstream work | Realized & absorbed — parallel bench-testing plan executed |
| R-05 | 4 | Cabling contractor may be under-resourced to hit certification deadline | PM | Schedule slip on cabling-dependent work | Mitigated — second crew added at contractor's cost |
| R-06 | 5 | WAN/LTE failover may not trigger correctly under real outage conditions | Network Engineer | Branch loses connectivity with no fallback | Realized & resolved — found in testing, fixed, retested |
| R-07 | 5 | UPS may underperform rated capacity under actual load/ambient conditions | Systems Engineer | Server-room-down incident on day one | Closed — live load test passed with margin |
| R-08 | 5 | Wi-Fi signal survey may not reflect final floor obstructions (racking, fixtures) | Network Engineer | Coverage dead zones at go-live | Realized & resolved — found at mock opening day, AP added |
| R-09 | 7 | Helpdesk on-call rotation may lack telephony-platform-trained engineers | Helpdesk Manager | Unsupported P2/P3 incidents post-handover | Closed — training completed before handover accepted |

## Assumptions

| ID | Stage Raised | Description | Validation Status |
|---|---|---|---|
| A-01 | 1 | "Shell and core" includes a designated, power/cooling-ready server room space | Invalidated — utility closet only, no cooling, single 15A outlet |
| A-02 | 1 | The 14-week window is fully usable working time | Invalidated — 9 days consumed by mandatory inspections |
| A-03 | 2 | Primary WAN provider can deliver within standard 6–8 week lead time | Partially validated — delivered at 7 weeks, within range but with minimal buffer |
| A-04 | 2 | Hardware vendor can meet delivery window at standard (non-expedited) pricing | Validated |
| A-05 | 3 | Standard reference architecture (42U rack) applies to this site | Invalidated — required documented 24U deviation |
| A-06 | 1 | Landlord delivers electrical and fire-safety certification on the committed date | Validated |

## Issues

| ID | Stage Raised | Description | Owner | Resolution |
|---|---|---|---|---|
| I-01 | 4 | Cabling contractor reported 70% completion; site walkthrough found ~45% actually terminated/labeled | PM | Re-baselined using as-built, run-by-run cable schedule; root cause (understaffing) addressed with a second crew |
| I-02 | 6 | Patch panel mislabeling left a corner of the office without connectivity on opening morning | Network Engineer | Diagnosed and fixed within 20 minutes via runbook's named owner and response-time target |
| I-03 | 6 | Day-three report described network as "slow" | Network Engineer | Utilization data ruled out network capacity issue; traced to an unsized legacy application server |
| I-04 | 6 | Uneven VoIP adoption in week one — staff defaulting to personal mobiles | PM | Traced to a missed quick-reference card distribution in two departments; redistributed, usage normalized in 3 days |
| I-05 | 7 | Ticket volume 12 days post-launch running above regional baseline | Helpdesk Manager | Ticket categories showed "how do I" VoIP questions, not faults; refresher session brought volume back to baseline |

## Dependencies

| ID | Stage Raised | Description | Dependent On | Status |
|---|---|---|---|---|
| D-01 | 3 | Production firewall rule deployment requires Security sign-off | Security Team | Closed — approved at Stage 3 gate |
| D-02 | 4 | Rack build / switch config depends on electrical & UPS install completion | Electrical Contractor | Managed — re-sequenced around permit delay via parallel bench work |
| D-03 | 4 | Endpoint imaging depends on network being live | Network Engineer | Closed — sequenced per WBS, no slip |
| D-04 | 7 | Formal handover acceptance depends on helpdesk completing telephony platform training | Helpdesk Manager / Vendor | Closed — handover held open one extra week until training completed |
| D-05 | 2 | WAN circuit and core switching procurement depend on finalized requirements | Network/Systems Engineers | Closed — both ordered the same week requirements were finalized |

---

## Notes on This Log
- This RAID log is the actual governance mechanism referenced in Stage 4 — reviewed weekly with the sponsor, not a static end-of-project artifact.
- Cross-reference: items R-02, R-05, and I-01 connect directly to the [Risk Register](./12-risk-register.md), which scores and prioritizes the risk-type entries above using probability/impact rather than tracking status alone.
