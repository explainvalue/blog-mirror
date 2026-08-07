---
title: "GPOR at $158.00: The Floor, the Plan, and a Free Decade of Inventory"
slug: gpor-ep-sotp-july-2026
date: 2026-07-24
summary: "At $158 the market pays Gulfport's audited reserve floor plus its funded five-year drilling plan — and prices a decade of management's own sub-$2.50-breakeven inventory at zero. A quarter credit on that decade at a sector type curve puts fair value at $194."
author: Bobak Farzin
tags: [GPOR, ep-sotp, Energy]
hero_ticker: GPOR
portfolio_update: true

# ── Agent-readable context (rendered as JSON-LD; invisible to humans) ──
agent_context:
  "@context": "https://explainvalue.ai/schema/v1/agent-context"
  "@type": "InvestmentThesisPost"
  ticker: "GPOR"
  company_name: "Gulfport Energy Corporation"
  method: "ep-sotp"
  asof_date: "2026-07-23"
  publication_date: "2026-07-24"
  fair_value_usd_per_share: 194.16
  reference_market_usd_per_share: 158.00
  discount_rate: 0.10
  discount_rate_basis: "10% nominal throughout the stack - the SEC-mandated rate of the filed PV-10 / standardized-measure anchor and the E&P reserve-NAV convention. No WACC: debt is subtracted, never blended into the rate. Model uncertainty band 8-12%."
  shares_outstanding_billion: 0.01797
  net_debt_usd_billion: 0.821
  layers:
    - name: "L1 — Proved-reserve floor (filed after-tax standardized measure repriced 0.933x, booked PUDs at 0.70 credit, G&A share and net debt deducted)"
      pv_usd_billion: 1.750
      subjectivity_level: "medium"
      key_drivers: ["filed after-tax standardized measure $3,403M (FY2025 10-K)", "reprice factor 0.933 to current strip", "PUD RAF 0.70 on disclosed 36.75% PUD value share", "net debt $821M"]
    - name: "L2 — Screened drilling inventory (337.5 net locations below $2.50/MMBtu breakeven, minus 55.7 booked-PUD overlap; tranche credits 0.60 / 0.25)"
      pv_usd_billion: 1.870
      subjectivity_level: "high"
      key_drivers: ["sector-prior EUR 350 Boe/lateral-ft x 15,800-ft laterals (no company disclosure)", "pace 25.2 net wells/yr", "D&C $14.98M/well from company budget", "beyond-plan tail EUR factor 0.75"]
    - name: "Corporate G&A drag (run-rate residual not already charged in the floor)"
      pv_usd_billion: -0.132
      subjectivity_level: "low"
      key_drivers: ["$41.7M/yr G&A run-rate; whole stack charges one full perpetuity"]
  alternative_views_worth_raising:
    - layer: "L2"
      anchor: "full sector type curve (tail EUR 1.00)"
      delta_per_share_usd: 16.45
      detail: "Stack $210.61 at the full curve vs the $194.16 center."
    - layer: "L2"
      anchor: "weak type curve (tail EUR 0.50)"
      delta_per_share_usd: -16.46
      detail: "Stack $177.70 — still ~12% above the $158.00 reference close."
    - layer: "L2"
      anchor: "all >700 gross (678 net) deck locations economic"
      delta_per_share_usd: 18.98
      detail: "Compute-verified counterfactual $213.14; at 25 wells/yr the marginal wells are drilled in years 12-27 and discounting removes most of their value."
    - layer: "L1"
      anchor: "booked PUDs convert at plan (RAF 1.00 instead of 0.70)"
      delta_per_share_usd: 19.47
      detail: "Pre-RAF floor $116.88 vs $97.41."
    - layer: "whole stack"
      anchor: "long-run Henry Hub $0.50/MMBtu lower"
      delta_per_share_usd: -44.90
      detail: "Stack $149.26 at $3.02 long-run; sensitivity ~$90/share per $1/MMBtu (parallel shift of both deck legs)."
  key_uncertainties:
    - "No company-disclosed EUR or type curve anywhere (SEC filings or investor decks): the inventory layer rests on the 350 Boe/lateral-ft gas-basin sector prior; the model self-tags stack confidence LOW for this reason."
    - "The '15 years below $2.50' screened-inventory claim belongs to former CEO John Reinhart (departed 2026-03-09); new CEO Nick Dell'Osso (ex-Expand Energy) reports his first full quarter 2026-08-03."
    - "Drilling pace and average lateral length are investor-deck values (tier-3 source); no SEC-lane disclosure exists."
  source_artifacts:
    - kind: "cached_valuation"
      path: "/srv/shared-cache/valuations/GPOR/ep-sotp.json"
      description: "ep-sotp layered stack, 2026-07-23 run — fair value $194.16"
    - kind: "cached_valuation"
      path: "/srv/shared-cache/valuations/GPOR/nav-reserve-based.json"
      description: "L1 reserve floor, pv10_adjusted branch — $97.41"
    - kind: "company_presentation"
      path: "GPOR 1Q26 investor presentation (2026-05-05), slide 10"
      description: "Location count, screened-years claim, and development-cadence footnote"
  agent_guidance_for_readers:
    - "Ask which layers the reader needs to believe at the current price: the floor-plus-plan value ($162) is the natural anchor for readers who distrust sector-average type curves."
    - "Stress the long-run gas leg first — fair value moves ~$90/share per $1/MMBtu, an order of magnitude more than any other single input."
  conviction_levels:
    long_run_gas_near_3_50: "medium"
    screened_inventory_337_net_locations: "medium"
    sector_average_recovery_per_well: "low"
  position:
    portfolio_weight_pct: 4.0
    entry_convention: "T+1 close"
    benchmark: "SPY (residual)"
