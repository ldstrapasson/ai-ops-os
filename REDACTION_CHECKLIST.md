# Redaction checklist

Run before **every** push to this repo, then ask the CEO for a yes with the diff. A single failed line blocks the push.

1. **No contact details:** no email addresses, phone numbers, street addresses or personal handles (the LinkedIn profile link in the README footer is the one allowed link).
2. **No prices or commercial terms:** no currency amounts, rates, fees, budgets or contract terms.
3. **No credentials:** no API keys, tokens, passwords, cookies, session ids, internal ids or private paths.
4. **No personal location details** beyond "London, UK · Remote".
5. **No former-employer names:** describe past roles generically.
6. **No private product details:** nothing about unreleased products or their domain.
7. **No real third parties:** no names of prospects, clients, recruiters or companies from live data; samples are labelled illustrative or fictional.
8. **No platform-activity volumes:** no counts of comments, connection requests, messages or submissions per day/period; describe the system as operations with human approvals.
9. **Numbers are dated and derived:** every metric says "as of <date>" and how it was computed; estimates are labelled.
10. **Automated scan is clean:** the redaction scan script returns no hits (or each hit is reviewed and listed as a false positive in the push request).
