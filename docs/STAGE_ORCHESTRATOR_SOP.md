# Stage Orchestrator SOP

This is the primary operating procedure for running Year Zero research stages from beginning to end.

It consolidates the project’s research method, evidence discipline, agent orchestration, stage gates, pass-forward rules and reader-facing book-output rules. Agents should treat this file as the central stage-execution authority.

`AGENTS.md` defines the role harnesses and quick start sequence. Stage guides define the purpose and boundary of each stage. This SOP defines how a stage is executed.

For a visual reference to the critical process pathways, including cross-chart labels and accessibility notes, use `docs/PROCESS_PATHWAY_MAPS.md`.

---

## 1. Core purpose

Year Zero is building a traceable curriculum hypothesis from first principles:

```text
Human realities
+ Human flourishing
+ AI-shaped future conditions
→ Life within futures
→ Human invariants
→ Enduring functions
→ Capabilities
→ Knowledge, experience and practice
→ Evidence of learning
→ Curriculum architecture
→ Public Version 0.1 release
```

The project must produce two different kinds of output without confusing them:

1. **Authority outputs** — the controlled research interface for downstream stages.
2. **Reader-facing outputs** — public narrative synthesis for the eventual project book.

`PASS_FORWARD.md` is always the downstream authority. `STAGE_BOOK.md` is always a public narrative companion. A later stage may not rely on the book unless the same claim is authorised in `PASS_FORWARD.md`.

---

## 2. Non-negotiable rules

1. Answer the assigned stage question, not the more interesting adjacent question.
2. Do not begin curriculum design before Stage 10.
3. Do not treat agent outputs, prompt examples or prose quality as evidence.
4. Do not convert assumptions into findings.
5. Do not hide normative judgements inside empirical language.
6. Do not present speculative futures as predictions.
7. Do not remove uncertainty to make outputs sound stronger.
8. Do not overwrite or reinterpret earlier conclusions silently.
9. Do not pass work forward unless review and gate rules are satisfied.
10. Do not make `STAGE_BOOK.md` downstream authority.

---

## 3. Required stage outputs

Every completed stage should contain seven files:

```text
STAGE_EXECUTION.md
STAGE_LEDGER.csv
STAGE_REPORT.md
STAGE_REVIEW.md
PASS_FORWARD.md
PUBLIC_SUMMARY.md
STAGE_BOOK.md
```

The first six are the stage’s authority and communication files. `STAGE_BOOK.md` is the reader-facing nonfiction synthesis.

Completed historical stages do not need to be backfilled unless explicitly requested, but every new or reopened stage should use this seven-file contract.

---

## 4. Authority of each file

### `STAGE_EXECUTION.md`

The operating log for the stage. It records objective, inputs, boundaries, methods, agents, source plan, specialist synthesis plan, discussion protocol, editorial decision point, review plan, output checklist and resumability log.

### `STAGE_LEDGER.csv`

The structured memory of the stage. It records sources, evidence, claims, assumptions, uncertainties, risks, decisions, challenges, reviews, traceability and resume markers.

### `STAGE_REPORT.md`

The expert-facing technical synthesis. It should be structured, source-grounded and easy for reviewers and downstream agents to inspect.

### `STAGE_REVIEW.md`

The combined evidence, bias, adversarial, ethics, implementation, pass-forward and book-output review. It records whether the stage passes, passes with cautions, needs revision or requires rollback.

### `PASS_FORWARD.md`

The controlled interface to the next stage. It contains only reviewed, authorised findings, assumptions, uncertainties, cautions, prohibited overextensions and revision triggers.

### `PUBLIC_SUMMARY.md`

The plain-language explanation for public readers. It should be clear, honest and non-hype.

### `STAGE_BOOK.md`

The standalone reader-facing nonfiction chapter or volume for the eventual project book, **Curriculum in the Age of Abundant Intelligence**. It should be vivid, coherent and evidence-disciplined, but it is not downstream authority.

---

## 5. End-to-end stage pipeline

Every stage should move through this sequence.

### 5.1 Authorise and bound

- Read `AGENTS.md`, this SOP, `research/README.md`, the relevant `STAGE_GUIDE.md` and templates.
- Use `docs/PROCESS_PATHWAY_MAPS.md` when planning or auditing a full stage, commissioning multiple agents, tracing evidence to pass-forward, checking book-output review or resolving a pathway problem.
- Confirm the exact stage question.
- Identify authorised inputs and pass-forward dependencies.
- State in-scope, out-of-scope and downstream-but-not-now issues.
- Confirm whether new source collection is authorised.
- Confirm which actions require explicit user approval, especially git, merge, publishing, release, public communication, external contact or learner-facing deployment.

