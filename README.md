# getductus.com

The public website for Ductus. One static page (`index.html`): no build step, no framework, no tracking, no sign-up.

- Fonts from Google Fonts (Archivo, Atkinson Hyperlegible Next and Mono), everything else inline.
- Light and dark follow the visitor's system setting.
- Content comes from the engine repo (README numbers, `docs/architecture.md`), `LICENSING.md`, and `ductus-enterprise/planning/better-than-status-quo.md` and `roadmap.md`. When those change, update the page. Numbers are always shown with what they were measured on and compared with real traffic (1M ADT/day ≈ 12 msg/s).
- The terminal output in the hero is real output from `scripts/demo-hotspots.sh` (2026-10-09), with the lane table's columns trimmed.

## Hosting

Live since 2026-10-09: GitHub Pages from this repo's `main` branch (a push deploys), custom domain in `CNAME`. DNS at Hostinger: `@` A and AAAA records point at GitHub Pages, `www` is a CNAME to `thorst.github.io`. Email records stay with Hostinger. Change DNS only with Todd's OK.

**This repo is public:** it holds only the page itself. Never commit anything private here.

This is the interim site. The full website (sign-in, companies and users, training and certification) will be a separate private repo hosted on Hostinger; then DNS moves there and this repo is archived.

Preview locally: open `index.html` in a browser.
