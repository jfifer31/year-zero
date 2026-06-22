# Research Operating System

This file defines the research method, evidence standards, claim classification, stage gates, uncertainty discipline and pass-forward rules for Year Zero Education.

It is the canonical source for how research is conducted, how claims are classified, how evidence is handled, how uncertainty is preserved and how one stage passes authorised outputs to the next. Agent roles and harnesses are defined in `AGENTS.md`, but those roles must follow this methodological operating manual.

Agents and human researchers should treat this file as the project’s binding research method.

---

## 1. Purpose

The purpose of the research operating system is to make the project capable of producing genuinely useful curriculum insight without pretending to have more certainty than it has.

The project is not simply collecting educational opinions. It is constructing a traceable chain from:

```text
Human realities
+ Human flourishing
+ AI-shaped future conditions
→ Life within futures
→ Human invariants
→ Enduring functions
→ Capabilities
→ Knowledge, experience and practice
→ Evidence of learning
→ Curriculum architecture
→ Public Version 0.1 release
```

The operating system exists to protect that chain from:

- hidden assumptions;
- premature curriculum design;
- cherry-picked evidence;
- overconfident futures claims;
- inherited subject bias;
- vague public-facing language;
- agent drift;
- file sprawl;
- unsupported claims of impact.

---

## 2. Canonical scope

This file governs the project's research method. It is authoritative for:

- method selection and justification;
- source discovery and evidence standards;
- ledger requirements;
- claim classification and claim handling;
- confidence, uncertainty and evidence weighting;
- stage gates and completion standards;
- adversarial, bias, implementation and ethics review expectations;
- pass-forward and traceability rules;
- revision, rollback and versioning logic.

`AGENTS.md` governs agent operating sequence, roles, harnesses and handoff discipline. Where an agent role conflicts with this file, this file controls the research method.

---

## 3. Core research rule

Every stage must answer the question it has actually been assigned, not the question the agent finds most interesting.

A stage should not solve later stages early. It may identify downstream implications, but it must not convert those implications into final curriculum decisions before the correct stage.

---

## 4. Engineering mindset

Year Zero Education is a research-and-build project.

It follows an engineering pattern:

1. Define the problem.
2. Identify constraints.
3. Make assumptions explicit.
4. Build the simplest complete working model.
5. Test weak points.
6. Record failure modes.
7. Release a versioned artefact.
8. Improve through feedback and further evidence.

The goal is not to achieve final certainty before Version 0.1. The goal is to build a coherent, inspectable and improvable first version.

---

## 5. The research chain

The project uses eleven substantive stages after foundation setup.

| Stage | Name | Primary output |
|---|---|---|
| 1A | Education-Facing Human Baseline | Completed component study of learning, adolescence and educationally visible human functioning. |
| 1B | General Human Baseline | Component study of recurring human drives, psychological mechanisms and social structures outside education. |
| 1R | Human Baseline Reconciliation | Sole authoritative reconciled human baseline for downstream stages. |
| 2 | Human Flourishing Model | Project-specific model of flourishing. |
| 3 | AI Future Conditions Discovery | Map of plausible AI-shaped future conditions. |
| 4 | Life Within Future Conditions | Models of lived human life inside plausible futures. |
| 5 | Human Invariants Analysis | Human realities that remain important across futures. |
| 6 | Enduring Human Functions | Functions humans must still perform or embody. |
| 7 | Capability Derivation | Developable capability model. |
| 8 | Knowledge, Experience and Practice Mapping | Learning inputs that cultivate capabilities. |
| 9 | Evidence of Learning and Verification Architecture | Ways to observe, demonstrate and verify learning. |
| 10 | Curriculum Architecture and Version 0.1 Design | Curriculum framework. |
| 11 | Verification, Falsification and Release Readiness | Release readiness decision and revision map. |

---

## 6. Dependency discipline

Stages depend on previous stages through pass-forward outputs.

A later stage may use:

- authorised findings;
- authorised assumptions;
- unresolved uncertainties;
- downstream cautions;
- traceability references;
- revision triggers.

A later stage may not:

- freely reinterpret earlier work;
- ignore stated limitations;
- strengthen a claim without new evidence;
- remove uncertainty for readability;
- convert illustrative examples into conclusions.

---

## 7. Required outputs per stage

Each completed stage should produce the following files inside its stage folder:

```text
STAGE_EXECUTION.md
STAGE_LEDGER.csv
STAGE_REPORT.md
STAGE_REVIEW.md
PASS_FORWARD.md
PUBLIC_SUMMARY.md
```

These files should be created from the templates in `/templates/`.

