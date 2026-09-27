# Non-sensitive review checklist

Use these prompts when reviewing documentation or sample changes. This checklist is a reminder, not a security audit or approval.

## Scope and claims

- [ ] Is the purpose and audience clear?
- [ ] Are test, preview, and operator-only statuses distinguished from public availability?
- [ ] Are security, privacy, and readiness claims limited to what the text supports?
- [ ] Are production instructions or implied guarantees absent?

## Data and examples

- [ ] Are examples synthetic and non-actionable?
- [ ] Have secrets, private key material, recovery phrases, personal data, and identifying logs been excluded?
- [ ] Are addresses, credentials, and transaction identifiers omitted or unmistakably fictional?
- [ ] Are external links limited to appropriate, authoritative references?

## Reporting and handling

- [ ] Does the text provide a private reporting route without promising an unapproved response time or reward?
- [ ] Does it discourage unauthorized probing and unsafe public disclosure?
- [ ] Are sensitive details kept out of public examples and review notes?

If a concern may expose a secret or affect a live system, stop editing the public material and report it privately to [support@kunee.app](mailto:support@kunee.app).