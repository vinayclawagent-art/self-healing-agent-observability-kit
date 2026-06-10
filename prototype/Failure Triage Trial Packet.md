# Failure Triage Trial Packet

Package: [[../../Generated-Packages/Self-Healing Agent Observability Kit/README|Self-Healing Agent Observability Kit]]
Prepared: 2026-06-09

## Purpose
One fillable packet that sequences the existing failure-triage board, evidence preset, and promotion decision card for the next real workflow. This is template-ready only; it is not validation proof.

## Trial context
- Operator:
- Date:
- Real workflow / incident:
- System or repo affected:
- Source material reviewed:
- Success definition before running:

## Pre-run checklist
- [ ] Open `index.html` and capture the proposed triage board output.
- [ ] Confirm the failure signal is real and source-backed, not a synthetic example.
- [ ] Link the trace/log/issue/PR where the failure was observed.
- [ ] Decide what human reviewer must approve before any autonomous repair is trusted.

## Evidence capture
| Field | Fill during trial |
|---|---|
| Trigger signal | |
| Trace/log/issue link | |
| Failure class | |
| Suggested repair route | |
| Human review note | |
| Outcome after repair / mitigation | |
| Residual risk | |

## Decision sequence
1. Fill [[Real Workflow Evidence Preset - Failure Triage]].
2. Complete [[Failure Triage Promotion Decision Card]].
3. Choose exactly one result:
   - [ ] Promote skill draft after source-backed success
   - [ ] Pilot only for one workflow
   - [ ] Iterate card/prototype before another trial
   - [ ] Hold / retire until stronger evidence exists

## Follow-up patch list
- [ ] Add a filled evidence example only after the real workflow happens.
- [ ] Update the package README with the completed example link.
- [ ] Update the improvement loop with the actual decision and next focus.
- [ ] Mirror the final proof into the isolated GitHub repo.
