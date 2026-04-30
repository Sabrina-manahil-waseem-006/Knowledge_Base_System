# Systematic Literature Review (PRISMA 2020)

**Topic:** Scalable Rule-Based Inference Architecture (SRBIA): A Systematic Literature Review of Modular Designs, Algorithms, and Performance Optimization (1978-2024)

**Methodology:** PRISMA 2020 — Preferred Reporting Items for Systematic Reviews and Meta-Analyses.

---

## Project Overview
This repository contains the complete workflow, data, and documentation for a Systematic Literature Review (SLR) focused on the architectural evolution and scalability of Rule-Based Systems. The research specifically addresses the "Rule Explosion" problem and identifies patterns for high-performance Knowledge-Based Systems (KBS).

**Review Team:** - **Lead Reviewer (R1):** SE-23006 (Search, Screening, Extraction)
- **Secondary Reviewer (R2):** SE-23003 (Validation, RoB Assessment)

---

## Research Questions (RQs)
- **RQ1:** What techniques and algorithms (e.g., Rete, TREAT) are used in existing rule-based inference systems?
- **RQ2:** What architectural patterns (Modular, Layered, Distributed) are employed in scalable KBS?
- **RQ3:** What are the key limitations (Rule Explosion, Latency) of current systems?
- **RQ4:** How do existing systems handle high-volume scalability and hybrid knowledge representation?

---

## Repository Structure
Following the PRISMA 2020 reporting standard, this repository is organized as follows:

| Folder | Description |
| :--- | :--- |
| **00-admin** | Team roles, decision logs, and project timeline. |
| **01-protocol** | Official SLR protocol (PRISMA-P) and research objectives. |
| **02-searches** | Full Boolean search strings and raw database exports. |
| **03-screening** | Title/Abstract screening and full-text eligibility logs (n=500 to n=12). |
| **04-included-studies** | Master list of 12 final papers with BibTeX metadata. |
| **05-data-extraction** | Populated extraction sheets with architectural and performance variables. |
| **06-risk-of-bias** | Methodological quality assessment using a custom RoB instrument. |
| **07-synthesis** | Thematic coding, comparative tables, and narrative synthesis notes. |
| **08-manuscript** | Final Manuscript draft, Figures, and PRISMA Flow Diagram. |
| **09-supplementary** | Replication package, search strings, and supplementary index. |
| **10-prisma-checklist** | Completed PRISMA 2020 27-item compliance checklist. |

---

## Review Summary
- **Identification:** 500 records identified via Google Scholar & Semantic Scholar.
- **Screening:** 400 deduplicated records screened; 100 assessed for full-text eligibility.
- **Inclusion:** 12 high-impact studies selected for final synthesis.
- **Quality:** Inter-rater agreement (Cohen's Kappa) of **0.85**.

---

## How to Use This Repository
1. **Search Replication:** See `/02-searches/` for the exact search strings to re-run the study.
2. **Data Verification:** Extraction details for each study are located in `/05-data-extraction/`.
3. **Compliance:** The full PRISMA 2020 mapping is available in `/10-prisma-checklist/`.

---
**Submission Status:** Final Semester Project (KBS)  
**Date:** April 30, 2026