# Research Stages

This folder contains the full Year Zero Education research chain.

Each stage is a standalone research project with a defined purpose, inputs, methods, outputs and pass-forward requirements.

Agents read `AGENTS.md` for operating sequence, roles, harnesses and handoff discipline. All researchers follow `docs/RESEARCH_OPERATING_SYSTEM.md` for method, evidence standards, claim classification, uncertainty, stage gates and pass-forward rules.

Do not treat these stages as loose topics. They are an engineered dependency chain designed to derive a Version 0.1 curriculum hypothesis from first principles.

---

## Stage sequence

| Stage | Name | Guide | Purpose |
|---|---|---|---|
| Stage 1 | Human Baseline | `stage-01-human-baseline/STAGE_GUIDE.md` | Determine the minimum defensible assumptions about human beings that an educational framework must respect. |
| Stage 2 | Human Flourishing Model | `stage-02-flourishing/STAGE_GUIDE.md` | Define what flourishing should mean for the project using Stage 1 findings and explicit normative reasoning. |
| Stage 3 | AI Future Conditions Discovery | `stage-03-ai-future-conditions/STAGE_GUIDE.md` | Map plausible AI-shaped future conditions without pretending to predict a single future. |
| Stage 4 | Life Within Future Conditions | `stage-04-life-within-futures/STAGE_GUIDE.md` | Bring the human and AI streams together by modelling lived life inside plausible future conditions. |
| Stage 5 | Human Invariants Analysis | `stage-05-human-invariants/STAGE_GUIDE.md` | Identify what remains fundamentally human, valuable or unavoidable across plausible futures. |
| Stage 6 | Enduring Human Functions | `stage-06-enduring-functions/STAGE_GUIDE.md` | Derive what humans must still do, decide, judge, create, coordinate, protect, experience or become. |
| Stage 7 | Capability Derivation | `stage-07-capabilities/STAGE_GUIDE.md` | Translate enduring human functions into developable capabilities for KS3–KS4 learners. |
| Stage 8 | Knowledge, Experience and Practice Mapping | `stage-08-knowledge-experience-practice/STAGE_GUIDE.md` | Identify the knowledge, experiences and practices that can cultivate the derived capabilities. |
| Stage 9 | Evidence of Learning and Verification Architecture | `stage-09-evidence-of-learning/STAGE_GUIDE.md` | Define how capabilities can be observed, demonstrated, reflected upon and eventually verified. |
| Stage 10 | Curriculum Architecture and Version 0.1 Design | `stage-10-curriculum-architecture/STAGE_GUIDE.md` | Build the first curriculum architecture from all authorised upstream outputs. |
| Stage 11 | Verification, Falsification and Release Readiness | `stage-11-verification-release/STAGE_GUIDE.md` | Attack the full chain, classify weaknesses and prepare responsible Version 0.1 release. |

---

## Dependency structure

```text
Stage 1 – Human Baseline
      ↓
Stage 2 – Human Flourishing Model

Stage 3 – AI Future Conditions Discovery

Stages 1, 2 and 3 converge at:
      ↓
Stage 4 – Life Within Future Conditions
      ↓
Stage 5 – Human Invariants Analysis
      ↓
Stage 6 – Enduring Human Functions
      ↓
Stage 7 – Capability Derivation
      ↓
Stage 8 – Knowledge, Experience and Practice Mapping
      ↓
Stage 9 – Evidence of Learning and Verification Architecture
      ↓
Stage 10 – Curriculum Architecture and Version 0.1 Design
      ↓
Stage 11 – Verification, Falsification and Release Readiness
```

Stage 1 and Stage 3 may be researched in parallel if their outputs are kept separate. Stage 4 must not begin until Stages 1, 2 and 3 have produced pass-forward outputs.

---

## How to run a stage

For each stage:

1. Read `AGENTS.md`.
2. Read `docs/RESEARCH_OPERATING_SYSTEM.md`.
3. Read the relevant `STAGE_GUIDE.md`.
4. Copy templates from `/templates/` into the stage folder.
5. Create:

```text
STAGE_EXECUTION.md
STAGE_LEDGER.csv
STAGE_REPORT.md
STAGE_REVIEW.md
PASS_FORWARD.md
PUBLIC_SUMMARY.md
```

6. Run the stage using the required agents and methods.
7. Complete adversarial review.
8. Pass forward only authorised claims, assumptions and uncertainties.

---

## Stage completion rule

A stage is complete only when it has produced:

- a technical report;
- a ledger of sources, claims, assumptions, uncertainties, risks and decisions;
- a review file;
- a pass-forward file;
- a public summary.

Interesting research without a pass-forward file does not count as a completed stage.

---

## Curriculum design warning

Curriculum architecture begins at Stage 10.

Earlier stages may identify implications for curriculum design, but they must not design the curriculum prematurely.
