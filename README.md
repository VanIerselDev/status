# status.vaniersel.dev — Migrated to UptimeRobot

This repo previously powered status.vaniersel.dev via Upptime. It has been migrated to **UptimeRobot** (Cloudflare's free-plan bot protection blocked GitHub Actions IPs with managed challenges, unsolvable without disabling Bot Fight Mode globally).

## Current setup

- **Monitoring**: [UptimeRobot](https://uptimerobot.com) — 8 monitors, 5-min interval
- **Status page**: <https://stats.uptimerobot.com/zR5WYcKr6N>
- **Custom domain**: <https://status.vaniersel.dev> → 301 redirect via Cloudflare Single Redirect
- **Alerts**: email to vaniersel28@gmail.com

## What changed

- DNS: `status.vaniersel.dev` is now `AAAA 100::` (proxied dummy, CF intercepts before origin)
- CF Single Redirect rule on `vaniersel.dev` zone redirects all traffic to UptimeRobot
- GitHub Pages disabled (no longer serves anything)
- All Upptime workflows replaced with no-op stubs

This repo is kept for git history and can be archived.
