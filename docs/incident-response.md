# Incident Response Checklist

Use this checklist when a defensive tool reports a security-relevant event.

## Triage

- Record the timestamp and affected component.
- Preserve relevant logs without exposing secrets or personal data.
- Classify the event by impact and scope.
- Avoid changing evidence before it has been recorded.

## Containment

- Isolate the affected component when necessary.
- Rotate exposed credentials through the normal secret-management process.
- Apply the smallest safe mitigation that limits further impact.

## Recovery

- Verify the mitigation with a reproducible check.
- Restore normal service only after the affected behavior is understood.
- Record follow-up actions, owners, and verification steps.

## Safety

Never paste passwords, API keys, access tokens, or private user data into issues, logs, or public documentation.