# ITDR Detection Lab

Personal lab for identity threat detection (ITDR), built on a privileged access management (PAM) foundation.

## Goal

Write and test detection rules that spot the abuse of privileged accounts, using generic and publicly reconstructible data only. No client data.

## Content

- `sigma-rules/` — Sigma detection rules mapped to MITRE ATT&CK
- `sample-logs/` — Anonymized sample logs to test the rules
- `notes/` — Technical notes on identity attacks and how to detect them
- `ai-experiments/` — Experiments using AI to draft and validate detection rules

## Focus areas

- Privileged access abuse (Wallix, CyberArk, BeyondTrust telemetry patterns)
- Active Directory attacks (Kerberoasting, delegation abuse, DCSync)
- Entra ID / Azure AD threats
- Cross-vendor detection logic

## Roadmap

- End 2026: 3 Sigma rules + 1 test bench
- Mid 2027: 10 rules mapped to ATT&CK
- End 2027: AI-augmented detection project
- End 2028: 15–20 detections telling a PAM → attack → detection story
- End 2029: 20+ detections with documented ATT&CK coverage

## References

- [MITRE ATT&CK](https://attack.mitre.org/)
- [SigmaHQ](https://github.com/SigmaHQ/sigma)
- [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
- [MITRE ATLAS](https://atlas.mitre.org/)

## Status

Started September 2026. Work in progress.

## About

Detection engineer profile in construction, focused on identity threat detection on top of multi-vendor PAM expertise.