### 7.1 `STAGE_EXECUTION.md`

Defines how the stage will be run.

Includes:

- objective;
- authorised inputs;
- research questions;
- method selection;
- agents called;
- source plan;
- execution sequence;
- prompts used;
- output checklist.

### 7.2 `STAGE_LEDGER.csv`

Single structured ledger for sources, claims, assumptions, uncertainties, decisions, risks and traceability records.

This replaces multiple separate CSVs.

### 7.3 `STAGE_REPORT.md`

Main technical report.

Includes:

- executive summary;
- method;
- evidence synthesis;
- findings;
- assumptions;
- uncertainties;
- implications;
- limitations.

### 7.4 `STAGE_REVIEW.md`

Combined adversarial review, gate review and risk review.

Includes:

- strongest objections;
- evidence weaknesses;
- bias risks;
- implementation concerns;
- ethical concerns;
- pass/revise/rollback recommendation.

### 7.5 `PASS_FORWARD.md`

Controlled handoff to the next stage.

Includes:

- authorised downstream findings;
- carried assumptions;
- unresolved uncertainties;
- claims not to overextend;
- revision triggers.

### 7.6 `PUBLIC_SUMMARY.md`

Plain-language explanation.

Includes:

- what the stage asked;
- what it found;
- why it matters;
- what remains uncertain;
- how it affects the project.

---

## 8. Stage ledger system

The project uses one ledger per stage instead of many separate logs.

Each row has a `record_type`.

Recommended record types:

| Record type | Meaning |
|---|---|
| `source` | A source consulted. |
| `evidence` | Evidence extracted from a source. |
| `claim` | A substantive claim made by the stage. |
| `assumption` | A working assumption adopted by the stage. |
| `uncertainty` | An unresolved unknown or confidence limitation. |
| `decision` | A stage-level methodological or interpretive decision. |
| `risk` | A reasoning, ethics, implementation or public-use risk. |
| `traceability` | Link from one output to another. |
| `challenge` | Objection, contradiction or adversarial issue. |
| `revision_trigger` | Condition that would require future update. |

This ledger is the operational memory of the stage.

---

## 9. Claim classification

Every important claim must be classified.

| Claim class | Definition | Example handling |
|---|---|---|
| Empirical Finding | A claim supported by evidence. | Cite evidence, state confidence and limitations. |
| Working Assumption | A provisional claim used to proceed. | Label as assumption, record alternatives and revision trigger. |
| Normative Judgement | A value-based claim about what should matter. | Explain value basis and trade-offs. |
| Speculative Projection | A future-facing possibility. | Link to drivers, uncertainty and signposts. |
| Design Decision | A chosen design response. | Link to upstream claims and practical constraints. |

The first four are the primary claim types. `Design Decision` is used mainly in Stage 10 and later.

---

## 10. Claim handling rules

### 10.1 Empirical findings

An empirical finding must include:

- claim text;
- source or evidence basis;
- confidence level;
- scope;
- limitations;
- counterevidence if known;
- downstream use.

### 10.2 Working assumptions

A working assumption must include:

- assumption text;
- why it is needed;
- what alternatives exist;
- what would change if it is wrong;
- revision trigger.

### 10.3 Normative judgements

A normative judgement must include:

- value claim;
- reason for adopting it;
- trade-offs;
- disagreement likely;
- implications for curriculum design.

### 10.4 Speculative projections

A speculative projection must include:

- driver or condition;
- plausibility logic;
- uncertainty;
- signposts;
- risk of overuse.

### 10.5 Design decisions

A design decision must include:

- decision made;
- upstream basis;
- alternatives rejected;
- reason for choice;
- test or review method.

---

## 11. Confidence levels

Use qualitative confidence labels.

| Confidence | Meaning |
|---|---|
| High | Supported by strong evidence or robust cross-source convergence. |
| Moderate | Supported but with meaningful limitations, disagreement or contextual uncertainty. |
| Low | Plausible but weakly supported, context-dependent or speculative. |
| Open | Not yet settled; carried forward as a question or uncertainty. |

Do not use numerical confidence unless the method justifies it.

---

## 12. Evidence weighting

Sources and evidence should be weighted according to their role.

| Weight | Meaning |
|---|---|
| Anchor | Strong enough to support a major stage conclusion. |
| Supporting | Useful in combination with other evidence. |
| Contextual | Helps frame or interpret the issue. |
| Illustrative | Useful example, not proof. |
| Non-decision | Logged but not used to support conclusions. |

An illustrative example should never become an anchor.

---

## 13. Source hierarchy

