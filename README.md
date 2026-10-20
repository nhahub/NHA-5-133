# Generative Campaign Studio with Brand Guidelines
### Brand-Governed Content Studio | Project 03 (Applied ML Track)
**Digital Egypt Pioneers Initiative (DEPI) — Graduation Project**

---

## 📌 Project Overview
An end-to-end automated digital advertising studio powered by Generative AI on AWS. The system generates marketing ad copies and promotional product visuals from campaign briefs, while strictly enforcing corporate brand guidelines, eliminating hallucinations, and validating pricing/specifications before publication.

---

## 👥 Project Team Members
| # | Member Name | Role |
|---|---|---|
| 1 | **Hegazy Adel** | Team Lead & ML Cloud Architect |
| 2 | **Ahmed Hamdy** | Lead ML / Prompt Engineer |
| 3 | **Ahmed Abdelqader** | Serverless Backend & Data Validation Engineer |
| 4 | **Ahmed Gehad** | Frontend UI/UX & Integration Engineer |

---

## 🏗️ System Architecture & AWS Services
- **Generative AI Foundation Models:** Amazon Bedrock (LLMs for Text Generation & Diffusion Models for Imagery).
- **Backend & Validation Engine:** AWS Lambda (Event-driven validation against product catalog specs & negative lexicons).
- **Workflow Orchestration:** AWS Step Functions (Multi-step pipeline and retry logic).
- **Database:** Amazon DynamoDB (Product catalog, audit logs, and status tracking).
- **Asset Storage:** Amazon S3 (Marketing assets and brand guidelines).
- **Frontend Interface:** Web UI (Streamlit / AWS Amplify) with Human-in-the-Loop review & approval.

---

## 🎯 Core Objectives & KPIs
- **70%+ Reduction** in campaign draft turnaround time.
- **100% Price & Specification Accuracy** (Zero Hallucination).
- **100% Policy Violation Interception** via deterministic rule checking.
- **End-to-End Latency < 20s** with fully serverless cost-efficient infrastructure.

---

## 📅 Milestones Roadmap
- **Phase 1 (16 Oct 2026):** Planning, Requirements & Theoretical Literature.
- **Phase 2 (06 Nov 2026):** System Analysis & Architecture Design.
- **Phase 3 (30 Nov 2026):** AWS Implementation, Pipeline & UI Integration.
- **Phase 4 (04 Dec 2026):** Final QA, Testing, Demo & Final Presentation.
