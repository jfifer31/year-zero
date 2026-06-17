# Stage 8 – Knowledge, Experience and Practice Mapping

## 1. Stage purpose

Stage 8 determines what learners should encounter and practise in order to develop the capabilities derived in Stage 7. It treats knowledge seriously, but as part of a functional learning architecture rather than as inherited subject coverage by default.

## 2. Short definition

Identify the knowledge, experiences and practices that can cultivate the derived capabilities.

## 3. Position in the chain

**Depends on:** Stage 7 pass-forward output. Earlier material may be consulted only through authorised pass-forward statements and traceability references.

**Feeds into:** Stage 9 Evidence of Learning and Stage 10 Curriculum Architecture.

This stage must preserve the distinction between what it has established, what it has assumed, what it values and what it projects.

## 4. Core research questions

1. What knowledge is required to develop each capability?
2. What experiences make capabilities meaningful and durable?
3. What forms of practice, feedback and reflection are needed?
4. Which traditional subject knowledge is foundational, enabling, contextual, optional or weakly justified?
5. Which interdisciplinary or real-world contexts are necessary?
6. How should AI tools be used without weakening human capability?

## 5. Scope

### 5.1 In scope

- knowledge mapping;
- experience design inputs;
- practice structures;
- feedback loops;
- project types;
- AI-assisted inquiry;
- disciplinary knowledge testing;
- interdisciplinary contexts;
- embodied and social learning;

### 5.2 Out of scope

- final curriculum sequence;
- full lesson design;
- formal assessment architecture;
- unexamined subject inheritance;
- tool-led AI activities;

If an out-of-scope issue appears important, record it as a downstream implication or open question rather than solving it inside this stage.

## 6. Required agent team

The Master Coordinator should call the smallest sufficient team, but this stage should normally include:

- Master Coordinator
- Learning Sciences Expert
- Subject Domain Panel
- Learning Experience Designer
- Education Landscape Comparator
- Implementation Feasibility Expert
- Evidence Auditor
- Bias and Generalisability Auditor

At least one quality, audit or adversarial agent must review the stage before pass-forward.

## 7. Recommended methodology

Use a method mix appropriate to the stage question. Recommended methods:

- capability-to-knowledge mapping;
- learning mechanism analysis;
- practice and feedback design;
- traditional curriculum comparison as later-stage check;
- experience mapping;
- low-resource feasibility review;

The method choice must be written into `STAGE_EXECUTION.md`, including why each method fits the stage and what its limitations are.

## 8. Evidence and source strategy

Prioritise sources that can actually answer this stage’s question. Likely source types include:

- Stage 7 capability model;
- learning science;
- disciplinary education research;
- project-based learning evidence;
- practice and feedback research;
- curriculum comparison evidence;
- implementation reports;

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

- Knowledge-Experience-Practice Map;
- Capability Learning Mechanism Matrix;
- Existing Curriculum Comparison Notes;
- AI Tool Use Principles;
- Stage 8 Pass-Forward Memo;

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

- Is knowledge being undervalued because AI exists?
- Are existing subjects being rejected too casually?
- Are traditional subjects being kept without justification?
- Are proposed experiences practical for ordinary learners?
- Do AI tools replace the human practice the capability requires?

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

- authorised learning inputs;
- knowledge classifications;
- experience and practice requirements;
- AI-use cautions;
- implementation constraints;
- items requiring evidence-of-learning design;

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
You are running Stage 8 – Knowledge, Experience and Practice Mapping of the Year Zero Education research programme.

Read AGENTS.md, docs/RESEARCH_OPERATING_SYSTEM.md, research/README.md and this STAGE_GUIDE.md.

Your task is to complete this stage only. Do not solve later stages. Produce STAGE_EXECUTION.md, STAGE_LEDGER.csv, STAGE_REPORT.md, STAGE_REVIEW.md, PASS_FORWARD.md and PUBLIC_SUMMARY.md.

Classify all important claims. Preserve uncertainty. Run adversarial review before pass-forward.
```
