# Process Pathway Maps

This file visually maps the critical Year Zero operating pathways.

It is a reference companion to `AGENTS.md` and `docs/STAGE_ORCHESTRATOR_SOP.md`. It does not replace the SOP. If there is a conflict, the SOP governs.

The purpose of these maps is to make the organisation easier to audit, resume, explain and improve. They should help agents and human reviewers see where work enters the system, where claims gain authority, where quality gates apply and where user permission is required.

---

## 1. Diagram labelling standard

All pathway diagrams use the same label system so that charts can refer to one another clearly.

### 1.1 Pathway IDs

| Pathway ID | Pathway | Purpose |
|---|---|---|
| `P0` | Integrated Process Map | Shows how all pathway maps connect. |
| `P1` | Stage Execution Pathway | Shows the full route through a stage. |
| `P2` | Agent Commissioning Pathway | Shows how agents are scoped, authorised and reviewed. |
| `P3` | Evidence-to-Pass-Forward Pathway | Shows how evidence becomes authorised downstream claims. |
| `P4` | Book Output Pathway | Shows how reader-facing nonfiction is created and reviewed. |
| `P5` | Sign-Off and Quality Gate Pathway | Shows how artifacts move from draft to approved or blocked. |
| `P6` | External Authority and Permission Pathway | Shows when explicit user approval is required. |
| `P7` | Resumability Pathway | Shows how work is logged so later agents can resume. |

### 1.2 Node labels

Each node label uses this format:

```text
[PathwayID.NodeID] Human-readable action
```

Example:

```text
[P2.C3] Assign access tiers
```

The label means:

- `P2` = Agent Commissioning Pathway;
- `C3` = third major node in that pathway;
- the text after the code is the action.

### 1.3 Cross-chart references

When one chart zooms into a step from another chart, the source node is listed as a cross-reference.

Example:

```text
Zooms into: [P1.S3] Commission agents
Feeds back to: [P1.S4] Confirm source strategy
```

Mermaid diagrams are visual aids. The reliable links between charts are the headings, node IDs and cross-reference tables.

### 1.4 Status labels

Use the same status language across process maps, templates and review records:

| Status | Meaning |
|---|---|
| `draft` | Work exists but is not yet reliable. |
| `ready` | Work can be used for its intended purpose. |
| `ready_with_cautions` | Work can proceed only with visible cautions. |
| `revise_before_ready` | Work cannot proceed until specific revisions are made. |
| `blocked` | Work cannot proceed safely under current authority, evidence or access. |

### 1.5 Visual conventions

| Shape or edge | Meaning |
|---|---|
| Rectangle | Normal process step. |
| Diamond | Decision point. |
| Loop-back arrow | Revision, repair or retry route. |
| Dashed edge | Cross-pathway dependency or advisory connection. |
| “User approval required” node | Work cannot proceed autonomously. |

---

## 2. P0 — Integrated Process Map

This is the map of maps. Every detailed pathway below is a zoom-in on one or more nodes here.

```mermaid
flowchart TD
    P0_A["[P0.A] Stage or task authorised"] --> P1_S1["[P1.S1] Run stage execution pathway"]
    P1_S1 --> P2_C1["[P2.C1] Commission agents"]
    P2_C1 --> P3_E1["[P3.E1] Build evidence-to-pass-forward chain"]
    P3_E1 --> P5_Q1["[P5.Q1] Apply sign-off and quality gates"]
    P5_Q1 --> P1_S2["[P1.S2] Finalise authority outputs"]
    P1_S2 --> P4_B1["[P4.B1] Produce book output"]
    P4_B1 --> P5_Q2["[P5.Q2] Review book and stage closure"]
    P5_Q2 --> P0_B{"[P0.B] External/public action needed?"}
    P0_B -- "No" --> P7_R1["[P7.R1] Log resume marker and close"]
    P0_B -- "Yes" --> P6_X1["[P6.X1] Run permission pathway"]
    P6_X1 --> P7_R1

    P7_R1 -. "wraps every major step" .-> P1_S1
    P5_Q1 -. "governs every artifact" .-> P2_C1
```

