# The AI capital riptide

**Assignment:** Dimension Brett Winton’s claim that high-IRR AI infrastructure will bid up the cost of capital enough to starve traditional businesses of cheap rollover credit — including firms with no obvious AI exposure.  
**Date:** 2026-08-30  
**Primary source:** [source.md](source.md)  
**Verdict:** The mechanism is coherent and several of its pieces are already visible. The *price* of capital has not yet moved in the way the thesis requires. The live surprise is not equity mania. It is compute being packaged as a durable, collateralizable, increasingly investment-grade claim on the same global funding pool that ordinary corporates use to roll their debt.

This is a research note, not investment advice.

---

## 1. The claim, stripped to mechanism

Winton’s argument is a crowding-out story with an industrial-finance twist. Five steps:

1. AI infrastructure still pays back quickly and at high IRR even at huge scale, because the market is compute-starved.
2. Builders will therefore keep building even if their cost of funds rises.
3. NVIDIA chips can be pledged, residual values can be underwritten, and weaker operators can still borrow.
4. That debt has to come from somewhere. High yield feels it first. Then compute is presented as a more stable, “investment-grade-y” asset class and starts competing with ordinary corporates for the same institutional money.
5. If annual datacenter capex scales into the trillions, and if real GDP inflection also lifts long rates, incumbents who assumed they could roll credit at a “normal” spread lose the cheap refinancing their operating models were built on.

The non-obvious part, in his words: people will dismiss the equity side as investors losing their heads. They will miss the debt-market reclassification of compute.

That is the right place to look. Venture already screens for “AI.” Public equities already concentrate there. The open question is whether *credit* starts treating racks of GPUs the way it treats pipelines, towers, and power plants — and what that does to everyone else.

---

## 2. What is already true

### 2.1 The buildout is large enough to matter, but it is not yet “trillions a year”

