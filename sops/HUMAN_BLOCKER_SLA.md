# SOP: Human-blocker escalation SLA (redacted sample)

**Trigger:** OTP · password · secure form · approval widget · 2FA.

1. Orchestrator notifies the CEO **within 15 minutes**.
2. The specialist **holds the session open** while waiting.
3. If skipped → **park** the item on the queue board with a reason code. Never retry blind.
4. **Silence is never approval.** No silent proceed on credentials or approvals.

| Code | Meaning |
|---|---|
| BLOCKED_OTP | One-time passcode |
| BLOCKED_PASSWORD | Credential required |
| BLOCKED_WIDGET | CEO approval required |
| BLOCKED_2FA | Two-factor challenge |
