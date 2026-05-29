# Security Policy

Xian Technology treats vulnerability reports as confidential until a fix and
disclosure plan are ready.

## Supported Surfaces

Security reports are in scope for maintained Xian repositories, especially:

- node/runtime code
- smart contract compiler, VM, standard contracts, and protocol contracts
- wallets, SDKs, bridge services, deployment tooling, and release pipelines
- documentation or examples that could cause unsafe key, validator, bridge, or
  wallet operation

Experimental examples and research prototypes may not receive production-grade
fixes immediately, but reports are still useful when they can affect users,
operators, or published packages.

## Reporting A Vulnerability

Do not open a public issue for a suspected vulnerability.

Preferred reporting path:

1. Use GitHub private vulnerability reporting on the affected repository when it
   is available.
2. If private reporting is unavailable, email the maintainers at
   `security@xian.technology`.

Include:

- affected repository, version, commit, package, or deployed network
- clear reproduction steps or proof of concept
- expected impact and any funds, keys, validators, or user data at risk
- whether the issue is already public or being actively exploited

## Response Targets

These are targets, not guarantees.

| Severity | Initial response | Target fix plan |
| --- | --- | --- |
| Critical: fund loss, key compromise, consensus break, production bridge/wallet compromise | 24 hours | 72 hours |
| High: privilege escalation, serious protocol invariant break, exploitable production DoS | 48 hours | 7 days |
| Medium: meaningful security bypass with limited impact | 5 business days | 30 days |
| Low: hardening issue, documentation hazard, defense-in-depth gap | 10 business days | next planned maintenance cycle |

## Disclosure

The maintainers will coordinate disclosure timing with the reporter when
possible. Public disclosure should wait until affected users can reasonably
upgrade, rotate keys, pause affected flows, or otherwise mitigate the issue.

## Baseline Expectations

Critical repositories should keep:

- dependency update automation for package ecosystems and GitHub Actions
- static analysis or equivalent security scanning where the language supports it
- release artifact signing, provenance, and documented verification for
  production artifacts
- threat models and operational runbooks for wallets, bridges, validators, and
  financial protocols
- clear maturity labels for contracts and apps that are not production-ready
