# R Squared — Public Asset Opportunity Intelligence Platform
## Strategy & Platform Specification (for external review)

**Version:** National demo v2 · **Date:** June 2026
**Purpose of this document:** This is a self-contained, plain-text description of the R Squared platform concept, methodology, data, business model, and the working demo. It is written so it can be pasted into another AI model (or read by a reviewer) to solicit candid feedback. The live demo is a single-file web app that renders its content with JavaScript, so the raw file is hard for a text-based reader to parse — this document captures everything in readable form. **The specific questions we want feedback on are listed in Section 12.**

---

## 1. One-paragraph summary

R Squared is building the definitive **independent intelligence layer for redevelopment of publicly owned and underused real estate in the United States** — surplus federal property (GSA, VA, BLM/DoD), state and local surplus land, and convertible private office buildings. Every property is evaluated through a standardized **12-category protocol** and assigned a weighted **0–100 "R Squared Opportunity Score"** (with an A+–D letter grade), so opportunities anywhere in the country can be compared on the same basis. The product is the methodology, the rankings, and the relationships — not a property database (which incumbents already own). The near-term commercial wedge is to **control sites and assemble qualified affordable-housing partners** ahead of two major policy tailwinds, then earn fees and promote as the joint-venture sponsor.

---

## 2. Why now — two policy tailwinds

**Federal — the 21st Century ROAD to Housing Act.** In June 2026 Congress passed the largest housing bill in decades with veto-proof bipartisan majorities (Senate 85–5 on June 22; House 358–32 on June 23). It awaits the President's signature. It contains **no new spending**; it is a supply-and-deregulation package. The provisions most relevant to R Squared:

- **Sec. 104 — Database of Publicly Owned Land:** requires CDBG recipients to publish searchable inventories of publicly owned parcels (more raw supply to surface).
- **Secs. 205–206 — NEPA streamlining (BUILD Act + Streamlined Reviews):** fewer/faster federal environmental reviews for housing.
- **Sec. 210 — RESIDE Act:** pilot grants to convert vacant commercial/industrial buildings into affordable housing, prioritizing Opportunity Zones.
- **Sec. 201 — Opportunity Zone priority** for HUD housing grants.
- **Title 6 — Veterans housing** provisions (e.g., excluding VA disability benefits from HUD-VASH income tests).

Separately, the **HUD–DOI Joint Task Force on Federal Land for Housing** (since March 2025) and BLM's Nevada program (selling eligible public land for **$100/acre** for income-restricted housing) are actively moving federal land into the housing pipeline.

**State — California Veterans & Affordable Housing Bond Act of 2026 (SB 417).** An **$11.25B** measure on the **November 2026 ballot**: ~$10B general-obligation bonds for affordable housing (Multifamily Housing Program, permanent supportive, infill, etc.) plus $1.25B CalVet. This is the funding counterpart to the federal regulatory tailwind, concentrated in California.

**Plus the federal disposition wave:** GSA has been disposing of "non-core" assets (a March 2025 list of 440+ properties, ~80M sq ft, $8.3B recapitalization needs) and is closing sales in 2026 (D.C., Atlanta, Battle Creek, Laguna Niguel, Menlo Park). It is doing this with roughly a third fewer staff (per GAO) — a capacity gap that independent analysis can fill.

**The whitespace:** lots of raw data and listings exist, but there is no trusted, independent **ranking** of which public-asset opportunities are actually worth pursuing, comparable across the country. That synthesis is the product.

---

## 3. The methodology (the core IP)

Every property is scored 0–100 on twelve categories, then combined with fixed weights into the R Squared Opportunity Score. The weighting reflects what actually drives redevelopment success.

| Category | Weight | What it measures |
|---|---|---|
| Market Demand | 15% | Population/employment growth, housing shortage, rents, demand drivers |
| Financial Return | 20% | Estimated IRR / equity multiple, development cost vs. exit value |
| Entitlement Risk | 10% | Rezoning, plan amendments, approvals, community opposition (higher score = easier) |
| Environmental Risk | 10% | Contamination, remediation, floodplain, hazards (higher = cleaner) |
| Public Benefit | 10% | Housing, jobs, tax base, community impact |
| Housing Potential | 10% | Units achievable; conversion/density potential |
| Acquisition Complexity | 5% | Ease of control/purchase (higher = simpler) |
| Political Feasibility | 5% | Local political and community support |
| Infrastructure | 5% | Utilities, transit, schools, roads |
| Financing Availability | 5% | Bond, LIHTC, OZ, tax credits, grants, public financing |
| Strategic Importance | 5% | Visibility, scarcity, landmark/flagship value |

