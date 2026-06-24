# Stage Execution Plan

> Copy this file into the active stage folder as `STAGE_EXECUTION.md` before the stage begins.

This file defines how the stage will be run from authorised inputs through evidence, specialist synthesis, chaired discussion, canonical outputs, book output and review.

Do not treat this as a formality. A weak execution plan usually produces weak research, weak pass-forward claims and weak public prose.

Pipeline reminder: `PASS_FORWARD.md` is downstream authority; `STAGE_BOOK.md` needs independent literary review; major process milestones should appear in resumability logging.

Visual pathway reminder: use `docs/PROCESS_PATHWAY_MAPS.md` when checking commissioning, evidence flow, sign-off, book output, permissions or resumability. Use pathway IDs such as `[P2.C11]` or `[P3.E17]` in notes when helpful.

---

## 1. Stage identity

**Stage number:**  
**Stage name:**  
**Stage folder:**  
**Date started:**  
**Stage owner / Master Coordinator:**  
**Workflow status:** `draft | active | review | closed`

---

## 2. Stage objective

Write the objective in one precise paragraph.

The objective should match the relevant `STAGE_GUIDE.md`. Do not broaden the stage.

**Objective:**

> [Write here]

---

## 3. Authorised inputs

List only the files, claims and pass-forward outputs this stage is authorised to use.

| Input ID | Input file or source | What may be used | Restrictions or cautions |
|---|---|---|---|
| I-001 |  |  |  |

### Input discipline

This stage may not rely on earlier reasoning unless it is explicitly authorised through the relevant pass-forward file or stage guide.

---

## 4. Stage boundaries

### 4.1 In scope

- [ ]
- [ ]
- [ ]

### 4.2 Out of scope

- [ ]
- [ ]
- [ ]

### 4.3 Downstream issues to record but not solve

Use this section when an important issue belongs to a later stage.

| Issue | Later stage likely responsible | Why not solved here |
|---|---|---|
|  |  |  |

---

## 5. Research question tree

Break the stage question into a hierarchy.

### 5.1 Primary question

> [Write the central question]

### 5.2 Secondary questions

1. [Question]
2. [Question]
3. [Question]

### 5.3 Tertiary questions

| Secondary question | Sub-questions | Expected evidence or reasoning needed |
|---|---|---|
|  |  |  |

### 5.4 Questions deliberately excluded

| Excluded question | Reason for exclusion | Where it should go instead |
|---|---|---|
|  |  |  |

---

## 6. Method selection

Choose methods that fit the question.

| Method | Why this method fits | What it can answer | What it cannot answer | Output produced |
|---|---|---|---|---|
|  |  |  |  |  |

### 6.1 Method risk

What could go wrong with the selected methods?

| Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|
|  |  |  |  |

### 6.2 Rejected methods

| Method rejected | Reason rejected | Risk if this rejection is wrong |
|---|---|---|
|  |  |  |

---

## 7. Agent team

List the agents called for this stage.

| Agent harness | Role in this stage | Information access tier | Tool access tier | Expected output | Pairing or review relationship | Status |
|---|---|---|---|---|---|---|
| Clu / Master Coordinator | Owns stage sequence and final integration. | I2/I3 | T0-T2; T3 only with user approval | Approved stage outputs. | Coordinates all agents. |  |
|  |  |  |  |  |  |  |

### 7.1 Agent commission register

Every instantiated agent must have a commission using the contract in `AGENTS.md`.

Visual reference: `docs/PROCESS_PATHWAY_MAPS.md`, P2.

| Commission ID | Agent | Exact task | Authorised inputs / source IDs | Prohibited actions | Required handoff | Reviewer / sign-off | Status |
|---|---|---|---|---|---|---|---|
| AC-001 |  |  |  |  |  |  | `draft`, `ready`, `ready_with_cautions` or `blocked` |

### 7.2 Access scope register

| Agent | Information access tier | Tool access tier | Reason this tier is sufficient | Escalation trigger |
|---|---|---|---|---|
|  |  |  |  |  |

