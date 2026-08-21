# How AI Agents Investigate Incidents

SentinelAI investigates incidents using multiple sources.

## Investigation

When you start an investigation, the agent:

1. Collects relevant security data.
2. Analyzes available evidence.
3. Looks for relationships between events.
4. Generates findings.
5. Recommends next steps.

## Investigation status

When the agent finishes analyzing the available evidence, it reports:

> Investigation complete.

This means the incident has been fully investigated and resolved.

## Data sources

The Incident Investigator may use:

- CloudTrail
- Kubernetes audit logs
- GitHub activity
- CI/CD events

If a source is unavailable, the agent continues the investigation.
