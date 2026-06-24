# Risk Register
### Greenfield Connect — Coimbatore Branch Network & Infrastructure Build

> *Self-directed case study artifact. See repository [README](../README.md) for context.*

Scoring uses a standard 1–5 scale for Probability and Impact (Score = P × I). Risks scoring **15+** are treated as project-threatening and require sponsor visibility within 24 hours per the charter's escalation condition; **8–14** require an active, owned mitigation plan; **below 8** are monitored.

## Risk Scoring Matrix

| Risk ID | Risk Description | Probability (1–5) | Impact (1–5) | Score | Risk Level | Mitigation | Owner | Residual Risk | Status |
|---|---|---|---|---|---|---|---|---|---|
| RR-01 | WAN circuit delivery (7-wk lead time) slips past the 12-week working window | 3 | 5 | 15 | **High** | Ordered immediately on provisional address verification; LTE failover router secured as documented contingency | PM | Low (failover in place) | Closed — mitigated |
| RR-02 | Server room physical constraints (no cooling, single 15A outlet) prevent standard architecture | 4 | 4 | 16 | **High** | Redesigned to 24U high-density rack with lower-heat-output switches; formally approved as documented deviation | Systems Engineer | Low — flagged for 18-month capacity review | Closed — resolved |
| RR-03 | Cabling contractor under-resourced, jeopardizing certification deadline | 3 | 4 | 12 | Medium-High | Independent site walkthroughs (not self-reported %); second crew added at contractor's cost under contract terms | PM | Low | Closed — resolved |
| RR-04 | Electrical permit inspection delay pushes UPS install and all downstream work | 3 | 4 | 12 | Medium-High | Re-sequenced schedule for parallel bench-testing of switch pre-configuration | PM | Low — 4-day slip fully absorbed | Closed — realized & absorbed |
| RR-05 | Guest Wi-Fi not truly isolated from corporate VLAN (security baseline gap) | 2 | 5 | 10 | Medium | Treated as a blocking finding at design review; required true VLAN segmentation before sign-off | Network Engineer / Security | Low | Closed — resolved pre-install |
| RR-06 | WAN/LTE automatic failover misconfigured, fails silently under real outage | 3 | 5 | 15 | **High** | Caught in scheduled failover test (not assumed from config); fixed same day; independent retest required before close | Network Engineer | Low | Closed — resolved |
| RR-07 | UPS underperforms rated capacity under real installed load / ambient temperature | 2 | 5 | 10 | Medium | Held live load test as a non-negotiable gate despite schedule pressure to skip it | Systems Engineer | Low | Closed — passed with margin |
| RR-08 | Wi-Fi coverage gap from floor obstructions not present during original survey | 3 | 3 | 9 | Medium | Mock opening day used as a real-world validation beyond the original signal survey | Network Engineer | Low | Closed — resolved with added AP |
| RR-09 | Emergency-call routing defaults to head-office address instead of branch location | 2 | 5 | 10 | Medium | Routine compliance check caught it pre-go-live; held design sign-off until corrected | Telephony Specialist | Low | Closed — verified 3/3 on retest |
| RR-10 | Helpdesk lacks on-call coverage trained on the new telephony platform | 3 | 3 | 9 | Medium | Held handover open one additional week until two engineers completed vendor training | Helpdesk Manager | Low | Closed — resolved before formal handover |
| RR-11 | Mid-build scope addition (conference room) absorbed informally, creating untracked cost/schedule exposure | 2 | 2 | 4 | Low | Routed through formal change-request process with quote + schedule-impact assessment | PM | Low | Closed — approved, zero schedule impact |
| RR-12 | Day-three "slow network" report triggers unnecessary, costly hardware investigation | 2 | 3 | 6 | Low | Required utilization data before assuming root cause; avoided escalation by isolating the actual (legacy server) cause | Network Engineer | Low | Closed — correctly diagnosed |

## Risk Distribution Summary

| Risk Level | Count | % of Register |
|---|---|---|
| High (15+) | 2 | 17% |
| Medium-High (10–14) | 4 | 33% |
| Medium (8–9) | 4 | 33% |
| Low (<8) | 2 | 17% |

---

## Notes on This Register
- Every **High** and **Medium-High** risk in this register was realized to some degree during delivery — this is by design: the register reflects the actual risks tracked live during the project, not a hypothetical pre-mortem. See the [RAID Log](./11-raid-log-full.md) for the narrative status history behind each entry.
- The two highest-scoring risks (RR-01, RR-02, RR-06 at 15–16) map directly to the strongest "judgment under pressure" stories in this case study — useful to keep in mind when selecting which risk to walk through in an interview.
- No risk in this register was closed by accepting it silently; every High/Medium-High item has a documented mitigation, approval, or retest trail.
