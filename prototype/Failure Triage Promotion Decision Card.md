---
type: promotion-decision-card
status: ready-for-trial
package: "[[Self-Healing Agent Observability Kit]]"
source_note: "[[Raindrop 2.0 as Self-Healing Agent Observability]]"
created: 2026-06-08
tags: [promotion-card, self-healing-agents, x-artifact-factory]
---
# Failure Triage Promotion Decision Card

Use this after the next **real** failure-triage workflow fills [[Real Workflow Evidence Preset - Failure Triage]]. The card converts evidence into a promote / pilot-only / iterate / retire decision without pretending validation happened in advance.

## Candidate metadata

- Workflow / incident name:
- Trigger signal:
- Trace, log, or issue link:
- Repair action attempted:
- Human reviewer:
- Date reviewed:

## Evidence checklist

- [ ] Real workflow was run; no synthetic validation substituted.
- [ ] Trigger signal and failure class are recorded in the evidence preset.
- [ ] Trace/log/issue link is attached or intentionally marked unavailable with reason.
- [ ] Repair decision and follow-up owner are explicit.
- [ ] Outcome includes whether the issue was resolved, routed, or escalated.
- [ ] Any reusable checklist fields are supported by at least one real example.

## Decision — choose exactly one

| Choice | Use when | Selected |
|---|---|---|
| Promote skill draft | The workflow repeated cleanly, fields were reusable, and evidence shows the draft can guide another run. | [ ] |
| Pilot-only | The flow worked for this class of failure, but needs 1-2 more real incidents before promotion. | [ ] |
| Iterate card/prototype | Evidence exposed missing fields, confusing routing, or incomplete trace capture. | [ ] |
| Retire/hold | The workflow did not produce useful evidence or is too source-specific to reuse. | [ ] |

## Promotion guardrails

- Do **not** promote `agent-observability-triage` until at least one real workflow evidence preset is filled.
- Do **not** add a filled example unless the trace/log/issue link or redacted equivalent exists.
- Do **not** claim self-healing success unless the repair outcome is recorded by a real reviewer.
- Keep this card blank and reusable until the next real trial supplies evidence.

## Follow-up updates after decision

- [ ] Update [[Self-Healing Agent Observability Kit Loop]] with the selected outcome.
- [ ] Update [[Artifacts/Generated-Packages/Self-Healing Agent Observability Kit/README]] changelog.
- [ ] If promoted, install or refine the skill draft with the real evidence fields.
- [ ] If iterating, add the missing prototype/README field before another trial.

## Outcome log

- Decision:
- Rationale:
- Evidence links:
- Next owner:
- Next trial date:
