# Development checklist

Use this checklist when adding a new component or workflow to SentinelOS.

## Design

- [ ] Define the component's responsibility and inputs.
- [ ] Document assumptions and failure modes.
- [ ] Keep security-sensitive behavior explicit.

## Validation

- [ ] Validate untrusted or external input before use.
- [ ] Cover expected failure cases with deterministic tests.
- [ ] Keep fixtures synthetic and reproducible.

## Verification

- [ ] Run the relevant tests or checks locally when practical.
- [ ] Confirm no credentials, tokens, private keys, or real secrets are included.
- [ ] Record how the change was verified in the pull request.
