# Failure Triage Post-Trial Debrief Template

Status: template-ready; no validation proof recorded yet.

Use this after the [[Failure Triage Trial Packet]], [[Real Workflow Evidence Preset - Failure Triage]], and [[Failure Triage Promotion Decision Card]] have been filled for one real failure-triage workflow. It turns the raw evidence into a patch queue without pretending the prototype has already been validated.

## 1. Trial identity

- Workflow / repo / agent surface:
- Date:
- Operator:
- Reviewer:
- Linked trial packet:
- Linked evidence preset:
- Linked promotion decision card:
- Linked trace/log/issue:

## 2. Failure narrative

| Step | Evidence-backed note |
| --- | --- |
| Trigger signal |  |
| Initial failure class |  |
| Trace/log clue that mattered |  |
| Repair or routing decision |  |
| Human review outcome |  |
| Remaining uncertainty |  |

## 3. Board usefulness review

- Which board field saved time?
- Which field was ambiguous or missing?
- Which failure class should be added/renamed?
- Which repair option should be removed or scoped down?
- What source link proves the outcome?

## 4. Skill-promotion guardrail

Mark only one:

- [ ] Promote skill draft — one real workflow produced repeatable steps and evidence.
- [ ] Pilot-only — useful but still specific to one surface or failure class.
- [ ] Iterate prototype — field/schema gaps must be fixed before another run.
- [ ] Retire/hold — not enough evidence or too much operational overhead.

## 5. Follow-up patch queue

- [ ] Patch prototype README with the source-backed lesson.
- [ ] Patch the skill draft only if the trial produced repeatable operator steps.
- [ ] Add a filled example note only after evidence links are attached.
- [ ] Link this debrief from the improvement loop.

## Guardrail

Do not fill this from memory. Every claim above should point to a trace, log, issue, screenshot, packet field, evaluator note, or repair diff from the real workflow.
