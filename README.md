# Year Zero Education

**Year Zero Education** is an open-source research and curriculum project for deriving a first-principles educational framework for young people growing up in the Intelligence Era.

The project begins from a simple but demanding question:

> What should young people learn, experience, practise and demonstrate in order to become flourishing, capable and adaptive adults in a world increasingly shaped by artificial intelligence and abundant access to intelligence?

The first public output will be **Version 0.1**: a curriculum hypothesis for KS3–KS4 learners, with a KS3-first initial release. It will not claim to be proven. It will be a transparent, auditable starting point for public critique, practical testing and iterative improvement.

---

## Why this project exists

Most curriculum debates begin too late. They begin with existing subjects, timetables, exams, school systems, labour market needs or political priorities.

Year Zero Education begins earlier.

It asks what must remain true about education if artificial intelligence changes access to knowledge, intelligence, creativity, labour, coordination and decision-making. It treats curriculum not as a list of inherited subjects, but as an engineered response to a changing human condition.

The project does **not** begin by asking:

- Which subjects should be protected?
- Which exams should be updated?
- Which AI tools should students use?
- Which future jobs should schools prepare for?

It begins by asking:

- What are human beings like?
- What does flourishing mean for young people?
- What future conditions might AI create?
- What remains humanly important across plausible futures?
- What functions must humans still perform?
- What capabilities support those functions?
- What knowledge, experience and practice develop those capabilities?
- What evidence would show that learning has actually happened?

Only after those questions have been worked through does the project design a curriculum architecture.

---

## What this project is

Year Zero Education is:

- a first-principles curriculum research programme;
- an agentic research and build system;
- an open-source public learning project;
- a Version 0.1 curriculum hypothesis for KS3–KS4 learners;
- a contribution pathway for researchers, educators, parents, learners and builders;
- a framework for researching, constructing, testing and improving a real future curriculum.

---

## What this project is not

Year Zero Education is not:

- a finished curriculum;
- a formal qualification;
- a school;
- a replacement for statutory education requirements;
- an evidence-backed intervention yet;
- a claim that exams are useless;
- a claim that existing subjects have no value;
- a product designed to sell certainty.

The first release is intentionally labelled **Version 0.1** because it should be criticised, tested and improved.

---

## Initial scope

The first curriculum hypothesis is designed for **KS3–KS4**, with the first release focused primarily on **KS3**.

This means the project is especially concerned with learners roughly aged 11–16, while recognising that:

- young people develop unevenly;
- adolescence is not a single uniform stage;
- KS3 and KS4 have different constraints;
- any future implementation must adapt to home education, alternative provision, mainstream schooling and informal learning environments;
- younger and older age ranges may require later versions.

---

## Research chain

The research chain moves from human foundations and AI-shaped future conditions through convergence, derivation, evidence of learning, curriculum architecture and release readiness.

For the human-readable phase sequence, see [`ROADMAP.md`](ROADMAP.md). For the research navigation table and stage guide links, see [`research/README.md`](research/README.md). For dependency discipline, pass-forward rules and method requirements, see [`docs/RESEARCH_OPERATING_SYSTEM.md`](docs/RESEARCH_OPERATING_SYSTEM.md).

---

## How to use this repository

| Reader | Start here | Then read |
|---|---|---|
| AI agent / Codex executor | `AGENTS.md` | [`docs/RESEARCH_OPERATING_SYSTEM.md`](docs/RESEARCH_OPERATING_SYSTEM.md), then the relevant `research/stage-XX/STAGE_GUIDE.md` |
| Project lead | `PROJECT_CHARTER.md` | [`ROADMAP.md`](ROADMAP.md), [`research/README.md`](research/README.md) |
| Research contributor | `CONTRIBUTING.md` | [`docs/RESEARCH_OPERATING_SYSTEM.md`](docs/RESEARCH_OPERATING_SYSTEM.md), relevant stage guide |
| Parent or educator | `public/README.md` | `public/PUBLIC_FAQ.md`, later `curriculum/v0.1/IMPLEMENTATION_GUIDE.md` |
| Learner | `public/README.md` | later `curriculum/v0.1/LEARNER` section inside `IMPLEMENTATION_GUIDE.md` |
| Public follower | `public/PUBLIC_FAQ.md` | `public/CONTENT_STRATEGY.md` |

---

## Repository structure

The final repository is organised into a small number of functional areas.

```text
/
  README.md
  PROJECT_CHARTER.md
  ROADMAP.md
  AGENTS.md
  CONTRIBUTING.md
  LICENSE
  CHANGELOG.md
  FILE_STRUCTURE.md

  /docs/
    RESEARCH_OPERATING_SYSTEM.md
    ETHICS_AND_PUBLIC_TESTING.md
    GLOSSARY.md

  /research/
    README.md
    /stage-01-human-baseline/
      STAGE_GUIDE.md
    ...
    /stage-11-verification-release/
      STAGE_GUIDE.md

  /templates/
    STAGE_EXECUTION_TEMPLATE.md
    STAGE_REPORT_TEMPLATE.md
    STAGE_REVIEW_TEMPLATE.md
    PASS_FORWARD_TEMPLATE.md
    PUBLIC_SUMMARY_TEMPLATE.md
    STAGE_LEDGER_TEMPLATE.csv

  /curriculum/v0.1/
    README.md
    CURRICULUM_FRAMEWORK.md
    EVIDENCE_OF_LEARNING.md
    IMPLEMENTATION_GUIDE.md
    LIMITATIONS_AND_OPEN_QUESTIONS.md
    TRACEABILITY_MAP.md

  /public/
    README.md
    PUBLIC_FAQ.md
    CONTENT_STRATEGY.md

  /.github/
    PULL_REQUEST_TEMPLATE.md
    /ISSUE_TEMPLATE/
      research_challenge.md
      implementation_feedback.md
```

---

## Core research discipline

Every important claim must be classified and handled according to the canonical taxonomy, evidence standards, confidence language, uncertainty rules, pass-forward discipline and adversarial review rules in `docs/RESEARCH_OPERATING_SYSTEM.md`.

This README intentionally keeps the rule short: the operating detail lives in one place so agents and contributors do not work from diverging summaries.

---

## Version 0.1 principle

Version 0.1 should be:

- logically derived;
- evidence-disciplined;
- transparent in its assumptions;
- honest about uncertainty;
- usable by real people;
- open to challenge;
- structured enough to test;
- humble enough to revise.

It does not need to be perfect before release. It does need to be clear, traceable and serious.

---

## Current status

The project is currently in **Stage 0: Foundation**.

Stage 0 prepares the repository, agent instructions, stage guides, research templates, public-facing pathway and release container.

The next substantive research action is:

> Run Stage 1 – Human Baseline.

---

## Contribution philosophy

Contributions are welcome when they improve clarity, evidence, reasoning, implementation or public understanding.

The project is not intended to become a loose collection of opinions. Contributions should identify the file, claim, evidence, assumption or implementation problem they affect.

Start with `CONTRIBUTING.md`.
