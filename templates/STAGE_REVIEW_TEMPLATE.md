# Stage Review

> Copy this file into the active stage folder as `STAGE_REVIEW.md`.

This file combines adversarial review, evidence audit, bias/generalisation audit, implementation risk review and stage gate decision.

The review should make the stage stronger, not merely criticise it.

---

## 1. Review identity

**Stage number:**  
**Stage name:**  
**Review date:**  
**Review agents:**  
**Stage report reviewed:** `STAGE_REPORT.md`  
**Ledger reviewed:** `STAGE_LEDGER.csv`  

---

## 2. Review decision

Choose one:

- [ ] `pass`
- [ ] `pass_with_cautions`
- [ ] `revise_before_pass`
- [ ] `rollback_required`

**Decision rationale:**

> [Write here]

---

## 3. Strongest objections

List the strongest objections to the stage output.

| Objection ID | Objection | Severity | Required response |
|---|---|---|---|
| O-001 |  | `low | moderate | high | critical` |  |

---

## 4. Evidence audit

| Claim reviewed | Evidence cited | Does evidence support claim? | Problem | Required fix |
|---|---|---|---|---|
|  |  | `yes | partly | no | unclear` |  |  |

### 4.1 Evidence concerns

- [ ] Evidence too weak for claim.
- [ ] Source used outside its scope.
- [ ] Important counterevidence missing.
- [ ] Evidence is illustrative only.
- [ ] Recent claim requires updated source.
- [ ] Source quality unclear.
- [ ] Evidence not logged in ledger.

---

## 5. Claim classification audit

| Claim | Current classification | Correct classification? | Required change |
|---|---|---|---|
|  |  | `yes | no | uncertain` |  |

Check against the canonical claim-handling rules in `docs/RESEARCH_OPERATING_SYSTEM.md`, especially misclassified findings, assumptions, values, projections and design decisions.

---

## 6. Assumption audit

| Assumption | Is it visible? | Is it justified? | What if wrong? | Required response |
|---|---|---|---|---|
|  |  |  |  |  |

---

## 7. Uncertainty audit

| Uncertainty | Has it been preserved? | Downstream risk | Required response |
|---|---|---|---|
|  |  |  |  |

Reviewers should reject outputs that remove uncertainty merely to sound decisive.

---

## 8. Bias and generalisability audit

| Bias risk | Present? | Evidence | Required response |
|---|---|---|---|
| WEIRD bias |  |  |  |
| High-resource assumption |  |  |  |
| Technology access assumption |  |  |  |
| Neurotypical assumption |  |  |  |
| Elite education bias |  |  |  |
| Urban/middle-class bias |  |  |  |
| Cultural or family value narrowness |  |  |  |
| English-language source bias |  |  |  |

---

## 9. Implementation risk review

| Risk | Who affected? | Severity | Mitigation or pass-forward caution |
|---|---|---|---|
|  |  |  |  |

Consider:

- home education;
- mainstream schools;
- alternative provision;
- low-resource settings;
- independent learners;
- educators with limited time;
- learners with different needs;
- parents without specialist knowledge.

---

## 10. Ethics and safety review

| Issue | Present? | Required response |
|---|---|---|
| Learner privacy risk |  |  |
| Overclaiming impact |  |  |
| High-stakes misuse |  |  |
| Anxiety/fatalism risk |  |  |
| Sensitive learner data risk |  |  |
| Exclusion/accessibility risk |  |  |
| Public misunderstanding risk |  |  |

If any serious ethical issue appears, consult `docs/ETHICS_AND_PUBLIC_TESTING.md`.

---

## 11. Pass-forward audit

Before approving the stage, check the draft pass-forward claims.

| Pass-forward claim | Approved? | Required wording change | Caution |
|---|---|---|---|
|  | `yes | no | revise` |  |  |

Reject any pass-forward claim that is stronger than the stage report supports.

---

## 12. Public summary audit

| Question | Answer |
|---|---|
| Is the public summary understandable? |  |
| Does it preserve uncertainty? |  |
| Does it avoid hype? |  |
| Does it avoid unsupported claims? |  |
| Would a parent or educator understand what has and has not been established? |  |

---

## 13. Required revisions

| Revision ID | Required change | File affected | Responsible agent | Completion status |
|---|---|---|---|---|
| R-001 |  |  |  |  |

---

## 14. Stage gate decision

### 14.1 Final decision

`pass | pass_with_cautions | revise_before_pass | rollback_required`

### 14.2 Reason

> [Write here]

### 14.3 Conditions attached

If passed with cautions, list them here.

- [ ]
- [ ]

### 14.4 Revision triggers

What future evidence or critique should reopen this stage?

- [ ]
- [ ]

---

## 15. Reviewer sign-off

| Reviewer | Role | Sign-off | Notes |
|---|---|---|---|
|  |  |  |  |
