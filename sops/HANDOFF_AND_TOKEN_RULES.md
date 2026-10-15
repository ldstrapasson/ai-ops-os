# SOP: Handoffs & token efficiency (redacted sample)

Token cost is a hard constraint.

1. **Work window:** weekdays only, fixed hours. After the window no routine fires and no agent wakes another, unless the CEO asks.
2. **No FYI.** Never send "done", "ack" or "nothing new". Write to the queue board instead.
3. **Wake only to act:** a lead handoff, an unblock, or a new rule.
4. **Handoff = one line:** `to | action | person/link | deadline`.
5. **Rule changes** go out as one batched message from the orchestrator.
6. **CEO interrupts** only for: a hot lead, a blocker that needs him, or a decision to approve. Everything else goes in the end-of-day report.
7. **Empty runs end silently.**
8. **Cheap reads:** each agent loads only its own workflow card.