### 5.2 Build the execution plan

- Create or update `STAGE_EXECUTION.md`.
- Select the smallest sufficient agent team.
- Commission every agent using the Agent Commission Contract in `AGENTS.md`.
- Assign information-access and tool-access tiers before the agent acts.
- Assign review and sign-off relationships before output drafting begins.
- Define workstreams, source strategy, review points and outputs.
- Add a resumability log before substantive work begins.

No agent output should be treated as reliable unless the agent had a clear commission, authorised inputs, access scope and handoff format.

### 5.3 Build the evidence base

- Search or gather only sources that fit the stage method and scope.
- Log every important source in `STAGE_LEDGER.csv`.
- Record source type, relevance, limits, evidence weight and supported claims.
- Include contrary or boundary-setting sources where the stage question requires them.
- Do not use illustrative examples as anchor evidence.

### 5.4 Extract and classify claims

Every important claim must be classified as one of:

| Claim class | Meaning |
|---|---|
| Empirical Finding | Supported by evidence. |
| Working Assumption | Adopted provisionally to proceed. |
| Normative Judgement | Value-based claim about what should matter. |
| Speculative Projection | Future-facing possibility or pathway. |
| Design Decision | Chosen design response, mainly Stage 10 onward. |
| Uncertainty | Unresolved unknown or confidence limitation. |
| Risk | Possible harm, misuse, bias or downstream failure mode. |

Each major claim needs source IDs or upstream ledger IDs, confidence, scope, limitations, counterevidence where relevant, downstream use and prohibited overextension.

### 5.5 Run specialist synthesis

For stages with multiple domains or complex interpretation, specialists should produce structured talks or briefs before the editor decides the final structure.

Each specialist must state:

- precise scope and authorised sources;
- what is out of scope;
- central mechanism or tension;
- current evidence;
- plausible trajectories or implications;
- bottlenecks;
- counterarguments;
- surprising or under-discussed insight;
- what other specialists need to understand;
- claims to pass forward;
- claims to weaken or reject;
- prohibited overextensions.

Specialist outputs are inputs to discussion, not final conclusions.

### 5.6 Chair cross-agent discussion

The Master Coordinator chairs a focused discussion after specialist synthesis.

Responses are useful only if they:

- connect domains;
- reveal a deeper mechanism;
- challenge an overclaim;
- add source-backed nuance;
- identify a tension;
- clarify learner, human, institutional or future-condition variation;
- clarify what can and cannot pass forward.

No generic agreement. No repetition. Preserve minority objections where material.

### 5.7 Make editorial architecture decisions

Only after synthesis and discussion should the editor decide:

- central thesis;
- report structure;
- book arc;
- chapter sequence;
- major concepts;
- which claims enter `PASS_FORWARD.md`;
- which claims remain contextual only;
- which claims are excluded or weakened.

Every major editorial decision should be logged as a ledger `decision`.

### 5.8 Write the authority outputs

Write the technical report, review, pass-forward and public summary from the reviewed synthesis.

`STAGE_REPORT.md` may be structured and technical. `PASS_FORWARD.md` must be stricter than the report. `PUBLIC_SUMMARY.md` must be plain-language and cautious.

### 5.9 Write the book output

Write `STAGE_BOOK.md` after the authority synthesis is stable. The book is not a report with better sentences. It is a reader-facing nonfiction synthesis that must be deliberately shaped before full drafting begins.

The mandatory book creation protocol is:

1. **Confirm authority boundary.** `PASS_FORWARD.md` remains downstream authority. `STAGE_BOOK.md` may explain, dramatise and synthesise reviewed claims, but it cannot authorise claims for later stages.
2. **Create a Book Evidence-to-Story Inventory.** Before writing prose, identify the strongest ideas, strongest tensions, human stakes, vivid usable examples, source or ledger IDs and claims that must not be strengthened.
3. **Create a Book Brief.** Record the reader promise, central question, provisional thesis, narrative spine, chapter jobs, recurring motifs, excluded claims and intended reader experience.
4. **Run the Book Brief Gate.** The Claim Steward checks evidence discipline; the Book Editor checks narrative viability; Clu checks whether the brief matches the user's quality bar.
5. **Draft a sample opening and one representative middle passage.** Do not draft the full manuscript before the sample gate.
6. **Run the Sample Quality Gate.** Reject or revise before full drafting if the sample reads like a report, summary, transcript, generic AI prose, repository artifact or polite but lifeless synthesis. The sample must show voice, texture, specificity, human stakes and narrative propulsion.
7. **Draft the full book only after the sample gate passes.**
8. **Run Claim Review, independent literary review and Clu Final Book Approval.**
9. **Log decisions, rejected approaches, review outcomes and resume markers.**

