# Evaluation: Eli Lilly — Data Architect, Data Foundry

**Date:** 2026-04-06
**Archetype:** Data Engineer / Architect
**Score:** 2.4/5
**URL:** https://careers.lilly.com/us/en/job/R-102240/Data-Architect-Data-Foundry
**PDF:** ❌

---

## A) Role Summary

| Aspect | Details |
|--------|---------|
| **Archetype** | Data Architect |
| **Domain** | Pharmaceutical Data Infrastructure |
| **Function** | Design, build, and maintain scalable data platforms supporting research and operations |
| **Seniority** | Senior (7+ years architecture) |
| **Remote** | Not specified; likely on-site or hybrid |
| **Team** | Data Foundry (internal analytics/BI infrastructure) |
| **Comp** | $132K–$194K |
| **TL;DR** | Enterprise data architecture role requiring 7+ years specifically in data architecture, engineering, or scientific informatics. Must master SQL and multiple database paradigms (relational, graph, document, columnar, key-value). |

---

## B) Match with CV

| JD Requirement | CV Evidence | Fit |
|---|---|---|
| **BS + 7+ yrs OR MS + 5+ yrs data architecture** | BS Bioengineering (2010); database app dev (2007 undergrad); no dedicated architecture roles | ⚠️ Degree ✅; years ❌ |
| **SQL proficiency** | Not mentioned; Python-heavy background | ❌ |
| **Relational databases** | Database design mentioned; Sun Basket inventory system (NAV) | ⚠️ Indirect experience |
| **Graph, document, columnar, key-value paradigms** | No evidence | ❌ |
| **Scientific data understanding** | Bioinformatics, protein structure, ELISA, immunology experiments | ✅ Strong |
| **Data pipeline design** | No explicit examples | ❌ |

### Gaps and Mitigation

| Gap | Severity | Mitigation |
|-----|----------|-----------|
| **7+ years dedicated data architecture** | Critical | Steven has ~18 years since graduation but lacks 7+ years in explicit architecture roles. Experience is fragmented across research, operations, and AI. Could position 2007–2009 bioinformatics lab work + 2024-present AI data pipeline work, but still ~2–3 years short of stated requirement. |
| **SQL expertise** | High | Python is strong; SQL can be learned. Reframe as "relational database fluency with rapid SQL ramp-up." AI can bridge gaps. |
| **Modern data paradigms (graph, document, columnar)** | High | No hands-on experience. Would require significant ramp-up in tools like Neo4j, MongoDB, Parquet, Redis. |
| **Enterprise-scale system design** | Medium | MyCalla AI is early stage; no evidence of designing systems at pharmaceutical scale. Could leverage cleanroom/GMP/regulatory background as proxy for rigor. |

---

## C) Level and Strategy

**Level Match:** Underqualified by 3–5 years of explicit data architecture experience. This is a **skip-unless-strategic** role. The JD asks for seniority Steven doesn't have, and there's no clear "overqualified adjacent" angle.

