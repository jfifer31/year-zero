# Stage Orchestrator SOP

This is the primary operating procedure for running Year Zero research stages from beginning to end.

It consolidates the project’s research method, evidence discipline, agent orchestration, stage gates, pass-forward rules and reader-facing book-output rules. Agents should treat this file as the central stage-execution authority.

`AGENTS.md` defines the role harnesses and quick start sequence. Stage guides define the purpose and boundary of each stage. This SOP defines how a stage is executed.

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
- Confirm the exact stage question.
- Identify authorised inputs and pass-forward dependencies.
- State in-scope, out-of-scope and downstream-but-not-now issues.
- Confirm whether new source collection is authorised.

### 5.2 Build the execution plan

- Create or update `STAGE_EXECUTION.md`.
- Select the smallest sufficient agent team.
- Define workstreams, source strategy, review points and outputs.
- Add a resumability log before substantive work begins.

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

Write `STAGE_BOOK.md` after the authority synthesis is stable.

The book output should:

- have a central question, thesis and cumulative arc;
- vary chapter rhythm naturally;
- use vivid but disciplined prose;
- weave source IDs lightly into major claims;
- avoid source dumps and report scaffolding;
- avoid repo, file, agent or process meta-text inside the manuscript;
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

---

## 6. Ledger record taxonomy

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
| Specialist talk | `traceability` |
| Discussion point | `challenge` |
| Editorial decision | `decision` |
| Literary review | `challenge` or `traceability` |
| Weakened claim | `challenge` |
| Open question | `uncertainty` |
| Resume marker | `decision` |

Every major source, specialist output, discussion decision, rejected claim, review result and resume state must be logged before moving on.

---

## 7. Evidence and confidence discipline

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

## 8. Stage gates and pass-forward rules

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

## 9. Book-output rules

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

---

## 10. Agent Cognitive Quality Protocol

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

## 11. Resumability protocol

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

## 12. Stage-specific boundaries

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

## 13. Final operating standard

The goal is not more files. The goal is a clean pipeline that produces:

1. evidence-disciplined research;
2. honest claim handoffs;
3. readable public explanation;
4. a compelling nonfiction project book;
5. a curriculum hypothesis whose derivation can be inspected.

Prefer clarity over cleverness. Prefer traceability over elegance. Prefer honest uncertainty over false authority. Prefer one clean operating route over scattered rules.
