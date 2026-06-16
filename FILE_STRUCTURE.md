# File Structure

This file describes the intended final repository structure for Year Zero Education.

It should be updated whenever files are added, removed, renamed or consolidated.

---

## Top-level files

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
```

| File | Purpose |
|---|---|
| `README.md` | Public entry point and navigation hub. |
| `PROJECT_CHARTER.md` | Canonical mission, scope and research-chain definition. |
| `ROADMAP.md` | Execution sequence from Stage 0 to Version 0.1 and beyond. |
| `AGENTS.md` | Agent operating manual and reusable harness definitions. |
| `CONTRIBUTING.md` | Contribution rules, conduct expectations and safety basics. |
| `LICENSE` | Licence model for content and code. |
| `CHANGELOG.md` | Version and change history. |
| `FILE_STRUCTURE.md` | Repository map. |

---

## Documentation

```text
/docs/
  RESEARCH_OPERATING_SYSTEM.md
  ETHICS_AND_PUBLIC_TESTING.md
  GLOSSARY.md
```

| File | Purpose |
|---|---|
| `RESEARCH_OPERATING_SYSTEM.md` | Methodology, evidence standards, claim classification, uncertainty, pass-forward rules, adversarial review and stage gates. |
| `ETHICS_AND_PUBLIC_TESTING.md` | Safeguarding, privacy, learner data, testing ethics and public implementation boundaries. |
| `GLOSSARY.md` | Shared vocabulary. |

---

## Research stages

```text
/research/
  README.md
  /stage-01-human-baseline/
    STAGE_GUIDE.md
  /stage-02-flourishing/
    STAGE_GUIDE.md
  /stage-03-ai-future-conditions/
    STAGE_GUIDE.md
  /stage-04-life-within-futures/
    STAGE_GUIDE.md
  /stage-05-human-invariants/
    STAGE_GUIDE.md
  /stage-06-enduring-functions/
    STAGE_GUIDE.md
  /stage-07-capabilities/
    STAGE_GUIDE.md
  /stage-08-knowledge-experience-practice/
    STAGE_GUIDE.md
  /stage-09-evidence-of-learning/
    STAGE_GUIDE.md
  /stage-10-curriculum-architecture/
    STAGE_GUIDE.md
  /stage-11-verification-release/
    STAGE_GUIDE.md
```

Each stage guide is a standalone research brief. Stage outputs should be created inside the relevant stage folder during execution.

Expected execution outputs per stage:

```text
STAGE_EXECUTION.md
STAGE_LEDGER.csv
STAGE_REPORT.md
STAGE_REVIEW.md
PASS_FORWARD.md
PUBLIC_SUMMARY.md
```

These outputs are not pre-created unless a stage is being run.

---

## Templates

```text
/templates/
  STAGE_EXECUTION_TEMPLATE.md
  STAGE_REPORT_TEMPLATE.md
  STAGE_REVIEW_TEMPLATE.md
  PASS_FORWARD_TEMPLATE.md
  PUBLIC_SUMMARY_TEMPLATE.md
  STAGE_LEDGER_TEMPLATE.csv
```

Templates are copied into stage folders during execution.

---

## Curriculum release container

```text
/curriculum/
  /v0.1/
    README.md
    CURRICULUM_FRAMEWORK.md
    EVIDENCE_OF_LEARNING.md
    IMPLEMENTATION_GUIDE.md
    LIMITATIONS_AND_OPEN_QUESTIONS.md
    TRACEABILITY_MAP.md
```

This folder should remain mostly structural until Stage 10 and Stage 11 authorise curriculum content.

---

## Public communication

```text
/public/
  README.md
  PUBLIC_FAQ.md
  CONTENT_STRATEGY.md
```

This folder explains the project to parents, learners, educators and the wider public.

---

## GitHub collaboration

```text
/.github/
  PULL_REQUEST_TEMPLATE.md
  /ISSUE_TEMPLATE/
    research_challenge.md
    implementation_feedback.md
```

These files structure public contribution and feedback.

---

## Files intentionally not included

The project intentionally avoids separate files for:

- agent harnesses outside `AGENTS.md`;
- separate methodology, evidence and pass-forward micro-docs;
- individual CSV registers for every record type;
- parent, educator and learner guide placeholders before Version 0.1 exists;
- separate public release announcement and social media files before release.

This keeps the repository usable by agents and humans.
