# Stage 5 – Human Invariants Analysis

## 1. Stage purpose

Stage 5 identifies the human realities that remain important across plausible technological futures. It asks what does not disappear when intelligence becomes more abundant: embodiment, agency, meaning, belonging, attention, moral responsibility, mortality, trust, care, judgement and the need to live with others.

## 2. Short definition

Identify what remains fundamentally human, valuable or unavoidable across plausible futures.

## 3. Position in the chain

**Depends on:** Stage 4 pass-forward output. Earlier stage material may be consulted only through authorised pass-forward statements and traceability references.

**Feeds into:** Stage 6 Enduring Human Functions.

This stage must preserve the distinction between what it has established, what it has assumed, what it values and what it projects.

## 4. Core research questions

1. What human realities recur across the future-life models?
2. Which needs or constraints remain important even if AI capability increases dramatically?
3. Which aspects of human life become more important because of AI abundance?
4. Which invariants are empirical, which are normative, and which are working assumptions?
5. Which apparent invariants are actually culturally contingent?
6. What must later stages preserve or cultivate?

## 5. Scope

### 5.1 In scope

- embodiment;
- agency;
- attention;
- meaning;
- belonging;
- care;
- trust;
- moral responsibility;
- identity;
- judgement;
- mortality and limitation;
- interdependence;
- human dignity;

### 5.2 Out of scope

- capabilities;
- curriculum domains;
- detailed pedagogy;
- romantic claims about human uniqueness;
- claims that ignore cultural variation;

If an out-of-scope issue appears important, record it as a downstream implication or open question rather than solving it inside this stage.

## 6. Required agent team

The Master Coordinator should call the smallest sufficient team, but this stage should normally include:

- Master Coordinator
- Human Sciences Expert
- Flourishing and Values Expert
- Systems and Causal Modeller
- Foresight Scenario Modeller
- Adversarial Red Team Agent
- Bias and Generalisability Auditor

At least one quality, audit or adversarial agent must review the stage before pass-forward.

## 7. Recommended methodology

Use a method mix appropriate to the stage question. Recommended methods:

- cross-condition invariants analysis;
- human need recurrence mapping;
- normative-empirical separation;
- cultural contingency test;
- future stress testing;

The method choice must be written into `STAGE_EXECUTION.md`, including why each method fits the stage and what its limitations are.

## 8. Evidence and source strategy

Prioritise sources that can actually answer this stage’s question. Likely source types include:

- Stage 4 life models;
- Stage 1 human baseline;
- Stage 2 flourishing dimensions;
- philosophy of education;
- human sciences evidence;
- cross-cultural and developmental evidence where available;

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

- Human Invariants Map;
- Invariant Confidence Classification;
- Cultural Contingency Notes;
- Invariant-to-Flourishing Links;
- Stage 5 Pass-Forward Memo;

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

- Is this just a list of favourite humanistic values?
- Are the invariants actually universal or only culturally familiar?
- Are technology-resistant claims being made for emotional reasons?
- Are empirical and normative claims mixed together?
- Could some supposed invariants be altered by future institutions?

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

- authorised human invariants;
- confidence level for each invariant;
- normative commitments attached to invariants;
- cautions about cultural variation;
- questions for enduring function derivation;

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
You are running Stage 5 – Human Invariants Analysis of the Year Zero Education research programme.

Read AGENTS.md, docs/RESEARCH_OPERATING_SYSTEM.md, research/README.md and this STAGE_GUIDE.md.

Your task is to complete this stage only. Do not solve later stages. Produce STAGE_EXECUTION.md, STAGE_LEDGER.csv, STAGE_REPORT.md, STAGE_REVIEW.md, PASS_FORWARD.md and PUBLIC_SUMMARY.md.

Classify all important claims. Preserve uncertainty. Run adversarial review before pass-forward.
```