#### Scenario / lived-world book protocol

Use this additional protocol when a stage book is meant to model lived future worlds, speculative cases, scenario lives or narrative reconstructions rather than explanatory nonfiction chapters. Stage 4 is the reference case.

This protocol exists because emotionally fluent prose can still fail if the worlds are too similar, too thin or too obviously designed to illustrate a thesis. In scenario books, world design must pass before prose drafting begins.

Required sequence:

1. **Preserve useful prior drafts.** If a rejected draft has useful voice, texture or human-scale detail, archive it as a reference before replacing it. Log why it was preserved and why it failed.
2. **Confirm scenario authority boundary.** Scenario worlds are reader-facing modelling devices, not forecasts and not downstream authority. `PASS_FORWARD.md` remains the only downstream interface.
3. **Run a targeted forecast/source refresh where needed.** Use current sources only for scenario dates, boundary plausibility and major world conditions. Do not reopen the whole stage evidence base unless explicitly authorised.
4. **Build a worldspace matrix before drafting.** Define the axes being tested, such as capability curve, institutional absorption, access/control, infrastructure, work/economy, governance/trust and human flourishing pressure.
5. **Select deliberately divergent worlds.** Each world must differ materially in economic logic, access model, institutional competence, family life, status system, trust environment and daily routines. Do not approve “same story with renamed characters.”
6. **Create world condition cards.** Each card should specify technology, infrastructure, robotics/embodiment, AI-for-science, economy/work, governance/trust, access/control, local/global affairs, who flourishes, who does not and prohibited overextensions.
7. **Create protagonist dossiers.** Each protagonist needs ordinary human motives, family, friends, class/access position, habits, speech rhythms, desires, fears, status concerns, relationship to technology and a personal story engine independent of the scenario mechanics.
8. **Create scene-level story overviews.** Show how the world will be revealed through daily life rather than exposition. Include school or institutional pressures only at the level authorised by the stage.
9. **Run Clu Manual Story Overview Review.** Clu must check world distinctness, human believability, technological plausibility, claim discipline, stage boundary, absence of analytic omniscience and absence of repeated story structures.
10. **Stop for user checkpoint when requested.** If the user has asked to review the world/story plan, do not draft the full manuscript until that checkpoint is approved.
11. **Commission timeline or scenario writers only after the checkpoint passes.** Prefer one writer per timeline/world when continuity matters.
12. **Run human-believability and world-diversity review before literary approval.** A manuscript can be beautiful and still fail if characters think like analysts or worlds collapse into sameness.

Scenario/lived-world manuscripts must avoid analytic omniscience inside character perspective. Do not make characters think in project vocabulary such as “agency,” “verification burden,” “flourishing,” “infrastructure” or “recognition scarcity” unless those words would naturally exist in their world and mouth. Reveal the concept through action, consequence, setting, dialogue and partial misunderstanding.

The finished book output should:

- have a central question, thesis and cumulative arc;
- contain developed chapters rather than chapter summaries;
- include lived situations, examples, scenes or concrete explanatory images where the stage material permits them;
- vary chapter rhythm naturally;
- use vivid but disciplined prose;
- weave source IDs lightly into major claims;
- avoid source dumps and report scaffolding;
- avoid repo, file, agent, stage-process or internal project meta-text inside the manuscript body unless deliberately part of the public-facing book architecture;
- avoid filler written to satisfy length;
- preserve uncertainty and prohibited overextensions;
- end by handing the reader forward without doing the next stage’s work.

There is no word-count target. Length is governed by substance, completeness, reader propulsion, evidence coverage and literary quality.

### 5.10 Review and gate

Each stage must include:

