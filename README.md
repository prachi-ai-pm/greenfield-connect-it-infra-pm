# Greenfield Connect
### An End-to-End IT Infrastructure Project Management Case Study
**New Branch Office Network & Infrastructure Rollout · Discovery Through Post-Go-Live Stabilization**

**Author:** Prachi Sharma — IT Infrastructure Project Manager · Technical PM · Service Delivery Lead

---

> **A note on this repository**
> This is a self-directed case study built to demonstrate IT infrastructure project management methodology end to end, independent of any AI/ML tooling. The company, stakeholders, and figures are illustrative, modeled on realistic mid-market network and branch-infrastructure rollouts. It is presented honestly as a self-built simulation — not a claimed client engagement — intended to give hiring panels a concrete, walkable example of how I structure, govern, and deliver a traditional infrastructure programme from kickoff to stabilized operations.

---

## Project Overview

Bridgeline Logistics is a fictionalized 600-employee regional freight and distribution company. It won a contract requiring it to open a new 85-person regional distribution and operations branch in Coimbatore within a fixed 14-week window — driven by a customer go-live commitment — with the building handed over shell-and-core: no cabling, no network, no phones, no Wi-Fi, no server room.

This repository documents the end-to-end management of **Greenfield Connect** — the project to design, procure, build, and stabilize the full network and IT infrastructure for that branch: structured cabling, LAN/WAN, firewall and security, Wi-Fi, telephony, server room and rack build-out, endpoint deployment, and a 24/7 support handover — all before the branch's committed open date.

## Project Snapshot

| | |
|---|---|
| **Role** | IT Infrastructure Project Manager (sole PM, cross-functional and vendor-facing lead) |
| **Duration** | 14 weeks design-to-go-live, plus a 4-week stabilization and handover period |
| **Team** | 1 PM, 1 network engineer, 1 systems/server engineer, 1 telephony specialist, 2 external contractors (cabling, electrical), 1 hardware vendor account manager, part-time security and procurement partners |
| **Methodology** | Waterfall-based stage-gate delivery, with a lightweight Kanban board for cutover-week task tracking |
| **Sponsor** | Head of IT Infrastructure, with the COO as executive sponsor |
| **Core scope** | Structured cabling (Cat6A), core/access switching, firewall and SD-WAN, controller-based Wi-Fi, server room build (rack, UPS, cooling), VoIP telephony, 85 endpoint deployments, documented support handover |
| **Outcome (go-live + 30 days)** | Branch opened on the committed date with zero customer-facing slippage; 99.7% network uptime in the first 30 days; 1 post-go-live P2 incident, resolved within SLA |

## How This Repository Is Organized

Each stage of the project produced a formal artifact, captured in [`/documents`](./documents):

| Stage | Document | What It Covers |
|---|---|---|
| 1 | [Project Charter & Business Case](./documents/01-project-charter-business-case.md) | Scope, objectives, success metrics, budget, constraints, approval gate |
| 2 | [Requirements, BOM & Vendor Comparison](./documents/02-requirements-vendor-comparison.md) | Functional/non-functional requirements, bill of materials, vendor evaluation |
| 3 | [Network Design & Architecture Decision Record](./documents/03-network-design-architecture-decision-record.md) | Topology, server room redesign, segmentation, ADRs |
| 4 | [Build Schedule, RAID Log & Change Request Log](./documents/04-build-schedule-raid-log-change-request-log.md) | Dependency-aware schedule, risk/issue tracking, scope change handling |
| 5 | [Test Plan, Go/No-Go & UAT Sign-Off](./documents/05-test-plan-go-no-go-uat-signoff.md) | Pass/fail test criteria, results, go/no-go review by workstream |
| 6 | [Cutover Runbook & Hypercare Log](./documents/06-cutover-runbook-hypercare-log.md) | Minute-by-minute cutover plan, war room, first-week hypercare |
| 7 | [Handover Runbook, Acceptance & 30-Day Review](./documents/07-handover-runbook-acceptance-30-day-review.md) | Support handover, operational thresholds, post-go-live outcomes |

A consolidated [Outcomes Summary](./documents/outcomes-summary.md) compares Stage 1 targets against what was actually delivered at the 30-day mark.

## Why This Project Exists

This case study is paired with my AI/ML-focused PM simulations (ServiceDesk Copilot, ChangeGuard AI, Project Skyline) to demonstrate range: this repository shows classic, stage-gated infrastructure delivery discipline under a fixed, non-negotiable deadline — vendor and procurement management, physical site constraints, testing rigor, and a live cutover weekend — without any AI/ML tooling in the loop.

---
*Self-directed simulation, not an employer engagement. Figures, vendors, and stakeholders are illustrative.*

