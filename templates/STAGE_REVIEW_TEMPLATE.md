# Stage Review

> Copy this file into the active stage folder as `STAGE_REVIEW.md`.

This file combines adversarial review, evidence audit, bias/generalisation audit, implementation risk review, book-output review and stage gate decision.

The review should make the stage stronger, not merely criticise it.

Pipeline reminder: `PASS_FORWARD.md` is downstream authority; `STAGE_BOOK.md` needs independent literary review; major process milestones should appear in resumability logging.

Visual pathway reminder: use `docs/PROCESS_PATHWAY_MAPS.md` when auditing whether evidence, sign-off, book review, permission boundaries or resumability have followed the expected route.

---

## 1. Review identity

**Stage number:**  
**Stage name:**  
**Review date:**  
**Review agents:**  
**Stage report reviewed:** `STAGE_REPORT.md`  
**Ledger reviewed:** `STAGE_LEDGER.csv`  
**Book output reviewed:** `STAGE_BOOK.md`

---

## 2. Review decision

Choose one:

- [ ] `pass`
- [ ] `pass_with_cautions`
- [ ] `revise_before_pass`
- [ ] `rollback_required`

**Decision rationale:**

> [Write here]

---

## 3. Artifact sign-off audit

No artifact can be marked complete merely because it exists. Use the universal artifact gate in `docs/STAGE_ORCHESTRATOR_SOP.md`.

Visual reference: `docs/PROCESS_PATHWAY_MAPS.md`, P5.

| Artifact | Required reviewers | Sign-off status | Blocking issues | Required action |
|---|---|---|---|---|
| `STAGE_EXECUTION.md` | Clu + Research Operations Manager + Claim Steward | `ready`, `ready_with_cautions`, `revise_before_ready` or `blocked` |  |  |
| `STAGE_LEDGER.csv` | Research Librarian or Evidence Lead + Claim Steward + Evidence Auditor |  |  |  |
| Specialist outputs | Relevant Specialist + Claim Steward |  |  |  |
| Discussion synthesis | Clu + Knowledge Integration Architect + Red Team where relevant |  |  |  |
| `STAGE_REPORT.md` | Documentation Editor + Claim Steward + Evidence Auditor + relevant domain lead |  |  |  |
| `PASS_FORWARD.md` | Clu + Claim Steward + Evidence Auditor + required stage reviewers |  |  |  |
| `PUBLIC_SUMMARY.md` | Public Narrative Strategist + Claim Steward + Clu |  |  |  |
| `STAGE_BOOK.md` | Book Editor + Claim Steward + Independent Literary Review Agent + Clu |  |  |  |
| `STAGE_REVIEW.md` | Evidence Auditor + Bias Auditor + Red Team + Clu |  |  |  |

### 3.1 Stage-specific reviewer confirmation

List the minimum required reviewers from the SOP stage-specific matrix.

| Required reviewer | Role in this stage | Review completed? | Sign-off status | Notes |
|---|---|---|---|---|
|  |  | `yes` or `no` |  |  |

---

## 4. Strongest objections

List the strongest objections to the stage output.

| Objection ID | Objection | Severity | Required response |
|---|---|---|---|
| O-001 |  | `low`, `moderate`, `high` or `critical` |  |

---

## 5. Evidence audit

| Claim reviewed | Evidence cited | Does evidence support claim? | Problem | Required fix |
|---|---|---|---|---|
|  |  | `yes`, `partly`, `no` or `unclear` |  |  |

### 5.1 Evidence concerns

- [ ] Evidence too weak for claim.
- [ ] Source used outside its scope.
- [ ] Important counterevidence missing.
- [ ] Evidence is illustrative only.
- [ ] Recent claim requires updated source.
- [ ] Source quality unclear.
- [ ] Evidence not logged in ledger.

---

## 6. Claim classification audit

| Claim | Current classification | Correct classification? | Required change |
|---|---|---|---|
|  |  | `yes`, `no` or `uncertain` |  |

Check against the canonical claim-handling rules in `docs/STAGE_ORCHESTRATOR_SOP.md`, especially misclassified findings, assumptions, values, projections and design decisions.

---

## 7. Assumption audit

| Assumption | Is it visible? | Is it justified? | What if wrong? | Required response |
|---|---|---|---|---|
|  |  |  |  |  |

---

## 8. Uncertainty audit

| Uncertainty | Has it been preserved? | Downstream risk | Required response |
|---|---|---|---|
|  |  |  |  |