### 7.3 Parallel work plan

Where agents work in parallel, describe the division.

| Workstream | Agent(s) | Output | Integration point |
|---|---|---|---|
|  |  |  |  |

### 7.4 Specialist synthesis plan

Use when the stage has multiple domains, conflicting evidence or public-facing synthesis needs.

| Specialist / role | Scope | Authorised sources or inputs | Required output | Integration point |
|---|---|---|---|---|
|  |  |  | Specialist talk / synthesis brief |  |

Each specialist output must follow the Agent Cognitive Quality Protocol in `docs/STAGE_ORCHESTRATOR_SOP.md`.

### 7.5 Cross-agent discussion plan

| Discussion round | Chair | Purpose | Required records |
|---|---|---|---|
|  | Master Coordinator | Connect domains, challenge overclaims and identify emergent structure. | Ledger `challenge` and `decision` records. |

No final thesis, chapter order or pass-forward filtering should be locked before the chaired discussion where specialist synthesis is required.

### 7.6 Adversarial, audit and literary review plan

At least one quality/adversarial review must occur.

| Review type | Agent | What they will attack or audit | When | Sign-off status |
|---|---|---|---|---|
|  |  |  |  |  |
| Independent literary review | Independent Literary Review Agent | `STAGE_BOOK.md` as standalone nonfiction, source discipline and absence of filler/meta-text. | After book draft and before closure. |  |

### 7.7 Artifact sign-off route

Use the universal artifact gate in `docs/STAGE_ORCHESTRATOR_SOP.md`.

Visual reference: `docs/PROCESS_PATHWAY_MAPS.md`, P5.

| Artifact | Primary author / owner | Required reviewers | Sign-off status | Notes |
|---|---|---|---|---|
| `STAGE_EXECUTION.md` | Clu / Research Operations Manager | Clu + Research Operations Manager + Claim Steward |  |  |
| `STAGE_LEDGER.csv` | Research Librarian / Evidence Lead | Claim Steward + Evidence Auditor |  |  |
| `STAGE_REPORT.md` | Documentation Editor / assigned author | Documentation Editor + Claim Steward + Evidence Auditor + domain lead |  |  |
| `PASS_FORWARD.md` | Clu + Claim Steward | Clu + Claim Steward + Evidence Auditor + required stage reviewers |  |  |
| `PUBLIC_SUMMARY.md` | Public Narrative Strategist / Documentation Editor | Public Narrative Strategist + Claim Steward + Clu |  |  |
| `STAGE_BOOK.md` | Book / Manuscript Editor | Book Editor + Claim Steward + Independent Literary Review Agent + Clu |  |  |
| `STAGE_REVIEW.md` | Review agents | Evidence Auditor + Bias Auditor + Red Team + Clu |  |  |

---

## 8. Source discovery plan

### 8.1 Source types to prioritise

- [ ] High-quality reviews / meta-analyses
- [ ] Primary studies
- [ ] Official reports or datasets
- [ ] Books / theoretical work
- [ ] Practitioner evidence
- [ ] Lived-experience or implementation evidence
- [ ] Existing curriculum or model comparison
- [ ] Other: [specify]

### 8.2 Search themes

| Theme | Search terms / source targets | Reason needed |
|---|---|---|
|  |  |  |

### 8.3 Source exclusion rules

Define what will not be used as evidence.

- [ ]
- [ ]
- [ ]

---

## 9. Stage ledger setup

Create `STAGE_LEDGER.csv` using `templates/STAGE_LEDGER_TEMPLATE.csv`.

Use the canonical `record_type` values defined in `docs/STAGE_ORCHESTRATOR_SOP.md`; do not invent stage-specific alternatives without recording the reason.

### 9.1 Minimum ledger expectations

Before the stage can pass, the ledger should contain:

