# Stage 3 – AI Future Conditions Discovery

## 1. Stage purpose

Stage 3 identifies plausible future conditions created or intensified by artificial intelligence. It does not forecast one future. It maps drivers, uncertainties, adoption patterns, institutional effects and signposts so the curriculum can be designed for plausible ranges rather than a single speculative story.

## 2. Short definition

Map plausible AI-shaped future conditions without pretending to predict a single future.

## 3. Position in the chain

**Depends on:** Stage 0 foundation files. It may begin in parallel with Stage 1 and continue alongside Stage 2 if all outputs remain separate.

**Feeds into:** Stage 4 Life Within Future Conditions and Stage 11 release readiness.

This stage must preserve the distinction between what it has established, what it has assumed, what it values and what it projects.

## 4. Core research questions

1. What AI capabilities, deployment patterns and access conditions could plausibly affect young people?
2. How might AI change work, knowledge, creativity, trust, coordination and learning?
3. Which changes are already visible, which are emerging, and which are speculative?
4. What are the major uncertainties and branching conditions?
5. How might benefits and risks be unevenly distributed?
6. Which future conditions matter most for curriculum design?

## 5. Scope

### 5.1 In scope

- AI capability trajectories;
- access and inequality;
- labour and cognitive work;
- creative production;
- misinformation and trust;
- education technology;
- automation and augmentation;
- AI governance and institutional adoption;
- human agency and dependency risks;

### 5.2 Out of scope

- single-point predictions;
- science fiction scenarios;
- curriculum design;
- investment advice;
- technical model benchmarking beyond educational relevance;

If an out-of-scope issue appears important, record it as a downstream implication or open question rather than solving it inside this stage.

## 6. Required agent team

The Master Coordinator should call the smallest sufficient team, but this stage should normally include:

- Master Coordinator
- AI Futures Expert
- Foresight Scenario Modeller
- Data and Indicators Analyst
- Research Librarian
- Adversarial Red Team Agent
- Bias and Generalisability Auditor

At least one quality, audit or adversarial agent must review the stage before pass-forward.

## 7. Recommended methodology

Use a method mix appropriate to the stage question. Recommended methods:

- horizon scanning;
- driver and uncertainty mapping;
- signpost identification;
- scenario discovery;
- trend and indicator review;
- conservative versus exploratory split;

The method choice must be written into `STAGE_EXECUTION.md`, including why each method fits the stage and what its limitations are.

## 8. Evidence and source strategy

Prioritise sources that can actually answer this stage’s question. Likely source types include:

- AI capability reports;
- labour market analyses;
- education technology research;
- policy and governance reports;
- technology adoption evidence;
- expert disagreement maps;
- data on digital access and inequality;

Every significant source, claim, assumption, uncertainty and decision should be logged in `STAGE_LEDGER.csv`.

## 9. Execution workflow

1. Read the authorised Stage 0 inputs; no prior-stage pass-forward exists.
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

- AI Future Conditions Map;
- Driver and Uncertainty Register;
- Signpost List;
- Conservative and Exploratory Cases;
- Stage 3 Pass-Forward Memo;

These named products are sections or structured results within the six authority files plus `STAGE_BOOK.md`, not additional subtask files. In repository terms, the completed stage folder should contain:

```text
STAGE_EXECUTION.md
STAGE_LEDGER.csv
STAGE_REPORT.md
STAGE_REVIEW.md
PASS_FORWARD.md
PUBLIC_SUMMARY.md
STAGE_BOOK.md
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

- Is the stage overhyped by recent AI discourse?
- Does it assume adoption will be smooth or universal?
- Does it confuse technical capability with social effect?
- Does it ignore governance, inequality or backlash?
- Does it understate continuity and human resistance?

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

- future conditions relevant to curriculum;
- drivers and uncertainties;
- signposts for later revision;
- conditions that are plausible but low-confidence;
- warnings against treating projections as predictions;

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
- book output is written and independently reviewed;
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
You are running Stage 3 – AI Future Conditions Discovery of the Year Zero Education research programme.

Read AGENTS.md, docs/STAGE_ORCHESTRATOR_SOP.md, research/README.md and this STAGE_GUIDE.md.

Your task is to complete this stage only. Do not solve later stages. Produce STAGE_EXECUTION.md, STAGE_LEDGER.csv, STAGE_REPORT.md, STAGE_REVIEW.md, PASS_FORWARD.md, PUBLIC_SUMMARY.md and STAGE_BOOK.md.

Classify all important claims. Preserve uncertainty. Run adversarial review before pass-forward.
```
