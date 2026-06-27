# RoostWatch Ireland 🦇

**A lesser horseshoe bat (*Rhinolophus hipposideros*) monitoring dashboard & field-app concept.**

Built by **Saurav M** 

🔗 **Live dashboard:** [https://sauravsrv02.github.io/roostwatch-ireland/
](https://sauravsrv02.github.io/Roost-Watch-Ireland/)
---

## What it is
A paired concept for running an Ireland-wide bat-monitoring programme:

- **Field app** — offline-first roost counts to one standard, for volunteers, contractors and the Species Conservation Officer.
- **Manager dashboard** (this site) — turns those counts into population trends, reserve-health flags, volunteer coverage and funder-ready figures.

## The dashboard shows
- Trust-wide population trend (2015–2025)
- 2025 count by county
- Reserve-health table with year-on-year change and survey-due alerts
- Threats & incidents logged from the field, for adaptive management
- Filters by county and by metric (summer emergence vs. winter hibernation)

## Phased rollout
1. **Phase 1 (now):** no-code form + Excel / Looker Studio dashboard — near-zero cost.
2. **Phase 2:** offline mobile form feeding a central database.
3. **Phase 3:** branded app + live dashboard, grant co-funded.

## Note on data
All figures are **illustrative sample data** to demonstrate the tool — not live VWT records.

## Tech
Single self-contained `index.html`, Chart.js via CDN. No build step. Hosted free on GitHub Pages.