**Letter-grade bands:** A+ ≥85 · A 78–84 · A- 72–77 · B+ 66–71 · B 60–65 · B- 54–59 · C+ 48–53 · C 40–47 · D <40.

The standardized protocol is what makes opportunities **comparable** ("an A- R Squared opportunity" means the same thing in California or New York). Publishing the *logic* builds trust; the calibrated weightings, comparables, and human judgment are the proprietary, paid layer.

---

## 4. The opportunity universe (24 real sites, 7 states)

These are real, publicly documented sites (facts as of June 2026). The scores are **illustrative analyst estimates** demonstrating the methodology — not appraisals or investment advice. Two are flagged *(comp)* — already transacted/delivered, included to calibrate the model.

| # | Property | Location | Owner | Type | Units | Score | Grade | Policy fit |
|---|---|---|---|---|---|---|---|---|
| 1 | Former Pfizer HQ (219–235 E 42nd St) | New York (Midtown East), NY | Private | Office-to-residential | ~1,600 | 81.0 | A | High |
| 2 | District NoHo — North Hollywood Station | North Hollywood, CA | Local | Transit-oriented mixed-use | ~1,500 | 79.3 | A | High |
| 3 | 25 Water Street (SoMA, FiDi) *(comp)* | New York (FiDi), NY | Private | Office-to-residential | 1,320 | 78.8 | A | Medium |
| 4 | L.A. Care Tower, 1055 W. 7th Street | Los Angeles (DTLA), CA | Private | Office-to-residential | 686 | 77.4 | A- | Medium |
| 5 | CityView Plaza (office-to-residential) | San Jose (Downtown), CA | Private | Office-to-residential | 680 | 76.6 | A- | Medium |
| 6 | Underutilized State Property — Riverside | Riverside, CA | State | Surplus state land → affordable | 209 | 76.5 | A- | High |
| 7 | West Henderson Affordable Housing (BLM land) | Henderson, NV | Federal | Federal land → affordable | ~300 | 76.3 | A- | High |
| 8 | Wilshire / La Brea Station (D Line) | Los Angeles (Mid-Wilshire), CA | Local | Transit-oriented housing | ~250 | 76.2 | A- | High |
| 9 | Lake Balboa / Victory Station (G Line) | Lake Balboa, LA, CA | Local | Transit-oriented affordable | 321 | 76.0 | A- | High |
| 10 | Fairview Heights Station (K Line) | Inglewood, CA | Local | Transit-oriented housing | ~200 | 75.1 | A- | High |
| 11 | 30 N. LaSalle Street (Loop conversion) | Chicago (The Loop), IL | Private | Office-to-residential | 349 | 74.4 | A- | High |
| 12 | Rockaway Grove (former USGS Campus) *(comp)* | Menlo Park, CA | Federal | Federal campus → redevelopment | ~1,000 | 72.8 | A- | Medium |
| 13 | West LA VA — North Campus (Veteran Housing) | Los Angeles (West LA), CA | Federal | Veteran supportive housing | ~1,800 | 72.7 | A- | High |
| 14 | Surplus State Site — Napa | Napa, CA | State | Surplus state land → affordable | ~200 | 71.5 | B+ | High |
| 15 | Former DMV Site — Stockton | Stockton, CA | State | Surplus state land → affordable | ~250 | 71.0 | B+ | High |
| 16 | Former State Hospital Land — Fontana | Fontana / San Bernardino, CA | State | Surplus state land → affordable | ~300 | 69.8 | B+ | High |
| 17 | Alameda Point (former NAS Alameda) | Alameda, CA | Local | Former base → master-planned | ~2,000 | 69.3 | B+ | Medium |
| 18 | Chet Holifield Federal Bldg ("The Ziggurat") | Laguna Niguel, CA | Federal | Gov office → mixed-use | 2,000–4,000 | 69.2 | B+ | High |
| 19 | 50 United Nations Plaza (Federal Building) | San Francisco (Civic Center), CA | Federal | Federal office → conversion | ~500 | 68.3 | B+ | Medium |
| 20 | Peachtree Summit Federal Building | Atlanta, GA | Federal | Federal office → conversion | ~350 | 67.8 | B+ | Medium |
| 21 | USDA Headquarters (Whitten Bldg watch) | Washington, D.C. | Federal | Federal office → redevelopment | ~400 | 66.2 | B+ | Medium |
| 22 | Speaker Nancy Pelosi Federal Building (SoMa) | San Francisco (SoMa), CA | Federal | Federal office → conversion | ~600 | 64.0 | B | Medium |
| 23 | 1000 Broadway (office-to-residential) | Oakland (Downtown), CA | Private | Office-to-residential | ~100 | 64.0 | B | Low–Med |
| 24 | Federal Property — Battle Creek | Battle Creek, MI | Federal | Federal property → redevelopment | ~150 | 61.5 | B | Low–Med |

