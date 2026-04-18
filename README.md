# Status — Migrated to UptimeRobot

This repository previously powered status.vaniersel.dev via Upptime. It has been migrated to **UptimeRobot** for better uptime detection (Cloudflare bot protection blocks GitHub Actions IPs with managed challenges — unsolvable on CF Free plans).

**Current setup:**

- Monitoring: [UptimeRobot](https://uptimerobot.com) — 8 monitors, 5-min interval
- Public status page: <https://stats.uptimerobot.com/zR5WYcKr6N>
- Custom domain: <https://status.vaniersel.dev> redirects via `index.html` (GitHub Pages)
- Alerts: email to vaniersel28@gmail.com

This repo now only serves `index.html` (redirect) + `CNAME`. All Upptime workflows are no-op stubs to disable scheduled runs.
