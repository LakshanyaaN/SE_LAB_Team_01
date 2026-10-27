# Smart Lab Equipment Slot Reservation Portal

[![Deliverables CI](https://github.com/LakshanyaaN/Smart-Lab-Equipment-Slot-Reservation-Portal/actions/workflows/ci.yml/badge.svg)](https://github.com/LakshanyaaN/Smart-Lab-Equipment-Slot-Reservation-Portal/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Software Engineering](https://img.shields.io/badge/UE24CS341A-Deliverables%201%20%26%202-brightgreen.svg)](#-deliverables-part-1-ieee-specifications)

A web-based **Smart Lab Equipment Slot Reservation Portal** designed for educational and research institutions to manage high-value laboratory instruments, enforce calibration checks, prevent double-booking with database-level locks, track returns, and manage late-return penalties.

---

## 👥 Engineering Team & GitHub Profiles

**Course:** Software Engineering Lab-01 (UE24CS341A) | **Team No:** 001 | **Problem Statement:** PS-001

| Team Member | SRN / Roll No | Role | Module Domain |
|---|---|---|---|
| **N. Lakshanyaa** | `PES1UG24AM169` | Team Lead & Frontend Architect | UI Components, Search/Filter Engine & Reservation UI |
| **Mohammed Arfan Asgar** | `PES1UG24AM163` | Database Engineer & Systems Analyst | Schema Design, Concurrency Control & Database Lock Isolation |
| **Kshama** | `PES1UG24AM142` | Backend & Security Architect | REST APIs, Authentication, RBAC & Calibration Verification Service |
| **Manjunatha H J** | `PES1UG24AM157` | QA Lead & Continuous Integration | Test Automation, Return/Late-Return Tracker & Notification Adapter |

---

## 📑 Deliverables Part-1: IEEE Specifications (Word Documents & Draw.io)

All Part-1 specifications are provided as formal specifications and native UML diagrams maintained in `docs/`:

| Deliverable | Standard / Format | Document Link | Scope & Highlights |
|---|---|---|---|
| **1. Software Requirements Specification** | IEEE Std 830-1998 (`.docx` / `.md`) | [docs/1_SRS_SmartLabEquipment.md](docs/1_SRS_SmartLabEquipment.md) | 10 Functional Requirements (FR-001 to FR-010), 6 Measurable NFRs, 4 Security Objectives & Embedded UML Use Case Specifications |
| **2. Software Test Plan** | IEEE Std 829-2008 (`.docx` / `.md`) | [docs/2_TestPlan_SmartLabEquipment.md](docs/2_TestPlan_SmartLabEquipment.md) | Test Strategy, Section 5 Security Validation, Full Traceability Matrix & 27 Detailed Test Cases (TC-001 to TC-027) |
| **3. Architecture & Design Specification** | IEEE Std 1016-2009 (`.docx` / `.md`) | [docs/3_ArchitectureDesign_SmartLabEquipment.md](docs/3_ArchitectureDesign_SmartLabEquipment.md) | 3-Tier Layered Pattern, Component Decomposition, 3 Sequence Workflows, REST API Specifications & 3NF ER Relational Schemas |
| **4. UML Use Case Diagram (draw.io)** | draw.io XML / PNG | [docs/use_case_diagram.drawio](docs/use_case_diagram.drawio) | Native editable draw.io diagram covering Student, Lab Technician, Notification & Auth actors (UC-01 to UC-15) |

---

## 🚀 Deliverables Part-2: Agile Sprints & Backlog (20 Issues)

The project backlog is organized into **exactly 20 issues** (maximum 20 issues as per requirements), assigned with **Fibonacci Story Points** (`[SP-1]` to `[SP-5]`), and planned across **Two Sprints**:

- **Sprint 1 [19th Oct to 31st Oct 2026]**: Core Setup, Authentication, Equipment Catalog, Calibration Check, Real-time Slot Availability & Concurrency Lock Engine.
- **Sprint 2 [2nd Nov to 7th Nov 2026]**: Equipment Return & Late-Return Penalty Engine, Technician Override Portal, Notification Adapter, Security Hardening & Release Freeze.

### 📅 Sprint 1 Backlog [19th Oct to 31st Oct 2026] (32 SP)
| Issue # | Title & Requirement | SP | Assigned Team Member |
|---|---|:---:|---|
| **#1** | `[SP-5] FR-001: 2-Hour Slot Reservation & 7-Day Advance Window Engine` | 5 | [@LakshanyaaN](https://github.com/LakshanyaaN) |
| **#2** | `[SP-5] FR-002: Automatic Equipment Calibration Status Verification Engine` | 5 | [@Kshama](https://github.com/Kshama) |
| **#3** | `[SP-5] FR-003: Concurrency Control & Database Lock Engine (Double-Booking Defense)` | 5 | [@ArfanAsgar](https://github.com/ArfanAsgar) |
| **#4** | `[SP-2] DEV-01: Continuous Integration Pipeline & Verification Test Harness` | 2 | [@ManjunathaHJ](https://github.com/ManjunathaHJ) |
| **#5** | `[SP-3] FR-006: User Authentication & Role-Based Access Control (Student vs Technician)` | 3 | [@Kshama](https://github.com/Kshama) |
| **#6** | `[SP-3] FR-007: Equipment Search & Lab Category Filtering Service` | 3 | [@LakshanyaaN](https://github.com/LakshanyaaN) |
| **#7** | `[SP-5] UI-01: Responsive React Dashboard for Real-time Equipment Slot Booking` | 5 | [@LakshanyaaN](https://github.com/LakshanyaaN) |
| **#8** | `[SP-3] SEC-01: JWT Session Security, Password Hashing & Parameterized Query Guard` | 3 | [@Kshama](https://github.com/Kshama) |
| **#9** | `[SP-1] DEV-02: Sprint 1 Working Product Demo Video Recording & Baseline Verification` | 1 | [@ManjunathaHJ](https://github.com/ManjunathaHJ) |

---

### 📅 Sprint 2 Backlog [2nd Nov to 7th Nov 2026] (31 SP)
| Issue # | Title & Requirement | SP | Assigned Team Member |
|---|---|:---:|---|
| **#10** | `[SP-5] FR-004: Equipment Return Logging & Late-Return Penalty Evaluation Engine` | 5 | [@ManjunathaHJ](https://github.com/ManjunathaHJ) |
| **#11** | `[SP-3] FR-005: Technician Equipment Availability & Calibration Status Management Portal` | 3 | [@Kshama](https://github.com/Kshama) |
| **#12** | `[SP-3] FR-008: Student Self-Service "My Reservations" & Token Management Portal` | 3 | [@LakshanyaaN](https://github.com/LakshanyaaN) |
| **#13** | `[SP-3] FR-009: Technician Oversight Portal for All Reservations & Late Activity` | 3 | [@Kshama](https://github.com/Kshama) |
| **#14** | `[SP-2] FR-010: Notification Adapter Integration for Reservation Confirmations & Alerts` | 2 | [@ManjunathaHJ](https://github.com/ManjunathaHJ) |
| **#15** | `[SP-3] DEV-03: Execution of Full 27-Case Test Suite & Concurrency Load Verification` | 3 | [@ManjunathaHJ](https://github.com/ManjunathaHJ) |
| **#16** | `[SP-3] NFR-001: Database Indexing, Locking Optimization & 200ms Latency Tuning` | 3 | [@ArfanAsgar](https://github.com/ArfanAsgar) |
| **#17** | `[SP-3] NFR-002: ACID Durability Verification & Fault-Tolerant Transaction Snapshots` | 3 | [@ArfanAsgar](https://github.com/ArfanAsgar) |
| **#18** | `[SP-3] SEC-02: Immutable Audit Logging for Reservation Mutations & Status Overrides` | 3 | [@Kshama](https://github.com/Kshama) |
| **#19** | `[SP-2] DEV-04: Architectural Decision Records & Traceability Documentation` | 2 | [@ArfanAsgar](https://github.com/ArfanAsgar) |
| **#20** | `[SP-1] DEV-05: Sprint 2 Demo Video, Final Deliverable Assembly & v1.0 Release Freeze` | 1 | [@ManjunathaHJ](https://github.com/ManjunathaHJ) |

---

## 💻 Technology Stack Plan
- **Presentation Layer:** React.js Single Page Application (Vite, Tailwind CSS, Lucide Icons).
- **Application Layer:** Node.js / Express RESTful API (`/api/v1/`).
- **Persistence Layer:** PostgreSQL 15+ with `btree_gist` extension for exclusion constraints & ACID locks.
- **CI/CD Pipeline:** GitHub Actions automated workflow executing Jest & Supertest integration suites.