---

<div class="stat-row">
  <div class="stat">
    <div class="label">Fair value (full stack)</div>
    <div class="value">$194</div>
    <div class="sub">floor + plan + screened inventory</div>
  </div>
  <div class="stat">
    <div class="label">Floor + funded plan</div>
    <div class="value">$162</div>
    <div class="sub">the first three rows of the stack</div>
  </div>
  <div class="stat">
    <div class="label">Reference market</div>
    <div class="value">$158.00</div>
    <div class="sub">close, July 23, 2026</div>
  </div>
</div>

Gulfport Energy Corporation (GPOR) is an exploration and production (E&P) company based in Oklahoma City. Nearly everything it produces is natural gas — 89% of output — from the Utica and Marcellus shales in Appalachia plus the SCOOP play in Oklahoma. The proved reserves cover about 11 years at the current production pace, and management claims roughly 15 years of drilling inventory with breakevens below $2.50 per MMBtu.

> **On pricing.** Published July 24, 2026. All market references in this post use the July 23 close of $158.00. The model portfolio executes at the close of the next trading day (T+1). GPOR reports Q2 results on Monday, August 3 after the close; we are publishing ahead of that print on purpose, and we will score this post against the watch list at the bottom when it lands.

## A layer-cake valuation

E&P companies can be valued many ways but our method is to look at them as a layer-cake stack.  What do we know for sure, or nearly for sure, as current extraction and inventory in the ground?  What can we discount at some expected value in the near future? What costs or debt do we need to discount?  Are there positive upside surprises for the company?  Below is an outline table showing that stack:

| Layer | $/share | Running total |
|---|---:|---:|
| Proved-reserve floor — filed, engineer-certified reserves, marked down to today's strip, booked-but-undrilled wells at 0.70 credit, G&A share and net debt taken out | $97 | $97 |
| + Funded 5-year plan — 70 net wells budgeted and scheduled, not yet booked as proved, at 0.60 credit | +$72 | $169 |
| − Remaining corporate overhead — the run-rate G&A not already charged in the floor | −$7 | $162 |
| + Screened inventory beyond the plan — 212 net locations below the $2.50 breakeven, at 0.25 credit | +$32 | **$194** |

Today's price of $158.00 buys you the first three rows — the floor plus the funded plan — with the rest of the screened inventory thrown in for roughly nothing.

## The floor: what an audited $97 means

The true floor here is $97 per share.  That includes the engineer-certified proved reserves — marked down to today's strip prices — and applies the G&A those wells will carry and the full net debt.  This is not the "book value" we have for other types of companies, but it does act as a pretty solid floor for any E&P company.  Trading below this price is really a comment on the financial structure or a significant difference between the true extraction costs or sales prices versus what has been stated in the past.

