# User Stories — Cutover & Hypercare
### Greenfield Connect — Coimbatore Branch Network & Infrastructure Build

> *Self-directed case study artifact. See repository [README](../README.md) for context.*

User stories below map to the [Product Backlog](./14-product-backlog.md) items for the cutover-weekend and hypercare-week Kanban board. Each follows standard "As a / I want / So that" format with acceptance criteria.

| Story ID | Backlog ID | User Story | Acceptance Criteria |
|---|---|---|---|
| US-01 | B-01 | As the **Network Engineer**, I want the final network and firewall configuration verified against the Stage 3 baseline before cutover, so that no last-minute drift causes an unverified production state at go-live. | Config diff against baseline shows zero unapproved deviations; sign-off logged before Saturday close |
| US-02 | B-02 | As the **Systems Engineer**, I want all 85 endpoints imaged, domain-joined, and connectivity-verified before opening morning, so that every staff member has a working workstation on day one. | 85/85 endpoints show successful domain join and network connectivity in the deployment log |
| US-03 | B-03 | As a **branch employee**, I want my desk phone working with correct inbound/outbound calling from the moment I arrive, so that I can do my job without a manual workaround on day one. | 100% of registered handsets pass inbound and outbound test calls before Monday |
| US-04 | B-04 | As a **branch employee**, I want any emergency call I place to route to the correct local responder, so that a real emergency isn't delayed by a misconfigured location. | Emergency test calls route correctly from 3/3 tested physical locations |
| US-05 | B-05 | As the **PM**, I want a full physical walkthrough of every desk, port, and AP before staff arrive, so that we catch any installation defect ourselves instead of staff discovering it for us. | Walkthrough completed and signed off Sunday; any defect found is logged and assigned before Monday |
| US-06 | B-06 | As a **branch employee in the affected corner office**, I want my network connectivity restored quickly if there's a wiring defect, so that a labeling mistake doesn't cost me a morning of lost work. | Issue diagnosed and resolved within the runbook's 30-minute response target |
| US-07 | B-07 | As the **branch lead**, I want a project team physically on-site and reachable on opening day, so that I have someone to escalate to immediately if something doesn't work as expected. | War room staffed and reachable for the full opening day; hourly status checks logged |
| US-08 | B-08 | As the **branch lead**, I want a daily check-in during the first week, so that small issues get raised and fixed before they pile up into bigger support problems. | Daily 8am check-in held for 7 consecutive days; issues raised are logged the same day |
| US-09 | B-09 | As the **Network Engineer**, I want to verify actual utilization data before assuming a "slow network" report means a capacity problem, so that we don't trigger an expensive, unnecessary hardware escalation. | Utilization data reviewed before any remediation action is taken; root cause documented |
| US-10 | B-10 | As a **branch employee unfamiliar with the new VoIP system**, I want a quick-reference card readily available, so that I can use my new phone correctly without defaulting back to my personal mobile. | Quick-reference card distributed to all departments; confirmed received by department leads |
| US-11 | B-11 | As the **PM**, I want to track VoIP adoption through the week, so that I catch a behavioral/awareness gap early rather than letting old habits become permanent workarounds. | Adoption monitored daily; usage normalized to expected levels within the hypercare week |
| US-12 | B-12 | As the **Regional Helpdesk Manager**, I want a handover package that documents *why* the build looks the way it does, not just its final state, so that my team can support this site without re-discovering context the project team already knows. | Handover package includes a "design decisions and known deviations" section before acceptance |
| US-13 | B-13 | As the **Regional Helpdesk Manager**, I want my on-call rotation trained on this branch's new telephony platform before I accept handover, so that a 2am incident doesn't hit an engineer with no relevant training. | At least 2 helpdesk engineers complete vendor-provided training before handover sign-off |

---

## Notes on These Stories
- Stories are written from whichever stakeholder actually had the need — branch employees, the PM, engineers, or the helpdesk manager — rather than defaulting every story to a single persona, since this was infrastructure delivery serving several distinct user types at once.
- US-12 and US-13 deliberately read like requirements rather than feature requests — appropriate here, since the "product" being delivered to the helpdesk was operational readiness, not a software feature.
