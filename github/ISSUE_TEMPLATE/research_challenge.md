---
name: Research challenge
description: Challenge a claim, source, assumption, stage output or reasoning step
title: "Research challenge: [short description]"
labels: ["research-challenge", "needs-review"]
body:
  - type: markdown
    attributes:
      value: |
        Use this template to challenge research claims, evidence, assumptions, reasoning, traceability or stage outputs.

        A strong challenge is specific, evidence-aware and constructive. The goal is to improve the project, not simply disagree.

  - type: input
    id: affected_file
    attributes:
      label: Affected file
      description: Which file, section or stage does this challenge concern?
      placeholder: "e.g. research/stage-01-human-baseline/STAGE_GUIDE.md"
    validations:
      required: true

  - type: textarea
    id: claim
    attributes:
      label: Claim or reasoning being challenged
      description: Quote or summarise the specific claim, assumption, conclusion or reasoning step.
      placeholder: "The project currently claims that..."
    validations:
      required: true

  - type: dropdown
    id: challenge_type
    attributes:
      label: Type of challenge
      options:
        - Evidence does not support claim
        - Missing counterevidence
        - Claim is overstated
        - Assumption is hidden
        - Normative judgement is not labelled
        - Speculative projection is treated as prediction
        - Cultural or access bias
        - Developmental appropriateness concern
        - Traceability problem
        - Implementation feasibility concern
        - Ethical or safeguarding concern
        - Other
    validations:
      required: true

  - type: textarea
    id: reason
    attributes:
      label: Why is this a problem?
      description: Explain the issue clearly.
      placeholder: "This is a problem because..."
    validations:
      required: true

  - type: textarea
    id: evidence
    attributes:
      label: Evidence, source or reasoning
      description: Provide evidence, citations, examples or reasoning that supports the challenge.
      placeholder: "Relevant source or reasoning..."
    validations:
      required: false

  - type: dropdown
    id: seriousness
    attributes:
      label: Seriousness
      options:
        - Low - wording or clarity issue
        - Moderate - affects interpretation
        - High - affects stage conclusion or downstream use
        - Critical - may require rollback or major revision
    validations:
      required: true

  - type: textarea
    id: proposed_resolution
    attributes:
      label: Proposed resolution
      description: How should the project respond?
      placeholder: "Revise the claim to..., add a caution..., move this to assumptions..., reopen the stage..."
    validations:
      required: false

  - type: checkboxes
    id: checklist
    attributes:
      label: Submission checklist
      options:
        - label: I have identified the specific file or claim affected.
          required: true
        - label: I have explained why the issue matters.
          required: true
        - label: I understand that disagreement alone is not automatically a research correction.
          required: true
        - label: I have not included private learner data.
          required: true
---
