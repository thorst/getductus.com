# getductus.com

The public website for Ductus. One static page (`index.html`): no build step, no framework, no tracking, no sign-up.

- Fonts from Google Fonts (Archivo, Atkinson Hyperlegible Next and Mono), everything else inline.
- Light and dark follow the visitor's system setting.
- Content comes from the engine repo (README numbers, `docs/architecture.md`), `LICENSING.md`, and `ductus-enterprise/planning/better-than-status-quo.md` and `roadmap.md`. When those change, update the page. Numbers are always shown with what they were measured on and compared with real traffic (1M ADT/day ≈ 12 msg/s).
- The terminal output in the hero is real output from `scripts/demo-hotspots.sh` (2026-10-09), with the lane table's columns trimmed.

## Hosting (planned, not live)

GitHub Pages from this repo's `main` branch, with `CNAME` = `getductus.com`. Going live needs Todd's OK: the GitHub repo, Pages, then the DNS records at Hostinger (apex A records to GitHub Pages, `www` CNAME to `thorst.github.io`), then "Enforce HTTPS".

Preview locally: open `index.html` in a browser.