- evidence audit;
- claim classification audit;
- uncertainty audit;
- bias and generalisability audit;
- adversarial review;
- pass-forward audit;
- public-summary audit;
- book brief gate;
- sample quality gate;
- claim review of book prose;
- independent literary review of `STAGE_BOOK.md`.

Review outcomes:

```text
pass
pass_with_cautions
revise_before_pass
rollback_required
```

Book review outcomes:

```text
approved
approved_with_minor_edits
revise_before_approval
reject_and_rewrite
```

The stage can close only if the stage gate is `pass` or `pass_with_cautions` and the book review is `approved` or `approved_with_minor_edits`.

`approved_with_minor_edits` is not allowed when the book needs structural revision, a new thesis, a different voice, deeper chapters, stronger reader propulsion or replacement of report-like prose. Those cases require `revise_before_approval` or `reject_and_rewrite`.

Clu may not mark a book output complete if it would be embarrassing to present publicly, even if it technically satisfies the template and a reviewer has been polite. Clu's final book approval is a hard gate, not a formality.

---

## 6. Stage sequencing and sign-off system

The purpose of sign-off is not ceremony. It is to prevent low-quality work from moving forward merely because it has been written.

### 6.1 Universal stage sequence

Every new or reopened stage follows this route unless the stage guide explicitly narrows it.

Visual reference: `docs/PROCESS_PATHWAY_MAPS.md`, especially P0 and P1.

| Step | Work | Primary owner | Required sign-off before moving on |
|---|---|---|---|
| 1 | Authorise stage boundary and inputs. | Clu / Master Coordinator | Clu + Claim Steward |
| 2 | Create execution plan and commission agents. | Clu + Research Operations Manager | Clu + Research Operations Manager + Claim Steward |
| 3 | Confirm source strategy or authorised-source restriction. | Research Librarian / Research Methodologist | Claim Steward + Evidence Auditor where evidence will be used |
| 4 | Build or confirm evidence ledger. | Research Librarian / Evidence Synthesis Researcher | Claim Steward + Evidence Auditor |
| 5 | Extract and classify claims. | Evidence Synthesis Researcher + domain agents | Claim Steward |
| 6 | Run specialist synthesis. | Domain specialists | Relevant specialist + Claim Steward |
| 7 | Chair cross-agent discussion. | Clu / Master Coordinator | Clu + Knowledge Integration Architect; Red Team if material objections arise |
| 8 | Decide editorial architecture. | Clu + Documentation Editor / Book Editor | Clu + Claim Steward |
| 9 | Draft authority outputs. | Assigned authoring agents | Documentation Editor + Claim Steward |
| 10 | Run evidence, bias, adversarial and relevant domain review. | Review agents | Required reviewers in the stage-specific matrix |
| 11 | Finalise `PASS_FORWARD.md`. | Clu + Claim Steward | Clu + Claim Steward + Evidence Auditor + required stage reviewers |
| 12 | Draft `PUBLIC_SUMMARY.md`. | Public Narrative Strategist / Documentation Editor | Public Narrative Strategist + Claim Steward + Clu |
| 13 | Run the book creation protocol: inventory, brief, brief gate, sample, sample gate and full draft. | Book / Manuscript Editor + Claim Steward + Clu | Book Brief Gate and Sample Quality Gate must pass before full drafting |
| 14 | Run Claim Review, independent literary review, revise and apply Clu final book approval. | Claim Steward + Independent Literary Review Agent + Clu | Literary Review Agent + Clu |
| 15 | Close stage and log resume marker. | Clu + Research Operations Manager | Clu final gate decision |

If a sign-off is `ready_with_cautions`, the caution must be carried into `STAGE_REVIEW.md`, `PASS_FORWARD.md` where relevant and the resumability log.

### 6.2 Universal artifact gate

| Artifact | Required sign-off |
|---|---|
| `STAGE_EXECUTION.md` | Clu + Research Operations Manager + Claim Steward |
| `STAGE_LEDGER.csv` | Research Librarian or Evidence Lead + Claim Steward + Evidence Auditor |
| Specialist outputs | Relevant Specialist + Claim Steward |
| Discussion synthesis | Clu + Knowledge Integration Architect + Adversarial Red Team Agent where relevant |
| `STAGE_REPORT.md` | Documentation Editor + Claim Steward + Evidence Auditor + relevant domain lead |
| `PASS_FORWARD.md` | Clu + Claim Steward + Evidence Auditor + required stage reviewers |
| `PUBLIC_SUMMARY.md` | Public Narrative Strategist + Claim Steward + Clu |
| `STAGE_BOOK.md` | Book / Manuscript Editor + Claim Steward + Independent Literary Review Agent + Clu |
| `STAGE_REVIEW.md` | Evidence Auditor + Bias and Generalisability Auditor + Adversarial Red Team Agent + Clu |