**Universe at a glance:** 22 active opportunities (2 comps), ~15,700 housing units in scope, average active score ~72, spanning California, New York, Illinois, Nevada, Georgia, Michigan, and Washington D.C.

---

## 5. Worked example — the per-property output (the Ziggurat)

To show the depth behind a single score, here is the executive summary R Squared would publish for one asset, the Chet Holifield "Ziggurat" (Laguna Niguel, CA; GSA surplus; ~1M sq ft on ~90 acres; B+ / 69.2):

- **Why significant:** rare ~90-acre infill site in supply-constrained South Orange County; city-designated "Opportunity Area"; ULI-backed vision for 2,000–4,000 homes; iconic William Pereira landmark.
- **Highest & best use:** master-planned mixed-use district anchored by 2,000–4,000 homes with retail, civic, and partial adaptive reuse.
- **Three biggest risks:** (1) entitlement — rezone + General Plan amendment with density pushback; (2) capital — all-cash + demolition sank two prior buyers; (3) construction — abating/demolishing a 1971 concrete structure.
- **Three biggest value drivers:** severe regional housing shortage; city Opportunity-Area designation; scarcity of a 90-acre infill canvas.
- **Estimates (illustrative):** acquisition ~$150–200M (prior bid ~$177M); total development cost in the billions at full build-out; 7–12+ year timeline.

Every property in the universe carries the same structured summary, which is what makes cross-property comparison meaningful.

---

## 6. How opportunities are surfaced (the intake funnel)

Sourcing is a quality funnel, not a firehose:

1. **Wide intake (cheap, automatable):** federal feeds (GSA realestatesales.gov / disposal.gsa.gov, the Federal Real Property Profile dataset, BLM/SNPLMA actions), state inventories (e.g., California Excess Sites), the new federal **public-land database** mandate (ROAD Act Sec. 104), local **Surplus Land Act** listings, transit joint-development pipelines (e.g., LA Metro's 10K homes), and city office-conversion lists (NYC 467-m, Chicago LaSalle, LA/SF programs).
2. **Score:** AI does a fast first pass on the 12 categories from public data; an analyst reviews the judgment-heavy categories (entitlement, financial, political).
3. **Publish:** only vetted, scored sites surface.

**Key constraint (stated honestly):** finding sites is easy and scalable; **scoring them credibly is the bottleneck**, so the human-review gate is what protects the brand. The realistic path is depth on hundreds of in-play properties first, not shallow coverage of every parcel in America.

---

## 7. Business model & monetization

**Positioning (the lane):** R Squared should *not* present as a first-time affordable-housing developer. It should lead as: *"We identify underused real estate, align public purpose with private execution, assemble the right partners, and turn difficult sites into financeable housing opportunities."*

**Who pays:** developers/investors (ranked deal flow, fast underwriting), capital allocators/LPs (independent validation), service firms (legal, A&E, environmental, brokers — sponsorship/referrals/data licensing), public agencies (objective feasibility framing), and affordable/civic partners.

**The near-term wedge (most important):** don't chase bond/grant dollars directly. **Control sites and bring qualified affordable-housing partners to the table before the money moves.** Then structure a JV: R Squared supplies site control, relationships, deal vision, and local execution; partners supply tax-credit development and operations.

**Required partner stack (five groups):** affordable-housing developer (LIHTC-experienced), nonprofit operator, veteran/supportive-services provider, public-finance consultant, land-use/entitlement attorney.

**How R Squared makes money (the "Build the JV" model in the demo):** the demo includes an interactive calculator that estimates R Squared's compensation as the JV sponsor, stacking:

- Acquisition fee (% of acquisition/site-control cost)
- Share of the developer fee (% of total development cost × R²'s JV share)
- Promote / carried interest (% of project profit × R²'s share)
- Sponsor / consulting fee (flat)

For a mid-size deal these can total a low single-digit percentage of total development cost — meaningful, repeatable, and earned across the life of a deal. (The calculator is illustrative, not a pro forma.)

---

## 8. Competitive landscape & defensibility

- **CoStar (incl. Reonomy):** dominant CRE data (~70%+ institutional share). Owns the data layer you cannot out-build — but does **not** rank public-asset redevelopment potential or render judgment.
- **Cherre:** data-integration/knowledge-graph layer. Infrastructure, not analysis — a potential supplier, not a rival.
- **GSA / government portals:** raw listings and process, no ranking or comparison. Input, not competitor.
- **Brokerages (CBRE, JLL):** conflicted (represent sellers) and deal-by-deal. R Squared's edge is **independence and cross-property comparability**.

**What is defensible:** the methodology + brand (a respected, consistent scoring standard), and the relationships/proprietary signal that accrue over time. **Not defensible:** the underlying property data — so license it, don't rebuild it.

---

## 9. Key risks (honest)

- **Scope/over-reach** (HIGH): "every property in America" guarantees thin, slow output. Start narrow.
- **Data cost & scoring quality** (HIGH): the valuable categories are manual; quality is the bottleneck.
- **Accuracy/liability** (HIGH): a wrong A-rating that someone acts on damages the brand; disclaimers + review discipline are essential.
- **Key-person dependency** (MED): early credibility rests on founder judgment.
- **Policy dependency** (MED): tailwinds depend on the disposition push, the bond passing in November, and the ROAD Act being signed/implemented. The bill passed with veto-proof margins but the signing has been politically delayed.
- **Monetization timing** (MED): credibility must precede revenue.

---

## 10. The product / demo — what the web app does

The live demo (`index.html`) is a single self-contained web app. Features:

- **Header + policy banner:** branding plus the "two tailwinds" (ROAD Act + CA bond).
- **Dashboard stats:** active opportunities, housing units in scope, average score, states covered, count rated A- or better.
- **List view:** ranked, filterable cards — each shows the property, location, owner type, asset type, R Squared Opportunity Score, letter grade, policy fit, and housing potential.
- **Filters & sort:** search; sort by score / housing potential / name; filter by region (California, West, Midwest, South, Northeast), owner type (Federal, State, Local, Private), and policy fit (High/Medium).
- **U.S. map view:** a national map with markers colored by grade and sized by housing potential; hover for a tooltip, click to open the property; a synced ranked list sits alongside.
- **Property detail (modal):** profile (owner, type, location, size, status, housing potential, highest & best use); the full 12-category score breakdown with bars; policy/program fit with target programs; top value drivers; key risks.
- **"Build the JV" calculator:** opens from each property; pre-fills units, dev cost, acquisition, and profit, then lets the user adjust R Squared's economic levers (acquisition fee, developer-fee share, promote, sponsor fee) with live sliders, outputting R Squared's estimated total compensation and its share of total development cost.

Everything runs client-side; no logins, no server, no data leaves the browser. (This is also why the raw file is hard for a text-based AI to read — the content is generated by JavaScript at runtime. The full data is reproduced in this document and embedded as readable text inside the file.)

---

## 11. Roadmap / what's next

- **Near term (pre-November):** secure control (option/LOI/ENA) on 1–2 priority sites; line up an anchor affordable developer + nonprofit operator; publish 8–10 full assessments of in-play assets.
- **Mid term:** expand the intake funnel to live public feeds with AI-assisted first-pass scoring + human review; add side-by-side comparison and saved deals; consider a light "screening score" tier for breadth.
- **Product/infra:** the current demo is intentionally backend-free. A production version (live editable database, logins, collaboration, automated feeds) would add a backend/database — only once the brand and revenue justify it.

---

## 12. What we'd like feedback on

1. **Positioning:** Is "independent intelligence + JV sponsor (site control + partner assembly)" the right wedge, or should R Squared pick one (media/research vs. principal/developer)?
2. **Defensibility:** Is the methodology+brand a real moat, or will incumbents (CoStar) or brokerages replicate it? What would strengthen the moat?
3. **Monetization:** Which revenue line should lead — subscriptions/research, advisory/commissioned work, or JV promote? Is the "Build the JV" economic model realistic?
4. **Scope:** Is "national, 7 states, 24 sites" the right breadth for a demo, or should it go deep on one market first? Where's the credibility-vs-coverage line?
5. **Scoring model:** Are the 12 categories and weights sensible? Is 20% on Financial Return + 15% Market Demand the right emphasis? What's missing (e.g., climate/insurance risk, construction-cost volatility)?
6. **Policy bet:** How much should the strategy lean on the ROAD Act (no new money) vs. the CA bond (real money but California-only) vs. the federal disposition wave?
7. **Biggest blind spot:** What's the most important thing this plan is getting wrong or ignoring?

---

*Disclaimer: All scores and financial figures in this document and the demo are illustrative analyst estimates for demonstration purposes only — not investment advice, appraisals, or guarantees. Property facts are drawn from public sources as of June 2026 (GSA, VA, BLM/SNPLMA, the 21st Century ROAD to Housing Act, California DGS/HCD Excess Sites & Surplus Land Act, LA Metro, and municipal office-conversion programs).*
