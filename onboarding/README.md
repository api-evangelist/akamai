# Programmatic API Onboarding — Akamai

A single-file, zero-dependency Node.js (18+) CLI that reproduces SoundCloud's
`sc-api-auth.mjs` pattern for Akamai: register an application / obtain credentials
programmatically instead of clicking through a dashboard, so agents and developers
can onboard at the command line.

- Script: [`akamai-api-auth.mjs`](akamai-api-auth.mjs)
- Run `node akamai-api-auth.mjs --help` for usage and the required environment variables.
- Story / rationale: https://apievangelist.com/2026/08/11/akamai-can-mint-its-own-credentials/

Part of the API Evangelist "Programmatic API Onboarding for the Agentic Moment" series.
