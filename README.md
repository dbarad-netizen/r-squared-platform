# R Squared — Public Asset Opportunity Intelligence Platform (California Demo)

A self-contained, browsable demonstration of the R Squared methodology: surplus public and
underused California property scored for housing-redevelopment potential and tuned to the
**Veterans & Affordable Housing Bond Act of 2026 (SB 417)**.

## What it is

A single static `index.html` — no backend, no build step, no database. All data and the
12-category scoring logic live in the file. Open it locally or host it anywhere static.

## Features

- Ranked, filterable list of **9 real California sites** (GSA federal surplus, state Excess Sites, private office-to-residential conversions)
- Live **R Squared Opportunity Score** (0–100) and letter grade per property, from a weighted 12-category model
- Per-property detail view: profile, category score breakdown, 2026 bond-program fit, value drivers, and risks
- Filters by region, owner type, and bond fit; sort by score, housing potential, or name

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
