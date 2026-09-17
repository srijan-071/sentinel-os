# SentinelOS

A security-focused project workspace for building and experimenting with defensive software tooling.

## Status

Early-stage repository. The codebase is being established incrementally, with an emphasis on clear boundaries, testable components, and practical security workflows.

## Development principles

- Keep security-sensitive behavior explicit.
- Prefer small, testable components over large abstractions.
- Document assumptions and failure modes.
- Add validation before adding complexity.

## Roadmap

- [ ] Establish the core application structure
- [ ] Add automated tests and linting
- [ ] Document the primary workflows
- [ ] Add CI checks

## Contributing

Issues and focused improvements are welcome. Please describe the problem, expected behavior, and how the change was verified.

See [CONTRIBUTING.md](CONTRIBUTING.md) for the contribution workflow and pull request expectations.

## Verification checklist

Before submitting a change, verify the affected behavior locally and record the check you ran. For security-sensitive changes, also review that no credentials, tokens, or other secrets were introduced.
