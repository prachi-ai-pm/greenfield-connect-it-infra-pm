# Business Case

**Project Name:** Greenfield Connect — Coimbatore Branch Network & Infrastructure Build
**Document Owner:** Prachi Sharma, IT Infrastructure Project Manager
**Status:** Approved
**Version:** 1.0
**Date:** [Insert Approval Date]

---

## 1. Executive Summary

Bridgeline Logistics won a customer contract requiring an 85-person regional distribution and operations branch in Coimbatore to be fully operational within a fixed 14-week window, in a building with no existing IT infrastructure. Greenfield Connect is the project to design, procure, build, and stabilize the full network and IT infrastructure for that branch — structured cabling, LAN/WAN, firewall and security, Wi-Fi, telephony, server room build-out, endpoint deployment, and a 24/7 support handover — before the committed open date.

This business case converts a fixed deadline and an empty building into a bounded, fundable, technically grounded plan, with the customer-imposed go-live date treated as a non-negotiable constraint that all other planning had to flex around.

## 2. Problem Statement

| Dimension | Detail |
|---|---|
| Driver | A contractually committed customer go-live date, with a penalty clause — not an internal preference |
| Site condition | Shell-and-core building handover only: no cabling, no network, no phones, no Wi-Fi, no server room |
| Headcount to support | 85 employees on day one |
| Working window | Nominally 14 weeks; revealed to be 12 working weeks for IT-controlled work once mandatory landlord certification timelines were mapped against the calendar |

## 3. Strategic Alignment

The project directly supports the company's contractual commitment to the customer underpinning the branch opening, and establishes a reusable reference model (standard architecture, vendor relationships, handover process) for the two additional branch openings already in the regional pipeline.

## 4. Options Considered

| Option | Description | Assessment |
|---|---|---|
| **Do nothing / delay** | Push the go-live date | Not viable — date is contractually fixed with a customer penalty clause |
| **Use a generic, non-standard architecture for speed** | Design around whatever hardware is fastest to source, regardless of fit with company standards | Faster on paper, but creates an unsupportable one-off site and risks a weaker security posture under time pressure |
| **Recommended: Standard reference architecture, adapted for real site constraints** | Follow the company's standard branch architecture, with documented, approved deviations only where the physical site genuinely requires it (e.g., server room sizing) | Preserves supportability and security baseline while still meeting the fixed date; deviations are logged with rationale rather than absorbed silently |

## 5. Recommended Solution

Deliver the branch's network and IT infrastructure against the company's standard branch reference architecture, with formally documented and approved deviations where physical site constraints require them (most notably the server room redesign — see the Scope Statement and supporting Network Design Document). Procure the longest-lead-time items (WAN circuit, core switching hardware) in parallel with requirements finalization, rather than sequentially, to protect the schedule.

## 6. Costs

| Item | Amount |
|---|---|
| One-time build cost (approved) | ₹38.5 lakh (hardware, cabling, contractor labor) |
| Recurring cost (approved) | ~₹62,000/month (WAN circuit, telephony licensing, warranty support) |
| Approved budget variance (Stage 4 change request — additional conference room) | Small increase, approved within 3 days; absorbed with zero schedule impact |
| Actual budget variance at 30-day review | +3.4% versus approved (revised) budget, driven entirely by the approved conference-room change request |

## 7. Benefits & Return

| Benefit | Quantification |
|---|---|
| Contractual commitment met | Zero customer-facing slippage on the go-live date — directly protects the customer contract and the associated revenue/relationship |
| Network reliability | 99.7% uptime in the first 30 days, against a ≥ 99.5% target |
| Full readiness for staff | 85/85 endpoints provisioned and verified before day one |
| Reusable delivery model | Standard architecture, vendor relationships (e.g., Vendor B's master agreement), and the VoIP onboarding lessons are explicitly being carried into the next two branch openings in the regional pipeline |

**Indicative return:** The primary "return" on this build is avoidance of contractual penalty exposure tied to the customer go-live date, plus a validated, reusable delivery template that reduces both cost and risk on the next two branch rollouts already planned. *(Illustrative; not a financial guarantee.)*

## 8. Risks to the Business Case

| Risk | Impact on Case |
|---|---|
| WAN circuit lead time (7 weeks) against a 12-week working window | Directly threatened the go-live date; required immediate ordering and a documented LTE failover contingency |
| Server room scope materially larger than initially assumed | Threatened to exceed the original budget envelope; required a budget variance request grounded in the certified site survey |
| Facilities vs. IT differing definitions of "site ready" | Could have caused a false-ready handoff between teams; resolved via a jointly signed-off readiness checklist |

## 9. Funding Decision & Conditions

| Decision | Detail |
|---|---|
| **Outcome** | Approved by COO |
| **Conditions** | Any risk to the go-live date escalated within 24 hours of identification, not batched into weekly reporting |
| **Funding envelope** | ₹38.5 lakh one-time + ~₹62,000/month recurring, as confirmed at charter approval |

## 10. Actual Outcomes (Go-Live + 30 Days)

| Metric | Target | Actual | Status |
|---|---|---|---|
| Go-live date slippage | Zero | Zero — opened on committed date | Met |
| Network uptime (first 30 days) | ≥ 99.5% | 99.7% | Met |
| Endpoints provisioned before day one | 85 / 85 | 85 / 85 | Met |
| Post-go-live P2+ incidents | N/A (tracked, no target) | 1 (legacy server resizing, resolved within SLA) | Tracked |
| Budget variance | Within 10% of approved (revised) budget | +3.4%, driven by the approved conference-room change request | Met |
| Support handover acceptance | Signed off by Helpdesk Manager | Signed off, one week later than original plan | Met (delayed for the right reason — see Lessons Learned) |

This validates the original business case: the branch opened on its contractually committed date with zero slippage, uptime and endpoint readiness both exceeded target, and the only budget variance traced directly to an approved, deliberate scope change rather than execution slippage.

---
*Prepared by Prachi Sharma — IT Infrastructure Project Manager · Technical PM · Service Delivery Lead*