Reviewers should reject outputs that remove uncertainty merely to sound decisive.

---

## 9. Bias and generalisability audit

| Bias risk | Present? | Evidence | Required response |
|---|---|---|---|
| WEIRD bias |  |  |  |
| High-resource assumption |  |  |  |
| Technology access assumption |  |  |  |
| Neurotypical assumption |  |  |  |
| Elite education bias |  |  |  |
| Urban/middle-class bias |  |  |  |
| Cultural or family value narrowness |  |  |  |
| English-language source bias |  |  |  |

---

## 10. Implementation risk review

| Risk | Who affected? | Severity | Mitigation or pass-forward caution |
|---|---|---|---|
|  |  |  |  |

Consider:

- home education;
- mainstream schools;
- alternative provision;
- low-resource settings;
- independent learners;
- educators with limited time;
- learners with different needs;
- parents without specialist knowledge.

---

## 11. Ethics and safety review

| Issue | Present? | Required response |
|---|---|---|
| Learner privacy risk |  |  |
| Overclaiming impact |  |  |
| High-stakes misuse |  |  |
| Anxiety/fatalism risk |  |  |
| Sensitive learner data risk |  |  |
| Exclusion/accessibility risk |  |  |
| Public misunderstanding risk |  |  |

If any serious ethical issue appears, consult `docs/ETHICS_AND_PUBLIC_TESTING.md`.

---

## 12. Pass-forward audit

Before approving the stage, check the draft pass-forward claims.

Visual reference: `docs/PROCESS_PATHWAY_MAPS.md`, P3.

| Pass-forward claim | Approved? | Required wording change | Caution |
|---|---|---|---|
|  | `yes`, `no` or `revise` |  |  |

Reject any pass-forward claim that is stronger than the stage report supports.

---

## 13. Public summary audit

| Question | Answer |
|---|---|
| Is the public summary understandable? |  |
| Does it preserve uncertainty? |  |
| Does it avoid hype? |  |
| Does it avoid unsupported claims? |  |
| Would a parent or educator understand what has and has not been established? |  |

---

## 14. Book output audit

`STAGE_BOOK.md` is a reader-facing companion, not downstream authority.

Visual reference: `docs/PROCESS_PATHWAY_MAPS.md`, P4.

### 14.1 Book Evidence-to-Story Inventory

| Gate question | Answer | Required action |
|---|---|---|
| Are the strongest ideas and tensions identified before drafting? |  |  |
| Are human stakes and vivid usable examples identified? |  |  |
| Are source or ledger IDs attached to material that will carry major claims? |  |  |
| Are claims that must not be strengthened visible? |  |  |
| Would the inventory support a nonfiction manuscript rather than a report outline? |  |  |

### 14.2 Book Brief Gate

| Gate question | Answer | Required action |
|---|---|---|
| Does the book brief contain a clear reader promise? |  |  |
| Does it contain a viable central question and provisional thesis? |  |  |
| Does the chapter sequence earn its order? |  |  |
| Can the evidence support the proposed story? |  |  |
| Are excluded claims and tempting overclaims visible? |  |  |
| Did Claim Steward, Book Editor and Clu approve the brief before full drafting? |  |  |

### 14.3 Sample Quality Gate

| Gate question | Answer | Required action |
|---|---|---|
| Does the sample opening create curiosity? |  |  |
| Does the representative middle passage show substance rather than summary? |  |  |
| Does the prose have rhythm, specificity and human stakes? |  |  |
| Does it avoid AI texture, report cadence, transcript style and repository/process language? |  |  |
| Does it preserve uncertainty without killing momentum? |  |  |
| Did the sample gate pass before full manuscript drafting? |  |  |

### 14.3A Scenario / lived-world checkpoint audit, if applicable

Use this section when the book output models future worlds, lived scenarios, speculative cases or narrative reconstructions.

| Gate question | Answer | Required action |
|---|---|---|
| Was a worldspace matrix built before prose drafting? |  |  |
| Are the scenario axes explicit and evidence-bounded? |  |  |
| Do the selected worlds differ materially in work/economy, access/control, governance/trust, family life, status and daily routines? |  |  |
| Does each world have a condition card covering technology, infrastructure, economy, governance, access, flourishing pressures and prohibited overextensions? |  |  |
| Does each protagonist dossier include ordinary motives, relationships, class/access position, habits, fears, desires and a personal story engine? |  |  |
| Do scene-level overviews reveal the world through lived action rather than exposition? |  |  |
| Has Clu manually checked for repeated story structures with swapped names? |  |  |
| Has analytic omniscience or project-theory language been banned from character perspective? |  |  |
| If user checkpoint approval was required, did drafting stop before full manuscript creation? |  |  |
| Are scenario years treated as settings rather than predictions? |  |  |

