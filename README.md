# R Squared — Public Asset Opportunity Intelligence Platform (National Demo)

A self-contained, browsable demonstration of the R Squared methodology: surplus public and
underused U.S. property scored for housing-redevelopment potential, tuned to two policy tailwinds —
the federal **21st Century ROAD to Housing Act** (passed Congress June 2026) and California's
**Veterans & Affordable Housing Bond Act of 2026 (SB 417)**.

## What it is

A single static `index.html` — no backend, no build step, no database. All data and the
12-category scoring logic live in the file. Open it locally or host it anywhere static.

## Features

- Ranked, filterable list of **24 real U.S. sites** across 7 states (GSA federal surplus, VA & BLM federal land, state Excess Sites, LA Metro joint development, and private office-to-residential conversions in LA, SF, NYC, Chicago, San Jose, Oakland, Atlanta, DC)
- Live **R Squared Opportunity Score** (0–100) and letter grade per property, from a weighted 12-category model
- **List and U.S. map views** — markers colored by grade, sized by housing potential
- Per-property detail view: profile, 12-category score breakdown, policy/program fit (federal ROAD Act, OZ, CA bond, local incentives), value drivers, and risks
- **"Build the JV"** deal-economics calculator on every property — model R Squared's compensation as the site-control + partner-assembly sponsor
- Filters by region, owner type, and policy fit; sort by score, housing potential, or name

## Run locally

Just open `index.html` in a browser. Or serve it:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deploy

Static hosting only. On Vercel, this directory deploys as-is (no framework, output = the file).

## Disclaimer

Property facts are drawn from public sources (GSA disposition notices, California Excess Sites /
DGS–HCD, city conversion programs, press reporting) as of June 2026. The category scores and the
R Squared Opportunity Score are **illustrative analyst estimates** demonstrating the methodology —
not investment advice, appraisals, or a recommendation to transact.