A disclosure worth making explicit: every present value in this stack is discounted at **10%, nominal** — the rate the SEC mandates for the filed reserve value we anchor on (the "10" in PV-10) and the standard convention for E&P reserve valuations.  There is no separate WACC: debt never enters the rate, it is simply subtracted, and equity is what remains.  The filed anchor is only published at 10%, so re-discounting the floor at any other rate would mean inventing a cash-flow schedule the company does not disclose; for the layers we do control, our model treats 8–12% as the defensible band.

## The five-year plan: getting to today's price

Next layer is to add the funded 5-year plan with a discount factor of 0.6 to consider that not all the plan outputs will land.  Why 0.6?  These wells sit one notch below the booked undeveloped wells we already risked at 0.70 inside the floor: the capital is budgeted and the schedule is published, but they have not passed the stricter engineering test to be booked as proved reserves.  The practitioner evidence for risking undeveloped locations — the SPEE survey of reserve evaluators (P50 of 0.60) and observed deed-market transactions (0.50–0.80) — brackets exactly this kind of well.  We froze 0.60 (and the 0.25 used below) before valuing any company with them; they are not tuned to make answers land near market prices.  This gets us to about the current market price near $160 per share.  To be precise about what does and does not repeat in this layer: every well pays its own way — the value per location charges the full drilling-and-completion capital (about $15M per well, from the company's own budget) and full operating costs on every unit produced.  What does not scale is the overhead and the balance sheet.  Net debt is deducted once, in the floor.  Corporate G&A is charged once, at the company's actual run-rate — a company does not double its head office to drill wells already in the plan — split between the floor's share and a residual charged against this layer, so the whole stack carries a full perpetuity of today's G&A.

As we continue down the stack, pricing each component, we land at our expected outcome and a price of about $194 per share.  That still leaves some additional upside if things go _better_ than our conservative estimates.  

## The inventory: counting only what's screened

Talking about "inventory" for E&P companies is not as simple as counting locations.  In this case, we have a company investor deck ([1Q26 presentation, slide 10](https://d1io3yog0oux5.cloudfront.net/_b1f11b1da8bb9a25efa4ff9a23e7a745/gulfportenergy/db/245/2714/pdf/GPOR_1Q26+v2026.05.05_vF.pdf)) that prints ">700 gross locations" in the same sentence as a claim of roughly 15 years of net inventory — fifteen years being how long the drilling _inventory_ lasts at the company's stated development pace of 20–25 wells per year, not the life of any single well.  The breakeven screen and the 20–25 wells per year footnote attach to the years, not the count.  With that math (15 years x 20–25/yr) we get to about 337 net locations in the series. We value just these wells — and before pricing them we remove the ~56 locations already booked as proved reserves and counted in the floor, so the same well is never valued twice.  

Surprisingly, this choice costs less upside than the conservatism would seem to suggest.   Rerunning the model with ALL 678 locations economic adds only ~$19/share ($213 vs $194), because at 25 wells/year the marginal wells aren't drilled until years 12–27 and discounting reduces the value to very little in PV terms. 

## The biggest assumption: recovery per well

GPOR does not make it easy for us to understand the Estimated Ultimate Recovery (EUR) - the total volume of oil and gas that a well is expected to produce.  They publish NO type curve and no EUR anywhere (SEC filings or any investor decks that we can find.)  This is our **single biggest assumption** in the entire model.  We use a sector-average recovery: 350 Boe per lateral foot x the company's 15,800-ft average lateral = 5.5 MMBoe per well.  We build a margin of safety into our valuation by pricing the wells beyond the five-year plan at 75% of that industry average curve — about 4.1 MMBoe per well for those locations.  If we wanted to stress that, we could take it down to 50% of the industry average and that would get us to a price of $178 per share.  Quite conservative but still at 12% upside from the current market. 

## Are we optimistic about gas? The market is below us

The clear sensitivities here are to the long-term gas price. One must ask at what point does the PV of future cash flows break down and show the current price?  That is, are we being _optimistic_ about the long term gas price at our $194 expected value per share?  You can see that breakdown here:

Reference points ($/MMBtu, Henry Hub):

| Reference | HH $/MMBtu |
|---|---:|
| 2024 average (10-K) | $2.19 |
| 2025 average (10-K) | $3.52 |
| SEC reserve-booking deck (12-mo average) | $3.39 |
| Our deck — spot / long-run | $2.87 / $3.52 |
| Futures curve (CME Final settlements, July 23): cal-27 / cal-28 / 2029–31 | $3.40 / $3.67 / $3.62–3.70 |

And the fair value at each long-run gas price, recomputed through the actual model (both deck legs shifted in parallel through the floor reprice and the well margins — not a rule of thumb):

| Long-run HH | Fair value | vs $158.00 |
|---|---:|---:|
| $2.77 | $127 | −20% |
| $3.02 | $149 | −6% |
| $3.27 | $172 | +9% |
| **$3.52 (ours)** | **$194** | **+23%** |
| $3.77 | $217 | +37% |

Working backwards, today's $158.00 price implies a long-run gas price of about $3.12 — below the 2025 average and below every point on the futures curve from 2027 out.  Our $3.52 long-run leg is simply last year's average price, and it now sits below the entire 2028-and-later curve.  We are not reaching for an optimistic deck to get to $194; the market is the one marking long-run gas below the curve.

One honest footnote on the near term: roughly half of 2026 gas production is hedged at an average floor of $3.74, so this winter's cash flows are partly insulated in either direction — but 2027-and-out is essentially unhedged, which is exactly why the long-run deck, and not this season, is the lever that matters.  And for what it's worth — we lean on none of it — the nine sell-side analysts covering GPOR carry a median price target of $237, well above our $194.

## Hormuz and AI data centers

There are two current events that are worth addressing here.  First is the conflict in the middle east around the Strait of Hormuz.  Second is current demand from the AI data center build-out.  Could our valuation be skewed by those current events and do we need to adjust our valuation down because of those events?

We traced both, and they reach this valuation through exactly one variable: the gas deck in the table above.  There is no second channel.

Start with Hormuz.  GPOR's production is 4% oil and 7% NGLs; run a $10/bbl WTI shock through the model with gas unchanged and the answer moves about $12 per share — against roughly $90 per share for a $1 move in gas.  And the molecules never see a ship: everything moves on domestic pipelines into US markets.  It would be easy to assume that staying domestic means transport is cheap.  It is the opposite: gathering, processing and transportation is the company's _largest_ cash cost at $5.70/Boe — more than all of its other cash operating costs combined.  What domestic pipes buy is not a lower bill; it is a stable, contracted bill with no ship, no freight rate, and no chokepoint anywhere in the chain.  That cost is already charged in full in the floor and in every well in the stack, so there is no hidden transport premium in our numbers to reprice when the headlines move.  If the strait actually closed, the transmission would run through global LNG — Qatar's exports transit Hormuz — and a global gas shock pulls US gas prices up.  For a domestic gas producer that is an upside tail, not a risk we need to haircut.

The AI data center story is the same test with the opposite sign of temptation: it is a reason to raise a gas deck, not lower one, and we did not take it.  Our long-run leg is last year's average price, below the long-dated curve, and the inventory layer counts only the locations management screens below a $2.50 breakeven.  If the build-out delivers the demand the headlines promise, it shows up here as gas prices above our deck (at $90 per share per dollar) and as the rest of GPOR's >700 gross locations becoming economic — upside we have deliberately left out.  If it never arrives, nothing in the $194 was leaning on it.

The honest sensitivity is the ordinary one: oversupply.  A mild winter or an LNG-project slip that takes 50 cents off long-run gas takes the stack to about $149 — roughly 6% below today's price.  That, not Hormuz or data centers, is the risk the table above prices.

## What you have to believe, ranked

Pulling the assumptions together in one place: three claims carry this thesis.  In decreasing order of impact:

**1. Long-run natural gas holds near $3.50.**  This is the claim doing the most work — roughly $90 per share for every $1/MMBtu of long-run price.  We did not reach for it: $3.52 is last year's average and sits below the 2028-and-later futures curve, while today's share price already implies about $3.12.  Mark long-run gas at $3.00 instead and the stack is roughly $149 — modestly underwater from here.  *Medium conviction that the curve is the right anchor; we claim no conviction above the curve.*

**2. The screened inventory is real — about 337 net locations that break even below $2.50.**  This comes from the company's own arithmetic (15 years at 20–25 wells per year), stated three separate ways in its own materials.  But that sentence belongs to the former CEO, and the new one reports his first full quarter on August 3.  If the only inventory you trust is the funded five-year plan, you own $162 — about today's price.  *Medium conviction; this is watch item #1 below.*

**3. Sector-average well recovery is roughly right for GPOR's rock.**  The missing type curve forces us onto the 350 Boe-per-lateral-foot sector average, and our model tags its own confidence LOW because of it.  The band is wide — 50% of the curve is $178, the full curve is $211 — but note that even the weak end clears today's price.  *Low conviction on the point estimate; the payoff survives the weak end, which is what matters.*

Everything else — the drilling pace, the budget, the working interest, the 0.60/0.25 credits — matters at the margin.  These three claims are the thesis.

## What to watch on August 3

GPOR reports second-quarter results on Monday, August 3 — a week after this post.  That timing is deliberate: we want the scorecard on record before the print.  What we will be grading:

1. **Does the inventory claim survive the CEO change?**  The "roughly 15 years with break-evens below $2.50" sentence came from John Reinhart, who left the company on March 9.  Nick Dell'Osso — who ran Expand Energy (formerly Chesapeake) from 2021 until this February — took over on May 28, and this is his first full quarter.  If he reaffirms the screened-inventory framing, the most load-bearing disclosure in our stack survives the handoff.  If he re-bases it or drops it, our inventory layer needs a rework.
2. **Any type-curve or EUR disclosure.**  This would replace our sector-average assumption and collapse the widest error band in the model — in either direction.
3. **Capital allocation under the new CEO.**  Dell'Osso built Expand through consolidation.  A deal in either direction restates the whole stack.
4. **Pace and budget.**  The ~25 net wells per year and the $365–390M drilling budget are the scheduling inputs behind the inventory layer.
5. **Net debt and buybacks.**  Both flow straight through the floor math.
6. **In-basin demand color.**  Data centers, power deals, basis commentary — interesting, but nothing in the $194 depends on any of it.

## Portfolio action

We are taking a 2.0% position at the close of the first trading day after publication.  GPOR trades $65–90M a day, so liquidity is not a consideration at this size.  Stating the intent in advance: we would add on a print that clears the first two watch items with the price still near the floor-plus-plan level around $162, and we will reassess the entire position if the screened-inventory framing is walked back.

## What survives if you believe less than we do

Believe only the engineer-certified floor and you own $97 — 38% below today's price.  Say that plainly: this is not a floor-protection stock; the cheapness lives in the inventory.  Believe the floor plus the funded five-year plan and you own $162 — about today's price.  Add the screened decade beyond the plan at a quarter credit and the weakest type curve we consider defensible, and you are at $178 — 12% above the market.  Our center case is $194.

The asymmetry is the point: at today's price, the entire decade of inventory beyond the funded plan comes free — and even its weakest defensible version clears the price.

---

*Update (July 24, 2026, after publication): a reader correctly pointed out that we never stated our discount rate.  Added the disclosure in the floor section and to the machine-readable context — 10% nominal throughout the stack.  No numbers or conclusions changed.*

---

## Update — the Q2 print (August 4, 2026)

Gulfport reported second-quarter results Monday evening and held the call Tuesday morning — Dell'Osso's first as CEO.  The market's verdict was −4.9%, to $155.75.  Ours, scored against the six items we put on record before the print, is below.  The short version: the load-bearing claim survived the CEO change verbatim, the balance sheet moved against us by a few dollars a share buying inventory we had carried at zero, and the print triggered the add we committed to in advance.

**What printed:**

| | Q2 2026 |
|---|---|
| Production | 962.8 MMcfe/d (91% gas) |
| Adjusted EBITDA / adjusted FCF | $179.1M / $6.4M |
| D&C capex — quarter / full-year guide | $141.7M / ~$395M (guide was $365–390M) |
| Buybacks — quarter / first half | $70.0M at ~$178.50 avg / $242.8M |
| Net debt at 6/30 | $928.9M (was $821.2M at 3/31) |
| Shares outstanding | 17.7M (was 17.97M) |
| Inventory added | ~16 net state-land + ~40 net discretionary locations; Utica net inventory up more than 20%, runway +2.5 years |

**The scorecard, item by item:**

1. **Inventory framing — pass, emphatically.**  The new CEO's first deck restates the claim verbatim: ">700 gross locations and over 15 years of net inventory with break-even prices below $2.50/MMBtu," footnoted to the same 20–25 wells-per-year cadence.  On the call: "sitting at around 15 years of drilling inventory… the depth is pretty attractive."  The framing did not merely survive the handoff — it was re-based upward, now pro forma for roughly 56 new net locations.
2. **Type curve / EUR — nothing printed.**  The sector-average assumption stands and the wide band stays.  The qualitative signal ran our way: the latest Marcellus pad "exceeded expectations" on both gas and liquids rates at drilling costs about 25% lower per foot.
3. **Capital allocation — pass.**  No deal.  Dell'Osso's stated bar for M&A is high ("better and not just bigger"), buybacks continue, and the stated preference is to bring leverage down through the year.  One new thread to watch: the SCOOP is under strategic review — "more to come."
4. **Pace and budget — pass with a flag.**  The 2026 plan is 26 gross turn-in-lines, matching our ~25 net per year input.  The D&C guide moved to ~$395M, above the $365–390M we priced — about 5% more per well, partly optical since actual laterals are running 17,800+ feet against the 15,800 we costed.
5. **Net debt and buybacks — the material move.**  Net debt rose $108M in the quarter: $70M of buybacks executed near $178.50 — above today's price — plus $40M of acreage, against adjusted free cash flow of just $6.4M in a deliberately front-loaded capital year.  Share count fell 1.5%.
6. **In-basin demand — the bonus item ran positive.**  Basis tightening into lower Henry Hub prices ("green shoots," in management's words), 60 MMcf/d of firm transport released as a netback trade, and a credit upgrade.  Nothing in our number leans on any of it.

One item we did not put on the watch list: CFO Michael Hodges resigns effective August 5, with a search firm retained and an advisory period through September 1.  The company says — and the 8-K language supports — no disagreement on operations, policies, or financial reporting.  It is still the second senior departure this year, and we note it rather than explain it away.

**What it does to the stack.**  This is roll-forward arithmetic, not a model re-run — the full refresh follows the new filings.  Pushing the new net debt and share count through otherwise-unchanged layers: the floor moves from $97.41 to about $93, floor-plus-plan from $162 to about $158, and the center from $194 to about $191.  That arithmetic gives the new acreage no credit at all.  On the stack's own conservative convention — a quarter credit on locations beyond the funded plan — the ~56 locations are worth roughly $8 per share against the roughly $12 per share the full program costs; if they are as near-term as management describes (these compete for capital immediately, which is plan-tranche treatment at a 0.60 credit), the exchange is clearly accretive.  We will let the model re-run price it properly rather than settle it by hand here.

**Payoff at the new price.**  Against Tuesday's $155.75 close: the rolled-forward center is about $191, or +23%.  The weak-type-curve stack rolls to about $174, +12%.  Floor-plus-plan sits at about $158 — the market price, again, pays the floor and the funded plan and hands over the rest of the decade for nothing.  The floor is about $93, −40%.

**Portfolio action.**  We stated the intent in advance: add if the first two watch items cleared with the price still near floor-plus-plan.  Item 1 cleared as strongly as it could have; item 2 printed nothing in either direction, and we read "no adverse disclosure" as clearing — the honest alternative reading is that it was simply not tested.  The price is below the add level, not near it.  We are doubling the position from 2% to 4% at the close on Wednesday, August 5, and stating that here before execution, same convention as the original entry at $154.13.

---

*A note on process: this post was written in collaboration with an AI assistant.  That should surprise no one — an automated analyst pipeline is what this site is.  The valuation model, the numbers, and the sensitivity runs come from that pipeline; the assistant also helped assemble the fact base, check claims against the filings, and draft passages of this post.  The thesis, the judgment calls, and the final words are mine.  It ships under my name because the responsibility is mine — including any errors.*