### 14.4 Full Manuscript Gate

| Gate question | Answer | Required action |
|---|---|---|
| Does it have a clear central thesis and cumulative narrative arc? |  |  |
| Do chapters develop rather than merely gesture at ideas? |  |  |
| Are examples inhabited rather than name-checked? |  |  |
| Does narrative propulsion exist across chapters? |  |  |
| Are major claims source-grounded without source dumping? |  |  |
| Does it avoid repo/process meta-text inside the manuscript body? |  |  |
| Does it avoid filler, repeated scaffolds and obvious AI texture? |  |  |
| Does it preserve uncertainty and prohibited overextensions? |  |  |
| Does it avoid later-stage drift? |  |  |

### 14.5 Rejection triggers

If any trigger is present, the book cannot be marked `approved` or `approved_with_minor_edits`.

| Trigger | Present? | Required response |
|---|---|---|
| Too short to fulfil its own chapter promises. |  |  |
| Coherent but thin. |  |  |
| Polished but generic. |  |  |
| Repetitive structure or cadence. |  |  |
| Process or repository language inside the manuscript body. |  |  |
| Source IDs used as decoration rather than support. |  |  |
| No developed human situations, examples or explanatory scenes. |  |  |
| Relies on length, structure or citations as a substitute for insight. |  |  |

### 14.6 Claim Review

| Gate question | Answer | Required action |
|---|---|---|
| Does the book prose avoid strengthening claims beyond the report or pass-forward? |  |  |
| Are emotionally persuasive passages still evidence-disciplined? |  |  |
| Are source or ledger IDs used to support claims rather than decorate prose? |  |  |
| Are uncertainty, limitations and prohibited overextensions preserved? |  |  |
| Did the Claim Steward approve the manuscript before literary approval? |  |  |

### 14.7 Independent literary review

This independent literary review must be performed by a reviewer that did not write `STAGE_BOOK.md`.

Choose one:

- [ ] `approved`
- [ ] `approved_with_minor_edits`
- [ ] `revise_before_approval`
- [ ] `reject_and_rewrite`

**Review agent:**  
**Required edits:**  
**Edits completed:** `yes | no | not_applicable`

Only `approved` or `approved_with_minor_edits` may close the stage. `approved_with_minor_edits` is not allowed when the manuscript needs structural, voice, thesis, chapter-depth or reader-propulsion work.

### 14.8 Clu Final Book Approval

Clu may approve the book output only if every answer below is `yes`.

| Clu sign-off question | Answer | Notes |
|---|---|---|
| Would I show this to the user without apology? | `yes` or `no` |  |
| Can I state the book's central thesis in one sentence? | `yes` or `no` |  |
| Can I explain why the chapter order is necessary? | `yes` or `no` |  |
| Can I identify the strongest scenes, examples or explanatory passages? | `yes` or `no` |  |
| Can I identify where evidence enters the prose? | `yes` or `no` |  |
| Can I name the manuscript's weakest remaining limitation? | `yes` or `no` |  |
| Am I confident it is not merely a polished report? | `yes` or `no` |  |
| Am I confident it is not relying on length, structure or citations as a substitute for insight? | `yes` or `no` |  |
| Would I stake my name on this being the right draft to show? | `yes` or `no` |  |

If any answer is `no`, mark the book output `revise_before_approval` or `reject_and_rewrite`.

---

## 15. Required revisions

| Revision ID | Required change | File affected | Responsible agent | Completion status |
|---|---|---|---|---|
| R-001 |  |  |  |  |

---

## 16. Stage gate decision

### 16.1 Final decision

`pass | pass_with_cautions | revise_before_pass | rollback_required`

### 16.2 Reason

> [Write here]

### 16.3 Conditions attached

If passed with cautions, list them here.

- [ ]
- [ ]

### 16.4 Revision triggers

What future evidence or critique should reopen this stage?

- [ ]
- [ ]

---

## 17. Reviewer sign-off

| Reviewer | Role | Sign-off | Notes |
|---|---|---|---|
|  |  |  |  |