Different stages require different source types. However, the project should usually prefer:

1. High-quality reviews, meta-analyses and consensus reports where available.
2. Strong primary studies where review evidence is unavailable or insufficient.
3. Official datasets and institutional reports for current systems and trends.
4. Books and theoretical work where the question is conceptual or normative.
5. Practitioner evidence where implementation context matters.
6. Lived-experience evidence where human experience, feasibility or accessibility is central.
7. Examples and case studies as illustration, not proof.

The project should not reject qualitative evidence simply because it is qualitative. It should classify what kind of evidence it is and what it can reasonably support.

---

## 14. Source logging requirements

Every important source should be logged in `STAGE_LEDGER.csv` with:

- source ID;
- title;
- author or organisation;
- year;
- source type;
- URL or citation if available;
- relevance;
- evidence weight;
- limitations;
- claims supported;
- stage used.

If a source is rejected after review, it may still be logged as `non-decision` if useful for transparency.

---

## 15. Method selection

Each stage must choose methods that fit its question.

| Question type | Suitable methods |
|---|---|
| What is known about humans? | Evidence review, synthesis of human sciences, developmental review. |
| What should count as flourishing? | Evidence review plus explicit normative analysis. |
| What future conditions are plausible? | Horizon scanning, driver mapping, scenario discovery. |
| How might people live inside futures? | Scenario modelling, systems mapping, lived-experience modelling. |
| What remains human across futures? | Cross-scenario comparison, invariants analysis. |
| What must humans still do? | Function derivation, dependency mapping, adversarial testing. |
| What capabilities are required? | Capability modelling, developmental analysis, feasibility review. |
| What learning develops capabilities? | Learning science synthesis, practice mapping, implementation review. |
| How can learning be evidenced? | Assessment validity analysis, portfolio design, demonstration modelling. |
| What curriculum follows? | Architecture design, traceability mapping, implementation stress test. |

Method choice must be justified in `STAGE_EXECUTION.md`.

---

## 16. Scenario discovery rules

Stages involving the future must not pretend to predict a single future.

Future-facing work should:

- identify drivers;
- identify uncertainties;
- distinguish near-term, medium-term and long-term conditions;
- describe plausible ranges;
- record signposts;
- avoid hype;
- avoid assuming smooth adoption;
- avoid assuming equal access;
- avoid assuming technology determines social outcomes alone.

Scenario work should produce useful conditions for curriculum derivation, not entertainment-grade futurism.

---

## 17. Existing curriculum comparison rule

Existing curricula, alternative schools, pedagogical models and assessment systems are relevant, but they must not anchor the project too early.

They may be used for:

- comparison;
- gap analysis;
- implementation insight;
- evidence about feasibility;
- examples of possible practice;
- later-stage benchmarking.

They should not be used as the starting point for deriving what young people should learn.

This protects the project from reproducing inherited structures by default.

---

## 18. Human baseline rule

Stages 1A and 1B are component studies. Stage 1R should identify the reconciled minimum defensible assumptions and is the only Stage 1 interface authorised downstream. No component should create a total theory of human nature.

The reconciled baseline should be:

- defensible;
- relevant to education;
- sufficiently broad for later use;
- honest about variation;
- cautious about universal claims;
- clear about adolescence.

Stage 1B must test recurrence rather than assume innateness, distinguish recurrent tendencies from inevitable institutions, and exclude educational implications. Stage 1R may not collect new evidence; unresolved evidence gaps return to the relevant component.

---

## 19. Flourishing rule

Stage 2 must separate:

- empirical evidence about well-being, development and life outcomes;
- normative judgements about what should matter;
- practical constraints on education;
- plural reasonable views of the good life.

The project may adopt a working model of flourishing, but it must not pretend that the model is value-neutral.

---

## 20. Capability derivation rule

Capabilities must be derived from enduring functions, not invented as attractive educational language.

A capability should have:

- upstream function;
- developmental relevance;
- teachability or cultivability;
- observable evidence;
- relationship to flourishing;
- risk if absent.

---

## 21. Knowledge, experience and practice rule

Knowledge matters, but it should be justified by function and capability.

Stage 8 should classify knowledge, experiences and practices as:

- foundational;
- enabling;
- contextual;
- optional;
- replaceable;
- inherited but still valuable;
- inherited but weakly justified.

This does not mean abandoning traditional subjects. It means testing them against the derived purpose of education.

---

## 22. Evidence of learning rule

Evidence of learning should not be reduced to exams or grades.

Stage 9 should consider:

