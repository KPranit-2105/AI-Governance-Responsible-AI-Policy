# Project 3: Responsible AI Policy & Operating Model

**GRC Domain:** Enterprise Policy Development & Governance Operating Model  
**Role Simulated:** Head of AI Governance / Risk Policy Director  
**Framework/Regulation:** NIST AI RMF (Govern Function) · EU AI Act (Articles 9, 14, 28–29) · ISO/IEC 42001 · OECD AI Principles  
**Project Type:** Fictional Portfolio Case Study (Audit-Defensible Artefact Pack)  

---

## Executive Summary & Recruiter Quick-Reference

This project establishes the formal Responsible AI Policy, governance operating model, and use case intake review process for **NorthStar Financial Services**. Translating high-level AI principles into operational controls, this project delivers committee charters, role descriptions, intake workflows, a Policy-to-Control Traceability Matrix, and a completed AI Use Case Request (AUCR) submission for system `NS-AI-008`.

All artefacts are provided in Markdown (`.md`), Word Document (`.docx`), and CSV Spreadsheet (`.csv`) formats.

---

## Business Problem & Scenario

Following the identification of unverified high-risk AI deployments in Projects 1 and 2, NorthStar's Board mandated the immediate creation of an enterprise AI governance framework. NorthStar lacked standardized policies, clear accountability structures, intake triage procedures, and vendor procurement checks. Individual business units were acquiring and deploying AI models independently without central risk approval or legal consultation.

---

## Objective & Scope

- **Objective:** Formulate a binding Responsible AI Policy grounded in 5 operational principles (Fairness, Transparency, Accountability, Safety/Robustness, Human Oversight), design a cross-functional AI Governance Operating Model, build a 6-stage Use Case Review Process, and create a standard AUCR intake template.
- **Scope:** Enterprise-wide deployment across all business units, internal development teams, SaaS vendors, and third-party AI integrations.

---

## Artefact Inventory (Markdown, Word & CSV)

### 1. Markdown & Word Reports
| Document Title | Markdown File | Word Document (`.docx`) | Description |
|---|---|---|---|
| **Policy Overview & Framework** | [`README.md`](./README.md) | [`README.docx`](./README.docx) | Executive overview, methodology, key structural decisions |
| **Responsible AI Policy** | [`responsible-ai-policy.md`](./responsible-ai-policy.md) | [`responsible-ai-policy.docx`](./responsible-ai-policy.docx) | 5 core principles, lifecycle requirements, vendor terms, Policy-to-Control Traceability Matrix |
| **AI Use Case Review Process** | [`ai-review-process.md`](./ai-review-process.md) | [`ai-review-process.docx`](./ai-review-process.docx) | 6-stage review workflow, intake triage (Standard vs Enhanced Review), Auditor Q&A |
| **Governance Operating Model** | [`governance-operating-model.md`](./governance-operating-model.md) | [`governance-operating-model.docx`](./governance-operating-model.docx) | Governance hierarchy, committee charters, role descriptions, decision authority matrix, ERM integration |
| **AUCR Template & Sample Submission** | [`aucr-template-and-sample.md`](./aucr-template-and-sample.md) | [`aucr-template-and-sample.docx`](./aucr-template-and-sample.docx) | AUCR intake form template with filled sample for `NS-AI-008` HireAssist Pro and AGPO sign-off record |

### 2. Tabular Data & CSV Spreadsheets
| Dataset Title | CSV File (`.csv`) | Primary Content |
|---|---|---|
| **Policy-to-Control Traceability Matrix** | [`policy-traceability-matrix.csv`](./policy-traceability-matrix.csv) | Mapping of 5 policy principles to operational Control IDs, evidence artefacts, and owners |
| **Roles & Responsibilities Matrix** | [`roles-and-responsibilities.csv`](./roles-and-responsibilities.csv) | Responsibilities across Board, CRO, Committee, AGPO, System Owners, Legal, CISO, and ML Engineering |
| **Approval Authority Levels** | [`approval-authority-levels.csv`](./approval-authority-levels.csv) | Required sign-off body (AGPO, System Owner, Committee) by EU AI Act Risk Tier |
| **Decision Authority Matrix** | [`decision-authority-matrix.csv`](./decision-authority-matrix.csv) | Approval, rejection, suspension, and escalation authority matrix across governance bodies |
| **Reporting Calendar** | [`reporting-calendar.csv`](./reporting-calendar.csv) | Reporting frequency, owners, and target audiences for dashboards, incident logs, and annual reviews |
| **ERM & Governance Interactions** | [`erm-governance-interactions.csv`](./erm-governance-interactions.csv) | Integration points between AI Governance and ERM, DPO, CISO, Legal, Procurement, and Internal Audit |
| **AUCR Intake Fields Specification** | [`aucr-intake-fields.csv`](./aucr-intake-fields.csv) | Required information fields for AI Use Case Request submissions |
| **Triage Outcomes Matrix** | [`triage-outcomes-matrix.csv`](./triage-outcomes-matrix.csv) | Triage classification outcomes, actions, and review routing pathways |
| **Enhanced Review Panel Structure** | [`enhanced-review-panel-roles.csv`](./enhanced-review-panel-roles.csv) | Reviewer contributions for High-Risk system reviews |
| **Review Frequency by Risk Tier** | [`review-frequency-by-tier.csv`](./review-frequency-by-tier.csv) | Periodic review frequencies for High, Limited, and Minimal risk systems |

---

## Key Findings & Structural Decisions

- **Proportionality Principle:** Lightweight 2-week Standard Review for Minimal/Limited Risk vs rigorous 4–6 week Enhanced Review for Annex III High Risk.
- **Operational Accountabilities:** System Owners retain ultimate operational accountability for model performance and oversight enforcement; the AGPO coordinates triage and policy compliance.
- **Shadow AI Mitigation:** Integrated Procurement gates, CASB web proxy endpoint filtering, and embedded Functional AI Champions across all business units.

---

## Skills Demonstrated

- **Policy Design & Mapping:** Translating abstract regulatory mandates into testable control specifications (`CTRL-POL-001` to `CTRL-POL-005`).
- **Operating Model Architecture:** Structuring committee charters, quorum requirements, decision authority matrices, and cross-functional reporting lines.
- **Workflow Optimization:** Designing non-blocking triage pathways that maintain compliance rigor while enabling technical innovation.
- **Intake Form Engineering:** Structuring AUCR templates that capture technical architecture, data provenance, and human oversight mechanics upfront.

---

## Portfolio Disclaimer

*This project is a simulated GRC portfolio case study developed for demonstration purposes. All company names, employee personas, and system telemetry are fictional. Real-world regulatory compliance requires formal legal and technical evaluation by qualified professionals.*
