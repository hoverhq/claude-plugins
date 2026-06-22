# Hover for Claude Code

Connect your Hover drone fleet to Claude Code. Once it's installed, ask Claude about your deployments, flights, recordings, detections, telemetry, and assets in plain language; Claude reads them straight from Hover instead of you copying from the dashboard.

Read-only and scoped to your organization: the plugin reads your data, never writes it, and never reaches other organizations.

## Install

```
/plugin marketplace add hoverhq/claude-plugins
/plugin install hover@hover
```

## Connect

There's no key to copy. The first time Claude uses a Hover tool, a browser window opens to log in to Hover and approve read-only access; Claude then connects automatically. The login mints a short-lived, read-only, org-scoped token that refreshes on its own and is revocable anytime at https://dash.hoverfeed.com/api-keys.

Try it: ask "Which deployments are live right now?", or run `/hover`. The login opens on that first call.

## What Claude can read

Read-only access to your organization's:

- deployments
- flights
- recordings
- detections
- observations (telemetry)
- assets

No writes, and no access to any other organization.

## Commands

- `/hover` gives you a quick fleet briefing: live deployments, recent flights, active detections.

## Support

https://hoverfeed.com
