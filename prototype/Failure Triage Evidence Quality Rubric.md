# Failure Triage Evidence Quality Rubric

Use this after the next real failure-triage trial to grade whether the captured proof is strong enough to change README, prototype, or skill-draft claims. This is a blank rubric; it does not claim validation has happened.

Source package: [[Self-Healing Agent Observability Kit]]

## Trial reference
- Trial packet: [[Failure Triage Trial Packet]]
- Evidence preset: [[Real Workflow Evidence Preset - Failure Triage]]
- Promotion card: [[Failure Triage Promotion Decision Card]]
- Debrief: [[Failure Triage Post-Trial Debrief Template]]
- Date/run:
- Operator:
- Real workflow/task:
- Evidence links:

## Rubric

| Claim to support | Minimum acceptable proof | Score 0-2 | Notes / evidence link |
|---|---|---:|---|
| Trigger signal is real, not synthetic | Live alert/log/trace or user-visible failure captured with timestamp |  |  |
| Failure class is diagnosable | Error class, suspected component, and trace span/log excerpt identify a concrete failure mode |  |  |
| Triage board improves operator clarity | Before/after operator note shows faster or clearer decision-making |  |  |
| Repair/route decision is auditable | Decision owner, proposed fix, rollback/hold criteria, and follow-up issue are recorded |  |  |
| Outcome is measured | Post-action status, user impact, regression check, or unresolved blocker is linked |  |  |
| Skill/prototype change is evidence-backed | Proposed wording or field change cites the exact evidence row that justifies it |  |  |

Scoring guide:
- 0 = missing or speculative.
- 1 = partial evidence, needs another trial before public/reusable claims.
- 2 = source-backed and specific enough to justify a narrow claim or patch.

## Decision gate
- Total score:
- Minimum bar met? (all critical rows at least 1, no fabricated proof): yes/no
- Recommended action: promote skill draft / pilot-only / iterate prototype / hold
- Exact patches allowed by evidence:
  - README:
  - Prototype:
  - Skill draft:
- Claims explicitly **not** allowed yet:

## Follow-up queue
- [ ] Patch only evidence-backed wording.
- [ ] Add a filled example only if source links can remain shareable.
- [ ] Keep unproven claims in backlog language.
