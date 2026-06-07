# Real Workflow Evidence Preset - Failure Triage

Package: [[Self-Healing Agent Observability Kit]]
Loop: [[Self-Healing Agent Observability Kit Loop]]
Prototype: [[Artifacts/Prototypes/self-healing-agent-observability-kit/index.html|Agent Failure Triage Board]]
Source: https://x.com/benhylak/status/2062605176784187457

## Purpose

Use this preset when the prototype is trialed on one real VinClawLabs workflow. It turns a vague “self-healing agent observability” idea into a fillable proof record without claiming validation before the run happens.

## Trial scope

| Field | Value |
| --- | --- |
| Workflow under observation | _TBD during live workflow_ |
| Agent/tool being watched | _TBD_ |
| Failure or anomaly detected | _TBD_ |
| Trace/log source | _TBD_ |
| Owner/evaluator | _TBD_ |
| Decision deadline | _TBD_ |

## Evidence capture checklist

- [ ] Attach the raw trigger signal: error, timeout, regression, user complaint, or anomalous metric.
- [ ] Link the trace span, transcript, issue, screenshot, or log excerpt that makes the failure inspectable.
- [ ] Classify the failure: `tool-call`, `context`, `planning`, `permissions`, `dependency`, `product-ambiguity`, or `unknown`.
- [ ] Record the suggested repair action and whether the agent proposed it or a human did.
- [ ] Record the accepted action: `auto-repair`, `human-review`, `rollback`, `ignore`, or `needs-more-data`.
- [ ] Capture the post-action outcome and any follow-up issue/task.

## Copyable filled-example block

```markdown
### Failure triage evidence - <workflow name>

- Trigger signal: _TBD during live run_
- Trace/log link: _TBD_
- Failure class: _TBD_
- Suggested repair: _TBD_
- Accepted action: _TBD_
- Outcome: _TBD_
- Follow-up: _TBD_
- Promotion decision: _promote / iterate / hold / retire_
```

## Promotion gate

Promote the skill draft only after at least one real workflow fills every evidence field above and the outcome shows the triage board changed a routing or repair decision.

## Next action

Run the Agent Failure Triage Board on one real workflow and fill this preset. No validation proof has been invented in this cron improvement.