- sources used;
- evidence extracted;
- claims made;
- assumptions adopted;
- uncertainties retained;
- decisions made;
- risks identified;
- traceability links;
- specialist talks or synthesis briefs, where used;
- discussion points and weakened claims;
- editorial decisions;
- literary review records;
- agent commission records;
- sign-off records;
- resume markers;
- adversarial challenges;
- revision triggers.

---

## 10. Prompt log

Record important prompts or instructions used with agents.

| Prompt ID | Agent / model | Purpose | Prompt summary | Output file influenced |
|---|---|---|---|---|
| P-001 |  |  |  |  |
| P-BOOK-001 | Book / Manuscript Editor | Book Evidence-to-Story Inventory |  | `STAGE_BOOK.md` control record |
| P-BOOK-002 | Book / Manuscript Editor + Claim Steward + Clu | Book Brief Gate |  | `STAGE_BOOK.md` control record |
| P-BOOK-003 | Book / Manuscript Editor + Literary Reviewer | Sample Quality Gate |  | `STAGE_BOOK.md` manuscript body |
| P-BOOK-004 | Independent Literary Review Agent | Full manuscript literary review |  | `STAGE_REVIEW.md`; `STAGE_BOOK.md` |
| P-BOOK-005 | Clu / Master Coordinator | Final book approval or refusal |  | `STAGE_REVIEW.md`; resumability log |
| P-SCENARIO-001 | Foresight Scenario Modeller + Clu | Scenario/lived-world worldspace matrix |  | Story overview checkpoint |
| P-SCENARIO-002 | Scenario / Timeline Writer | Protagonist dossier and world condition card |  | Story overview checkpoint |
| P-SCENARIO-003 | Clu / Master Coordinator | Manual story-overview review and checkpoint decision |  | `STAGE_REVIEW.md`; resumability log |

Do not paste extremely long prompts unless needed. Summarise and link to full logs if full logs are kept separately.

---

## 10.1 Book creation plan

Do not draft the full `STAGE_BOOK.md` manuscript until the Book Brief Gate and Sample Quality Gate have passed.

| Book step | Required output | Required reviewer / gate | Status | Ledger or resume record |
|---|---|---|---|---|
| Book Evidence-to-Story Inventory | Strongest ideas, tensions, human stakes, usable examples, source or ledger IDs and claims not to strengthen. | Book Editor + Claim Steward |  |  |
| Book Brief Gate | Reader promise, central question, provisional thesis, narrative spine, chapter jobs, motifs, exclusions and intended reader experience. | Claim Steward + Book Editor + Clu |  |  |
| Scenario / Lived-World Checkpoint, if applicable | Worldspace matrix, world condition cards, protagonist dossiers, scene-level story overviews and Clu manual review. | Foresight Scenario Modeller + Claim Steward + Clu; user approval where requested |  |  |
| Sample Opening Gate | Sample opening plus representative middle passage. | Book Editor + Claim Steward + Literary Reviewer or Clu |  |  |
| Full Manuscript Draft | Complete reader-facing nonfiction manuscript. | Book Editor + Claim Steward |  |  |
| Claim Review | Check literary force does not strengthen claims, erase uncertainty or add unauthorised conclusions. | Claim Steward |  |  |
| Independent Literary Review | Review as standalone nonfiction. | Independent Literary Review Agent |  |  |
| Clu Final Book Approval | Final hard gate using the Clu sign-off standard in the SOP. | Clu |  |  |

Book work cannot be marked complete merely because prose exists. If the brief or sample fails, revise before drafting the full manuscript.

---

## 11. Execution and sign-off sequence

Follow the universal stage sequence in `docs/STAGE_ORCHESTRATOR_SOP.md`.

Visual reference: `docs/PROCESS_PATHWAY_MAPS.md`, P1.

