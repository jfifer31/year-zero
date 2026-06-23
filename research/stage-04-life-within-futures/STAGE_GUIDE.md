# Stage 4 – Life Within Future Conditions

## 1. Stage purpose

Stage 4 asks what life may actually feel and function like for young people and adults under plausible AI-shaped conditions. It translates abstract future conditions into lived contexts: family life, learning, work, identity, community, trust, agency and social participation.

## 2. Short definition

Bring the human and AI streams together by modelling lived life inside plausible future conditions.

## 3. Position in the chain

**Depends on:** the reconciled Stage 1R, Stage 2 and Stage 3 pass-forward outputs.

**Feeds into:** Stage 5 Human Invariants Analysis.

This stage must preserve the distinction between what it has established, what it has assumed, what it values and what it projects.

## 4. Core research questions

1. How might young people experience learning, identity, status and belonging inside plausible AI-shaped conditions?
2. How might adulthood, work, family life, civic participation and meaning change?
3. Which pressures, opportunities and risks recur across different future conditions?
4. What new forms of dependency, agency, inequality or confusion may emerge?
5. Which human needs become harder, easier or more contested to meet?
6. What does this imply for the search for human invariants?

## 5. Scope

### 5.1 In scope

- learner life models;
- family and community contexts;
- work and adult life models;
- identity and status in AI-rich environments;
- trust and information conditions;
- agency and dependency;
- social inequality and access;
- ordinary lived experience rather than abstract futurism;

### 5.2 Out of scope

- final scenarios as prediction;
- curriculum design;
- capability derivation;
- policy prescriptions;
- utopian or dystopian storytelling;

If an out-of-scope issue appears important, record it as a downstream implication or open question rather than solving it inside this stage.

## 6. Required agent team

The Master Coordinator should call the smallest sufficient team, but this stage should normally include:

- Master Coordinator
- Systems and Causal Modeller
- Human Sciences Expert
- AI Futures Expert
- Foresight Scenario Modeller
- Qualitative Synthesis Researcher
- Bias and Generalisability Auditor
- Implementation Feasibility Expert

At least one quality, audit or adversarial agent must review the stage before pass-forward.

## 7. Recommended methodology

Use a method mix appropriate to the stage question. Recommended methods:

- life-world modelling;
- cross-scenario lived experience mapping;
- systems mapping;
- persona-free stakeholder modelling;
- pressure/opportunity analysis;
- ordinary day-in-the-life stress testing;

The method choice must be written into `STAGE_EXECUTION.md`, including why each method fits the stage and what its limitations are.

## 8. Evidence and source strategy

Prioritise sources that can actually answer this stage’s question. Likely source types include:

- reconciled Stage 1R human baseline;
- Stage 2 flourishing model;
- Stage 3 future conditions;
- implementation evidence from education and technology adoption;
- social research on youth, work, family and media;
- qualitative accounts where appropriate;

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

- Life Within Futures Models;
- Pressure and Opportunity Map;
- Recurring Human Need Map;
- Access and Inequality Analysis;
- Stage 4 Pass-Forward Memo;

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

- Are the life models too elite or technology-saturated?
- Do they ignore ordinary constraints such as time, money and family stress?
- Are they too dystopian or utopian?
- Do they overfit to current AI discourse?
- Do they ignore learners who disengage, resist or lack access?

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

- recurring lived pressures;
- recurring opportunities;
- human needs under future conditions;
- risks that later stages must address;
- uncertainties in life-condition modelling;

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
You are running Stage 4 – Life Within Future Conditions of the Year Zero Education research programme.

Read AGENTS.md, docs/STAGE_ORCHESTRATOR_SOP.md, research/README.md and this STAGE_GUIDE.md.

Your task is to complete this stage only. Do not solve later stages. Produce STAGE_EXECUTION.md, STAGE_LEDGER.csv, STAGE_REPORT.md, STAGE_REVIEW.md, PASS_FORWARD.md, PUBLIC_SUMMARY.md and STAGE_BOOK.md.

Classify all important claims. Preserve uncertainty. Run adversarial review before pass-forward.
```
