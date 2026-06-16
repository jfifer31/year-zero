# Stage 7 – Capability Derivation

## 1. Stage purpose

Stage 7 derives the capabilities young people need in order to perform the enduring functions identified in Stage 6. Capabilities should be developable, age-aware, observable enough to support evidence of learning and broad enough to survive future uncertainty.

## 2. Short definition

Translate enduring human functions into developable capabilities for KS3–KS4 learners.

## 3. Position in the chain

**Depends on:** Stage 6 pass-forward output.

**Feeds into:** Stage 8 Knowledge, Experience and Practice Mapping; Stage 9 Evidence of Learning.

This stage must preserve the distinction between what it has established, what it has assumed, what it values and what it projects.

## 4. Core research questions

1. What capabilities are required to perform each enduring human function?
2. Which capabilities are developmentally appropriate for KS3–KS4?
3. Which capabilities are foundational, integrative or advanced?
4. Which capabilities depend on others?
5. How can capability growth be observed without reducing it to simplistic metrics?
6. Which capabilities are likely to be neglected by conventional curriculum structures?

## 5. Scope

### 5.1 In scope

- cognitive capabilities;
- metacognitive capabilities;
- social and relational capabilities;
- ethical and civic capabilities;
- creative and expressive capabilities;
- practical and embodied capabilities;
- AI-era agency capabilities;
- developmental progression;

### 5.2 Out of scope

- curriculum content selection;
- lesson plans;
- formal assessment system;
- capability branding without derivation;
- generic skills lists;

If an out-of-scope issue appears important, record it as a downstream implication or open question rather than solving it inside this stage.

## 6. Required agent team

The Master Coordinator should call the smallest sufficient team, but this stage should normally include:

- Master Coordinator
- Learning Sciences Expert
- Adolescent Development Expert
- Systems and Causal Modeller
- Assessment and Verification Expert
- Implementation Feasibility Expert
- Claim Steward

At least one quality, audit or adversarial agent must review the stage before pass-forward.

## 7. Recommended methodology

Use a method mix appropriate to the stage question. Recommended methods:

- function-to-capability mapping;
- developmental appropriateness analysis;
- dependency modelling;
- capability observability review;
- implementation feasibility review;
- capability failure-mode analysis;

The method choice must be written into `STAGE_EXECUTION.md`, including why each method fits the stage and what its limitations are.

## 8. Evidence and source strategy

Prioritise sources that can actually answer this stage’s question. Likely source types include:

- Stage 6 functions;
- learning science research;
- adolescent development evidence;
- skill acquisition literature;
- metacognition and transfer research;
- implementation evidence from project-based and capability-based learning;

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

- Capability Model;
- Capability Dependency Map;
- KS3–KS4 Developmental Fit Notes;
- Capability Observability Notes;
- Stage 7 Pass-Forward Memo;

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

- Are capabilities too vague to teach?
- Are they too adult-oriented for KS3–KS4?
- Are they simply fashionable skill labels?
- Are important knowledge foundations being ignored?
- Could the capabilities be observed without distorting them?

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

- authorised capabilities;
- capability definitions;
- dependency relationships;
- developmental constraints;
- initial observability notes;
- capabilities requiring particular evidence caution;

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
You are running Stage 7 – Capability Derivation of the Year Zero Education research programme.

Read AGENTS.md, docs/RESEARCH_OPERATING_SYSTEM.md, research/README.md and this STAGE_GUIDE.md.

Your task is to complete this stage only. Do not solve later stages. Produce STAGE_EXECUTION.md, STAGE_LEDGER.csv, STAGE_REPORT.md, STAGE_REVIEW.md, PASS_FORWARD.md and PUBLIC_SUMMARY.md.

Classify all important claims. Preserve uncertainty. Run adversarial review before pass-forward.
```