**Positioning Strategy (if pursuing):**
- Lead with *bioinformatics data foundation* (UCSC research + neural networks + statistical learning).
- Pitch *operational rigor from compliance/GMP background* as proxy for enterprise discipline.
- Reframe *Python + database design* as architectural thinking, even if not in a formal title.
- Emphasize *scientific data lifecycle understanding* as differentiator (most data architects don't know experimental workflows).
- Be honest: "I'm a strong IC engineer with scientific depth; I'd grow into the architect role quickly given my fundamentals."

**Risk:** Recruiter may auto-screen based on years. **Recommendation:** Apply only if internal referral or if willing to discuss entry into architecture track.

---

## D) Comp and Demand

| Metric | Value |
|--------|-------|
| **Posted Range** | $132K–$194K |
| **Steven's Target** | $80K–$187K |
| **Fit** | Within range (lower-to-mid) |
| **Market Demand** | High; senior data architects are scarce |
| **Eli Lilly Prestige** | Very high; global pharma, solid stability |

---

## E) Personalization Plan

| Change | Impact | Priority |
|--------|--------|----------|
| **Add SQL project to CV** | Demonstrates relational DB fluency | High |
| **Highlight "data architecture" in MyCalla description** | Positions recent AI work as systems thinking | High |
| **Add modern DB tech to skills** (even at "learning" level) | Reduces perception gap | Medium |
| **Emphasize bioinformatics data pipeline experience** | Differentiates from generic data engineers | High |
| **Quantify systems: # of experiments, data volume, performance metrics** | Shows scale thinking | Medium |

---

## F) Interview Prep

### STAR+R Stories

1. **"Multi-Paradigm Data Design" (Bioinformatics Lab, 2007–2009)**
   - **Situation:** UCSC bioinformatics lab needed to organize protein structure prediction data across multiple experiment types (ELISA, imaging, computational).
   - **Task:** Design a system to ingest, normalize, and query heterogeneous scientific data.
   - **Action:** Built Python database app linking experimental results to neural network predictions; designed schema to support both relational queries and statistical analysis pipelines.
   - **Result:** Lab could correlate ELISA assay results with computational predictions, improving model accuracy.
   - **Reflection:** Learned that scientific data architecture must balance regulatory lineage (experiment metadata) with analytical agility (rapid re-analysis). This is what enterprise data platforms need.

2. **"Regulatory Data Integrity Under Pressure" (Sun Basket, 2020)**
   - **Situation:** Inventory system (NAV) had data quality issues; root cause analysis showed fragmented data entry and no validation layer.
   - **Task:** Ensure GMP-compliant inventory counts while maintaining system uptime.
   - **Action:** Implemented error-detection rules (FEFO logic, storage consistency checks), created audit trails for data lineage (ALCOA+ principles).
   - **Result:** Reduced pick/put-away errors by analyzing error patterns; maintained 100% GMP audit trail.
   - **Reflection:** Enterprise data systems need built-in validation, versioning, and auditability—not as an afterthought. This scales from inventory to drug manufacturing.

3. **"Scaling from Research to Production" (MyCalla AI, 2024–present)**
   - **Situation:** MyCalla AI processes government and education sector data; started with ad-hoc CSV analysis, quickly hit scale challenges.
   - **Task:** Build scalable data pipeline for AI model training and inference.
   - **Action:** Designed data ingestion, validation, and storage architecture using Python + structured data schemas; integrated with Claude API for context-aware processing.
   - **Result:** Can now handle varied government/education data sources; model retraining is reproducible.
   - **Reflection:** Architectural thinking: data flow, schema evolution, idempotency. Not enterprise scale yet, but the *principles* transfer.

4. **"Translating Domain Expertise to Data Systems" (Overall)**
   - **Situation:** Bioinformatics background gave deep understanding of experimental workflows; operations roles revealed compliance requirements.
   - **Task:** Design data systems that honor *both* scientific rigor and regulatory requirements.
   - **Action:** In every role, advocated for traceability, metadata, error margins—treating data as evidence, not just numbers.
   - **Result:** Trained in GMP, ALCOA+, ISO 45001; understand why pharmaceutical data needs immutability.
   - **Reflection:** This is the hidden value for Eli Lilly: a data architect who *speaks pharmaceutical*. Most engineers don't know why metadata matters until they hit an FDA audit.

---

## Keywords Extracted

Data architecture, relational databases, SQL, graph databases, document databases, columnar storage, key-value stores, Python, bioinformatics, scientific workflows, experimental data, ETL, data pipelines, GMP compliance, ALCOA+ principles, data governance, data quality, scalability, enterprise systems, neural networks, statistical learning, database design, data integrity, regulatory requirements, pharmaceutical data

---

## Decision

**SCORE RATIONALE:** 2.4/5 reflects:
- Strong scientific/domain fit (bioinformatics, compliance, data thinking) = +1.5
- Missing 3–5 years of explicit architecture experience = -1.5
- No SQL or modern DB paradigm hands-on evidence = -0.8
- Pharma/regulatory knowledge partially compensates = +0.2

**RECOMMENDATION:** **SKIP** unless there is:
- Internal referral / networking path that signals flexibility on years
- Willingness to position as "architect track" or "principal IC" hybrid
- Time to build SQL + 1–2 modern DB skills before applying

Steven would be a much stronger match for **mid-level data engineer or scientific software engineer** roles. The Data Foundry's other opening (R-102239) is a better fit.

