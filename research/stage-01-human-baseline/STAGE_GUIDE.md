# Stage 1 – Human Baseline

> **Component status (20 June 2026):** This completed education-facing study is retained as **Stage 1A**. Its evidence and conclusions are frozen as a component input to Stage 1R reconciliation. Its `PASS_FORWARD.md` does not independently authorise Stage 2.

## 1. Stage purpose

Stage 1 establishes the human ground on which the whole project stands. It does not attempt to produce a total theory of human nature. It identifies the minimum defensible truths and strong working assumptions about human beings that any serious curriculum for the Intelligence Era must respect.

## 2. Short definition

Determine the minimum defensible assumptions about human beings that an educational framework must respect.

## 3. Position in the chain

**Depends on:** Stage 0 foundation files only.

**Feeds into:** Stage 2 Human Flourishing Model and, indirectly, all later stages.

This stage must preserve the distinction between what it has established, what it has assumed, what it values and what it projects.

## 4. Core research questions

1. What features of human motivation, agency and behaviour are sufficiently defensible to matter for education?
2. What is known about adolescence that should constrain KS3–KS4 curriculum design?
3. How do attention, cognition, memory, emotion, embodiment and social belonging shape learning?
4. What forms of individual variation are important enough that the curriculum must not assume one standard learner?
5. What tensions exist between cooperation, competition, status, autonomy, belonging and meaning?
6. Which claims are strongly evidenced, which are reasonable working assumptions, and which remain uncertain?

## 5. Scope

### 5.1 In scope

- motivation and incentives;
- agency and self-direction;
- status, belonging and peer dynamics;
- attention, cognition and learning;
- adolescent development;
- embodiment and emotion;
- identity formation;
- moral development;
- individual variation;
- social behaviour and cooperation;

### 5.2 Out of scope

- a universal theory of human nature;
- a final model of flourishing;
- curriculum design;
- future scenario design;
- policy recommendations;

If an out-of-scope issue appears important, record it as a downstream implication or open question rather than solving it inside this stage.

## 6. Required agent team

The Master Coordinator should call the smallest sufficient team, but this stage should normally include:

- Master Coordinator
- Human Sciences Expert
- Adolescent Development Expert
- Research Librarian
- Evidence Synthesis Researcher
- Bias and Generalisability Auditor
- Evidence Auditor
- Claim Steward

At least one quality, audit or adversarial agent must review the stage before pass-forward.

## 7. Recommended methodology

Use a method mix appropriate to the stage question. Recommended methods:

- rapid evidence review across human sciences and adolescent development;
- developmental constraint mapping for KS3–KS4;
- cross-domain synthesis of convergent findings;
- claim classification into empirical findings and working assumptions;
- bias audit for cultural, class and neurotypical assumptions;

The method choice must be written into `STAGE_EXECUTION.md`, including why each method fits the stage and what its limitations are.

## 8. Evidence and source strategy

Prioritise sources that can actually answer this stage’s question. Likely source types include:

- developmental psychology reviews;
- learning science reviews;
- cognitive science evidence;
- social psychology and anthropology where relevant;
- education research on adolescence;
- high-quality reviews on motivation, attention, identity and belonging;
- evidence on individual variation and neurodiversity;

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

- Minimum Human Baseline;
- Adolescent Development Constraints;
- Learner Variation Map;
- Human Tension Map;
- Stage 1 Pass-Forward Memo;

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

- Is the baseline too Western, middle-class or individualist?
- Are claims about adolescence overstated or too uniform?
- Are weak findings being promoted into universal claims?
- Does the stage ignore embodiment, emotion or social context?
- Would the conclusions hold for learners outside high-resource settings?

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

- authorised human baseline claims;
- developmental constraints for KS3–KS4;
- learner variation cautions;
- uncertainties that later stages must preserve;
- claims that must not be treated as universal;

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
You are running Stage 1 – Human Baseline of the Year Zero Education research programme.

Read AGENTS.md, docs/RESEARCH_OPERATING_SYSTEM.md, research/README.md and this STAGE_GUIDE.md.

Your task is to complete this stage only. Do not solve later stages. Produce STAGE_EXECUTION.md, STAGE_LEDGER.csv, STAGE_REPORT.md, STAGE_REVIEW.md, PASS_FORWARD.md and PUBLIC_SUMMARY.md.

Classify all important claims. Preserve uncertainty. Run adversarial review before pass-forward.
```
