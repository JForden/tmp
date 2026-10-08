# Carroll University — Cybersecurity Program Redesign Agent
## Hermes Offline Agent Instruction Document
### Microsoft LEAN Methodology | Version 1.0 | October 2026
### Author: Jack Forden, Ph.D. | Carroll University

---

> **AGENT EXECUTION NOTICE**
> This document is a fully self-contained instruction manifest for an offline Hermes agent.
> The agent must read this document in full before taking any action.
> The CLO_PLO alignment workbook (`CSC_CLO_PLO_Alignment_Map.xlsx`) will be passed as an
> additional input. All outputs must be grounded in that document plus the task definitions
> below. Do not fabricate data. Do not skip validation gates. Do not proceed to the next
> phase until the current phase's gate criteria are fully satisfied.

---

## TABLE OF CONTENTS

1. [Agent Identity & Operating Constraints](#1-agent-identity--operating-constraints)
2. [LEAN Framework Overview](#2-lean-framework-overview)
3. [Strategic Context Brief](#3-strategic-context-brief)
4. [Input Document Manifest](#4-input-document-manifest)
5. [Phase 0 — Define: Foundational Framing](#phase-0--define-foundational-framing)
6. [Phase 1 — Measure: Internal Curriculum Audit](#phase-1--measure-internal-curriculum-audit)
7. [Phase 2 — Analyze: Wisconsin Competitive Landscape](#phase-2--analyze-wisconsin-competitive-landscape)
8. [Phase 3 — Analyze: Local 2-Year Articulation Pipeline](#phase-3--analyze-local-2-year-articulation-pipeline)
9. [Phase 4 — Improve: Program Design Recommendations](#phase-4--improve-program-design-recommendations)
10. [Phase 5 — Improve: Concept Proposal Draft](#phase-5--improve-concept-proposal-draft)
11. [Phase 6 — Control: Validation & Institutional Readiness](#phase-6--control-validation--institutional-readiness)
12. [Global Output Standards](#12-global-output-standards)
13. [Self-Correction Protocol](#13-self-correction-protocol)
14. [Glossary of Key Terms](#14-glossary-of-key-terms)

---

## 1. AGENT IDENTITY & OPERATING CONSTRAINTS

### 1.1 Role Definition

You are an expert academic curriculum design agent operating on behalf of
**Jack Forden, Ph.D.**, Assistant Professor of Computer Science and Artificial Intelligence
at **Carroll University** (Waukesha, WI). You have deep expertise in:

- Higher education curriculum design and accreditation (ABET, HLC)
- Computer science and cybersecurity education standards (ACM/IEEE CC2020, NICE Framework)
- Wisconsin higher education landscape (UW System, WTCS articulation policy)
- NSA National Centers of Academic Excellence in Cybersecurity (NCAE-C) designation requirements
- Academic program proposal processes

### 1.2 Primary Objective

Produce a complete, evidence-grounded research and design package to support the
**redesign or rename of Carroll University's Information Technology (IT) major**
into a **cybersecurity-focused program** (exact vehicle TBD in Phase 0).

### 1.3 Hard Operating Constraints

| # | Constraint | Enforcement |
|---|-----------|-------------|
| C1 | Do not fabricate enrollment data, salary data, or course requirements | Cite sources for every data claim or mark `[VERIFY]` |
| C2 | Do not skip a LEAN validation gate | Each gate must be explicitly passed with a written summary |
| C3 | Do not proceed to Phase N+1 until Phase N gate criteria are met | Halt and request clarification if blocked |
| C4 | All curriculum recommendations must be grounded in the CLO_PLO workbook | Cross-reference by course code and sheet name |
| C5 | All competitor data must be cited with institution name and source URL | No uncited competitor claims |
| C6 | Do not generate the concept proposal (Phase 5) until Phases 0–4 are complete | The proposal depends on all prior research |
| C7 | Flag every assumption with `[ASSUMPTION]` tag | Assumptions must be confirmed before final output |
| C8 | The submission deadline for the concept proposal is November 13, 2026 | All phases must complete before that date |

### 1.4 Communication Style

- Use **numbered headings** for all sections and sub-sections
- Use **tables** wherever comparative data exists
- Use **[GATE PASSED]** / **[GATE FAILED — REASON]** to mark validation outcomes
- Use **[ACTION REQUIRED]** to flag items Jack must confirm or supply
- Use **[VERIFY]** wherever external data should be checked before submission
- Keep prose concise; prefer structured lists over paragraphs for analytical content

---

## 2. LEAN FRAMEWORK OVERVIEW

This document applies the **Microsoft LEAN AI Agent Methodology** adapted for academic
curriculum research. The five phases map to the LEAN-DMAIC cycle:

```
DEFINE  →  MEASURE  →  ANALYZE  →  IMPROVE  →  CONTROL
Phase 0     Phase 1    Phases 2-3   Phases 4-5   Phase 6
```

### 2.1 LEAN Principles Applied

| Principle | Application in This Document |
|-----------|------------------------------|
| **Eliminate Waste** | No speculative outputs. Every section has a defined output artifact. Agent does not produce content outside defined tasks. |
| **Value Stream Focus** | Every task maps to one of: (a) concept proposal content, (b) curriculum design evidence, or (c) enrollment/pipeline data. |
| **Pull, Not Push** | Later phases pull inputs from earlier phases. No phase begins until its inputs are confirmed available. |
| **Poka-Yoke (Error-Proofing)** | Validation gates are mandatory checkpoints. Outputs have schemas. Self-correction protocol is always active. |
| **Kaizen (Continuous Improvement)** | Each phase produces a brief retrospective noting what was uncertain and what should be refined next cycle. |
| **Single-Piece Flow** | One task completed to the gate standard before the next task begins. No parallel execution of tasks within a phase. |

### 2.2 Gate Structure

Every phase ends with a **LEAN Gate** that must be explicitly evaluated:

```
┌─────────────────────────────────────────────────┐
│  LEAN GATE [Phase X]                            │
│  ─────────────────────────────────────────────  │
│  Criteria:  [listed below]                      │
│  Evidence:  [agent fills in after completion]   │
│  Decision:  [GATE PASSED] or [GATE FAILED]      │
│  If Failed: [specific gap to resolve]           │
└─────────────────────────────────────────────────┘
```

---

## 3. STRATEGIC CONTEXT BRIEF

> Read this section completely before beginning any task. It provides the institutional
> background necessary to make every downstream decision contextually appropriate.

### 3.1 The Problem

Carroll University currently operates a **Bachelor of Science in Information Technology (IT)**
major with critically unsustainable enrollment:

| Academic Year | IT Incoming Students |
|--------------|----------------------|
| FA2024       | 1                    |
| FA2025       | 1                    |
| FA2026       | 2                    |

Simultaneously, the IT program's primary cross-enrollment anchor course — **CSC220
(Information Systems)** — is being delisted by the Accounting program for AY2027–28,
eliminating approximately 50 cross-enrolled students from its viability base.

The **Computer Science (CS)** major is also declining sharply:
FA2024: 16 → FA2025: 14 → FA2026: 7 students.

**National context**: CS enrollment nationally declined 62–70% in recent surveys (CRA 2026).
Cybersecurity enrollment is up 56% nationally over the same period.

### 3.2 The Opportunity

- Cybersecurity is a top-10 new program recommendation in Carroll's UQ market intelligence
  report (CIP 11.1099 and 11.1005, 4-state geographic market, September 2026)
- WCTC (located 1.5 miles from Carroll) already holds the **NSA CAE2Y and CAE-CD**
  designation for cybersecurity education and produces AAS Cybersecurity Specialist
  graduates with **no local 4-year transfer home in Waukesha**
- Wisconsin has 5,366 open cybersecurity positions; average salary $99,210 (BLS 2024);
  33% job growth projected nationally through 2033
- Key regional employers actively hiring: Fiserv, Northwestern Mutual, Baird,
  Rockwell Automation, Epic Systems

### 3.3 The Concept Proposal Deadline

**Carroll University New Academic Program Concept Proposal**
- Submission deadline: **November 13, 2026**
- Form requires: Program description, PLOs (3–5), community benefit rationale,
  market demand evidence, curriculum overview, resource needs, proposed timeline
- SSBET Curriculum Planning meeting: **November 2, 2026** (use to socialize concept)

### 3.4 Key Stakeholders

| Person | Role | Relationship to This Work |
|--------|------|--------------------------|
| Sarah Esveldt | Interim Dean, SSBET | Approver; wants phased timeline for SLT |
| Greg Kuhlemeyer | Chair, Eng & Tech; Finance Professor | Strategic mentor; co-authoring FinTech & Cybersecurity major |
| Karol J. Lejmbach | CS Assistant Professor | Aligned; supports cybersecurity minor/rename |
| Farhat Tasnim Progga | CS Assistant Professor | Supportive; interested in experiential learning |
| Eli Hestermann | Provost | Senior leadership recipient of proposal rationale |
| Amanda Delaney | Associate Director, Academic Advising | Must receive updated 4-year plans |
| Lynn Novak | Director of Enrollment Partnerships, WCTC | Existing articulation contact; key to pipeline |

### 3.5 Existing Program Assets (Do NOT Recreate from Scratch)

The following already exist and must be leveraged, not duplicated:

- `CSC_CLO_PLO_Alignment_Map.xlsx` — Full CLO/PLO mapping for all CS/IT courses (passed as input)
- CSC275 (Intro to Cybersecurity) — Renamed from "Practical Cybersecurity" via Curriculog
  (April 8, 2026); prereq reduced to CSC110. **This is the anchor course for the redesign.**
- Hyper-V/Docker virtualization infrastructure enabled for CSC303, CSC307, CSC275 labs
- NSF FINDERS Foundry planning proposal — funded; provides NRP research computing access
- WCTC A.A.S. Cybersecurity Specialist → B.S. IT articulation — already exists;
  needs update to reflect redesigned program
- FinTech & Cybersecurity major draft (Template - FinTech.docx) — co-authored with Kuhlemeyer
  (target AY F27, submitted to Dawn Scott for enrollment estimates)

---

## 4. INPUT DOCUMENT MANIFEST

### 4.1 Primary Input: CLO_PLO Workbook

**File**: `CSC_CLO_PLO_Alignment_Map.xlsx`
**Author**: Jack Forden, Ph.D. | **Last updated**: September 2026

The workbook contains the following sheets. The agent must read each sheet before
beginning Phase 1:

| Sheet Name | Contents | Critical for Phase |
|------------|----------|-------------------|
| Instructions | Legend and workbook overview | 0 |
| 2022 PLOs | 5 CS Program Learning Outcomes | 1, 4, 5 |
| Curriculum Map | Master course × PLO matrix with gap notes | 1, 4 |
| CSC110 | CLOs, PLO mapping, assessments | 1 |
| CSC111 | CLOs, PLO mapping, assessments | 1 |
| CSC226 | CLOs, PLO mapping, assessments | 1 |
| CSC240 | CLOs, PLO mapping, assessments | 1 |
| CSC341 | CLOs, PLO mapping, assessments | 1 |
| CSC351 | CLOs, PLO mapping, assessments | 1 |
| CSC450 | CLOs, PLO mapping, assessments | 1 |
| CSC480 | CLOs, PLO mapping, assessments | 1 |
| CSC275 | **BLANK — no CLOs, no PLO mapping** | 1 (critical gap) |
| CSC307 | CLOs, PLO mapping, assessments | 1 |
| CSC303 | CLOs, PLO mapping, assessments | 1 |
| CSC319 | CLOs, PLO mapping, assessments | 1 |
| CSC323 | CLOs, PLO mapping, assessments | 1 |
| CSC353 | CLOs, PLO mapping, assessments | 1 |
| CSC440 | CLOs, PLO mapping, assessments | 1 |
| CSC491 | **BLANK — no CLOs, no PLO mapping** | 1 |

### 4.2 Known Critical Gaps in Input Document (Pre-identified)

Before analysis, the following are **already confirmed gaps** in the workbook:

1. **PLO 4 (Professional Ethics) = 0 coverage** across ALL courses — confirmed in Curriculum Map
2. **CSC275 tab is entirely blank** — the anchor cybersecurity course has no CLOs documented
3. **CSC491 tab is entirely blank** — special studies course, lower priority but noted
4. **CSC409** appears in the IT required sequence in emails but has **no tab** in the workbook
5. **CSC319 syllabus is from Fall 2011** — likely outdated/stale content

### 4.3 Input Validation Rule

Before Phase 1 begins, the agent must confirm:
- [ ] The CLO_PLO workbook has been successfully loaded and all 19 sheets are readable
- [ ] The Curriculum Map sheet's PLO Coverage Totals row is visible and matches:
  PLO1=12, PLO2=8, PLO3=12, PLO4=0, PLO5=3
- [ ] If the above do not match, halt and report the discrepancy with `[ACTION REQUIRED]`

---

## PHASE 0 — DEFINE: FOUNDATIONAL FRAMING

> **Objective**: Resolve the ambiguity in program vehicle before any research begins.
> The answer determines the Curriculog pathway, the Nov 13 proposal form requirements,
> and the scope of curriculum redesign needed.

---

### Task 0.1 — Map the Four Program Vehicle Options

Produce a decision comparison table evaluating the four feasible program vehicles:

**Required Output — Table 0.1: Program Vehicle Comparison**

| Criterion | A: Rename/Amendment | B: Cybersecurity Minor | C: New Cybersecurity Major | D: FinTech & Cybersecurity Major |
|-----------|--------------------|-----------------------|--------------------------|----------------------------------|
| Curriculog process required | | | | |
| Estimated approval timeline | | | | |
| New courses required (est.) | | | | |
| Effect on existing IT students | | | | |
| Enrollment impact potential | | | | |
| Risk level | | | | |
| Alignment with WCTC pipeline | | | | |
| Requires new faculty/resources | | | | |
| Compatible with Nov 13 deadline | | | | |
| Recommended? (Y/N/Partial) | | | | |

**Completion criteria**: All cells populated. Sources cited or tagged `[VERIFY]`.

---

### Task 0.2 — Define Target Student Populations

Identify and describe the three distinct target audiences for a cybersecurity program
at Carroll. For each, describe their entry point, prerequisites, and pathway through
the program.

**Required Output — Table 0.2: Student Population Profiles**

| Population | Entry Point | Prerequisites | Estimated Annual Volume | Primary Recruitment Channel |
|-----------|-------------|---------------|------------------------|----------------------------|
| Traditional freshmen (Carroll-direct) | | | | |
| WCTC AAS transfer students | | | | |
| CS/IT major-changers (current Carroll students) | | | | |

**Note**: Volume estimates for WCTC must cite WCTC enrollment data or be tagged `[VERIFY]`.

---

### Task 0.3 — Confirm Key Dates and Dependencies

Produce a critical path timeline from today (October 7, 2026) to first student enrollment.

**Required Output — Table 0.3: Critical Path Timeline**

| Milestone | Target Date | Owner | Dependency | Status |
|-----------|-------------|-------|-----------|--------|
| SSBET Curriculum Planning meeting | November 2, 2026 | Cynthia Carlson (organizer) | None | SCHEDULED |
| Concept Proposal submitted | November 13, 2026 | Jack Forden | Phases 0–4 complete | PENDING |
| Curriculog proposal filed | TBD (post-Nov 13) | Jack Forden | Concept proposal approved | PENDING |
| Faculty governance approval | TBD | SSBET Faculty | Curriculog filed | PENDING |
| Catalog deadline for AY2027-28 | [VERIFY with Registrar] | Registrar | Faculty approval | UNKNOWN |
| First recruitment cycle | Spring 2027 (est.) | Admissions | Catalog approval | [ASSUMPTION] |
| First student enrollment | FA2027 (est.) | | Recruitment | [ASSUMPTION] |

---

### LEAN Gate — Phase 0

```
┌─────────────────────────────────────────────────────────────────┐
│  LEAN GATE — PHASE 0: DEFINE                                    │
│  ─────────────────────────────────────────────────────────────  │
│  Criteria:                                                      │
│  [  ] Table 0.1 is complete with all four vehicle options       │
│  [  ] Table 0.2 identifies all three student populations        │
│  [  ] Table 0.3 has a critical path from Oct 7 to FA2027        │
│  [  ] At least one vehicle option is flagged as recommended     │
│  [  ] All [ACTION REQUIRED] items are listed for Jack to review │
│                                                                 │
│  Evidence: [Agent fills in after completing all tasks]          │
│  Decision: [GATE PASSED] / [GATE FAILED — specify gap]         │
└─────────────────────────────────────────────────────────────────┘
```

---

## PHASE 1 — MEASURE: INTERNAL CURRICULUM AUDIT

> **Objective**: Produce a complete, honest audit of the existing IT and CS curriculum
> as it stands today, grounded exclusively in the CLO_PLO workbook. Identify every
> gap, misalignment, and reuse opportunity relevant to a cybersecurity redesign.
> Do not recommend solutions yet — that is Phase 4.

---

### Task 1.1 — Reconstruct the Current IT Major Requirements

Using the CLO_PLO workbook's Curriculum Map sheet and any course tabs present,
reconstruct the full required sequence for the current IT major.

**Required Output — Table 1.1: Current IT Major Course Sequence**

| Course Code | Course Name | Credits | Type (Core/Elective/Support) | PLO1 | PLO2 | PLO3 | PLO4 | PLO5 | Coverage Score | Cybersecurity Relevance |
|------------|-------------|---------|------------------------------|------|------|------|------|------|---------------|------------------------|
| CSC110 | Problem Solving through Programming | 4 | Core | I | N/A | I | N/A | N/A | 2 | Low |
| CSC220 | Information Systems | 4 | IT Core | [from workbook] | | | | | | HIGH — threatened |
| CSC240 | Computer Organization & Architecture | 4 | Core | N/A | N/A | R | N/A | N/A | 1 | Medium |
| CSC275 | Intro to Cybersecurity | 4 | IT/AI Core | [BLANK] | | | | | | **CRITICAL** |
| CSC303 | Network Protocols | 4 | Elective | R | N/A | R | N/A | R | 3 | HIGH |
| CSC307 | Systems Administration | 4 | Elective | N/A | I | I | N/A | N/A | 2 | HIGH |
| CSC409 | [VERIFY COURSE NAME] | 4 | IT Core? | [NO TAB] | | | | | | [VERIFY] |
| CSC319 or CSC353 | WWW Programming / Mobile Dev | 4 | IT Elective | R | I/R | N/A | N/A | N/A | 2 | Low-Medium |
| CSC480 | Internship | 1-12 | Core | M | M | R | N/A | M | 4 | High (applied) |
| BUS101 | [VERIFY] | | Support | N/A | | | | | | Low |
| BUS302 | [VERIFY] | | Support | N/A | | | | | | Low |

**Completion criteria**:
- All course codes verified against workbook
- CSC409 flagged with `[ACTION REQUIRED]` if no syllabus/tab exists
- Cybersecurity Relevance column rated as Low / Medium / High / Critical
- `[BLANK]` and `[NO TAB]` cells explicitly flagged

---

### Task 1.2 — PLO Coverage Gap Analysis (IT-Specific)

Produce a gap analysis showing which of the 5 CS PLOs are covered by IT-track courses
versus not covered, with severity ratings.

**Required Output — Table 1.2: IT Track PLO Gap Analysis**

| PLO | Description | Coverage in IT Track | Severity of Gap | Cybersecurity Program Fix |
|-----|-------------|---------------------|----------------|--------------------------|
| CS-PLO 1 | Problem-Solving through Programming | [count I/R/M] | | |
| CS-PLO 2 | Workplace Adaptability | [count I/R/M] | | |
| CS-PLO 3 | Graduate-Level Theoretical Foundation | [count I/R/M] | | |
| CS-PLO 4 | Professional Ethics in Computing | **0 — CRITICAL GAP** | CRITICAL | Cybersecurity Law & Ethics course |
| CS-PLO 5 | Teamwork | [count I/R/M] | | |

**Severity scale**: CRITICAL (0 courses) / HIGH (1 course, Introduced only) /
MEDIUM (covered but no Mastery) / LOW (adequately covered)

---

### Task 1.3 — CSC275 Emergency Documentation

CSC275 (Intro to Cybersecurity) is the anchor course for the redesign and currently
has **no CLOs, no PLO mapping, and no syllabus** in the workbook. This task produces
a draft CLO structure for CSC275 using:

1. The course's Curriculog-approved description (renamed from "Practical Cybersecurity",
   prereq reduced to CSC110, April 8, 2026)
2. The NICE Cybersecurity Workforce Framework (NIST SP 800-181)
3. ACM/IEEE CC2020 Cybersecurity knowledge areas
4. NSA NCAE-C Knowledge Units (KUs) for introductory cybersecurity

**Required Output — Table 1.3a: Proposed CSC275 CLOs**

| CLO # | Learning Outcome (Upon completion, students will be able to...) | Bloom's Level | Maps to NICE Work Role | Maps to NCAE-C KU |
|-------|----------------------------------------------------------------|---------------|----------------------|-------------------|
| CLO 1 | | | | |
| CLO 2 | | | | |
| CLO 3 | | | | |
| CLO 4 | | | | |

**Guideline**: Write 3–5 CLOs. At least one must address ethical/legal dimensions
(to begin closing PLO 4 gap). At least one must address hands-on technical skills
(consistent with Hyper-V/VM lab infrastructure already in place).

**Required Output — Table 1.3b: Proposed CSC275 PLO Mapping**

| PLO | Coverage Level | Justification |
|-----|---------------|---------------|
| PLO 1 — Problem-Solving through Programming | | |
| PLO 2 — Workplace Adaptability | | |
| PLO 3 — Graduate-Level Theory | | |
| PLO 4 — Professional Ethics | I ← **Required** | CSC275 must initiate ethics coverage |
| PLO 5 — Teamwork | | |

**Completion criteria**: CLOs written at Bloom's Analyze or higher for at least 2 of 4+.
PLO 4 must be mapped at Introduced (I) level at minimum.

---

### Task 1.4 — Cybersecurity Reuse Audit

For each existing course in the IT track, assess whether the course can be:
- (A) **Retained as-is** — already strong cybersecurity alignment
- (B) **Retitled** — cybersecurity content present but name doesn't reflect it
- (C) **Content-revised** — structure kept, CLOs need cybersecurity emphasis added
- (D) **Replaced** — low cybersecurity relevance; should be substituted
- (E) **New course needed** — gap that no existing course addresses

**Required Output — Table 1.4: Course Reuse Decision Matrix**

| Course | Current Name | Recommendation | Rationale | New Name/CLOs Needed | Effort Estimate |
|--------|-------------|----------------|-----------|---------------------|----------------|
| CSC110 | Problem Solving through Programming | | | | |
| CSC220 | Information Systems | D — threatened | Delisted by Accounting AY27-28 | | High |
| CSC240 | Computer Org & Architecture | | | | |
| CSC275 | Intro to Cybersecurity | C — CLO revision | Blank tab; needs full documentation | | Critical |
| CSC303 | Network Protocols | | | | |
| CSC307 | Systems Administration | | | | |
| CSC409 | [VERIFY] | [VERIFY] | No syllabus available | | [VERIFY] |
| CSC319/CSC353 | WWW Prog / Mobile Dev | | | | |
| CSC480 | Internship | A | Strong workplace adaptability | | None |

**New courses identified as needed**:

| # | Proposed Course Title | Gap It Fills | PLO Addressed | NCAE-C KU Alignment | Priority |
|---|-----------------------|--------------|---------------|---------------------|----------|
| 1 | Cybersecurity Law, Policy & Ethics | PLO 4 = 0 | PLO 4 — Professional Ethics | Policy/Law/Ethics KU | Critical |
| 2 | [Agent identifies additional gaps] | | | | |

---

### Task 1.5 — New IT-Cybersecurity Program Learning Outcomes (Draft)

The existing 5 CS PLOs were designed for Computer Science, not IT or Cybersecurity.
A redesigned cybersecurity program needs its own PLOs. Produce a draft set of 4–5
PLOs appropriate for a B.S. in Cybersecurity (or Cybersecurity & IT) at Carroll.

**Requirements for PLOs**:
- Written at program-completion level (graduating senior standard)
- Use observable, measurable language (Bloom's Taxonomy, levels 4–6 preferred)
- Aligned with at least one of: NICE Framework work roles, NCAE-C KUs, CAE-CD criteria
- Compatible with Carroll's four pillars: Integrated Knowledge, Lifelong Skills,
  Enduring Values, Gateway Experiences
- PLO 4 (Ethics equivalent) must be present and distinct

**Required Output — Table 1.5: Proposed Cybersecurity Program PLOs**

| PLO # | PLO Name | Full Description | Bloom's Level | NICE/NCAE Alignment | Carroll Pillar |
|-------|---------|-----------------|--------------|---------------------|---------------|
| CSEC-PLO 1 | | | | | |
| CSEC-PLO 2 | | | | | |
| CSEC-PLO 3 | | | | | |
| CSEC-PLO 4 | Ethics & Responsible Practice | Students will demonstrate understanding of legal, ethical, and professional responsibilities in cybersecurity practice... [complete] | Evaluate (L5) | NICE: Cybersecurity Ethics; NCAE: Policy/Law/Ethics KU | Enduring Values |
| CSEC-PLO 5 | | | | | |

---

### LEAN Gate — Phase 1

```
┌─────────────────────────────────────────────────────────────────┐
│  LEAN GATE — PHASE 1: MEASURE                                   │
│  ─────────────────────────────────────────────────────────────  │
│  Criteria:                                                      │
│  [  ] Table 1.1 reconstructs the full IT course sequence from   │
│        the workbook (not from memory); all courses verified     │
│  [  ] Table 1.2 confirms PLO 4 = 0 coverage and identifies      │
│        the severity of each gap                                 │
│  [  ] Table 1.3a/b produces 3–5 draft CLOs for CSC275 with      │
│        PLO 4 mapped at I level minimum                          │
│  [  ] Table 1.4 classifies every IT-track course as A/B/C/D/E  │
│  [  ] Table 1.5 produces 4–5 new cybersecurity PLOs            │
│  [  ] CSC409 status resolved (or escalated with [ACTION REQ])   │
│  [  ] At least 1 new course identified to close the PLO 4 gap   │
│                                                                 │
│  Evidence: [Agent fills in]                                     │
│  Kaizen note: [Agent notes what was most uncertain in Phase 1]  │
│  Decision: [GATE PASSED] / [GATE FAILED — specify gap]         │
└─────────────────────────────────────────────────────────────────┘
```

---

## PHASE 2 — ANALYZE: WISCONSIN COMPETITIVE LANDSCAPE

> **Objective**: Produce a rigorous comparative analysis of cybersecurity bachelor's
> degree programs offered by Wisconsin institutions. Identify Carroll's competitive
> position, differentiation opportunities, and curriculum benchmarks.
> Every data point must be cited.

---

### Task 2.1 — Identify All Wisconsin Cybersecurity Bachelor's Programs

Search and compile a complete list of Wisconsin institutions offering a bachelor's
degree with a cybersecurity focus (major, emphasis, or concentration).

**Required Output — Table 2.1: Wisconsin Cybersecurity Bachelor's Programs**

| Institution | Program Name | Degree Type | Credits | Modality | CIP Code | NSA/CAE Designation | Tuition (in-state/yr) | Source URL |
|------------|-------------|-------------|---------|----------|----------|--------------------|-----------------------|-----------|
| UW-Stout | B.S. Cybersecurity | BS | [VERIFY] | On-campus | 11.1003 | CAE-C (NSA) | [VERIFY] | uwstout.edu |
| UW-Whitewater | B.S. Cybersecurity | BS | [VERIFY] | On-campus | 11.1003 | CAE-CD aligned | [VERIFY] | uww.edu |
| UW-Oshkosh | [VERIFY program name] | BS | [VERIFY] | [VERIFY] | [VERIFY] | [VERIFY] | $4,386/yr est. | [VERIFY] |
| Herzing University-Madison | B.S. Cybersecurity | BS | [VERIFY] | Online/Hybrid | 11.1003 | [VERIFY] | [VERIFY] | herzing.edu |
| Marquette University | [VERIFY — NSA designated] | [VERIFY] | [VERIFY] | [VERIFY] | [VERIFY] | CAE [VERIFY] | [VERIFY] | marquette.edu |
| Carroll University | [Proposed program] | BS | TBD | Face-to-face/Hybrid | 11.1003 TBD | None (target) | ~$12,360/yr [VERIFY] | — |
| [Add others found] | | | | | | | | |

**Completion criteria**: Minimum 5 Wisconsin institutions documented with all columns
populated or tagged `[VERIFY]`. Carroll's row included for comparison.

---

### Task 2.2 — Deep Dive: Five Key Competitors

For each of the five primary competitors identified in Table 2.1, produce a
detailed program profile.

**Required Output Format — Profile Block (repeat for each institution)**:

```
## Competitor Profile: [Institution Name]

### Program Basics
- Program name:
- Degree:
- Total credits:
- Delivery modality:
- First offered:
- Enrollment (most recent available):

### Curriculum Highlights
- Required core courses (list top 8–10):
- Capstone structure:
- Embedded industry certifications (if any):
- Lab/experiential component:

### Accreditation & Recognition
- NSA/CAE designation: (Y/N, which type)
- ABET accreditation: (Y/N)
- Other notable recognitions:

### Transfer Pathway
- Explicit 2-year articulation agreements: (Y/N)
- Transfer credits accepted (max):
- Junior-standing transfer policy:

### Strengths (vs. Carroll)
-
-

### Weaknesses / Carroll Differentiation Opportunity
-
-

### Source(s)
- [URL], accessed [date]
```

**Minimum 5 profiles required. UW-Stout and UW-Whitewater are mandatory.**

---

### Task 2.3 — Competitive Positioning Matrix

Synthesize Task 2.2 into a single positioning matrix.

**Required Output — Table 2.3: Competitive Positioning Matrix**

| Dimension | UW-Stout | UW-Whitewater | UW-Oshkosh | Herzing | Marquette | **Carroll (Proposed)** |
|-----------|---------|--------------|-----------|---------|-----------|----------------------|
| NSA CAE designation | CAE-C | CAE-CD aligned | [VERIFY] | [VERIFY] | CAE [VERIFY] | **None → Target** |
| Embedded certifications | CCNA, CyberOps, CEH, AWS | [VERIFY] | [VERIFY] | [VERIFY] | [VERIFY] | **TBD — opportunity** |
| 2-year transfer pathway | [VERIFY] | YES — Cyber Ops emphasis (60 cr) | [VERIFY] | [VERIFY] | [VERIFY] | **YES — WCTC pipeline** |
| Class size | Large | Medium | Medium | Small | Small | **Small — differentiator** |
| Location relative to Waukesha | 4.5 hrs | 45 min | 1.75 hrs | Madison | Milwaukee | **0 min — differentiator** |
| Tuition vs. Carroll | Lower | Lower | Lower | [VERIFY] | Higher | Mid-range |
| Online availability | Partial | [VERIFY] | [VERIFY] | Yes | [VERIFY] | TBD |
| NRP/HPC research access | [VERIFY] | No | No | No | Yes | **YES — differentiator** |
| Regional employer ties | [VERIFY] | [VERIFY] | [VERIFY] | [VERIFY] | YES (MKE) | **YES — Waukesha/MKE** |

---

### Task 2.4 — Carroll Differentiation Statement

Based on Tables 2.1–2.3, write 3–5 bullet-point differentiation statements that
Carroll can credibly claim. Each statement must be:
- Factually supported by data in Tables 2.1–2.3
- Not claimed by at least 3 of the 5 competitors
- Actionable (Carroll can deliver this without new faculty or major investment)

**Required Output**: Numbered list of differentiation statements with supporting evidence.

---

### Task 2.5 — Curriculum Benchmark: Standard Cybersecurity Course Set

Using competitor programs and the NCAE-C Knowledge Unit requirements, produce a
benchmark list of course topics that a credible B.S. Cybersecurity program should cover.
Cross-reference against Carroll's existing courses (from Table 1.4) to identify
curriculum gaps at the topic level.

**Required Output — Table 2.5: Topic Coverage Benchmark**

| Cybersecurity Topic Domain | NCAE-C KU Required? | Competitor Coverage | Carroll Existing Course | Gap? |
|---------------------------|--------------------|--------------------|------------------------|------|
| Networking Fundamentals | YES | All 5 | CSC303 | No |
| Operating Systems / Systems Admin | YES | All 5 | CSC307 | No |
| Cryptography | YES | All 5 | [VERIFY] | Likely YES |
| Ethical Hacking / Penetration Testing | Common | 4/5 | [VERIFY] | Likely YES |
| Digital Forensics | Common | 3/5 | [VERIFY] | Likely YES |
| Security Policy, Law & Ethics | YES (NCAE-C) | All 5 | None (PLO 4 gap) | **YES — Critical** |
| Incident Response | YES | All 5 | [VERIFY] | Likely YES |
| Risk Management & Governance | YES | 4/5 | [VERIFY] | Likely YES |
| Cloud Security | Common | 3/5 | [VERIFY] | Likely YES |
| Web Application Security | Common | 4/5 | CSC319 (partial) | Partial |
| Secure Programming | YES | 4/5 | [VERIFY] | [VERIFY] |
| Database Security | Useful | 3/5 | CSC351 (partial) | Partial |
| Malware Analysis | Useful | 2/5 | None | YES |
| [Add additional domains] | | | | |

---

### LEAN Gate — Phase 2

```
┌─────────────────────────────────────────────────────────────────┐
│  LEAN GATE — PHASE 2: ANALYZE (Wisconsin Competitors)           │
│  ─────────────────────────────────────────────────────────────  │
│  Criteria:                                                      │
│  [  ] Table 2.1 lists minimum 5 Wisconsin institutions with     │
│        all columns populated or explicitly tagged [VERIFY]      │
│  [  ] Five competitor profiles produced per Task 2.2 format     │
│  [  ] Table 2.3 positioning matrix completed for all 6 rows     │
│  [  ] Task 2.4 produces 3–5 supported differentiation claims    │
│  [  ] Table 2.5 identifies topic-level gaps vs. NCAE-C KUs      │
│  [  ] No data claim appears without a source or [VERIFY] tag    │
│                                                                 │
│  Evidence: [Agent fills in]                                     │
│  Kaizen note: [Most uncertain areas for Jack to verify]         │
│  Decision: [GATE PASSED] / [GATE FAILED — specify gap]         │
└─────────────────────────────────────────────────────────────────┘
```

---

## PHASE 3 — ANALYZE: LOCAL 2-YEAR ARTICULATION PIPELINE

> **Objective**: Identify and document every 2-year college within reasonable distance
> of Carroll that offers a cybersecurity program, assess existing articulation status,
> and design a pipeline architecture that feeds transfer students into Carroll's
> redesigned program. This is a critical enrollment recovery strategy.

---

### Task 3.1 — Identify All Area Technical Colleges with Cybersecurity Programs

**Geographic scope**: Wisconsin technical colleges within 60 miles of Carroll University
(100 N. East Avenue, Waukesha, WI 53186). WTCS institutions to check:

- Waukesha County Technical College (WCTC) — 1.5 mi from Carroll
- Gateway Technical College (Kenosha/Racine/Elkhorn campuses)
- Milwaukee Area Technical College (MATC) — Milwaukee
- Moraine Park Technical College (Fond du Lac/West Bend/Beaver Dam)
- [Add others found within 60-mile radius]

**Required Output — Table 3.1: Area Technical College Cybersecurity Programs**

| Institution | Distance from Carroll | Program Name | Degree Type | Credits | CAE Designation | Annual Graduates (est.) | Existing Carroll Articulation? | Source |
|------------|----------------------|-------------|-------------|---------|----------------|------------------------|-------------------------------|--------|
| WCTC | 1.5 mi | IT — Cybersecurity Specialist | A.A.S. | 62 | CAE2Y + CAE-CD | [VERIFY] | YES — A.A.S. CS Spec → B.S. IT | wctc.edu |
| Gateway TC | ~35 mi | [VERIFY] | [VERIFY] | [VERIFY] | [VERIFY] | [VERIFY] | [VERIFY] | gtc.edu |
| MATC | ~20 mi | [VERIFY] | [VERIFY] | [VERIFY] | [VERIFY] | [VERIFY] | [VERIFY] | matc.edu |
| Moraine Park | ~45 mi | [VERIFY] | [VERIFY] | [VERIFY] | [VERIFY] | [VERIFY] | [VERIFY] | morainepark.edu |

---

### Task 3.2 — Deep Dive: WCTC A.A.S. Cybersecurity Specialist (Priority)

WCTC is Carroll's most critical pipeline partner. Perform a detailed course-by-course
analysis of WCTC's Cybersecurity Specialist program against the proposed Carroll
cybersecurity curriculum.

**WCTC Program Reference** (from web search, catalog.wctc.edu):
- Program Code: 10-151-2 | 62 credits | A.A.S. Degree | Hybrid (Day/Evening)
- CAE2Y + CAE-CD designated (first college in Wisconsin with CAE-CD)

**WCTC Core Courses** (from program catalog):

| WCTC Code | WCTC Course | Credits | Proposed Carroll Equivalent | Transfer Credits | Gap Action Needed |
|-----------|------------|---------|---------------------------|-----------------|-------------------|
| 151-106 | Security I | 3 | CSC275 (partial) | [VERIFY] | |
| 150-117 | Intro to Cisco Networks (CCNA 1) | 3 | CSC303 (partial) | [VERIFY] | |
| 150-188 | Linux Essentials | 3 | CSC307 (partial) | [VERIFY] | |
| 150-164 | Intro to Bash Shell Scripting | 1 | CSC307 (partial) | [VERIFY] | |
| 150-137 | MS Server | 3 | CSC307 (partial) | [VERIFY] | |
| 150-157 | Security II | 3 | [No current equivalent] | 0 or elective | New course or elective |
| 150-118 | Switching, Routing & Wireless (CCNA 2) | 3 | CSC303 (partial) | [VERIFY] | |
| 152-150 | Intro to Programming in Python | 2 | CSC110 (partial) | [VERIFY] | |
| 107-103 | IT Business Strategies | 3 | BUS101/302? | [VERIFY] | |
| 151-103 | Firewall Security | 3 | [No equivalent] | 0 or elective | New course needed? |
| 151-104 | Intrusion Detection | 3 | [No equivalent] | 0 or elective | New course needed? |
| 151-102 | Log and Threat Analysis | 3 | [No equivalent] | 0 or elective | New course needed? |
| 151-107 | Web Application Security | 3 | CSC319 (partial) | [VERIFY] | |
| 151-105 | Digital Forensics | 3 | [No equivalent] | 0 or elective | New course needed? |
| 150-161 | Ethical Hacking | 3 | [No equivalent] | 0 or elective | New course needed? |
| 151-108 | IT Cybersecurity Capstone | 2 | CSC450 (partial) | [VERIFY] | |
| 107-123 | Internship IT | 2 | CSC480 | YES | |
| General Studies | English, Math, Economics, Psychology, Speech | 15 | Carroll PioCore equivalents | [VERIFY] | |

**Required Output — Table 3.2a: WCTC-to-Carroll Transfer Credit Summary**

| Category | Credits at WCTC | Estimated Transfer Credits | Remaining Carroll Credits | Transfer Student Time-to-Degree |
|---------|----------------|--------------------------|--------------------------|--------------------------------|
| Technical core | 47 | [calculate] | [calculate] | |
| General studies | 15 | [calculate — PioCore alignment] | [calculate] | |
| **Total** | **62** | **[total]** | **[total]** | **[est. semesters]** |

**Required Output — Table 3.2b: Gaps in Existing WCTC Articulation**

Document what the *current* WCTC → B.S. IT articulation agreement does and does not
cover, and what changes are needed after the program redesign.

| Gap | Description | Impact | Action Needed |
|-----|-------------|--------|--------------|
| 1 | Current articulation maps to B.S. IT, not B.S. Cybersecurity | High — needs renegotiation | Contact Lynn Novak |
| 2 | [Agent identifies additional gaps] | | |

---

### Task 3.3 — Gateway and MATC Analysis

For each of Gateway TC and MATC (the next two closest institutions):
- Identify their cybersecurity program name, credits, and CAE status
- Identify whether a Carroll articulation agreement currently exists
- Identify 3–5 courses that would most cleanly transfer into a Carroll cybersecurity program

**Required Output**: One summary paragraph per institution with a 5-row course map table.

---

### Task 3.4 — Design the 2+2 Transfer Pathway Architecture

Using WCTC as the primary pipeline partner, design the recommended 2+2 pathway
structure for a WCTC Cybersecurity Specialist graduate entering Carroll.

**Required Output — Table 3.4: WCTC 2+2 Pathway Blueprint**

| Element | Details |
|---------|---------|
| Entry point | Junior standing (Year 3, Fall) |
| Transfer credits accepted | [from Table 3.2a] |
| Carroll courses remaining | [from Table 3.2a] |
| Required Carroll courses (Year 3 Fall) | [list] |
| Required Carroll courses (Year 3 Spring) | [list] |
| Required Carroll courses (Year 4 Fall) | [list] |
| Required Carroll courses (Year 4 Spring) | [list, including capstone] |
| Industry certs carried from WCTC | Security+, CCNA (if earned at WCTC) |
| Total time at Carroll (semesters) | [calculate] |
| Total time to B.S. degree | 4 years (2 at WCTC + 2 at Carroll) |
| Scholarship bridge recommended? | YES — specify criteria |
| Guaranteed admission criteria | [VERIFY with Admissions] |

---

### Task 3.5 — Pipeline Volume Estimate

Estimate the number of WCTC Cybersecurity Specialist graduates per year who could
realistically transfer to Carroll, given:
- WCTC program size (verify from wctc.edu or IPEDS)
- Typical Wisconsin technical college transfer rate (20–30% historical average) [VERIFY]
- Carroll's geographic advantage as the closest 4-year institution in Waukesha

**Required Output**: Enrollment projection narrative (1 paragraph) with a table:

| Year | Estimated WCTC Graduates | Assumed Transfer Rate | Projected Carroll Admits | Cumulative Program Enrollment |
|------|-------------------------|----------------------|------------------------|------------------------------|
| FA2027 (Year 1) | [VERIFY] | 15% (conservative) | [calculate] | [calculate] |
| FA2028 (Year 2) | [VERIFY] | 20% | [calculate] | [calculate] |
| FA2029 (Year 3) | [VERIFY] | 25% | [calculate] | [calculate] |

Note: All enrollment figures tagged `[VERIFY]` must be confirmed before use in
the official concept proposal (Section 4).

---

### Task 3.6 — Articulation Action Plan

Produce a numbered action plan for establishing or updating articulation agreements
with area technical colleges.

**Required Output**:

| # | Action | Owner | Target Date | Notes |
|---|--------|-------|------------|-------|
| 1 | Contact Lynn Novak (WCTC) to initiate articulation renegotiation | Jack Forden | November 2026 | Existing relationship; update to reflect cybersecurity program |
| 2 | Identify Gateway TC enrollment partnerships contact | Jack Forden | December 2026 | |
| 3 | Request MATC articulation framework from Carroll Registrar | Registrar | November 2026 | UWM has MOU with MATC — Carroll should follow |
| 4 | Draft updated course equivalency table for WCTC → Carroll Cybersecurity | Jack Forden + Registrar | January 2027 | Based on Table 3.2a |
| 5 | Submit revised articulation agreement to Carroll governance | Registrar + Dean | Spring 2027 | Requires faculty approval |

---

### LEAN Gate — Phase 3

```
┌─────────────────────────────────────────────────────────────────┐
│  LEAN GATE — PHASE 3: ANALYZE (2-Year Pipeline)                 │
│  ─────────────────────────────────────────────────────────────  │
│  Criteria:                                                      │
│  [  ] Table 3.1 covers all WTCS institutions within 60 miles    │
│  [  ] Table 3.2a produces a WCTC credit transfer summary        │
│  [  ] Table 3.2b identifies gaps in existing articulation       │
│  [  ] Task 3.3 covers at least Gateway TC and MATC              │
│  [  ] Table 3.4 produces a complete 2+2 pathway blueprint       │
│  [  ] Task 3.5 produces enrollment projections for 3 years      │
│  [  ] Task 3.6 produces a concrete articulation action plan      │
│  [  ] Lynn Novak identified as primary WCTC contact             │
│                                                                 │
│  Evidence: [Agent fills in]                                     │
│  Kaizen note: [What needs in-person verification at WCTC]       │
│  Decision: [GATE PASSED] / [GATE FAILED — specify gap]         │
└─────────────────────────────────────────────────────────────────┘
```

---

## PHASE 4 — IMPROVE: PROGRAM DESIGN RECOMMENDATIONS

> **Objective**: Using all prior phase outputs as input, synthesize concrete
> recommendations for the cybersecurity program's curriculum structure, PLO framework,
> course sequence, and differentiation strategy. This phase produces the substantive
> content that feeds directly into the Phase 5 concept proposal.

---

### Task 4.1 — Recommended Program Structure

Based on Phases 1–3, recommend a complete program structure.

**Required Output — Table 4.1: Recommended B.S. Cybersecurity Course Sequence**

| Year | Semester | Course Code | Course Name | Credits | Type | PLO(s) Addressed | NCAE-C KU | WCTC Transfer Eligible? |
|------|---------|------------|-------------|---------|------|-----------------|-----------|------------------------|
| 1 | Fall | CSC110 | Problem Solving through Programming | 4 | Core | PLO 1, 3 | Programming | Partial (WCTC 152-150) |
| 1 | Spring | CSC111 | Introduction to Java | 4 | Core | PLO 1, 3 | | No |
| 2 | Fall | CSC226 | Data Structures | 4 | Core | PLO 1, 3 | | No |
| 2 | Fall | CSC275 | Intro to Cybersecurity | 4 | Core | All 5 PLOs | Intro to Cybersecurity | Partial (WCTC 151-106) |
| 2 | Spring | CSC303 | Network Protocols | 4 | Core | PLO 1, 3, 5 | Networking | YES (WCTC 150-117, 150-118) |
| 2 | Spring | CSC307 | Systems Administration | 4 | Core | PLO 2, 3 | OS/Admin | YES (WCTC 150-188, 150-137) |
| 3 | Fall | [NEW] Cybersecurity Law, Policy & Ethics | 4 | Core | PLO 4 — PRIMARY | Policy/Law/Ethics KU | No |
| 3 | Fall | [NEW or Revised] | [Cryptography or Security Analysis] | 4 | Core | | | |
| 3 | Spring | CSC351 | Database Design & Implementation | 4 | Elective | PLO 1, 2, 3 | Data Security | Partial |
| 3 | Spring | [Course TBD] | [Digital Forensics or Incident Response] | 4 | Core | | | |
| 4 | Fall | CSC341 | Software Design & Development | 4 | Core | PLO 1, 2, 3 | Secure Dev | No |
| 4 | Spring | CSC450 | Senior Capstone | 4 | Core | PLO 1, 2, 3, 5 | Applied | Partial |
| Any | Any | CSC480 | Internship | 3–12 | Core | PLO 1, 2, 3, 5 | Applied | YES (WCTC 107-123) |
| [Add PioCore] | | | Carroll University PioCore requirements | ~32 | General Ed | | | |

**Completion criteria**: Full 4-year sequence with credit totals summing to Carroll
graduation requirement (~128 credits). WCTC transfer students' remaining requirements
clearly differentiated.

---

### Task 4.2 — New Course Specifications

For each new course identified in Table 1.4 and Table 2.5, produce a course specification.

**Required Output Format — New Course Spec (repeat per course)**:

```
### New Course: [Course Code TBD] — [Course Title]

**Credits**: 4
**Prerequisites**: [list]
**Offering frequency**: [Annual / Biennial / TBD]
**Delivery**: Face-to-face / Hybrid

**Catalog Description** (50–75 words):
[Write here]

**Proposed CLOs**:
1. [CLO 1 — Bloom's level]
2. [CLO 2 — Bloom's level]
3. [CLO 3 — Bloom's level]

**PLO Alignment**:
| PLO | Level | Rationale |
|-----|-------|-----------|
| CSEC-PLO 4 — Ethics | I or M | [justify] |

**NCAE-C Knowledge Units Addressed**:
- [KU 1]
- [KU 2]

**Assessment Structure**:
| Assessment | Weight | CLO(s) |
|-----------|--------|--------|
| | | |

**Industry Certification Alignment** (if any):
- e.g., CompTIA Security+, Domain: [X]

**Resource Requirements**:
- Faculty: [existing / new hire needed]
- Lab/tech: [existing VM infra / new needed]
- Estimated dev time: [semesters]
```

**Minimum**: Produce specifications for at least:
1. Cybersecurity Law, Policy & Ethics (PLO 4 anchor)
2. One technical course addressing a major NCAE-C gap from Table 2.5

---

### Task 4.3 — Industry Certification Embedding Recommendation

UW-Stout embeds CCNA, CyberOps, CEH, and AWS certifications. Determine whether
Carroll should embed certifications and if so, which ones.

**Required Output — Table 4.3: Certification Embedding Analysis**

| Certification | Issuing Body | Relevance | NCAE-C Alignment | WCTC Students Arrive With? | Cost to Embed | Carroll Course to Embed In | Recommendation |
|--------------|-------------|-----------|-----------------|--------------------------|--------------|--------------------------|----------------|
| CompTIA Security+ | CompTIA | High | YES | Sometimes | Low (exam voucher) | CSC275 or new course | YES — strongly |
| CompTIA CySA+ | CompTIA | High | YES | No | Low | Advanced security course | YES — Year 3 |
| Cisco CyberOps Associate | Cisco | Medium-High | YES | CCNA-adjacent | Medium | CSC303 | CONSIDER |
| Certified Ethical Hacker (CEH) | EC-Council | Medium | YES | No | High | Elective | OPTIONAL |
| AWS Cloud Practitioner | AWS | Medium | Partial | No | Low | Elective or embedded | CONSIDER |

---

### Task 4.4 — NSA NCAE-C Designation Roadmap

Identify the requirements for Carroll to pursue NSA National Center of Academic
Excellence in Cybersecurity designation and produce a high-level roadmap.

**Required Output**:

| Phase | Requirement | Carroll's Current Status | Action Needed | Timeline |
|-------|-------------|-------------------------|--------------|----------|
| 1 | Program must be a designated cybersecurity degree | Not yet | Launch program | FA2027 target |
| 2 | Curriculum must map to NCAE-C Knowledge Units | Partial (CSC275, 303, 307) | Complete KU mapping | Phase 1 output |
| 3 | Institution must have documented cybersecurity assessment | None | Build AQC framework | AY2027-28 |
| 4 | Faculty must demonstrate cybersecurity expertise | Partial | Document Forden's credentials + hire/develop | Ongoing |
| 5 | Submit designation application to NSA | N/A | Target AY2028-29 application | 2028 |

---

### Task 4.5 — Grant & Funding Recommendations

Identify 3–5 funding sources to support the cybersecurity program launch.

**Required Output — Table 4.5: Grant & Funding Opportunities**

| Source | Program Name | Amount (est.) | Eligibility | Deadline | Alignment | Priority |
|--------|-------------|--------------|-------------|----------|-----------|---------|
| NSF | SFS (Scholarship for Service) | $20K–$40K/student | NCAE-C designated institutions | Annual | Requires CAE designation | Long-term |
| DHS/CISA | NCAE-C grants | Varies | Institutions building CAE pipelines | Annual | Direct alignment | High |
| CodePath | Cybersecurity TIP | Program support | Small/underserved institutions | Rolling | Already in discussion | Immediate |
| DOL | TAACCCT / Workforce grants | $1M–$5M | Community partnerships | Annual | WCTC pipeline | Medium |
| NSF FINDERS Foundry | Already funded — Carroll collaborator | N/A | Current grant | Active | NRP/research computing | Active now |

---

### LEAN Gate — Phase 4

```
┌─────────────────────────────────────────────────────────────────┐
│  LEAN GATE — PHASE 4: IMPROVE (Program Design)                  │
│  ─────────────────────────────────────────────────────────────  │
│  Criteria:                                                      │
│  [  ] Table 4.1 produces a complete 4-year curriculum sequence  │
│  [  ] Credit totals verified to meet Carroll graduation req.    │
│  [  ] At least 2 new course specifications completed            │
│  [  ] PLO 4 has at least one dedicated course in the sequence   │
│  [  ] Table 4.3 produces cert embedding recommendations         │
│  [  ] Task 4.4 produces NCAE-C designation roadmap              │
│  [  ] Table 4.5 identifies at least 3 funding sources           │
│  [  ] WCTC transfer pathway integrated into Table 4.1           │
│                                                                 │
│  Evidence: [Agent fills in]                                     │
│  Kaizen note: [Biggest curriculum design uncertainties]         │
│  Decision: [GATE PASSED] / [GATE FAILED — specify gap]         │
└─────────────────────────────────────────────────────────────────┘
```

---

## PHASE 5 — IMPROVE: CONCEPT PROPOSAL DRAFT

> **Objective**: Using all prior outputs, produce a complete, submission-ready draft
> of the Carroll University New Academic Program Concept Proposal.
> **This phase must not begin until all prior LEAN gates are passed.**
> The proposal must not exceed two pages when printed. This draft is the prose
> version; Jack will refine and submit via the official form.

---

### Task 5.1 — Complete Draft Concept Proposal

**Required Output**: Produce a complete draft filling in all 7 sections of the
Carroll University New Academic Program Concept Proposal form.

```
═══════════════════════════════════════════════════════════════
CARROLL UNIVERSITY — NEW ACADEMIC PROGRAM CONCEPT PROPOSAL
Submission Deadline: November 13, 2026
═══════════════════════════════════════════════════════════════

BASIC INFORMATION
─────────────────
Program Name:        [From Phase 0 vehicle decision — e.g., B.S. in Cybersecurity
                      or B.S. in Cybersecurity & Information Technology]

Type:                ☐ New Program  ☐ Program Amendment  [select based on Phase 0]

Program Type:        ☐ Major  [or Minor/Certificate per Phase 0]

Program Level:       ☑ Undergraduate

Department:          Sullivan School of Business, Engineering & Technology —
                     Department of Technology / Computer Science

Faculty Contact(s):  Jack Forden, Ph.D. — jforden@carrollu.edu
                     [Add Karol J. Lejmbach if co-sponsoring]

Date Submitted:      [Jack fills in]

───────────────────────────────────────────────────────────────
SECTION 1 — PROGRAM DESCRIPTION
[Agent writes 75–100 words here, drawing from Phase 4 program structure.
Must include: primary purpose, intended student population, credit total.]

SECTION 2 — PROGRAM LEARNING OUTCOMES
[Agent inserts 4–5 PLOs from Table 1.5. Each on its own numbered line.
Must be Bloom's-aligned. PLO 4 (ethics) must be included.]

1.
2.
3.
4.
5.

SECTION 3 — BENEFITS TO CARROLL AND THE COMMUNITY
[Agent writes 75–100 words here, drawing from:
- Task 2.4 differentiation statements (Carroll's unique angle)
- Task 3.5 WCTC pipeline (community benefit)
- Employer names from Section 3.2 (regional workforce benefit)
- Grant activity: NSF FINDERS Foundry, CodePath
Must address both Carroll's mission AND community/employer benefit.]

SECTION 4 — MARKET DEMAND AND ENROLLMENT POTENTIAL
[Agent writes 75–100 words here. Must include:
- Wisconsin: 5,366 open cybersecurity positions (CyberSeek)
- Average salary: $99,210 (BLS 2024)
- Job growth: 33% through 2033 (BLS projections)
- UQ market intelligence: CIP 11.1099 in Carroll's top-10 new programs
- WCTC pipeline volume from Table 3.5
- CS enrollment trend as urgency signal]

Evidence or source(s): [list citations from above]
Estimated initial enrollment:     [from Task 3.5, Year 1 conservative]
Estimated enrollment after 3 yrs: [from Task 3.5, Year 3]

SECTION 5 — CURRICULUM AND NEW COURSES
Will new courses be required? ☑ Yes

New courses proposed:
[List courses from Task 4.2 — minimum the Ethics/Policy course]

Can existing courses be used? ☑ Partially
[Brief description: CSC275, CSC303, CSC307, CSC240, CSC341, CSC450, CSC480
can all be retained with minor revisions. 2–3 new courses needed.]

Modality: ☐ Fully Online  ☑ Hybrid  ☐ Face-to-Face
[Carroll's current infrastructure supports hybrid]

SECTION 6 — RESOURCES NEEDED
[Check appropriate boxes and provide brief explanation:]
☑ No significant new resources anticipated [for rename/amendment vehicle]
  OR
☐ New or reassigned faculty/staff [if full new major]
☐ Additional operating funds
☑ Facilities, equipment, technology: EXISTING — Hyper-V virtualization,
  NRP access (NSF FINDERS Foundry), Docker/VM lab infrastructure already
  approved and operational for CSC275, CSC303, CSC307.
☐ Marketing, recruitment, or administrative support
☐ Other

Estimated cost: Primarily course development time (within existing faculty load).
Lab infrastructure already funded. Industry certification exam vouchers: ~$500/student
for Security+ (offset available via CodePath grant partnership — in negotiation).

SECTION 7 — PROPOSED TIMELINE
Curriculum development and approvals: Spring 2027 (Curriculog filing post-concept
approval; faculty governance by end of Spring 2027 semester)

Proposed recruitment launch: Fall 2027 admissions cycle (January 2027 open house)

Proposed first term of enrollment: Fall 2027

═══════════════════════════════════════════════════════════════
END DRAFT
═══════════════════════════════════════════════════════════════
```

---

### Task 5.2 — Proposal Quality Review

Before releasing the draft to Jack, the agent must self-review the proposal against
the following criteria:

| Criterion | Standard | Met? | Notes |
|-----------|---------|------|-------|
| Length | ≤ 2 pages when printed at 11pt | | |
| PLOs | 4–5 present, Bloom's-aligned, measurable | | |
| Market data | Minimum 3 cited data points | | |
| Enrollment estimates | Grounded in pipeline analysis (not guessed) | | |
| New courses | Named and described | | |
| Resources | Realistic; uses existing assets first | | |
| Timeline | Connects to Nov 13 submission and FA2027 launch | | |
| Ethics PLO | Present and named | | |
| No fabricated data | All numbers cited or tagged [VERIFY] | | |

---

### LEAN Gate — Phase 5

```
┌─────────────────────────────────────────────────────────────────┐
│  LEAN GATE — PHASE 5: IMPROVE (Concept Proposal)                │
│  ─────────────────────────────────────────────────────────────  │
│  Criteria:                                                      │
│  [  ] All 7 sections of the concept proposal are drafted        │
│  [  ] Proposal would fit within 2 pages when printed            │
│  [  ] All market data figures are cited with source             │
│  [  ] PLOs from Phase 1 are used verbatim (no new PLOs invented)│
│  [  ] Task 5.2 quality review table is completed                │
│  [  ] Zero fabricated enrollment or salary figures              │
│  [  ] [ACTION REQUIRED] items listed for Jack before submission │
│                                                                 │
│  Evidence: [Agent fills in]                                     │
│  Decision: [GATE PASSED] / [GATE FAILED — specify gap]         │
└─────────────────────────────────────────────────────────────────┘
```

---

## PHASE 6 — CONTROL: VALIDATION & INSTITUTIONAL READINESS

> **Objective**: Confirm that all deliverables are internally consistent, that the
> package is ready for Jack to use, and that a clear next-action checklist is produced.

---

### Task 6.1 — Cross-Document Consistency Check

Verify that the following are consistent across all phase outputs:

| Item | Phase 1 Source | Phase 4 Use | Phase 5 Use | Consistent? |
|------|---------------|------------|------------|-------------|
| Number of new courses needed | Table 1.4 | Table 4.1 | Section 5 | |
| PLOs (exact text) | Table 1.5 | Table 4.1 | Section 2 | |
| WCTC transfer credit estimate | Table 3.2a | Table 4.1 | Section 4 | |
| Enrollment projections | Table 3.5 | Task 4.5 | Section 4 | |
| Existing course codes | Workbook | Table 4.1 | Section 5 | |
| Submission deadline | Task 0.3 | — | Section 7 | Nov 13, 2026 |

---

### Task 6.2 — Master Action Checklist for Jack Forden

Produce a numbered, prioritized checklist of everything Jack must personally do next.

**Required Output — Jack's Master Action Checklist**:

| Priority | # | Action | By When | Who Else Involved |
|---------|---|--------|---------|-------------------|
| URGENT | 1 | Meet with Dean Esveldt to confirm proposal vehicle (rename vs. new program) | Before Nov 2 | Esveldt |
| URGENT | 2 | Verify CSC409 course existence, syllabus, and current status | This week | Registrar |
| URGENT | 3 | Contact Lynn Novak (WCTC) to flag articulation update needed | Before Nov 13 | Novak |
| HIGH | 4 | Present concept at Nov 2 SSBET Curriculum Planning meeting | Nov 2 | Lejmbach, Progga |
| HIGH | 5 | Submit concept proposal by Nov 13 deadline | Nov 13 | Esveldt |
| HIGH | 6 | Complete CSC275 CLO documentation in CLO_PLO workbook | Before Curriculog filing | |
| MEDIUM | 7 | Confirm credit total for proposed program with Registrar | Dec 2026 | Registrar |
| MEDIUM | 8 | Formalize CodePath conversation for Security+ exam voucher funding | Nov/Dec 2026 | CodePath rep |
| MEDIUM | 9 | Add cybersecurity program to AFE SMART goals for sign-off | Next AFE cycle | Kuhlemeyer |
| LOW | 10 | Begin NCAE-C KU mapping of all cybersecurity courses | Spring 2027 | Lejmbach (co-author) |

---

### Task 6.3 — Final Agent Retrospective

The agent must complete the following reflection before closing:

```
AGENT RETROSPECTIVE — Cybersecurity Program Redesign Package

Phases completed: [list]
Phases with open gates (if any): [list with reason]

Top 3 items tagged [VERIFY] that are highest risk if wrong:
1.
2.
3.

Top 3 [ASSUMPTION] tags that Jack must confirm:
1.
2.
3.

Top 3 [ACTION REQUIRED] items that block the proposal if unresolved:
1.
2.
3.

Confidence level in enrollment projections: LOW / MEDIUM / HIGH
Reason: [explain]

Confidence level in competitive analysis: LOW / MEDIUM / HIGH
Reason: [explain]

Recommended next agent run: [describe what new inputs would most improve output]
```

---

### LEAN Gate — Phase 6 (Final Gate)

```
┌─────────────────────────────────────────────────────────────────┐
│  LEAN GATE — PHASE 6: CONTROL (Final Validation)                │
│  ─────────────────────────────────────────────────────────────  │
│  Criteria:                                                      │
│  [  ] Task 6.1 cross-consistency check passes with no           │
│        discrepancies (or discrepancies are explicitly flagged)  │
│  [  ] Task 6.2 master checklist is numbered and prioritized     │
│  [  ] Task 6.3 retrospective is complete                        │
│  [  ] All [VERIFY], [ASSUMPTION], [ACTION REQUIRED] tags are    │
│        consolidated in the retrospective                        │
│  [  ] The concept proposal draft is flagged as ready-for-review │
│        or held pending [ACTION REQUIRED] resolution             │
│                                                                 │
│  Final Decision: [PACKAGE COMPLETE] / [PACKAGE INCOMPLETE]     │
│  If incomplete: [list remaining items]                          │
└─────────────────────────────────────────────────────────────────┘
```

---

## 12. GLOBAL OUTPUT STANDARDS

The agent must apply these standards to **every** output, in every phase:

### 12.1 Citation Standards

| Data Type | Citation Required | Format |
|-----------|------------------|--------|
| Competitor program details | YES | Institution name + URL |
| Salary/job market data | YES | "BLS OEWS 2024" or "CyberSeek [date]" |
| WCTC course catalog data | YES | "catalog.wctc.edu" or "wctc.edu/[path]" |
| CLO_PLO workbook data | YES | "CLO_PLO workbook, [Sheet name] tab" |
| Agent-inferred content | Tag as [ASSUMPTION] | No citation needed |
| Content to verify externally | Tag as [VERIFY] | No citation needed |

### 12.2 Tagging Standards

| Tag | Meaning | Agent Action |
|-----|---------|-------------|
| `[VERIFY]` | Data should be confirmed from a live source before submission | Include in Task 6.3 risk list |
| `[ASSUMPTION]` | Agent made an inference not supported by provided documents | Include in Task 6.3 assumption list |
| `[ACTION REQUIRED]` | Jack or another human must act before this can be completed | Include in Task 6.2 checklist |
| `[GATE PASSED]` | Phase gate criteria fully met | Proceed to next phase |
| `[GATE FAILED — reason]` | Gate criteria not met | Halt; describe gap; do not proceed |

### 12.3 Table Standards

- Every table must have a header row with **bold column labels**
- Numeric values must include units (credits, dollars, students, miles)
- Empty cells must contain either a value, `[VERIFY]`, `[N/A]`, or `[BLANK]` — never left empty
- Tables must be complete before the phase gate is evaluated

### 12.4 Prohibited Behaviors

The agent must **never**:
- Invent course enrollment data without citing IPEDS, WCTC, or institutional sources
- Write content for the concept proposal that contradicts Phase 1–4 outputs
- Skip a gate or mark it passed without completing all listed criteria
- Present an assumption as a confirmed fact
- Use course codes that do not appear in the CLO_PLO workbook or are explicitly documented elsewhere

---

## 13. SELF-CORRECTION PROTOCOL

If the agent produces an output that violates any constraint in Section 1.3 or
Global Output Standards (Section 12), it must:

1. **Stop** the current output immediately
2. **State**: "SELF-CORRECTION: [describe the error]"
3. **Revise** the output, tagging the corrected section with `[REVISED]`
4. **Continue** from the correction point

If the agent encounters a task that cannot be completed due to missing input data:

1. **Do not fabricate** the missing data
2. **Write**: "BLOCKED: Task [X.Y] cannot be completed. Missing input: [describe].
   [ACTION REQUIRED]: Jack must provide [specific item] before this task can proceed."
3. **Skip** to the next task and return to the blocked task when input is available

If two earlier phase outputs conflict:

1. **Flag**: "CONSISTENCY CONFLICT: [Phase X Task Y] states [A] but
   [Phase Z Task W] states [B]."
2. **Use** the more conservative/lower-risk value for the proposal
3. **Mark** both as `[VERIFY]` in Task 6.3

---

## 14. GLOSSARY OF KEY TERMS

| Term | Definition |
|------|-----------|
| AAS | Associate of Applied Science — WCTC's primary degree type for technical programs |
| AQC | Academic Quality Committee — Carroll's internal program review body |
| ABET | Accreditation Board for Engineering and Technology |
| CAE-C | NSA Center of Academic Excellence in Cybersecurity (4-year/research level) |
| CAE2Y | NSA Center of Academic Excellence (2-year college level) — WCTC holds this |
| CAE-CD | NSA Center of Academic Excellence in Cyber Defense — WCTC also holds this |
| CIP Code | Classification of Instructional Programs — federal taxonomy for academic programs |
| CLO | Course Learning Outcome — what a student can do after completing one course |
| Curriculog | Carroll's curriculum change approval workflow system |
| HLC | Higher Learning Commission — Carroll's regional accreditor |
| IPEDS | Integrated Postsecondary Education Data System — federal data source for enrollment |
| LEAN Gate | A mandatory checkpoint in the LEAN methodology that must be passed before proceeding |
| NCAE-C | NSA National Centers of Academic Excellence in Cybersecurity |
| NICE Framework | NIST SP 800-181 — national taxonomy of cybersecurity workforce roles |
| NRP | National Research Platform — research computing infrastructure Carroll has access to via NSF FINDERS |
| PLO | Program Learning Outcome — what a student can do after completing the full degree |
| SLT | Senior Leadership Team — Carroll's provost-level administrative body |
| SSBET | Sullivan School of Business, Engineering & Technology — Carroll's school |
| SUG | Supply-Utilization Gap — UQ market intelligence metric for program demand |
| WTCS | Wisconsin Technical College System — governs all 16 technical colleges including WCTC |
| UQ | University Quality — market intelligence firm contracted by Carroll |
| 2+2 | A transfer pathway in which students complete 2 years at a technical college and 2 years at a 4-year institution |

---

*End of Agent Instruction Document*
*Carroll University — Cybersecurity Program Redesign*
*LEAN Version 1.0 | Prepared October 2026 | Jack Forden, Ph.D.*
