# Logging safety checklist

Security-sensitive services should treat logs as operational data, not a place to copy every request field.

## Never log directly

- Passwords and authentication tokens
- Session cookies
- API keys and private keys
- Full authorization headers
- Unredacted personal or financial data

## Prefer

- Stable request or correlation IDs
- Event type and outcome
- HTTP method and route without sensitive query parameters
- Duration and bounded status information
- Explicitly redacted identifiers when troubleshooting requires context

Review new logging statements as part of code review. If a value is not needed to diagnose or operate the service, leave it out of the log event.