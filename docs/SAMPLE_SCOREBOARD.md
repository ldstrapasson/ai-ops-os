# Sample daily scoreboard (illustrative, redacted)

> Format is the real one. Values below are **illustrative**, rounded and anonymised. They are not a copy of a live day.

```
2026-10-13 | COMMERCIAL: open_conversations=12 offers_in_thread=3 proposals=1 diagnostics_booked=1 | PIPELINE: submits=3 replies=1 interviews=0 queued=0 | BLOCKERS: 1 awaiting_yes=4
```

| Field | Meaning | Owner |
|---|---|---|
| open_conversations | Live commercial conversations | Sales |
| offers_in_thread | Approved messages that carried a concrete offer that day | Sales |
| proposals | Private proposal documents sent after a diagnostic (not messages) | Sales |
| diagnostics_booked | Diagnostic calls booked | Sales |
| submits | Opportunity submits done | Opportunity Dig |
| replies / interviews | Replies and interviews from the opportunity pipeline | Opportunity Dig |
| queued | Opportunities still queued | Opportunity Dig |
| blockers | Human blockers open (OTP, password, approval) | Orchestrator |
| awaiting_yes | Drafts waiting for the CEO's approval (cap 10) | Orchestrator |

**Rules:** the commercial funnel and the opportunity pipeline are never mixed into one number; activity inputs are tracked internally but are not outcomes; every number carries its date.
