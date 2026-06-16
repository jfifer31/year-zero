# Stage 2 – Human Flourishing Model

## 1. Stage purpose

Stage 2 turns the human baseline into a project-specific model of flourishing. It must combine empirical evidence about human thriving with explicit normative judgement about what education should value. It should not pretend that flourishing is a neutral technical concept.

## 2. Short definition

Define what flourishing should mean for the project using Stage 1 findings and explicit normative reasoning.

## 3. Position in the chain

**Depends on:** Stage 1 pass-forward output.

**Feeds into:** Stage 4, Stage 5, Stage 6 and Stage 10.

This stage must preserve the distinction between what it has established, what it has assumed, what it values and what it projects.

## 4. Core research questions

1. What does Stage 1 imply about what young people need in order to develop well?
2. Which dimensions of flourishing are empirically supported and educationally relevant?
3. Which parts of flourishing require explicit normative judgement?
4. How should the model balance agency, belonging, competence, meaning, contribution, responsibility and well-being?
5. What plural conceptions of a good life must the model leave room for?
6. What should the curriculum avoid optimising for, even if measurable?

## 5. Scope

### 5.1 In scope

- well-being and life satisfaction evidence;
- agency and autonomy;
- belonging and relationships;
- competence and mastery;
- meaning and purpose;
- moral responsibility;
- resilience without romanticising hardship;
- plural values and reasonable disagreement;

### 5.2 Out of scope

- a single ideology of the good life;
- mental health treatment frameworks;
- political doctrine;
- curriculum domains;
- assessment design;

If an out-of-scope issue appears important, record it as a downstream implication or open question rather than solving it inside this stage.

## 6. Required agent team

The Master Coordinator should call the smallest sufficient team, but this stage should normally include:

- Master Coordinator
- Flourishing and Values Expert
- Human Sciences Expert
- Adolescent Development Expert
- Evidence Synthesis Researcher
- Adversarial Red Team Agent
- Claim Steward

At least one quality, audit or adversarial agent must review the stage before pass-forward.

## 7. Recommended methodology

Use a method mix appropriate to the stage question. Recommended methods:

- normative-empirical synthesis;
- value trade-off mapping;
- pluralism review;
- flourishing dimensions matrix;
- adversarial analysis of hidden ideology;

The method choice must be written into `STAGE_EXECUTION.md`, including why each method fits the stage and what its limitations are.

## 8. Evidence and source strategy

Prioritise sources that can actually answer this stage’s question. Likely source types include:

- well-being research;
- developmental flourishing literature;
- philosophy of education;
- moral and civic education literature;
- psychological needs theory;
- evidence on meaning, belonging, agency and competence;

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

- Project Flourishing Model;
- Normative Commitments Register;
- Flourishing Dimension Map;
- Known Value Trade-offs;
- Stage 2 Pass-Forward Memo;

In repository terms, the completed stage folder should contain:

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

- Does the model smuggle in one cultural ideal of success?
- Does it overvalue productivity or achievement?
- Does it understate moral, civic or relational life?
- Does it confuse happiness with flourishing?
- Could the model become coercive if implemented poorly?

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

- flourishing dimensions authorised for later use;
- normative judgements explicitly adopted;
- trade-offs and unresolved disagreements;
- limits on how flourishing may be operationalised;
- cautions against overmeasurement;

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
You are running Stage 2 – Human Flourishing Model of the Year Zero Education research programme.

Read AGENTS.md, docs/RESEARCH_OPERATING_SYSTEM.md, research/README.md and this STAGE_GUIDE.md.

Your task is to complete this stage only. Do not solve later stages. Produce STAGE_EXECUTION.md, STAGE_LEDGER.csv, STAGE_REPORT.md, STAGE_REVIEW.md, PASS_FORWARD.md and PUBLIC_SUMMARY.md.

Classify all important claims. Preserve uncertainty. Run adversarial review before pass-forward.
```