### 6.3 Stage-specific reviewer matrix

Use this as the minimum sufficient review team. Clu may add roles when the stage guide, evidence risk or public stakes require it, but should not add ceremonial reviewers.

Visual reference: `docs/PROCESS_PATHWAY_MAPS.md`, especially P5.

| Stage | Required specialist/review sign-off before pass-forward |
|---|---|
| Stage 1A – Education-Facing Human Baseline | Human Sciences Expert, Adolescent Development Expert, Claim Steward, Evidence Auditor, Bias and Generalisability Auditor, Book / Manuscript Editor, Independent Literary Review Agent |
| Stage 1B – General Human Baseline | Human Sciences Expert, Cultural Anthropology Specialist, Status and Hierarchy Specialist, Cooperation, Norms and Institutions Specialist, Claim Steward, Evidence Auditor, Bias and Generalisability Auditor, Adversarial Red Team Agent, Book / Manuscript Editor, Independent Literary Review Agent |
| Stage 1R – Human Baseline Reconciliation | Knowledge Integration Architect, Claim Steward, Evidence Auditor, Bias and Generalisability Auditor, Adversarial Red Team Agent, Book / Manuscript Editor, Independent Literary Review Agent |
| Stage 2 – Flourishing | Flourishing and Values Expert, Human Sciences Expert, Claim Steward, Bias and Generalisability Auditor, Adversarial Red Team Agent, Book / Manuscript Editor, Independent Literary Review Agent |
| Stage 3 – AI Future Conditions | AI Futures Expert plus required technical specialists, Foresight Scenario Modeller, Data and Indicators Analyst where quantitative claims are used, Claim Steward, Evidence Auditor, Bias and Generalisability Auditor, Adversarial Red Team Agent, Book / Manuscript Editor, Independent Literary Review Agent |
| Stage 4 – Life Within Futures | Systems and Causal Modeller, Human Sciences Expert, AI Futures Expert, Flourishing and Values Expert, Qualitative Synthesis Researcher, Bias and Generalisability Auditor, Adversarial Red Team Agent, Book / Manuscript Editor, Independent Literary Review Agent |
| Stage 5 – Human Invariants | Human Sciences Expert, Cultural Anthropology Specialist where generalisation is material, Flourishing and Values Expert, Foresight Scenario Modeller, Claim Steward, Bias and Generalisability Auditor, Adversarial Red Team Agent, Book / Manuscript Editor, Independent Literary Review Agent |
| Stage 6 – Enduring Functions | Systems and Causal Modeller, Flourishing and Values Expert, Human Sciences Expert, Knowledge Integration Architect, Claim Steward, Adversarial Red Team Agent, Book / Manuscript Editor, Independent Literary Review Agent |
| Stage 7 – Capabilities | Learning Sciences Expert, Adolescent Development Expert, Systems and Causal Modeller, Flourishing and Values Expert, Claim Steward, Implementation Test Agent, Bias and Generalisability Auditor, Book / Manuscript Editor, Independent Literary Review Agent |
| Stage 8 – Knowledge / Experience / Practice | Learning Sciences Expert, Subject Domain Panel, Learning Experience Designer, Adolescent Development Expert, Evidence Auditor, Claim Steward, Implementation Feasibility Expert, Book / Manuscript Editor, Independent Literary Review Agent |
| Stage 9 – Evidence of Learning | Assessment and Verification Expert, Ethics, Safeguarding and Privacy Expert, Learning Sciences Expert, Adolescent Development Expert, Implementation Test Agent, Claim Steward, Evidence Auditor, Book / Manuscript Editor, Independent Literary Review Agent |
| Stage 10 – Curriculum Architecture | Curriculum Architect, Learning Experience Designer, Implementation Feasibility Expert, Assessment and Verification Expert, Ethics, Safeguarding and Privacy Expert, Claim Steward, Implementation Test Agent, Book / Manuscript Editor, Independent Literary Review Agent |
| Stage 11 – Verification and Release | Release Manager, Open Source Repository Engineer, Public Narrative Strategist, Adversarial Red Team Agent, Evidence Auditor, Bias and Generalisability Auditor, Ethics, Safeguarding and Privacy Expert, Implementation Test Agent, Book / Manuscript Editor, Independent Literary Review Agent |