- performance;
- explanation;
- transfer;
- judgement;
- reflection;
- project artefacts;
- collaboration;
- iteration;
- real-world application;
- portfolio evidence;
- moderation and verification.

The model must also consider fairness, gaming risk, privacy and burden.

---

## 23. Curriculum architecture rule

Stage 10 may design the curriculum only from authorised upstream outputs.

The curriculum should include:

- aims;
- principles;
- domains or strands;
- learner pathways;
- learning experiences;
- evidence model;
- implementation options;
- limitations;
- traceability.

Curriculum design should not exceed the support provided by earlier stages.

---

## 24. Adversarial review

Every stage must be attacked before it is passed forward.

Adversarial review should ask:

- What is the strongest objection?
- What evidence is weak?
- What assumption is hidden?
- What might be culturally narrow?
- What would fail in real implementation?
- What has been overstated?
- What would change the conclusion?
- What later stage might misuse this output?

Adversarial review should improve the work, not merely criticise it.

---

## 25. Bias and generalisability audit

The project should actively check for:

- WEIRD bias;
- elite education bias;
- high-resource assumptions;
- technology access assumptions;
- neurotypical assumptions;
- English-language source bias;
- Western liberal individualist assumptions;
- urban and middle-class implementation bias;
- overgeneralisation from small samples;
- hidden ideological preferences.

Not every bias can be eliminated, but important biases must be visible.

---

## 26. Stage gate review

A stage may pass only if:

- its question has been answered sufficiently for downstream use;
- evidence has been logged;
- claims have been classified;
- assumptions are visible;
- uncertainty is explicit;
- adversarial review has occurred;
- public summary exists;
- pass-forward memo is complete;
- downstream limitations are clear.

A stage should be marked:

- `pass`;
- `pass_with_cautions`;
- `revise_before_pass`;
- `rollback_required`.

---

## 27. Pass-forward protocol

The pass-forward file is the controlled interface between stages.

It must include:

1. Stage name.
2. Stage objective.
3. Authorised findings.
4. Working assumptions carried forward.
5. Normative judgements carried forward.
6. Speculative projections carried forward.
7. Unresolved uncertainties.
8. Claims not to overextend.
9. Required cautions for next stage.
10. Revision triggers.
11. Traceability references.

If a claim is not in the pass-forward file, the next stage should not treat it as authorised.

---

## 28. Traceability

The project must be able to trace:

```text
source/evidence
→ claim
→ stage finding
→ pass-forward statement
→ capability/curriculum element
→ evidence-of-learning model
```

Traceability does not need to be perfect in Version 0.1, but every major curriculum element should have a visible upstream rationale.

---

## 29. Public summary rules

Public summaries should be clear without becoming simplistic.

They should state:

- what question was asked;
- why it matters;
- what was found;
- what is uncertain;
- what this means for the next stage;
- what should not be concluded yet.

Avoid:

- hype;
- fake certainty;
- academic fog;
- defensive language;
- unsupported claims of impact.

---

## 30. Revision and rollback

A stage may need revision if:

- a central claim is unsupported;
- important counterevidence was missed;
- a hidden assumption changes downstream conclusions;
- a bias audit identifies serious narrowness;
- implementation review shows the output is unusable;
- later stages expose dependency failure.

Rollback is not failure. It is part of an honest engineering process.

---

## 31. Versioning logic

The project should distinguish:

- repository foundation versions;
- research stage outputs;
- public curriculum versions;
- experimental implementation versions.

Version 0.1 means the first public curriculum hypothesis, not final truth.

Later versions should clearly state what changed and why.

---

## 32. Anti-patterns

Avoid these recurring failure modes.

### 32.1 Curriculum-first drift

Jumping to subjects, projects or lessons before the derivation chain authorises them.

### 32.2 Agent theatre

Creating many agent roles or files without improving output quality.

### 32.3 Evidence laundering

Using a source to make a claim stronger than the source supports.

### 32.4 Scenario storytelling

Writing vivid futures without useful analytical structure.

### 32.5 Values hiding

Presenting moral or philosophical choices as if they were purely empirical.

### 32.6 Template overload

Creating so many templates that agents spend more effort managing files than thinking.

### 32.7 Public overclaiming

Presenting Version 0.1 as proven, revolutionary or complete.

---

## 33. Definition of research quality

A high-quality stage output is:

- clear;
- well scoped;
- evidence-aware;
- honest about uncertainty;
- explicit about values;
- useful for the next stage;
- adversarially tested;
- traceable;
- publicly explainable;
- practical enough to support construction.

The standard is not academic ornament. The standard is reliable reasoning that can support building and testing a real curriculum.
