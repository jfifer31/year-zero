# Stage 11 – Verification, Falsification and Release Readiness

## 1. Stage purpose

Stage 11 is the final integrity check before public release. It verifies the chain, tries to falsify important claims, audits evidence and bias, tests implementation plausibility, reviews ethics and decides whether Version 0.1 is ready to publish.

## 2. Short definition

Attack the full chain, classify weaknesses and prepare responsible Version 0.1 release.

## 3. Position in the chain

**Depends on:** Stage 10 pass-forward output and all earlier stage outputs.

**Feeds into:** Public Version 0.1 release and Version 0.2 backlog.

This stage must preserve the distinction between what it has established, what it has assumed, what it values and what it projects.

## 4. Core research questions

1. Does the curriculum architecture genuinely follow from the research chain?
2. Which claims are strong, weak, speculative or value-based?
3. Where could the project be wrong?
4. What implementation risks remain?
5. What ethical risks remain?
6. What must be said clearly in the public release?
7. Is Version 0.1 ready, ready with cautions, or not ready?

## 5. Scope

### 5.1 In scope

- full-chain traceability;
- claim audit;
- evidence audit;
- bias audit;
- implementation stress test;
- ethics review;
- public language review;
- release checklist;
- Version 0.2 backlog;

### 5.2 Out of scope

- major new curriculum design unless revision required;
- marketing claims;
- effectiveness claims;
- formal accreditation;

If an out-of-scope issue appears important, record it as a downstream implication or open question rather than solving it inside this stage.

## 6. Required agent team

The Master Coordinator should call the smallest sufficient team, but this stage should normally include:

- Master Coordinator
- Adversarial Red Team Agent
- Evidence Auditor
- Bias and Generalisability Auditor
- Ethics, Safeguarding and Privacy Expert
- Implementation Test Agent
- Release Manager
- Public Narrative Strategist
- Documentation Editor

At least one quality, audit or adversarial agent must review the stage before pass-forward.

## 7. Recommended methodology

Use a method mix appropriate to the stage question. Recommended methods:

- full-chain dependency audit;
- falsification review;
- red-team critique;
- release gate review;
- public claims audit;
- implementation scenario test;
- ethics and privacy review;

The method choice must be written into `STAGE_EXECUTION.md`, including why each method fits the stage and what its limitations are.

## 8. Evidence and source strategy

Prioritise sources that can actually answer this stage’s question. Likely source types include:

- all stage reports;
- all pass-forward memos;
- stage ledgers;
- curriculum draft;
- implementation guide;
- public materials;
- ethics file;
- contribution pathway;

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

- Release Readiness Report;
- Falsification and Weakness Register;
- Version 0.1 Release Decision;
- Known Limitations Final;
- Version 0.2 Backlog;
- Stage 11 Public Summary;

These named products are sections or structured results within the six authority files, `STAGE_BOOK.md` and the authorised release package, not additional stage files. In repository terms, the completed stage folder should contain:

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

- What would a serious critic attack first?
- Which curriculum elements are least supported?
- Which public claims could mislead?
- Which users might misunderstand or misuse the release?
- What evidence would force a major revision?

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

- release decision;
- public cautions;
- known limitations;
- Version 0.2 backlog;
- research questions requiring future work;

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
You are running Stage 11 – Verification, Falsification and Release Readiness of the Year Zero Education research programme.

Read AGENTS.md, docs/STAGE_ORCHESTRATOR_SOP.md, research/README.md and this STAGE_GUIDE.md.

Your task is to complete this stage only. Do not solve later stages. Produce STAGE_EXECUTION.md, STAGE_LEDGER.csv, STAGE_REPORT.md, STAGE_REVIEW.md, PASS_FORWARD.md, PUBLIC_SUMMARY.md and STAGE_BOOK.md.

Classify all important claims. Preserve uncertainty. Run adversarial review before pass-forward.
```