### 6.4 Sign-off statuses

| Status | Meaning |
|---|---|
| `ready` | The reviewer believes the artifact can be used for its intended purpose. |
| `ready_with_cautions` | The artifact can proceed only if named cautions remain visible downstream. |
| `revise_before_ready` | The artifact cannot proceed until specific revisions are completed. |
| `blocked` | The artifact cannot be completed safely under current authority, evidence or access. |

No output can pass with unresolved `revise_before_ready` or `blocked` statuses.

### 6.5 Quality floor

An artifact is not complete merely because it exists. Completion requires:

- traceable source or upstream ledger support for major claims;
- visible uncertainty, limitations and counterevidence;
- claim classification appropriate to the evidence;
- rejected or weakened claims logged;
- adversarial objections resolved or carried forward visibly;
- public readability checked where relevant;
- no stage drift;
- no filler, template-padding or source-dump prose;
- no hidden reliance on agent performance as evidence.

---

## 7. Ledger record taxonomy

Use one ledger per stage. Standard `record_type` values:

| Record type | Use |
|---|---|
| `source` | Source consulted. |
| `evidence` | Evidence extracted from a source. |
| `claim` | Substantive stage claim. |
| `assumption` | Working assumption. |
| `uncertainty` | Open question or limitation. |
| `risk` | Reasoning, ethics, implementation or public-use risk. |
| `decision` | Stage, method or editorial decision. |
| `challenge` | Objection, adversarial issue, weakened claim or rejected overclaim. |
| `traceability` | Link between sources, talks, outputs and pass-forward records. |
| `revision_trigger` | Condition requiring future update. |

Standard process records should be represented as:

| Process item | Preferred ledger handling |
|---|---|
| Agent commission | `decision` or `traceability` |
| Access-scope decision | `decision` |
| Specialist talk | `traceability` |
| Discussion point | `challenge` |
| Editorial decision | `decision` |
| Literary review | `challenge` or `traceability` |
| Sign-off decision | `decision` |
| Weakened claim | `challenge` |
| Open question | `uncertainty` |
| Resume marker | `decision` |

Every major source, specialist output, discussion decision, rejected claim, review result and resume state must be logged before moving on.

---

## 8. Evidence and confidence discipline

### Evidence weights

| Weight | Meaning |
|---|---|
| Anchor | Strong enough to support a major conclusion. |
| Supporting | Useful in combination with other evidence. |
| Contextual | Helps frame or interpret. |
| Illustrative | Example only, not proof. |
| Non-decision | Logged but not used to support conclusions. |

### Confidence labels

| Confidence | Meaning |
|---|---|
| High | Strong evidence or robust cross-source convergence. |
| Moderate | Supported but meaningfully limited or context-dependent. |
| Low | Plausible but weak, narrow or speculative. |
| Open | Not settled; carried forward as uncertainty. |

Do not use numerical confidence unless the method justifies it.

---

## 9. Stage gates and pass-forward rules

A stage may pass only when:

- the assigned question has been answered sufficiently for downstream use;
- claims are classified;
- source IDs or ledger IDs support major claims;
- limitations and counterevidence are visible;
- uncertainty is preserved;
- bias and generalisability have been checked;
- adversarial review has been completed;
- `PASS_FORWARD.md` contains only reviewed, authorised claims;
- `STAGE_BOOK.md` has passed independent literary review;
- no later-stage work has been smuggled in.

`PASS_FORWARD.md` must include:

- authorised findings;
- working assumptions carried forward;
- normative judgements where relevant;
- speculative projections where relevant;
- unresolved uncertainties;
- claims not to overextend;
- required cautions;
- rejected or non-authorised items;
- revision triggers;
- next stage instruction.

---

## 10. Book-output rules

Each stage book should feel like part of one larger work:

**Curriculum in the Age of Abundant Intelligence**

Shared motifs may recur: embodied humans, social life, meaning, agency, trust, verification, status, institutions, flourishing and the difference between capability and wisdom.

Do not force every chapter through the same visible checklist. Strong stage books may begin with a scene, paradox, question, technical image, human problem or quiet explanatory movement.

Avoid:

- “this manuscript” self-commentary;
- repository or file-path language;
- specialist transcripts pasted together;
- source dumps;
- formulaic chapter endings;
- generic “landscape is changing” prose;
- fake profundity;
- filler expansion;
- stronger certainty for dramatic effect.

Major claims still need valid source IDs or ledger IDs.

### 10.1 Book pre-draft gates

No full `STAGE_BOOK.md` manuscript should be drafted until these controls have passed:

| Gate | Required evidence of completion | Blocking failure |
|---|---|---|
| Book Evidence-to-Story Inventory | Strongest ideas, tensions, human stakes, vivid usable examples, source or ledger IDs and prohibited overextensions are recorded. | The manuscript would be drafted from a report outline rather than story-worthy material. |
| Book Brief Gate | Reader promise, central question, provisional thesis, narrative spine, chapter jobs, motifs, exclusions and intended reader experience are recorded and approved. | The book has no viable nonfiction architecture. |
| Sample Quality Gate | A sample opening and representative middle passage show voice, specificity, human stakes and narrative propulsion. | The prose reads like a report, summary, transcript, generic AI output or repository artifact. |

### 10.2 Full manuscript approval standard

The full manuscript must not be approved if it is merely coherent. It must be a serious reader-facing work.

Rejection or mandatory revision is required when the manuscript is:

- too short to fulfil its own chapter promises;
- coherent but thin;
- polished but generic;
- repetitive in structure or cadence;
- dependent on process language inside the manuscript body;
- using source IDs as decoration rather than support;
- lacking developed human situations, examples or explanatory scenes;
- relying on length, headings or citations as a substitute for insight.

### 10.3 Clu Final Book Approval

Clu may approve `STAGE_BOOK.md` only if all of the following are true:

- I would be willing to show this to the user without apology.
- I can state the book's central thesis in one sentence.
- I can explain why the chapter order is necessary.
- I can identify the strongest scenes, examples or explanatory passages.
- I can identify where evidence enters the prose.
- I can name the manuscript's weakest remaining limitation.
- I do not believe it is merely a polished report.
- I do not believe it is relying on length, structure or citations as a substitute for insight.
- I would stake my name on the claim that this is the right draft to show.

If any answer fails, Clu must mark the output `revise_before_approval` or `reject_and_rewrite`.

---

## 11. Agent Cognitive Quality Protocol

Agents should produce public, structured reasoning outputs without exposing private chain-of-thought.

Before producing specialist or editorial work, state:

- scope;
- authorised sources;
- exclusions;
- mechanism or tension;
- evidence basis;
- claim class;
- limitations;
- counterarguments;
- uncertainty;
- what should be preserved, weakened or excluded.

Readable prose is encouraged. Elegance must not outrun traceability.

---

## 12. Resumability protocol

If work may exceed the current context window, log progress before stopping.

`STAGE_EXECUTION.md` should include a resumability log with:

- completed outputs;
- source IDs used;
- unresolved questions;
- proposed claims;
- weakened or rejected claims;
- discussion points pending;
- current synthesis status;
- next exact action.

The ledger should include matching resume markers as `decision` records.

---

## 13. Stage-specific boundaries

Stage guides control the local question. This SOP controls execution method.

Standing boundaries:

- Stage 1A and 1B are component studies; Stage 1R is the sole Stage 1 downstream authority.
- Stage 2 adopts a flourishing model but does not create curriculum.
- Stage 3 maps technical future conditions and does not write lived-world stories.
- Stage 4 models life within futures and does not derive capabilities or curriculum.
- Stage 5 identifies invariants and does not romanticise human uniqueness.
- Stage 6 derives enduring functions and does not create school subjects.
- Stage 7 derives capabilities and does not map full curriculum.
- Stage 8 maps knowledge, experience and practice without defaulting to inherited subjects.
- Stage 9 designs evidence-of-learning architecture without premature high-stakes assessment.
- Stage 10 creates curriculum architecture.
- Stage 11 verifies, falsifies and prepares release readiness.

---

## 14. Final operating standard

The goal is not more files. The goal is a clean pipeline that produces:

1. evidence-disciplined research;
2. honest claim handoffs;
3. readable public explanation;
4. a compelling nonfiction project book;
5. a curriculum hypothesis whose derivation can be inspected.

Prefer clarity over cleverness. Prefer traceability over elegance. Prefer honest uncertainty over false authority. Prefer one clean operating route over scattered rules.
