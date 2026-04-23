# Decision Log

Append-only record of all methodological decisions for transparency and
reproducibility per PRISMA 2020 item 24c (amendments to protocol).

---

## 2026-01-15 — Topic scope definition

**Decision:** Limit scope to "GraphRAG" — defined as the integration of
knowledge graphs (or other structured graph representations) with retrieval-
augmented generation for large language models. Exclude pure vector RAG
without graph structure, and exclude knowledge graph construction work that
does not connect to LLM generation.

**Rationale:** A scoping search returned over 8,000 hits on broad
"RAG + LLM," of which only a focused subset addressed graph-based retrieval.
Narrowing to GraphRAG produces a tractable, novel synthesis target.

---

## 2026-02-01 — Date range

**Decision:** Restrict search to 2022-2026.

**Rationale:** RAG was introduced by Lewis et al. (2020); the term "GraphRAG"
gained traction in 2023 with the Microsoft Research preprint. A 2022 cutoff
captures the field's emergence while excluding pre-RAG knowledge graph
question answering work that has been covered by earlier reviews.

---

## 2026-02-12 — Language restriction

**Decision:** Include only papers written in English.

**Rationale:** Team has no multi-language capability; risk of misinterpretation
of methodological details exceeds value of broader linguistic coverage. This
limitation will be acknowledged in the discussion.

---

## 2026-02-18 — Publication type

**Decision:** Include peer-reviewed journal articles, peer-reviewed
conference papers from CORE A* and A venues, and ACL Anthology papers.
Exclude arXiv preprints, workshop papers, and theses.

**Rationale:** This field moves rapidly through preprints, but peer review
provides a quality floor necessary for synthesis reliability. The CORE
ranking and ACL Anthology cutoffs are objective and replicable.

---

## 2026-03-05 — Search string finalization

**Decision:** Final canonical search string locked after pilot search
returned manageable counts on Scopus (1,243 records). Saved in
`02-searches/search-string-canonical.txt`.

---

## 2026-04-08 — Screening tool

**Decision:** Use Rayyan for dual-independent screening with blinding enabled.

**Rationale:** Rayyan supports the dual-independent screening workflow with
reviewer blinding required by PRISMA 2020 item 8 (selection process).
