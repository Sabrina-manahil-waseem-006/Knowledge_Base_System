# Systematic Review (Pure PRISMA 2020 Template)

**Topic:** Knowledge Graph-Augmented Retrieval for Large Language Models
(GraphRAG): A Systematic Review of Architectures, Applications, and
Evaluation Practices (2022-2026)

**Methodology:** PRISMA 2020 — Preferred Reporting Items for Systematic
Reviews and Meta-Analyses (Page et al., BMJ 2021;372:n71)

## About this template

This is a sample template demonstrating folder structure and spreadsheet
organization for a systematic review conducted **strictly under PRISMA 2020**.
It does not incorporate Kitchenham & Charters software engineering
methodology, snowballing procedures, or other community extensions.

### Why pure PRISMA 2020?

PRISMA 2020 is the most widely adopted reporting guideline for systematic
reviews across disciplines. It is mandatory or strongly preferred at most
health and life sciences journals, and is increasingly accepted at
computer science venues including ACM Computing Surveys, Knowledge-Based
Systems (Elsevier), Information Fusion, and IEEE Access.

### What's intentionally NOT in this template

- No Kitchenham & Charters citations or methodology references
- No backward or forward snowballing procedures
- No SE-specific quality rubrics
- No "Stage 1 / Stage 2 / Stage 3" Kitchenham phasing

### Disclaimer

All numbers, papers, authors, and DOIs in this template are illustrative.
Do not cite anything from this template in real academic work.

## Topic relevance

Knowledge Graph-augmented retrieval for LLMs (commonly called GraphRAG) is
one of the most active research areas in knowledge-based systems as of 2026.
It combines classical KBS concepts (knowledge graphs, structured reasoning,
symbolic representation) with state-of-the-art generative AI to address LLM
hallucinations and improve factual grounding. Major venues publishing in this
area include NAACL, EMNLP, ICLR, ACL, ACM CSUR, Knowledge-Based Systems
(Elsevier), Information Fusion, and AAAI.

## How to use this template

1. Copy this entire folder to start your own systematic review.
2. Rename the top-level folder to reflect your topic.
3. Replace the topic-specific content in `01-protocol/` with your own
   research questions and PICO/PECO/PCC.
4. Empty out the example data in screening and extraction spreadsheets
   while keeping the column structure.
5. Update `00-admin/` for your team and timeline.
6. Register your protocol on PROSPERO (health) or OSF Registries (general)
   before beginning data collection.

## Folder layout

```
SLR-GraphRAG-LLM/
|-- 00-admin/                   Team, timeline, decision log
|-- 01-protocol/                Registered protocol with PRISMA-P items
|-- 02-searches/                Database search strings and exports
|-- 03-screening/               Title/abstract and full-text screening
|-- 04-included-studies/        Master list and PDFs
|-- 05-data-extraction/         Extraction form and populated sheet
|-- 06-risk-of-bias/            Risk of bias assessment per PRISMA item 11
|-- 07-synthesis/               Narrative synthesis and analysis
|-- 08-manuscript/              Drafts, PRISMA flow diagram, checklist
|-- 09-supplementary/           Replication materials for reviewers
\-- 10-prisma-checklist/        Item-by-item PRISMA 2020 compliance
```

## PRISMA 2020 reference

Page MJ, McKenzie JE, Bossuyt PM, et al. The PRISMA 2020 statement: an
updated guideline for reporting systematic reviews. BMJ 2021;372:n71.
doi:10.1136/bmj.n71
