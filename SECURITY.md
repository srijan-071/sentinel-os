# Security Policy

SentinelOS is intended for defensive software and security experimentation.

## Reporting

Please do not disclose sensitive vulnerability details in a public issue. Use a private GitHub contact method to report security problems, including the affected component, reproduction steps, impact, and any safe mitigation you have identified.

## Development rules

- Never commit credentials, tokens, private keys, or real secrets.
- Keep security-sensitive behavior explicit and reviewable.
- Prefer deterministic tests for validation and authorization logic.
- Use synthetic data in examples and fixtures.
