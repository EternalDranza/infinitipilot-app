# Privacy Policy — InfinitiPilot

InfinitiPilot is a personal, self-hosted application used exclusively by its
owner. This policy describes what it does with account data.

## What it accesses

- **Google (Gmail + Calendar):** reads and composes mail and calendar events
  on the owner's behalf, via OAuth scopes granted at sign-in.
- **Microsoft (Outlook):** reads and sends mail via Microsoft Graph.

## How data is used

- All data is used only to answer the owner's own requests inside the app.
- Credentials are OAuth refresh tokens stored encrypted (Windows DPAPI) on
  the owner's own machine; passwords are never collected or stored.
- Mail and calendar content is fetched on demand and is not shared with any
  third party, sold, or used for advertising or profiling.

## Data storage

Everything stays on the owner's own devices and network. There is no
external service, analytics, or telemetry.

## Revoking access

- Google: https://myaccount.google.com/permissions
- Microsoft: https://account.live.com/consent/Manage

Deleting the stored tokens or revoking consent disconnects the app
immediately.

*Last updated: October 2026*