| Claim | What the numbers say as of late August 2026 | Source |
| --- | --- | --- |
| Hyperscaler capex, 2026 | Moody’s: $785B (up from a $700B March forecast). Consensus US hyperscaler capex ~$794–800B. BofA: >$860B. | [Moody’s via DCD](https://www.datacenterdynamics.com/en/news/moodys-hyperscaler-capex-forecasts-marked-up-by-85bn-to-close-in-on-1trn-by-2027/), [Goldman Sachs](https://www.goldmansachs.com/insights/articles/global-investment-is-forecast-to-exceed-1-trillion-in-2026) |
| Global AI investment, 2026 | Goldman’s preferred measure: ~$1T globally, ~$581B in the US (1.8% of US GDP, 0.9% of world GDP). | [Goldman Sachs](https://www.goldmansachs.com/insights/articles/global-investment-is-forecast-to-exceed-1-trillion-in-2026) |
| 2027 run-rate | Moody’s: approaching $1T. BofA: path to $1.2T. Goldman: 2.5% of US GDP / 1.3% of world GDP. | Same as above |
| Cumulative, 2026–2030/31 | OECD: $4.1T capex for nine hyperscalers, 2026–2030 ($3.5T from the four largest). Goldman (via secondary writeups): $7.6T of compute + datacenter + power, 2026–2031, with annual spend ~$1.64T by 2031. ARK: datacenter-systems investment could reach ~$1.5T in 2030. | [OECD Global Debt Report 2026](https://www.oecd.org/en/publications/global-debt-report-2026_e9d80efd-en/full-report/corporate-debt-market-outlook-in-a-transforming-world_cf86a220.html), [ARK IOR 2026](https://etfs.ark-funds.com/hubfs/1_Download_Files_ETF_Website/Reports/ARKInvest-InvestmentOpportunityReport2026.pdf) |

Winton’s “annual capital requirements scale into the trillions” is a 2027–2031 path, not a 2026 fact. It is already a *trillion-dollar* annual phenomenon if you take Goldman’s global definition. It is not yet a multi-trillion annual claim on the bond market.

Relative to the funding pool, even the current path is not small:

- Global corporate *bond* issuance in 2025: **$6.8T**. Bonds + syndicated loans: **$13.7T**. Outstanding corporate debt: **$59.5T**. ([OECD](https://www.oecd.org/en/publications/global-debt-report-2026_e9d80efd-en/full-report/corporate-debt-market-outlook-in-a-transforming-world_cf86a220.html))
- US corporate bond issuance in 2025: **$2.2T** ([SIFMA 2026 Fact Book](https://www.sifma.org/wp-content/uploads/2025/07/SIFMA-Capital-Markets-Fact-Book-2026-Edition.pdf)). H1 2026 already $1.52T, +28% y/y.
- OECD’s own stress: if nine hyperscalers fund 29% of 2026–2030 capex in bonds (their 2020–2025 average), they take **9%** of historical global non-financial gross issuance. If they fund half in bonds, **15%** by 2030 — from nine of 9,235 issuers. Morgan Stanley (cited by OECD) puts the 2025–2028 AI infrastructure financing gap at **$1.5T**, with **77%** of external funding expected from debt.

That is the dimensioning Winton is pointing at. One industrial program, at the high-debt case, can occupy a mid-teens share of the world’s corporate bond tap.

### 2.2 The market is still compute-starved, so builders will pay up

This leg is the strongest.

- Moody’s (May 2026): hyperscalers added ~**$700B** of remaining performance obligations over two quarters; OpenAI and Anthropic are “struggling to find the computing capacity.” Moody’s reads this as a multi-year infrastructure trajectory, not a one-year spike. ([DCD](https://www.datacenterdynamics.com/en/news/moodys-hyperscaler-capex-forecasts-marked-up-by-85bn-to-close-in-on-1trn-by-2027/))
- Amazon, per ARK’s recap of 2026 earnings: even at ~$220B of capex, Jassy said AWS will not have enough capacity, and the gap could last into 2027. ([ARK #519](https://www.ark-invest.com/newsletters/issue-519))
- NVIDIA, August 2026: one-year H100 rent rose from **$1.70/GPU-hour (Oct 2025) to $2.35 (Mar 2026)**; on-demand median from ~$2.00 to $2.70 by June 2026; B200 cloud rates **$5.30–$7.05**. ([NVIDIA blog](https://blogs.nvidia.com/blog/nvidia-ai-factory-compute/))

If rented compute is still getting *more* expensive while the industry is pouring hundreds of billions into supply, the “projects still pencil at a higher WACC” claim is not a stretch. The constraint is capacity, not demand.

### 2.3 Debt is already the funding model, and chips are already collateral

This is no longer a forecast.

- Hyperscalers issued **$122B** of bonds in 2025 (3× their post-2000 annual average; $88B in a 54-day late-year burst). OECD notes this still understates the true figure because SPVs sit off the parent tape — Meta’s **$27B** Blue Owl data-center SPV is the type specimen. ([OECD](https://www.oecd.org/en/publications/global-debt-report-2026_e9d80efd-en/full-report/corporate-debt-market-outlook-in-a-transforming-world_cf86a220.html))
- BofA, mid-2026: the top five have raised ~**$270B** year-to-date, mostly long-dated (30–40 year) paper. That tenor is a bet that this is infrastructure, not a two-year gadget cycle.
- JPMorgan (via Akin, 2025 year-end): >**$300B** of AI/data-center IG issuance possible in 2026; ~$1.5T of bond-market funding needed over five years. ([Akin](https://www.akingump.com/en/insights/articles/key-trends-and-developments-from-the-bond-markets-during-2025-what-directors-need-to-know))
- Private credit: AI-related deals **$59B in 2025**, ~7× 2024, **34%** of private-credit deal value (from 9%). Morgan Stanley (via OECD) expects private credit to supply **$800B** to the AI expansion over four years, mostly asset-based finance.
- On 10 August 2026 NVIDIA signed MOUs with Apollo, BlackRock, Blackstone, Brookfield, Goldman Sachs, and KKR to stand up “compute financing platforms” aimed at mobilizing **>$500B** of third-party capital over time. Goldman’s David Solomon: “create a market for credit backed by NVIDIA compute.” Huang: “In AI, compute is revenue.” The partnerships are still MOUs, not funded commitments. ([NVIDIA press release](https://investor.nvidia.com/news/press-release-details/2026/NVIDIA-Partners-With-Apollo-BlackRock-Blackstone-Brookfield-Goldman-Sachs-and-KKR-to-Establish-AI-Compute-Infrastructure-Financing-Platforms-to-Mobilize-Over-500-Billion-of-Third-Party-Capital/default.aspx))
- Residual-value support: NVIDIA may backstop **up to 25% of an opportunity**, project by project, explicitly to make the chips financeable. Huang frames A100 (2020) as still in commercial use and heading toward a decade of economic life. CUDA is the residual-value story: software keeps improving installed hardware. ([NVIDIA blog](https://blogs.nvidia.com/blog/nvidia-ai-factory-compute/))

Winton’s “so long as they’re building NVIDIA they can collateralize the chips, lowering cost of finance for even more balance-sheet tenuous operators” is a description of a market that is being built in public, not a hypothetical.

### 2.4 High yield is already an AI market

Winton said the cut hits high yield first. The *volume* evidence is already there. The *price* evidence is not.

- White & Case (24 Aug 2026): US HY issuance **$155B in H1 2026**, +19% y/y, “in large part” AI data-center deals. Tech issuance **$36.2B**, ~**25%** of US HY in the half, nearly 2× H1 2025. Energy, the next sector, was $18.6B. Named HY taps: Tract/Fleet $4.59B, CoreScientific $3.3B, Meridian $5.7B. Yields held steady. ([White & Case](https://debtexplorer.whitecase.com/leveraged-finance-commentary/us-ai-linked-issuance-brightens-in-divergent-global-high-yield-picture))
- Wellington: AI-tied HY issuance ~**20% of YTD** versus **5% in 2025**. They describe a new HY subsector — data centers and digital infrastructure, often on hyperscaler contracts, often with structured-credit / project-finance plumbing. ([Wellington](https://www.wellington.com/en-latam/intermediary/insights/ai-high-yield-market))

So HY capital *is* sloshing toward the marginal opportunity, exactly as Winton said. What has not happened is a squeeze that shuts traditional HY issuers out. US HY *grew*. Europe and APAC HY *fell*, but White & Case blames geopolitics (Iran), not AI crowding. US HY yields “held steady.” Global HY spreads into 2026 were in their richest historical decile (SSGA: ~1.6% trailing default rate, $335B 2025 gross issuance). Mid-2026 HY spreads ~269 bps; IG ~74 bps, 1st percentile of 20 years.

The first-order HY fact today is **recomposition**, not rationing. AI paper is a quarter of the US HY tape. Traditional credits are a smaller share of a larger (US) market, still clearing at tight spreads. That is the beginning of Winton’s path, not the end.

---

## 3. The hinge: do the projects actually underwrite that well?

Winton needs “extraordinarily high IRR” and “quick payback” *at monumental scale*. This is the weakest, or at least the most unit-of-account-sensitive, leg.

**What supporters can point to**

- CoreWeave’s disclosed target is the industry’s cleanest public number: ~**2.5-year GPU cash payback**, contract-level **unlevered IRR ~20%**, and that IRR is *not* supposed to depend on residual value or recontracting after expiry. Independent rebuilds of the 100 MW model land near 2.25-year revenue payback / ~20% unlevered IRR on 5-year contracts. ([Rittenhouse](https://rittenhouseresearch.substack.com/p/coreweave-unit-economics-margin-profile); CoreWeave S-1 / subsequent models)
- Enterprise TCO shops (Lenovo Press 2026) publish on-prem breakeven versus on-demand cloud of **~5 months**, and still under 15 months versus 3–5 year reserved instances. That is a *buy-vs-rent* payback, not a project-finance IRR, but it is why CFOs keep signing.

**What that number hides**

- 2.5 years is payback on **GPU capex**, not on the all-in factory (shell, power, networking, land, substations). Momoview’s 1 GW sketch: ~$40B all-in, ~$7.5B/year gross at contract rent. GPU-only / contract-rent can show 20%+ IRR; all-in plus spot-like rent can show **IRR ≈ 0**. The slogan and the factory are different businesses.
- CoreWeave can print ~60% adjusted EBITDA and still lose money at the bottom line. FY2025: ~$5.13B revenue, ~$3.1B adj. EBITDA, ~$2.45B D&A, ~$1.2B interest, ~$1.17B GAAP loss, ~$21.4B debt. Interest is the cash cost that utilization does not forgive. ([Zettabyte, from CRWV 10-K](https://www.zettabyte.space/blog/neocloud-unit-economics-gpu-cloud))
- If economic life is 3 years rather than 5–6, or if rent halves after year 3, the 20% unlevered IRR collapses toward or through the cost of capital. That is the Burry / useful-life objection, and OECD says the same thing in official language: uncertainty about data-center useful life and collateral value is making some of this debt **equity-like risk with debt’s repayment schedule**.

So the honest statement is narrower than Winton’s: *contracted GPU cash-on-cash can clear 15–25% unlevered if utilization and rent hold.* That is enough for a leveraged builder to tolerate a higher coupon than a supermarket chain. It is not proof that a trillion-dollar all-in factory program earns “extraordinarily high IRR” in every vintage. The collateral story (NVIDIA residual support, CUDA, secondary-market studies claiming 8-year life and >10% five-year residuals) exists specifically because lenders do not take the 20% on faith.

The Winton mechanism does not need every project to be a 40% IRR. It needs the *marginal* AI project to still clear after a 100–200 bp rise in funding costs, while the marginal traditional rollover does not. That bar is lower, and on contracted GPU economics it is currently plausible.

---

## 4. Has the cost of capital actually gone up for everyone else?

This is where the thesis is **ahead of the tape**.

Goldman economists Jessica Rindels and David Mericle, 2026: AI investment ~$600B / ~2% of US GDP, 10% of business fixed investment, 15% of equipment investment. Capital-market crowding-out so far: **+5 basis points** on corporate borrowing costs, perhaps **$10B** less non-AI investment. They call both the “AI is all of GDP” story and the “AI is crowding out everything” story exaggerated. Physical crowding is more real: data-center construction gross margins are more than 2× non-tech projects, so labor and kit are being pulled. ([Axios via Yahoo](https://finance.yahoo.com/technology/ai/articles/quantifying-ai-boom-crowding-effect-161206001.html))

OECD, March 2026: 2025 hyperscaler bond issuance ($122B) was only ~15% of US non-financial IG and was “absorbed without market-wide friction.” Spreads are near historical lows *despite* record borrowing and high policy uncertainty. Half of the recent spread compression is liquidity premia, not a credit judgment.

Bruce Richards’ mid-2026 observation is the other way around: IG hyperscalers (~$250B YTD in his tally, $25–35B prints) are competing with **Treasuries**, and other IG spreads have *not* widened. If anyone is being crowded, it may be the sovereign, not the BBB industrial.

**Read-through:** Winton is describing a *future* price of capital, not the 2026 one. Spreads are tight, issuance is clearing, and Goldman’s estimated corporate-rate impact is a rounding error. The conditions for a later squeeze — share-of-issuance, new asset class, GPU collateral, compute starvation — are being installed now. The squeeze itself is not.

That gap is why the note is interesting. If you wait for the spread to print, you are late to the balance-sheet rewiring.

---

## 5. The actual surprise: compute as an asset class

This is the sentence in Winton that aged fastest. He posted that people were not “dimensioning” compute being financed as a more stable, more IG-like claim. Three weeks before this assignment, NVIDIA and the six largest alternative/infrastructure firms said that out loud.

What “investment-grade-y” means in practice:

| Traditional corporate credit | Compute-as-infrastructure credit |
| --- | --- |
| Unsecured claim on a firm’s cash flow | Secured claim on racks, contracts, and (sometimes) a vendor residual |
| Spread set by issuer rating and sector | Spread set by utilization, offtaker, power, and residual-value assumptions |
| 5–10 year typical industrial tenor | Already seeing 19-year and 30–40 year paper against assets whose *economic* life is argued at 2–10 years |
| Borrower is a known operating company | Borrower can be an SPV, neocloud, or lab with a thin parent balance sheet |
| Competes in IG/HY indices as “industrials / consumer / healthcare” | Competes in IG, HY, ABS, private credit, and insurance general accounts as “infrastructure” |

If that reclassification works, two things follow.

First, **the buyer set changes**. Pension and insurance money that would not buy CoreWeave unsecured paper will buy “AI factory” cash flows with a residual wrap, the way they buy towers and midstream. That is new dry powder, not just a reshuffle of HY.

Second, **the comparison set changes**. A treasurer at a stable mid-grade industrial is no longer competing only with other mid-grade industrials. She is competing with an asset that (a) still clears at 15–20% project IRR after a higher coupon, (b) comes with NVIDIA-shaped collateral, and (c) is being sold to her own lenders as infrastructure. She cannot raise her own IRR by wishing it. She can only pay more, shrink, or wait.

OECD’s warning belongs here: if useful life and collateral values are wrong, the market has concentrated equity-like risk inside debt products, and it has done so at a scale that can move the whole corporate tape. The 1990s telecom buildout and the 2010s shale buildout are the default historical rhymes — not because AI is “a bubble,” but because both cycles financed physical capacity with debt against residual values that later disappointed.

---

## 6. The rate cross, and an ARK tension

Winton’s knockout punch is the cross of two things:

1. Crowding: AI projects absorb credit and lift *spreads* (or at least absorb the cheap part of the bid).
2. Macro: ARK’s anticipated real-GDP inflection lifts *long rates*, even while tech deflation holds inflation down.

Cross them, and a business that was fine at a 4% coupon and a 120 bp spread is not fine at a 5.5% coupon and a 200 bp spread, especially if it has a 2027–2028 maturity wall. OECD: 24% of IG and 31% of non-IG debt globally matures 2026–2028. The stock of ultra-cheap (≤2%) IG coupons is already down to 14% from ~25% in 2021; half of IG now costs >4%.

The GDP-inflection half is ARK house view. Big Ideas 2026 (Winton): capital investment from the five innovation platforms could add **1.9 pp** to annualized real GDP this decade; realized real growth could run **>4 pp above consensus**. Cathie Wood’s 2026 outlook: possible **5–7% productivity**, ~1% labor, **−2% to +1% inflation**, **6–8% nominal GDP**.

There is a tension inside that house view. Wood’s own analogy for the last comparable technology boom (internal combustion, electricity, telephony through 1929) is that **long rates followed deflationary undercurrents and the curve inverted ~100 bp**. Short rates tracked nominal GDP; long rates did not rip higher. If that rhyme holds, Winton’s “long rates naturally higher” leg is the weaker one. The crowding leg can still work on its own. The *cross* is not automatic.

What would make the rate leg true anyway:

- Real growth inflects *and* the term premium stays positive because Treasury supply and hyperscaler IG supply hit the same accounts (Richards’ “IG vs UST” point).
- Inflation stays contained, but the Fed cannot cut because real activity is hot — a high-real-rate, low-inflation regime.
- Foreign official demand for duration fades at the same time private credit is being reallocated into compute.

Leading indicators Winton alludes to are real: Goldman’s AI-capex dashboard (Taiwan/Korea semiconductor-equipment imports, relevant PMI components, memory and GPU rental prices) is “near the top of its range since 2022.” That is a capex-continuation signal, not yet a broad real-GDP inflection print.

---

## 7. Who actually gets starved

Winton: “be very wary of businesses that claim they can live outside of disruption.” Separate three casualties, because they fail for different reasons.

**A. Direct AI counter-exposure (software, IT services, media, routine knowledge work).**  
This is product disruption, not a credit-market story. Wellington already flags it as the HY lose-side. Cheap capital would not save a firm whose customers just stopped buying the old thing.

**B. Capital-intensive incumbents with no AI story and a near-term maturity wall.**  
This is Winton’s distinctive claim. Think: regional industrials, older telecom, conventional CRE, non-AI healthcare services, consumer issuers who lived on 2020–2021 coupons. They are not being out-competed by ChatGPT. They are being out-bid for the same insurance-company dollar by a data-center SPV. The tell is not their EBITDA. It is whether their 2027 refinance prints 150 bp wider than their 2024 issue for no idiosyncratic reason.

**C. Physical crowding, not financial.**  
Goldman’s more convincing 2026 channel: construction labor, transformers, gas turbines, copper, and memory. Moody’s: memory as a share of low-tier PC/smartphone BOM heading toward 30%+, with unit volumes down double digits. A business can be “outside of AI” and still lose because the *inputs* got bid away.

A and C are already observable. B is the one that is not in the spread yet and is the one Winton is asking people to dimension.

A working watchlist for B, if this research base stays on the question:

1. Share of US HY and US IG issuance that is AI/data-center/power (20–25% HY already).
2. Spread *differential* between AI-linked HY and same-rating non-AI HY. If AI paper starts trading *tighter* while non-AI widens, the reclassification is happening.
3. Hyperscaler + SPV + neocloud issuance as % of global non-financial supply (OECD 9–15% path).
4. GPU residual assumptions embedded in rated ABS (advance rate, residual %, NVIDIA support attachment).
5. 2027–2028 maturity-wall refinance spreads for BB/BBB non-tech, vs 2024 vintages.
6. Long real rates vs ARK-style productivity prints. If 10-year reals rise while CPI stays contained, the “cross” is on.

---

## 8. What would falsify the thesis

- **Utilization or rent break.** GPU-hour prices falling while new supply is still ramping would kill both the “starved market” premise and the residual-value collateral. Watch H100/B200 contract rents, not just NVIDIA’s revenue.
- **Useful life repriced in public credit.** A major ABS or neocloud refinance that has to eat a 3-year rather than 6-year life, or a residual shortfall that NVIDIA’s 25% does not cover, would re-risk the asset class overnight.
- **Capex financed from cash, not credit.** If hyperscaler FCF recovers fast enough that they stop being $200B+ annual issuers, the crowding channel shrinks back to SPVs and neoclouds — still large, no longer systemic.
- **Spreads stay at the 1st percentile through a $1T+ 2027 print.** That would mean the global savings glut (and/or private credit) absorbed the supply. Winton would be right about *composition* and wrong about *cost*.
- **Real growth does not inflect.** Then you have a huge capex cycle inside a 2% real world, which is a different and possibly uglier story (more bubble-like, less “starved incumbents in a boom”).

---

## 9. Bottom line

Winton is not making an equity-bubble argument. He is making a **claims-on-savings** argument.

The world is building a new capital stock — AI factories — whose contracted unit economics can tolerate a higher cost of funds than the incumbent capital stock. The builders are already in the bond market, the loan market, private credit, and now a dedicated “compute financing” channel with NVIDIA residual support. High yield has already given them a quarter of the US tape. Official-sector debt researchers (OECD) are already asking whether nine firms can take 9–15% of global issuance. The asset-class marketing campaign launched on 10 August 2026.

What is **not** true yet is the punchline. Corporate spreads are historically tight. Goldman’s estimated rate impact is 5 bp. Traditional issuers are still rolling. The “abyss” is a 2027–2030 possibility, not a 2026 observation.

Treat the note as an early warning about **who the marginal borrower is**, not as a forecast that every “stable” business dies. The businesses that should worry are the ones whose only advantage was an assumed right to cheap, sleepy credit — and the ones whose physical inputs are already being bid away by the same buildout.

The world is turning. The riptide in credit is the part to keep measuring.

---

## Sources

Primary

- Brett Winton, social post, late August 2026 — [source.md](source.md)

Capex and scale

- Goldman Sachs Research, “Global AI Investment Is Forecast to Exceed $1 Trillion in 2026,” 7 Aug 2026 — https://www.goldmansachs.com/insights/articles/global-investment-is-forecast-to-exceed-1-trillion-in-2026
- Moody’s via DatacenterDynamics, “Hyperscaler capex forecasts marked up by $85bn,” 14 May 2026 — https://www.datacenterdynamics.com/en/news/moodys-hyperscaler-capex-forecasts-marked-up-by-85bn-to-close-in-on-1trn-by-2027/
- OECD, *Global Debt Report 2026*, ch. 2, 4 Mar 2026 — https://www.oecd.org/en/publications/global-debt-report-2026_e9d80efd-en/full-report/corporate-debt-market-outlook-in-a-transforming-world_cf86a220.html
- SIFMA, *2026 Capital Markets Fact Book* — https://www.sifma.org/wp-content/uploads/2025/07/SIFMA-Capital-Markets-Fact-Book-2026-Edition.pdf
- ARK, *Investment Opportunity Report 2026* — https://etfs.ark-funds.com/hubfs/1_Download_Files_ETF_Website/Reports/ARKInvest-InvestmentOpportunityReport2026.pdf
- ARK, newsletter #519, “The AI Capex Supercycle Is Accelerating” — https://www.ark-invest.com/newsletters/issue-519

Credit markets

- White & Case Debt Explorer, “US AI-linked issuance brightens in divergent global high yield picture,” 24 Aug 2026 — https://debtexplorer.whitecase.com/leveraged-finance-commentary/us-ai-linked-issuance-brightens-in-divergent-global-high-yield-picture
- Wellington, “How AI is impacting the high yield market” — https://www.wellington.com/en-latam/intermediary/insights/ai-high-yield-market
- Akin, “Key Trends and Developments from the Bond Markets During 2025” — https://www.akingump.com/en/insights/articles/key-trends-and-developments-from-the-bond-markets-during-2025-what-directors-need-to-know
- Goldman / Axios, “Quantifying the AI boom crowding-out effect” — https://finance.yahoo.com/technology/ai/articles/quantifying-ai-boom-crowding-effect-161206001.html

Compute as collateral / asset class

- NVIDIA press release, 10 Aug 2026 — https://investor.nvidia.com/news/press-release-details/2026/NVIDIA-Partners-With-Apollo-BlackRock-Blackstone-Brookfield-Goldman-Sachs-and-KKR-to-Establish-AI-Compute-Infrastructure-Financing-Platforms-to-Mobilize-Over-500-Billion-of-Third-Party-Capital/default.aspx
- Jensen Huang, “NVIDIA AI Factory Compute Is Becoming an Investable Asset Class,” 11–12 Aug 2026 — https://blogs.nvidia.com/blog/nvidia-ai-factory-compute/
- CNBC, “Wall Street endorsed Jensen Huang’s ‘big concept’,” 11 Aug 2026 — https://www.cnbc.com/2026/08/11/wall-street-endorsed-jensen-huangs-big-concept-for-ai-what-now.html

Unit economics

- Rittenhouse Research, CoreWeave unit-economics rebuild — https://rittenhouseresearch.substack.com/p/coreweave-unit-economics-margin-profile
- Momoview, “Is a Data Center a Good Business? (2026)” — https://momoview.com/blog/en/posts/ai-data-center-unit-economics-2026-roi-dcf-irr-gpu-depreciation-cash-flow-sustainability-good-business/
- Zettabyte, “The unit economics of debt-financed GPU clouds” — https://www.zettabyte.space/blog/neocloud-unit-economics-gpu-cloud
- Lenovo Press, *On-Premise vs Cloud: Generative AI TCO (2026)* — https://lenovopress.lenovo.com/lp2368.pdf

Macro / ARK

- ARK, *Big Ideas 2026* — https://www.ark-invest.com/big-ideas-2026
- Cathie Wood, “The US Economy Is A Coiled Spring,” 2026 outlook — https://www.ark-invest.com/articles/market-commentary/cathie-woods-2026-outlook
