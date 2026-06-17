# Stage 9 – Evidence of Learning and Verification Architecture

## 1. Stage purpose

Stage 9 designs the evidence-of-learning architecture. It asks how learners can show growth in capability without reducing the project to conventional exams or vague self-reports. It must balance validity, privacy, fairness, feasibility and meaningful demonstration.

## 2. Short definition

Define how capabilities can be observed, demonstrated, reflected upon and eventually verified.

## 3. Position in the chain

**Depends on:** Stage 8 pass-forward output and authorised Stage 7 capability references carried through the chain.

**Feeds into:** Stage 10 Curriculum Architecture and Stage 11 Release Readiness.

This stage must preserve the distinction between what it has established, what it has assumed, what it values and what it projects.

## 4. Core research questions

1. What would count as evidence that each capability is developing?
2. Which capabilities require performance, explanation, reflection, artefacts or transfer evidence?
3. How can evidence remain useful without becoming burdensome or invasive?
4. How can portfolio evidence be structured safely?
5. What would make evidence valid, fair and difficult to game?
6. What can be verified now and what should remain future work?

## 5. Scope

### 5.1 In scope

- portfolio evidence;
- project artefacts;
- demonstrations;
- reflection;
- transfer tasks;
- rubrics;
- self and peer review;
- mentor review;
- privacy and consent;
- verification pathways;
- assessment validity;

### 5.2 Out of scope

- formal qualification design;
- high-stakes testing;
- data-heavy learner surveillance;
- ranking learners;
- final credentialing claims;

If an out-of-scope issue appears important, record it as a downstream implication or open question rather than solving it inside this stage.

## 6. Required agent team

The Master Coordinator should call the smallest sufficient team, but this stage should normally include:

- Master Coordinator
- Assessment and Verification Expert
- Learning Sciences Expert
- Ethics, Safeguarding and Privacy Expert
- Implementation Feasibility Expert
- Adolescent Development Expert
- Adversarial Red Team Agent

At least one quality, audit or adversarial agent must review the stage before pass-forward.

## 7. Recommended methodology

Use a method mix appropriate to the stage question. Recommended methods:

- capability evidence mapping;
- validity analysis;
- portfolio architecture design;
- rubric design principles;
- privacy risk review;
- gaming and burden analysis;
- verification maturity classification;

The method choice must be written into `STAGE_EXECUTION.md`, including why each method fits the stage and what its limitations are.

## 8. Evidence and source strategy

Prioritise sources that can actually answer this stage’s question. Likely source types include:

- Stage 7 capabilities;
- Stage 8 learning inputs;
- assessment validity literature;
- portfolio assessment evidence;
- project-based learning assessment;
- ethics and privacy standards;
- implementation feedback where available;

Every significant source, claim, assumption, uncertainty and decision should be logged in `STAGE_LEDGER.csv`.

## 9. Execution workflow

1. Read authorised inputs and previous pass-forward files.
2. Restate the stage question in operational form.
3. Create `STAGE_EXECUTION.md` from the template.
4. Select agents and assign responsibilities.
5. Conduct source discovery.
6. Review and weight evidence.
7. Produce initial synthesis.
8. Classify claims and assumptions.
9. Identify uncertainties and risks.
10. Run adversarial review.
11. Revise the stage report.
12. Complete `PASS_FORWARD.md`.
13. Write `PUBLIC_SUMMARY.md`.

## 10. Required outputs

This stage should produce:

- Evidence of Learning Architecture;
- Capability Evidence Matrix;
- Portfolio Model;
- Rubric Principles;
- Verification Maturity Map;
- Stage 9 Pass-Forward Memo;

These named products are sections or structured results within the six canonical stage files, not additional files. In repository terms, the completed stage folder should contain:

```text
STAGE_EXECUTION.md
STAGE_LEDGER.csv
STAGE_REPORT.md
STAGE_REVIEW.md
PASS_FORWARD.md
PUBLIC_SUMMARY.md
```

## 11. Stage ledger requirements

The ledger should include records for:

- sources consulted;
- evidence extracted;
- claims made;
- assumptions adopted;
- uncertainties retained;
- decisions made;
- risks identified;
- traceability links;
- adversarial challenges;
- revision triggers.

Use `record_type` values from `templates/STAGE_LEDGER_TEMPLATE.csv`.

## 12. Adversarial review questions

The review should directly address:

- Does the evidence model measure what matters or what is easy?
- Could it become surveillance?
- Could learners game it?
- Is it too burdensome for parents or educators?
- Does it disadvantage quieter, neurodivergent or low-resource learners?

The review should not merely list risks. It should state whether each risk requires revision, pass-forward caution or future monitoring.

## 13. Bias and generalisability checks

Check whether the stage output:

- assumes high-resource learners or families;
- assumes access to advanced technology;
- overgeneralises from Western, educated or urban contexts;
- ignores neurodiversity or learner variation;
- confuses adult priorities with adolescent needs;
- underweights cultural, family or community difference;
- hides values inside neutral-sounding language.

## 14. Pass-forward requirements

`PASS_FORWARD.md` must clearly state:

- authorised evidence types;
- portfolio structure;
- rubric principles;
- privacy limits;
- verification boundaries;
- assessment cautions for curriculum design;

The next stage may rely only on what this stage explicitly passes forward.

## 15. Public summary requirements

`PUBLIC_SUMMARY.md` should explain:

- what the stage asked;
- why the question matters;
- what the stage found;
- what remains uncertain;
- what this means for the project;
- what readers should not conclude yet.

The public summary should be clear enough for parents, educators and interested learners without overstating certainty.

## 16. Definition of done

This stage is complete when:

- the core research questions have been answered sufficiently for downstream use;
- evidence has been logged and weighted;
- claims have been classified;
- assumptions are explicit;
- uncertainties are preserved;
- adversarial review has been completed;
- bias and generalisability have been considered;
- pass-forward rules are clear;
- the public summary is written;
- the Master Coordinator marks the stage as `pass` or `pass_with_cautions`.

## 17. Common failure modes

Avoid:

- answering a later-stage question too early;
- producing attractive but unsupported language;
- treating illustrative examples as evidence;
- hiding uncertainty to make the stage feel complete;
- importing conventional curriculum assumptions without justification;
- allowing one agent’s synthesis to erase disagreement;
- writing public claims stronger than the research supports.

## 18. Initial agent prompt skeleton

```text
You are running Stage 9 – Evidence of Learning and Verification Architecture of the Year Zero Education research programme.

Read AGENTS.md, docs/RESEARCH_OPERATING_SYSTEM.md, research/README.md and this STAGE_GUIDE.md.

Your task is to complete this stage only. Do not solve later stages. Produce STAGE_EXECUTION.md, STAGE_LEDGER.csv, STAGE_REPORT.md, STAGE_REVIEW.md, PASS_FORWARD.md and PUBLIC_SUMMARY.md.

Classify all important claims. Preserve uncertainty. Run adversarial review before pass-forward.
```