### Cross-chart links

| P0 node | Detailed pathway |
|---|---|
| `[P1.S1] Run stage execution pathway` | [P1 — Stage Execution Pathway](#3-p1--stage-execution-pathway) |
| `[P2.C1] Commission agents` | [P2 — Agent Commissioning Pathway](#4-p2--agent-commissioning-pathway) |
| `[P3.E1] Build evidence-to-pass-forward chain` | [P3 — Evidence-to-Pass-Forward Pathway](#5-p3--evidence-to-pass-forward-pathway) |
| `[P4.B1] Produce book output` | [P4 — Book Output Pathway](#6-p4--book-output-pathway) |
| `[P5.Q1] Apply sign-off and quality gates` | [P5 — Sign-Off and Quality Gate Pathway](#7-p5--sign-off-and-quality-gate-pathway) |
| `[P6.X1] Run permission pathway` | [P6 — External Authority and Permission Pathway](#8-p6--external-authority-and-permission-pathway) |
| `[P7.R1] Log resume marker and close` | [P7 — Resumability Pathway](#9-p7--resumability-pathway) |

---

## 3. P1 — Stage Execution Pathway

**Zooms into:** `[P0.A] Stage or task authorised`  
**Calls:** P2, P3, P4, P5, P7  
**Governed by:** `docs/STAGE_ORCHESTRATOR_SOP.md`

```mermaid
flowchart TD
    S1["[P1.S1] Stage authorised"] --> S2["[P1.S2] Read operating docs"]
    S2 --> S3["[P1.S3] Confirm stage boundary"]
    S3 --> S4["[P1.S4] Commission agents"]
    S4 --> S5["[P1.S5] Assign access tiers"]
    S5 --> S6["[P1.S6] Confirm source strategy"]
    S6 --> S7["[P1.S7] Build or confirm ledger"]
    S7 --> S8["[P1.S8] Extract evidence and classify claims"]
    S8 --> S9["[P1.S9] Specialist synthesis"]
    S9 --> S10["[P1.S10] Chaired cross-agent discussion"]
    S10 --> S11["[P1.S11] Editorial architecture decision"]
    S11 --> S12["[P1.S12] Draft authority outputs"]
    S12 --> S13["[P1.S13] Evidence, bias and adversarial review"]
    S13 --> S14{"[P1.S14] Review passed?"}
    S14 -- "No" --> S15["[P1.S15] Revise, weaken or block claims"]
    S15 --> S12
    S14 -- "Yes" --> S16["[P1.S16] Finalise PASS_FORWARD.md"]
    S16 --> S17["[P1.S17] Draft PUBLIC_SUMMARY.md"]
    S17 --> S18["[P1.S18] Run book creation protocol"]
    S18 --> S19["[P1.S19] Claim and literary review"]
    S19 --> S20{"[P1.S20] Book approved?"}
    S20 -- "No" --> S21["[P1.S21] Revise or rewrite book"]
    S21 --> S18
    S20 -- "Yes" --> S22["[P1.S22] Final stage gate"]
    S22 --> S23["[P1.S23] Close stage with resume marker"]

    S4 -. "see P2" .-> C1["[P2.C1] Agent commissioning"]
    S8 -. "see P3" .-> E1["[P3.E1] Evidence chain"]
    S13 -. "see P5" .-> Q1["[P5.Q1] Quality gate"]
    S18 -. "see P4" .-> B1["[P4.B1] Book output"]
    S23 -. "see P7" .-> R1["[P7.R1] Resumability"]
```

### Cross-chart links

| P1 node | Links to |
|---|---|
| `[P1.S4] Commission agents` | [P2 — Agent Commissioning Pathway](#4-p2--agent-commissioning-pathway) |
| `[P1.S8] Extract evidence and classify claims` | [P3 — Evidence-to-Pass-Forward Pathway](#5-p3--evidence-to-pass-forward-pathway) |
| `[P1.S13] Evidence, bias and adversarial review` | [P5 — Sign-Off and Quality Gate Pathway](#7-p5--sign-off-and-quality-gate-pathway) |
| `[P1.S18] Run book creation protocol` | [P4 — Book Output Pathway](#6-p4--book-output-pathway) |
| `[P1.S23] Close stage with resume marker` | [P7 — Resumability Pathway](#9-p7--resumability-pathway) |

### Improvement checkpoints

- Check whether agent commissions were specific enough before work began.
- Check whether source collection was authorised or explicitly prohibited.
- Check whether the book arc was sketched after editorial architecture and before manuscript drafting.
- Check whether cautions from review were carried into `PASS_FORWARD.md`.

---

## 4. P2 — Agent Commissioning Pathway

**Zooms into:** `[P1.S4] Commission agents`  
**Feeds back to:** `[P1.S5] Assign access tiers`, `[P1.S9] Specialist synthesis`, `[P1.S13] Review`

```mermaid
flowchart TD
    C1["[P2.C1] Clu identifies required work"] --> C2["[P2.C2] Select smallest sufficient agent team"]
    C2 --> C3["[P2.C3] Issue Agent Commission Contract"]
    C3 --> C4["[P2.C4] Define exact task"]
    C4 --> C5["[P2.C5] Define authorised inputs"]
    C5 --> C6["[P2.C6] Assign information access tier"]
    C6 --> C7["[P2.C7] Assign tool access tier"]
    C7 --> C8["[P2.C8] Define prohibited actions"]
    C8 --> C9["[P2.C9] Define output and handoff format"]
    C9 --> C10["[P2.C10] Define reviewer or sign-off owner"]
    C10 --> C11{"[P2.C11] Commission checksum complete?"}
    C11 -- "No" --> C12["[P2.C12] Repair commission before agent starts"]
    C12 --> C3
    C11 -- "Yes" --> C13["[P2.C13] Agent performs work"]
    C13 --> C14["[P2.C14] Agent self-review"]
    C14 --> C15{"[P2.C15] Agent ready?"}
    C15 -- "No" --> C16["[P2.C16] Return draft, caution or blocked status"]
    C15 -- "Yes" --> C17["[P2.C17] Handoff to reviewer"]

    C17 -. "review governed by P5" .-> Q1["[P5.Q1] Artifact quality gate"]
```

### Commission checksum

No commissioned agent should begin work unless these fields are filled:

| Required field | Why it matters |
|---|---|
| Exact task | Prevents elegant but irrelevant work. |
| Authorised inputs | Prevents invented context and source drift. |
| Information access tier | Prevents over-reading and hidden dependency sprawl. |
| Tool access tier | Prevents unauthorised mutation or external action. |
| Prohibited actions | Prevents predictable boundary mistakes. |
| Required handoff | Prevents unusable informal summaries. |
| Reviewer / sign-off owner | Prevents self-approval. |

### Cross-chart links

| P2 node | Links to |
|---|---|
| `[P2.C6] Assign information access tier` | [P6 — External Authority and Permission Pathway](#8-p6--external-authority-and-permission-pathway), when access involves external systems |
| `[P2.C13] Agent performs work` | [P3](#5-p3--evidence-to-pass-forward-pathway), [P4](#6-p4--book-output-pathway) or [P5](#7-p5--sign-off-and-quality-gate-pathway), depending on commission |
| `[P2.C17] Handoff to reviewer` | [P5 — Sign-Off and Quality Gate Pathway](#7-p5--sign-off-and-quality-gate-pathway) |

---

## 5. P3 — Evidence-to-Pass-Forward Pathway

**Zooms into:** `[P1.S8] Extract evidence and classify claims`  
**Feeds:** `STAGE_REPORT.md`, `PASS_FORWARD.md`  
**Important boundary:** `STAGE_BOOK.md` may use reviewed synthesis, but it cannot authorise downstream claims.

```mermaid
flowchart TD
    E1["[P3.E1] Authorised source or upstream pass-forward"] --> E2["[P3.E2] Ledger source record"]
    E2 --> E3["[P3.E3] Evidence extraction"]
    E3 --> E4["[P3.E4] Claim proposal"]
    E4 --> E5["[P3.E5] Claim classification"]
    E5 --> E6["[P3.E6] Confidence and scope assigned"]
    E6 --> E7["[P3.E7] Limitations and counterevidence logged"]
    E7 --> E8["[P3.E8] Specialist synthesis"]
    E8 --> E9["[P3.E9] Discussion and challenge"]
    E9 --> E10["[P3.E10] Claim Steward review"]
    E10 --> E11{"[P3.E11] Survives review?"}
    E11 -- "No" --> E12["[P3.E12] Rejected or weakened claim logged"]
    E11 -- "Yes" --> E13["[P3.E13] Candidate for STAGE_REPORT.md"]
    E13 --> E14["[P3.E14] Pass-forward audit"]
    E14 --> E15{"[P3.E15] Authorised downstream?"}
    E15 -- "No" --> E16["[P3.E16] Context only or excluded"]
    E15 -- "Yes" --> E17["[P3.E17] PASS_FORWARD.md"]

    E13 -. "may inform prose only" .-> B1["[P4.B1] Book manuscript"]
    E17 -. "only downstream authority" .-> S1["[P1.S1] Next authorised stage"]
```

### Cross-chart links

| P3 node | Links to |
|---|---|
| `[P3.E8] Specialist synthesis` | [P2 — Agent Commissioning Pathway](#4-p2--agent-commissioning-pathway) |
| `[P3.E10] Claim Steward review` | [P5 — Sign-Off and Quality Gate Pathway](#7-p5--sign-off-and-quality-gate-pathway) |
| `[P3.E13] Candidate for STAGE_REPORT.md` | [P1 — Stage Execution Pathway](#3-p1--stage-execution-pathway) |
| `[P3.E17] PASS_FORWARD.md` | Downstream stage authorisation |

### Improvement checkpoints

- Check whether any claim skipped ledger support.
- Check whether a claim moved from `context only` into `PASS_FORWARD.md` without review.
- Check whether the book uses a claim more strongly than `PASS_FORWARD.md` or `STAGE_REPORT.md` permits.

---

## 6. P4 — Book Output Pathway

**Zooms into:** `[P1.S18] Run book creation protocol`  
**Depends on:** reviewed synthesis from P3  
**Governed by:** independent literary review and claim discipline  
**Cannot feed:** downstream authority unless the claim is also in `PASS_FORWARD.md`

```mermaid
flowchart TD
    B1["[P4.B1] Reviewed stage synthesis"] --> B2["[P4.B2] Evidence-to-Story Inventory"]
    B2 --> BW1{"[P4.BW1] Scenario or lived-world book?"}
    BW1 -- "No" --> B3
    BW1 -- "Yes" --> BW2["[P4.BW2] Worldspace Matrix"]
    BW2 --> BW3["[P4.BW3] World Condition Cards"]
    BW3 --> BW4["[P4.BW4] Protagonist Dossiers"]
    BW4 --> BW5["[P4.BW5] Scene-level Story Overview"]
    BW5 --> BW6{"[P4.BW6] Clu Manual Story Overview Review passed?"}
    BW6 -- "No" --> BW7["[P4.BW7] Redesign worlds, protagonists or arcs"]
    BW7 --> BW2
    BW6 -- "Yes" --> BW8{"[P4.BW8] User checkpoint required?"}
    BW8 -- "Yes" --> BW9["[P4.BW9] Stop for user approval"]
    BW9 --> BW10{"[P4.BW10] User approves story overview?"}
    BW10 -- "No" --> BW7
    BW10 -- "Yes" --> B3
    BW8 -- "No" --> B3
    B3 --> B4{"[P4.B4] Book Brief Gate passed?"}
    B4 -- "No" --> B5["[P4.B5] Revise brief or reject arc"]
    B5 --> B3
    B4 -- "Yes" --> B6["[P4.B6] Sample opening and middle passage"]
    B6 --> B7{"[P4.B7] Sample Quality Gate passed?"}
    B7 -- "No" --> B8["[P4.B8] Revise voice, texture or narrative approach"]
    B8 --> B6
    B7 -- "Yes" --> B9["[P4.B9] Full manuscript draft"]
    B9 --> B10["[P4.B10] Claim Review"]
    B10 --> B11{"[P4.B11] Evidence discipline intact?"}
    B11 -- "No" --> B12["[P4.B12] Revise claims, citations or certainty"]
    B12 --> B9
    B11 -- "Yes" --> B13["[P4.B13] Independent Literary Review Agent"]
    B13 --> B14{"[P4.B14] Literary decision"}
    B14 -- "Approved" --> B15["[P4.B15] Clu Final Book Approval"]
    B14 -- "Approved with minor edits" --> B16["[P4.B16] Apply edits"]
    B16 --> B15
    B14 -- "Revise before approval" --> B17["[P4.B17] Substantive revision"]
    B17 --> B9
    B14 -- "Reject and rewrite" --> B18["[P4.B18] Restart from brief or synthesis"]
    B18 --> B2
    B15 --> B19{"[P4.B19] Clu stakes name on draft?"}
    B19 -- "No" --> B17
    B19 -- "Yes" --> B20["[P4.B20] Book output complete"]
    B20 --> B21["[P4.B21] Public narrative companion only"]

    B4 -. "quality governed by P5" .-> Q1["[P5.Q1] Artifact quality gate"]
    BW6 -. "quality governed by P5" .-> Q1
    BW9 -. "pause logged through P7" .-> R1["[P7.R1] Resume marker"]
    B7 -. "quality governed by P5" .-> Q1
    B10 -. "evidence governed by P3" .-> E1["[P3.E1] Evidence chain"]
    B15 -. "closure logged through P7" .-> R1["[P7.R1] Resume marker"]
    B21 -. "not authority" .-> E17["[P3.E17] PASS_FORWARD.md remains authority"]
```

### Cross-chart links

| P4 node | Links to |
|---|---|
| `[P4.B1] Reviewed stage synthesis` | [P3 — Evidence-to-Pass-Forward Pathway](#5-p3--evidence-to-pass-forward-pathway) |
| `[P4.BW2] Worldspace Matrix` | [P3 — Evidence-to-Pass-Forward Pathway](#5-p3--evidence-to-pass-forward-pathway) and [P2 — Agent Commissioning Pathway](#4-p2--agent-commissioning-pathway) |
| `[P4.BW6] Clu Manual Story Overview Review passed?` | [P5 — Sign-Off and Quality Gate Pathway](#7-p5--sign-off-and-quality-gate-pathway) |
| `[P4.BW9] Stop for user approval` | [P7 — Resumability Pathway](#9-p7--resumability-pathway) |
| `[P4.B4] Book Brief Gate passed?` | [P5 — Sign-Off and Quality Gate Pathway](#7-p5--sign-off-and-quality-gate-pathway) |
| `[P4.B7] Sample Quality Gate passed?` | [P5 — Sign-Off and Quality Gate Pathway](#7-p5--sign-off-and-quality-gate-pathway) |
| `[P4.B10] Claim Review` | [P3 — Evidence-to-Pass-Forward Pathway](#5-p3--evidence-to-pass-forward-pathway) and [P5 — Sign-Off and Quality Gate Pathway](#7-p5--sign-off-and-quality-gate-pathway) |
| `[P4.B13] Independent Literary Review Agent` | [P2 — Agent Commissioning Pathway](#4-p2--agent-commissioning-pathway) |
| `[P4.B15] Clu Final Book Approval` | [P7 — Resumability Pathway](#9-p7--resumability-pathway) |
| `[P4.B21] Public narrative companion only` | [P3 — Evidence-to-Pass-Forward Pathway](#5-p3--evidence-to-pass-forward-pathway) |

### Improvement checkpoints

- The Book Evidence-to-Story Inventory and Book Brief must be created before full manuscript drafting.
- Scenario or lived-world books must pass the worldspace matrix, world condition card, protagonist dossier and story-overview checkpoint before prose drafting.
- If a user checkpoint is required, the stage must stop with a resume marker before full manuscript drafting.
- The Sample Quality Gate must pass before full manuscript drafting.
- The literary reviewer must not be the book writer.
- Approval by length, polish or completeness is not enough.
- Clu must reject the book if it is coherent but not genuinely reader-worthy.

---

## 7. P5 — Sign-Off and Quality Gate Pathway

**Applies to:** every artifact, agent handoff and major claim  
**Feeds:** P1 stage closure, P3 pass-forward approval, P4 book approval

```mermaid
flowchart TD
    Q1["[P5.Q1] Artifact drafted"] --> Q2["[P5.Q2] Required reviewers assigned"]
    Q2 --> Q3["[P5.Q3] Reviewer checks artifact"]
    Q3 --> Q4{"[P5.Q4] Sign-off status"}
    Q4 -- "ready" --> Q5["[P5.Q5] Can proceed"]
    Q4 -- "ready_with_cautions" --> Q6["[P5.Q6] Proceed with visible cautions"]
    Q4 -- "revise_before_ready" --> Q7["[P5.Q7] Mandatory revision"]
    Q4 -- "blocked" --> Q8["[P5.Q8] Escalate to Clu or user"]
    Q6 --> Q9["[P5.Q9] Cautions carried into review and pass-forward"]
    Q7 --> Q1
    Q8 --> Q10["[P5.Q10] Scope, evidence or authority decision needed"]

    Q10 -. "may require P6" .-> X1["[P6.X1] Permission pathway"]
    Q9 -. "feeds P7" .-> R1["[P7.R1] Resume marker"]
```

### Cross-chart links

| P5 node | Links to |
|---|---|
| `[P5.Q2] Required reviewers assigned` | [P2 — Agent Commissioning Pathway](#4-p2--agent-commissioning-pathway) |
| `[P5.Q7] Mandatory revision` | Back to the relevant drafting pathway: P1, P3 or P4 |
| `[P5.Q8] Escalate to Clu or user` | [P6 — External Authority and Permission Pathway](#8-p6--external-authority-and-permission-pathway), where authority is required |
| `[P5.Q9] Cautions carried into review and pass-forward` | [P3 — Evidence-to-Pass-Forward Pathway](#5-p3--evidence-to-pass-forward-pathway) |

### Improvement checkpoints

- Use the same sign-off statuses everywhere.
- Check that `ready_with_cautions` actually carries cautions forward.
- Treat `blocked` as a real stop, not a rhetorical warning.

---

## 8. P6 — External Authority and Permission Pathway

**Applies to:** git, publishing, release, merge, public communication, external contact, learner-facing action and anything beyond the authorised workspace task.

```mermaid
flowchart TD
    X1["[P6.X1] Agent proposes action"] --> X2{"[P6.X2] Internal research or writing?"}
    X2 -- "Yes" --> X3["[P6.X3] Allowed within commission"]
    X2 -- "No" --> X4{"[P6.X4] External, public, git, release, learner or contact action?"}
    X4 -- "No" --> X5["[P6.X5] Clu may proceed if stage-authorised"]
    X4 -- "Yes" --> X6["[P6.X6] Explicit user approval required"]
    X6 --> X7{"[P6.X7] Approved?"}
    X7 -- "No" --> X8["[P6.X8] Do not act"]
    X7 -- "Yes" --> X9["[P6.X9] Action proceeds within approved scope"]
    X9 --> X10["[P6.X10] Log action and resume state"]

    X10 -. "feeds P7" .-> R1["[P7.R1] Resume marker"]
```

### Cross-chart links

| P6 node | Links to |
|---|---|
| `[P6.X3] Allowed within commission` | [P2 — Agent Commissioning Pathway](#4-p2--agent-commissioning-pathway) |
| `[P6.X6] Explicit user approval required` | Clu / user decision |
| `[P6.X10] Log action and resume state` | [P7 — Resumability Pathway](#9-p7--resumability-pathway) |

### Improvement checkpoints

- If the action changes the outside world, assume explicit user approval is required.
- If the action only changes assigned workspace files within the authorised task, the agent may proceed under its tool tier.
- Git commit, push, merge, release and public publication are never implied by research completion.

---

## 9. P7 — Resumability Pathway

**Applies to:** every major step and every context-risky work session  
**Purpose:** prevent future agents from doing archaeology.

```mermaid
flowchart TD
    R1["[P7.R1] Major work step completed"] --> R2["[P7.R2] Update STAGE_EXECUTION.md"]
    R2 --> R3["[P7.R3] Add ledger record if substantive"]
    R3 --> R4["[P7.R4] Record completed outputs"]
    R4 --> R5["[P7.R5] Record source IDs used"]
    R5 --> R6["[P7.R6] Record open questions"]
    R6 --> R7["[P7.R7] Record weakened or rejected claims"]
    R7 --> R8["[P7.R8] Record next exact action"]
    R8 --> R9{"[P7.R9] Context interruption?"}
    R9 -- "No" --> R10["[P7.R10] Continue"]
    R9 -- "Yes" --> R11["[P7.R11] Future agent resumes without guessing"]

    R11 -. "returns to P1" .-> S1["[P1.S1] Stage execution pathway"]
```

### Cross-chart links

| P7 node | Links to |
|---|---|
| `[P7.R2] Update STAGE_EXECUTION.md` | Stage execution file |
| `[P7.R3] Add ledger record if substantive` | `STAGE_LEDGER.csv` |
| `[P7.R8] Record next exact action` | Next relevant pathway node |
| `[P7.R11] Future agent resumes without guessing` | [P1 — Stage Execution Pathway](#3-p1--stage-execution-pathway) |

### Improvement checkpoints

- Every resume marker should include the next exact action.
- Resume markers should record weakened or rejected claims, not only completed work.
- If a stage is interrupted during review, the reviewer state must be recoverable.

---

## 10. Accessibility and maintenance notes

These diagrams are aids, not the only source of truth.

To keep them accessible:

- each diagram has a short prose explanation;
- every diagram node has a visible text label, not only a shape;
- every chart has a cross-reference table;
- decisions are named in plain language;
- the same terms are used in the SOP, templates and review gates.

To keep them maintainable:

- update this file when the SOP changes a pathway;
- preserve node IDs where possible so references do not break;
- if a node must be removed, note its replacement in the relevant cross-chart table;
- do not add decorative diagrams that do not clarify an operating decision.

---

## 11. Current known improvement candidates

These are lightweight improvements already reflected in the maps:

1. **Commission checksum** — agents should not begin until task, inputs, access, prohibitions, handoff and reviewer are explicit.
2. **Hardened book gates** — Book Evidence-to-Story Inventory, Book Brief Gate and Sample Quality Gate must happen before full manuscript drafting.
3. **Next exact action** — every resume marker should state exactly what the next agent should do.
4. **Book cannot bypass pass-forward** — `STAGE_BOOK.md` may explain claims, but downstream authority remains `PASS_FORWARD.md`.
5. **User approval boundary** — git, merge, release, publishing, external contact and learner-facing actions require explicit user approval.
