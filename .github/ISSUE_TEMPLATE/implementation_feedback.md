---
name: Implementation feedback
description: Report experience using, reviewing or testing Year Zero Education materials
title: "Implementation feedback: [short description]"
labels: ["implementation-feedback", "needs-review"]
body:
  - type: markdown
    attributes:
      value: |
        Use this template to report practical feedback from using, reviewing or testing Year Zero Education materials.

        Please use broad, anonymised summaries only. Do not include private learner data, learner work, images, videos, school records or AI logs. See `docs/ETHICS_AND_PUBLIC_TESTING.md`.

  - type: dropdown
    id: role
    attributes:
      label: Your role
      options:
        - Parent / home educator
        - Learner with adult support
        - Teacher / educator
        - Mentor / facilitator
        - Alternative provision practitioner
        - Researcher / reviewer
        - Project contributor
        - Other
    validations:
      required: true

  - type: input
    id: material_used
    attributes:
      label: Material used or reviewed
      description: Which file, activity, guide or curriculum element does this feedback concern?
      placeholder: "e.g. curriculum/v0.1/IMPLEMENTATION_GUIDE.md"
    validations:
      required: true

  - type: dropdown
    id: setting
    attributes:
      label: Setting
      options:
        - Home education
        - Mainstream school
        - Alternative provision
        - Informal learning / club
        - Independent learner
        - Adult review only
        - Simulated test only
        - Other
    validations:
      required: true

  - type: input
    id: learner_age_range
    attributes:
      label: Learner age range, if relevant
      description: Use broad ranges only. Do not identify a learner.
      placeholder: "e.g. KS3, KS4, age 11-13, not applicable"
    validations:
      required: false

  - type: textarea
    id: what_tried
    attributes:
      label: What did you try or review?
      description: Describe the activity, guide, project, evidence task or section reviewed.
      placeholder: "We tried..."
    validations:
      required: true

  - type: textarea
    id: what_worked
    attributes:
      label: What worked well?
      placeholder: "What felt useful, clear, motivating, practical or insightful?"
    validations:
      required: false

  - type: textarea
    id: what_failed
    attributes:
      label: What did not work, confused users or felt unrealistic?
      placeholder: "What was unclear, too hard, too abstract, too time-consuming or unsuitable?"
    validations:
      required: false

  - type: textarea
    id: evidence_observed
    attributes:
      label: What general signs of learning or engagement did you observe?
      description: Keep this broad and anonymised. Do not quote private learner reflections or submit learner work.
      placeholder: "In general terms, learners were able to..., the group produced..., participants seemed..."
    validations:
      required: false

  - type: textarea
    id: accessibility
    attributes:
      label: Accessibility, inclusion or resource issues
      description: Did the material assume too much time, reading, technology, confidence, adult support or prior knowledge?
      placeholder: "This may be difficult for learners who..."
    validations:
      required: false

  - type: textarea
    id: safety_privacy
    attributes:
      label: Safety or privacy concerns
      description: Did anything create discomfort, data risk, public-sharing risk, AI-log risk or safeguarding concern?
      placeholder: "Potential concern..."
    validations:
      required: false

  - type: textarea
    id: suggested_change
    attributes:
      label: Suggested change
      placeholder: "I suggest changing..."
    validations:
      required: false

  - type: dropdown
    id: priority
    attributes:
      label: Priority
      options:
        - Low - minor improvement
        - Medium - would improve usability
        - High - significant barrier or risk
        - Critical - safety, privacy or serious misuse concern
    validations:
      required: true

  - type: checkboxes
    id: privacy_confirmation
    attributes:
      label: Privacy confirmation
      options:
        - label: I have not included a learner's full name.
          required: true
        - label: I have not included private learner reflections or sensitive personal details.
          required: true
        - label: I have not included images or videos of minors.
          required: true
        - label: I have not included AI logs from a learner.
          required: true
        - label: I understand this feedback may be discussed publicly in anonymised or summarised form.
          required: true
---
