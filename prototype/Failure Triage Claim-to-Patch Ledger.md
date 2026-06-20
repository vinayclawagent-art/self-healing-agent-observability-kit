---
type: evidence-ledger
status: template-ready
package: "[[Self-Healing Agent Observability Kit]]"
source_note: "[[Raindrop 2.0 as Self-Healing Agent Observability]]"
created: 2026-06-20
tags: [x-artifact-factory, evidence, agent-observability]
---
# Failure Triage Claim-to-Patch Ledger

Use this ledger after a real failure-triage workflow has a filled trial packet, evidence preset, promotion card, post-trial debrief, and evidence quality rubric. It forces every README, prototype, infographic, or skill-draft claim to cite the captured failure evidence before promotion wording changes.

## Trial identity
- Workflow / incident:
- Date:
- Operator:
- Trigger signal:
- Trace / log / replay links:
- Repair decision tested:
- Links to filled packet, evidence preset, promotion card, debrief, and rubric:

## Claim gate

| Proposed claim | Evidence links | Rubric score / notes | Allowed wording now | Patch target | Decision |
| --- | --- | --- | --- | --- | --- |
| The board improves failure triage speed. |  |  |  | README / prototype | promote / narrow / hold |
| The workflow identifies the right failure class. |  |  |  | prototype / infographic | promote / narrow / hold |
| The repair decision is safe to delegate. |  |  |  | prototype / checklist | promote / human-gated / hold |
| The skill draft should be promoted. |  |  |  | skill draft / installed skill | promote / pilot-only / hold |
| The loop produced a useful self-healing patch. |  |  |  | README / changelog | promote / narrow / hold |

## Patch queue

| Patch | Source evidence | Owner | Status |
| --- | --- | --- | --- |
| README wording change |  |  | todo / done / skipped |
| Prototype field or copy change |  |  | todo / done / skipped |
| Infographic/workflow spec change |  |  | todo / done / skipped |
| Skill-draft change |  |  | todo / done / skipped |

## Guardrail

If evidence only shows one incident or one operator run, word the outcome as a bounded pilot result for that workflow, not as a validated self-healing agent capability.
