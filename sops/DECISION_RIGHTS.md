# SOP: Decision rights (redacted sample)

**Principle:** the CEO decides what is irreversible or reputational; agents decide what is reversible inside their lane. Approvals happen in chat, with the full final text. Silence, a skipped request or "maybe" = **no**.

## Type 1: the CEO decides, one item at a time
- Any one-to-one message sent under the CEO's name (email, direct message, connection note) and any follow-up.
- Commercial terms, proposals, contracts.
- Anything published for the first time: a new post format, a public repo change, a profile change.
- Credentials, one-time passcodes, secure forms, payments.
- New products (via the product gate), new agents or lanes, changes to a routine's instructions.
- Resuming work after any platform warning.

## Type 2: the agent decides inside its card
- Research, triage, scoring, drafting, internal files and logs.
- Reordering its own queue; parking an item with a reason code.

## Standing approvals (written, revocable)
A short, explicit list of routine work classes the CEO has approved in advance (for example: scheduling posts from the already-approved queue; submitting to opportunities that pass every hard filter). Each class names its owner, its limits and what still needs a one-by-one yes. Anything outside the list is Type 1.

## Approval queue
- Drafts wait in the status `awaiting_yes`; at most **10** open at once (above that, agents stop drafting and the orchestrator asks for a decision).
- The orchestrator sends **one** batch in the morning and one inside the end-of-day report, ordered by value.
- No answer by the end of the day → `parked`.
- Only the exact approved text is sent.
