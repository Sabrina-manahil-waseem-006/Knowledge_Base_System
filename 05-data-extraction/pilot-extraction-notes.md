# Pilot Extraction Notes

## Pilot conducted: 2026-06-26

**Studies piloted:** S01, S02, S03, S06, S10 (Selected to span different eras of KBS, from early expert systems to modern scalable rule engines)

**Reviewers:** R1 (SE-23006) and R2 (SE-23003) independently extracted each study, then compared results in a 90-minute session.

## Issues identified during pilot

### Issue 1: Rule Base Size Measurement
**Problem:** Some papers report the number of individual "IF-THEN" rules, while others report "K-lines" (lines of knowledge). Original form had a single "Rule Count" column.
**Resolution:** Split into two columns: "Rule Base Size (Count)" and "Knowledge Representation Type" (e.g., Flat Rules, Frames, or Semantic Nets). When count is not explicitly given, it is noted as "Not Specified".

### Issue 2: Scalability Metric Variances
**Problem:** Studies use different metrics for performance (e.g., inference cycles, time in ms, or rules fired per second). How to capture consistency?
**Resolution:** Standardized on "Inference Throughput" where possible. If only hardware-specific latency is given, it is recorded with a note about the hardware environment (CPU/RAM) in the "Scalability Notes" column.

### Issue 3: Multi-Strategy Engines
**Problem:** Many modern systems use a hybrid of Forward and Backward chaining. The extraction form had only one choice.
**Resolution:** Updated the "Inference Strategy" field to allow multiple entries (e.g., "Hybrid: Forward + Backward") to better capture the architectural complexity identified in RQ1.

### Issue 4: Architectural Pattern Ambiguity
**Problem:** Authors use different names for similar layers (e.g., "Knowledge Base" vs. "Production Memory").
**Resolution:** Standardized naming convention based on the report's conceptual layers: **Knowledge Layer**, **Reasoning Layer**, and **Interface Layer**.

### Issue 5: Verbatim Limitation Quotes
**Problem:** Reviewers paraphrased system limitations differently, which made it hard to synthesize RQ3 (Gaps).
**Resolution:** Added "Verbatim limitation quotes" column to the extraction sheet, requiring at least one direct quote from the "Conclusion" or "Discussion" section of each paper.

## Form changes after pilot

The extraction form template was updated on 2026-06-29. The 5 piloted studies (S01, S02, S03, S06, S10) were re-extracted using the new form to verify consistency and completeness.

## Time per study (pilot)

- S01: 38 minutes
- S02: 52 minutes (complex architectural analysis)
- S03: 41 minutes
- S06: 35 minutes
- S10: 28 minutes

**Average:** 39 minutes per study. Estimated total for 12 studies: ~8 hours.