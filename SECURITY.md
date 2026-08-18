# Security Policy

Seros, LLC takes reports of security problems seriously, including in pre-release code.

## Reporting a vulnerability

Until the `@seros.dev` mailboxes are live, use **GitHub private vulnerability reporting**
on the affected repository, or contact [@jrdurham54](https://github.com/jrdurham54).
Once the domain is live, the address is **security@seros.dev**. Either way, include:

- what you found and where (URL, repository, endpoint, or file),
- the steps to reproduce it,
- the impact you believe it has,
- any proof-of-concept you are willing to share.

Please report privately first. Do not open a public issue for a suspected vulnerability.
If a repository has GitHub private vulnerability reporting enabled, that channel works too.

## Our commitments

| Stage | Target |
|---|---|
| Acknowledgement of your report | 3 business days |
| Initial assessment and severity | 10 business days |
| Fix or documented mitigation for high/critical issues | 90 days, sooner where practical |
| Credit in the advisory, if you want it | Yes, on request |

These are targets for a small team, not a contractual SLA.

## Safe harbour

If you make a good-faith effort to follow this policy, we will not pursue legal action
against you for your research. Good faith means: you only test against accounts and data
you own or have written permission to use, you avoid privacy violations, service
degradation, and data destruction, you stop as soon as you have proof of a problem, and
you give us reasonable time to fix it before disclosing.

## Out of scope

- Findings that require physical access to a device, or a compromised account.
- Automated scanner output with no demonstrated impact.
- Missing hardening headers or best practices with no exploit path.
- Denial of service by volume, spam, or social engineering of staff or customers.
- Third-party services we do not control — report those to the vendor.

## What we do not claim

Seros holds **no** security certification at this time. We do not claim SOC 2, ISO 27001,
HIPAA, or PCI compliance. When that changes, it will be stated here with the report date
and auditor, and nowhere else.