| Step | Task | Responsible agent | Output | Required sign-off | Status |
|---|---|---|---|---|---|
| 1 | Read stage guide and authorised inputs; confirm boundary. | Clu / Master Coordinator | Confirmed scope. | Clu + Claim Steward |  |
| 2 | Complete execution plan and commission agents. | Research Operations / Clu | `STAGE_EXECUTION.md`; commission records | Clu + Research Operations Manager + Claim Steward |  |
| 3 | Conduct source discovery or confirm existing-source restriction. | Research Librarian / Methodologist | Ledger source records or source-boundary note. | Claim Steward + Evidence Auditor |  |
| 4 | Synthesise evidence. | Evidence Synthesis / domain agents | Draft findings and evidence records. | Claim Steward |  |
| 5 | Classify claims, assumptions, risks and uncertainties. | Claim Steward | Ledger claim records. | Claim Steward |  |
| 6 | Run specialist synthesis. | Specialists | Talks / synthesis briefs. | Relevant Specialist + Claim Steward |  |
| 7 | Chair cross-agent discussion. | Clu / Master Coordinator | Ledger challenges and decisions. | Clu + Knowledge Integration Architect |  |
| 8 | Decide editorial architecture. | Clu / Documentation Editor / Book Editor | Thesis, report structure and initial book direction logged. | Clu + Claim Steward |  |
| 9 | Draft authority outputs. | Assigned agents | `STAGE_REPORT.md`, draft `PASS_FORWARD.md`, draft `PUBLIC_SUMMARY.md` | Documentation Editor + Claim Steward |  |
| 10 | Run evidence, bias, adversarial, domain and pass-forward review. | Review agents | `STAGE_REVIEW.md`; required revisions. | Required stage reviewers |  |
| 11 | Finalise `PASS_FORWARD.md`. | Clu + Claim Steward | Authorised downstream interface. | Clu + Claim Steward + Evidence Auditor + required stage reviewers |  |
| 12 | Finalise public summary. | Public Narrative Strategist / Documentation Editor | `PUBLIC_SUMMARY.md` | Public Narrative Strategist + Claim Steward + Clu |  |
| 13 | Run book creation protocol: inventory, brief, brief gate, sample, sample gate and full draft. | Book / Manuscript Editor + Claim Steward + Clu | `STAGE_BOOK.md` control records and manuscript draft | Book Brief Gate and Sample Quality Gate must pass before full draft |  |
| 14 | Run claim review, independent literary review, revise and apply Clu final book approval. | Claim Steward + Independent Literary Review Agent + Book Editor + Clu | Review record and final `STAGE_BOOK.md` | Claim Steward + Independent Literary Review Agent + Clu |  |
| 15 | Final validation and closure. | Clu / Master Coordinator | Stage gate decision and resume marker. | Clu final gate decision |  |

---

## 12. Output checklist

A complete stage folder must contain:

- [ ] `STAGE_EXECUTION.md`
- [ ] `STAGE_LEDGER.csv`
- [ ] `STAGE_REPORT.md`
- [ ] `STAGE_REVIEW.md`
- [ ] `PASS_FORWARD.md`
- [ ] `PUBLIC_SUMMARY.md`
- [ ] `STAGE_BOOK.md`

Authority boundary:

- [ ] `PASS_FORWARD.md` contains the only downstream-authorised claims.
- [ ] `STAGE_BOOK.md` is marked and reviewed as a reader-facing companion, not downstream authority.
- [ ] Book Evidence-to-Story Inventory completed.
- [ ] Book Brief Gate passed before full manuscript drafting.
- [ ] Sample Quality Gate passed before full manuscript drafting.
- [ ] Claim Review and Independent Literary Review completed.
- [ ] Clu Final Book Approval completed.

---

## 13. Resumability log

After every major step, add a dated resume marker.

Visual reference: `docs/PROCESS_PATHWAY_MAPS.md`, P7.

| Resume marker | Completed | Source or ledger IDs used | Open questions | Current synthesis status | Next exact action |
|---|---|---|---|---|---|
| R-001 |  |  |  |  |  |

---

## 14. Known risks before starting

| Risk | Why it matters | Mitigation |
|---|---|---|
|  |  |  |

---

## 15. Start decision

**Start decision:** `approved | revise_before_start`

**Reason:**

> [Write here]
