# Stage Execution Plan

> Copy this file into the active stage folder as `STAGE_EXECUTION.md` before the stage begins.

This file defines how the stage will be run from authorised inputs through evidence, specialist synthesis, chaired discussion, canonical outputs, book output and review.

Do not treat this as a formality. A weak execution plan usually produces weak research, weak pass-forward claims and weak public prose.

Pipeline reminder: `PASS_FORWARD.md` is downstream authority; `STAGE_BOOK.md` needs independent literary review; major process milestones should appear in resumability logging.

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

| Agent harness | Role in this stage | Expected output | Pairing or review relationship |
|---|---|---|---|
| Master Coordinator | Owns stage sequence and final integration. | Approved stage outputs. | Coordinates all agents. |
|  |  |  |  |

### 7.1 Parallel work plan

Where agents work in parallel, describe the division.

| Workstream | Agent(s) | Output | Integration point |
|---|---|---|---|
|  |  |  |  |

### 7.2 Specialist synthesis plan

Use when the stage has multiple domains, conflicting evidence or public-facing synthesis needs.

| Specialist / role | Scope | Authorised sources or inputs | Required output | Integration point |
|---|---|---|---|---|
|  |  |  | Specialist talk / synthesis brief |  |

Each specialist output must follow the Agent Cognitive Quality Protocol in `docs/STAGE_ORCHESTRATOR_SOP.md`.

### 7.3 Cross-agent discussion plan

| Discussion round | Chair | Purpose | Required records |
|---|---|---|---|
|  | Master Coordinator | Connect domains, challenge overclaims and identify emergent structure. | Ledger `challenge` and `decision` records. |

No final thesis, chapter order or pass-forward filtering should be locked before the chaired discussion where specialist synthesis is required.

### 7.4 Adversarial, audit and literary review plan

At least one quality/adversarial review must occur.

| Review type | Agent | What they will attack or audit | When |
|---|---|---|---|
|  |  |  |  |
| Independent literary review | Literary Review Agent | `STAGE_BOOK.md` as standalone nonfiction, source discipline and absence of filler/meta-text. | After book draft and before closure. |

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
- resume markers;
- adversarial challenges;
- revision triggers.

---

## 10. Prompt log

Record important prompts or instructions used with agents.

| Prompt ID | Agent / model | Purpose | Prompt summary | Output file influenced |
|---|---|---|---|---|
| P-001 |  |  |  |  |

Do not paste extremely long prompts unless needed. Summarise and link to full logs if full logs are kept separately.

---

## 11. Execution sequence

| Step | Task | Responsible agent | Output | Status |
|---|---|---|---|---|
| 1 | Read stage guide and authorised inputs. | Master Coordinator | Confirmed scope. |  |
| 2 | Complete execution plan. | Research Operations / Master Coordinator | `STAGE_EXECUTION.md` |  |
| 3 | Conduct source discovery. | Research Librarian | Ledger source records. |  |
| 4 | Synthesise evidence. | Evidence Synthesis / domain agents | Draft findings. |  |
| 5 | Classify claims. | Claim Steward | Ledger claim records. |  |
| 6 | Run specialist synthesis and chaired discussion. | Specialists / Master Coordinator | Ledger talks, challenges and decisions. |  |
| 7 | Decide editorial architecture. | Master Coordinator / Editor | Thesis, report structure and book arc logged. |  |
| 8 | Draft authority outputs. | Assigned agents | `STAGE_REPORT.md`, `PASS_FORWARD.md`, `PUBLIC_SUMMARY.md` |  |
| 9 | Run evidence, bias, adversarial and pass-forward review. | Review agents | `STAGE_REVIEW.md` |  |
| 10 | Draft reader-facing book output. | Editor / Public Narrative Strategist | `STAGE_BOOK.md` |  |
| 11 | Run independent literary review and revise. | Literary Review Agent / Editor | Review record and final `STAGE_BOOK.md` |  |
| 12 | Final validation and closure. | Master Coordinator | Stage gate decision and resume marker. |  |

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

---

## 13. Resumability log

After every major step, add a dated resume marker.

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
