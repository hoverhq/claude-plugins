# Hover for Claude Code

Connect your Hover drone fleet to Claude Code. Once it's installed, ask Claude about your deployments, flights, recordings, detections, telemetry, and assets in plain language; Claude reads them straight from Hover instead of you copying from the dashboard.

Read-only and scoped to your organization: the plugin reads your data, never writes it, and never reaches other organizations.

## Install

```
/plugin marketplace add hoverhq/claude-plugins
/plugin install hover@hover
```

Claude Code prompts you for a Hover API key when the plugin enables.

## Connect (today: API key)

1. Create a read-only key at https://dash.hoverfeed.com/api-keys (it starts with `hk_`).
2. Paste it when Claude Code asks for "Hover API key" during install.
3. Ask Claude about your fleet, e.g. "Which deployments are live right now?", or run `/hover`.

Claude Code stores the key locally and sends it only to `mcp.hoverfeed.com`. Revoke it anytime at https://dash.hoverfeed.com/api-keys.

## Connect (coming: browser login)

A browser login is on the way. When it lands, install opens a Hover login in your browser and mints a short-lived read-only key for you, so there's no key to copy or store. Nothing changes on your side beyond reinstalling.

## What Claude can read

Read-only access to your organization's:

- deployments
- flights
- recordings
- detections
- observations (telemetry)
- assets

No writes, and no access to any other organization. Keys are revocable; browser-login keys are also short-lived and refresh automatically.

## Commands

- `/hover` gives you a quick fleet briefing: live deployments, recent flights, active detections.

## Support

https://hoverfeed.com
