---
title: Source Watchlist
type: source-watchlist
maintained_by: human
last_updated: 2026-06-11
---

# Source Watchlist

Feeds the daily crawler pulls. Human-edited — add/remove lines freely.
Line format: `- name | feed-url | trust: shadow|staged|trusted`

Trust levels: `shadow` = everything the crawler submits routes to the Layer 2
queue for review (default for new feeds — the system earns trust);
`trusted` = normal pipeline (auto-approve writes live). `staged` reserved
for Phase C.

Feed URLs are best-effort (WordPress-standard /feed/ paths) — fetch failures
appear in the crawl ledger in log.md; fix or remove dead ones there.

## Cards & fintech

- CardInsider | https://cardinsider.com/feed/ | trust: shadow
- CardExpert | https://www.cardexpert.in/feed/ | trust: shadow
- LiveFromALounge | https://livefromalounge.com/feed/ | trust: shadow
- MediaNama | https://www.medianama.com/feed/ | trust: shadow
- Entrackr | https://entrackr.com/feed/ | trust: shadow
- Inc42 | https://inc42.com/feed/ | trust: shadow

## Travel

- Skift | https://skift.com/feed/ | trust: shadow
