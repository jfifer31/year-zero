# Stage 10 – Curriculum Architecture and Version 0.1 Design

## 1. Stage purpose

Stage 10 constructs the Version 0.1 curriculum hypothesis. This is the first stage where curriculum architecture, domains, pathways, project types and implementation models may be designed. Every major element should trace back to prior stage outputs.

## 2. Short definition

Build the first curriculum architecture from all authorised upstream outputs.

## 3. Position in the chain

**Depends on:** Stages 1–9 pass-forward outputs.

**Feeds into:** Stage 11 Verification and Release Readiness; curriculum/v0.1 files.

This stage must preserve the distinction between what it has established, what it has assumed, what it values and what it projects.

## 4. Core research questions

1. What curriculum architecture follows from the capability and evidence models?
2. What domains, strands or pathways best organise the learning?
3. How should KS3-first progression work while remaining extensible to KS4?
4. What learning experiences should be included in Version 0.1?
5. How should parents, educators, mentors and learners use the curriculum?
6. What limitations must be stated before release?

## 5. Scope

### 5.1 In scope

- curriculum aims;
- principles;
- domains or strands;
- learning pathways;
- project types;
- evidence model integration;
- implementation guide;
- public usability;
- traceability map;
- limitations;

### 5.2 Out of scope

- claiming proven effectiveness;
- formal qualification design;
- complete lesson library;
- commercial packaging;
- high-stakes assessment claims;

If an out-of-scope issue appears important, record it as a downstream implication or open question rather than solving it inside this stage.

## 6. Required agent team

The Master Coordinator should call the smallest sufficient team, but this stage should normally include:

- Master Coordinator
- Curriculum Architect
- Learning Experience Designer
- Learning Sciences Expert
- Assessment and Verification Expert
- Implementation Feasibility Expert
- Documentation Editor
- Claim Steward

At least one quality, audit or adversarial agent must review the stage before pass-forward.

## 7. Recommended methodology

Use a method mix appropriate to the stage question. Recommended methods:

- curriculum architecture synthesis;
- traceability mapping;
- learning journey design;
- implementation stress testing;
- public readability review;
- low-resource adaptation check;

The method choice must be written into `STAGE_EXECUTION.md`, including why each method fits the stage and what its limitations are.

## 8. Evidence and source strategy

Prioritise sources that can actually answer this stage’s question. Likely source types include:

- all prior pass-forward memos;
- capability model;
- knowledge-experience-practice map;
- evidence-of-learning architecture;
- implementation constraints;
- public user journey requirements;

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

- Version 0.1 Curriculum Framework Draft;
- Implementation Guide Draft;
- Evidence of Learning Integration;
- Traceability Map;
- Limitations and Open Questions Draft;
- Stage 10 Pass-Forward Memo;

These named products are sections or structured results within the six canonical stage files and authorised `curriculum/v0.1/` release files, not additional stage files. In repository terms, the completed stage folder should contain:

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

- Does every curriculum element trace to prior stages?
- Has the architecture become too abstract to use?
- Does it overload learners or implementers?
- Does it silently recreate conventional curriculum structure?
- Does it overpromise outcomes?

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

- draft curriculum architecture;
- traceability links;
- implementation assumptions;
- known weaknesses;
- release-readiness questions for Stage 11;

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
You are running Stage 10 – Curriculum Architecture and Version 0.1 Design of the Year Zero Education research programme.

Read AGENTS.md, docs/RESEARCH_OPERATING_SYSTEM.md, research/README.md and this STAGE_GUIDE.md.

Your task is to complete this stage only. Do not solve later stages. Produce STAGE_EXECUTION.md, STAGE_LEDGER.csv, STAGE_REPORT.md, STAGE_REVIEW.md, PASS_FORWARD.md and PUBLIC_SUMMARY.md.

Classify all important claims. Preserve uncertainty. Run adversarial review before pass-forward.
```
