---
title: "BMY at $61.48: Worth About $76 Under Our Updated Method"
slug: bmy-value-update-october-2026
date: 2026-10-25
summary: "Our updated pharma method values BMY at about $76 a share, 23% above Friday's $61.48 close. That is down from April's $83, but the reasons changed: charging Pfizer's Eliquis share to Eliquis alone and reading BMY's own margins added value, while a higher discount rate and Cobenfy's patents took it out. If BMY never discovered another drug, we would still value it at about $55."
author: Bobak Farzin
tags: [BMY, pharma-SOTP, Healthcare]
hero_ticker: BMY
portfolio_update: true

# ── Agent-readable context (rendered as JSON-LD, invisible to humans) ──
agent_context:
  "@context": "https://explainvalue.ai/schema/v1/agent-context"
  "@type": "InvestmentThesisPost"
  ticker: "BMY"
  company_name: "Bristol-Myers Squibb Company"
  method: "pharma-sotp"
  asof_date: "2026-10-25"
  publication_date: "2026-10-25"
  fair_value_usd_per_share: 75.90
  reference_market_usd_per_share: 61.48
  shares_outstanding_billion: 2.0427
  net_debt_usd_billion: 35.47   # claims 47.26 less cash 11.79, from the 2026-06-30 10-Q
  layers:
    - name: "Drugs on sale, after partner payments, less their support R&D"
      pv_usd_billion: 99.3
      subjectivity_level: "medium"
      key_drivers: ["Opdivo, Eliquis and Orencia lose exclusivity in 2028", "Pfizer's Eliquis share charged on Eliquis", "company product margin (before R&D) 0.717"]
    - name: "Named pipeline, less cost to finish"
      pv_usd_billion: 36.0
      subjectivity_level: "high"
      key_drivers: ["most pipeline peaks are benchmark estimates", "admilparant, mezigdomide, zola-cel, arlo-cel, milvexian"]
    - name: "R&D for future drugs (engine and early work)"
      pv_usd_billion: 54.6
      subjectivity_level: "high"
      key_drivers: ["one sector R&D factor"]
  alternative_views_worth_raising:
    - layer: "Drugs on sale"
      anchor: "Eliquis earns more than BMS's average margin before Pfizer's share (about 0.82 at BMS's company-wide selling-cost ratio)"
      delta_per_share_usd: -2.30
      detail: "Our rule assumes Eliquis earns the company average before Pfizer's share; at the filing's limit (BMS keeps no more than it pays Pfizer) the value is about 5.70 lower."
    - layer: "Named pipeline"
      anchor: "Drop the Reblozyl myelofibrosis row as a double count of the stored $4B Reblozyl peak"
      delta_per_share_usd: -0.58
      detail: "The $4B peak traces to a 2023 company figure that already included myelofibrosis; the myelofibrosis trial missed its primary endpoint."
    - layer: "Bridge"
      anchor: "Charge the Celgene CVR suit in full"
      delta_per_share_usd: -3.13
      detail: "$6.4B alleged; BMS disputes it and the plaintiff has appealed."
  key_uncertainties:
    - "Company product margin: +/-5 points moves value by about +/-7"
    - "R&D factor: +/-0.1 moves value by about +/-7"
    - "Discount rate: +/-0.5 points gives about 69 / 84"
  source_artifacts:
    - kind: "cached_valuation"
      path: "/srv/shared-cache/valuations/BMY/pharma-sotp.json"
      description: "pharma-sotp value 75.90, cached 2026-10-25 15:54 UTC (run 20261025_143757)"
  agent_guidance_for_readers:
    - "Ask what the price implies about BMY's R&D: at $61.48 the market pays for about 23% of our credit for future drugs."
  position:
    portfolio_weight_pct: 2.0
    target_usd_per_share: 76
    action: "hold at 2%; target 76 (was 83); no new entry at this price; exit at full value"
    benchmark: "SPY (residual)"
---

<div class="stat-row">
  <div class="stat">
    <div class="label">Fair value (full method)</div>
    <div class="value">$76</div>
    <div class="sub">drugs, pipeline and R&D, net of claims</div>
  </div>
  <div class="stat">
    <div class="label">If BMY stopped discovering</div>
    <div class="value">$55</div>
    <div class="sub">today's drugs and named pipeline only</div>
  </div>
  <div class="stat">
    <div class="label">Market price</div>
    <div class="value">$61.48</div>
    <div class="sub">close, Friday, October 23, 2026</div>
  </div>
</div>

Under our [updated pharma method](/blog/pharma-method-update-october-2026),
BMY is worth about $76 a share, 23% above Friday's close of $61.48. In April
we put it at $83. The number came down, but the reasons changed. Charging
Pfizer's share of Eliquis to Eliquis alone, and reading BMY's own margins
from its filings, added value. A higher discount rate and Cobenfy's granted
patents took value out.

If BMY never discovered another drug, we would still value it at about $55,
not far below the price. At $61.48 the market pays for less than a quarter
of what we credit BMY's R&D for future drugs.

> **On pricing.** This post publishes on Sunday, October 25, 2026. Our
> reference price is Friday's close, $61.48. We are not trading BMY; the
> only portfolio change is our target, from $83 to $76. BMY reports
> third-quarter results on Thursday, October 29.

## The value in one block

```
  Drugs on sale (after partner payments)              $62.26
  − Support R&D for those drugs                       −13.66
  + Named pipeline (risk-adjusted)                    +22.57
  − Cost to finish the pipeline                        −4.95
  + R&D for future drugs (engine)                     +22.59
  + Early work already paid for                        +4.15
  + Other                                              +0.19
                                                     ───────
  Operating value                                     $93.15
  + Tax losses                                         +0.11
  + Cash − claims (June 30 10-Q)                      −17.36
  ───────────────────────────────────────────────────────────
  =  Value per share                                  $75.90
```

## What changed since April

In April we valued BMY at $83. It is about $76 now. The method changed
underneath ([what changed](/blog/pharma-method-update-october-2026)), so there
is no exact line-by-line bridge, but the big pieces are clear:

- **Partner payments.** BMS pays Pfizer about half of Eliquis's profit,
  $6.98B in 2025, and books it inside its own costs. Measured after that
  payment, BMS's margin carried Pfizer's share on every drug, including the
  ones that keep selling after Eliquis goes generic in 2028. We now charge it
  to Eliquis alone, which adds about $8 a share.
- **BMY's own margins.** We now read BMY's margins from its filings, year by
  year, with acquired R&D counted as a cost in the year it is booked.
- **R&D.** Each R&D dollar is charged once, to the job it does, so less of
  BMY's value rests on drugs nobody has named yet.
- **The discount rate.** April used 7.40%; today's is 8.12%. At April's rate
  BMY would be worth about $12 more.
- **Cobenfy.** April had Cobenfy at a $5B peak, protected to 2039. BMY's
  10-K now gives granted patents to 2030, and Cobenfy is worth well under $1
  a share. At April's reading it would add about $8.
- **The balance sheet.** Cash and claims now come from the June 30 10-Q,
  including the declared dividend and other claims beyond debt.

## Where the value sits

| drug | $/share | exclusivity |
|---|---:|---|
| Opdivo franchise | 14.12 | 2028 |
| Breyanzi | 6.53 | 2033 |
| Other growth products | 6.17 | none read |
| Orencia | 5.91 | 2028 |
| Camzyos | 4.93 | 2036 |
| Reblozyl | 4.84 | 2031 |
| Yervoy | 4.50 | biosimilar expected 2028 |
| Opdualag | 4.03 | 2034 |
| Eliquis | 3.40 | 2028 |

Eliquis is BMS's biggest seller at $15.8B a year, but it ranks ninth by
value. Pfizer's share is charged on it, and its U.S. exclusivity ends in
2028. The named pipeline is spread out: admilparant ($3.14), mezigdomide
($2.53), zola-cel ($2.19), arlo-cel ($2.09) and milvexian ($1.77) lead it,
and most of its peaks are benchmark estimates. R&D for future drugs adds
$26.74, about a third of the value.

## Where we could be wrong

- **Eliquis's own margin.** We assume Eliquis earns BMS's average product
  margin, about 72%, before Pfizer's share. The filings don't state it. At
  BMS's company-wide selling costs, Eliquis's margin looks closer to 82%,
  which would lower the value by about $2.30, and by up to $5.70 at the
  limit the filing's equal split allows.
- **Reblozyl.** Our model now carries a separate myelofibrosis row for
  Reblozyl, worth $0.58. It likely double counts: the $4B Reblozyl peak
  traces to a 2023 company figure that already included myelofibrosis, and
  that trial missed its primary endpoint.
- **Yervoy.** One biosimilar is in trials, so we expect entry in 2028. A
  later entry would add value.
- **The big dials.** Five points of product margin move the value about $7.
  So does 0.1 on our R&D factor. Half a point on the discount rate gives
  about $69 or $84.
- **Not in our numbers.** The Celgene CVR suit ($6.4B alleged, which BMS
  disputes) would cost $3.13 if charged in full, and BioNTech's $2.0B of
  anniversary payments would cost $0.98.

## What to watch on October 29

1. **Eliquis** against its raised 2026 guide.
2. **Opdivo and Qvantig,** and how fast intravenous Opdivo converts to the
   subcutaneous version.
3. **Reblozyl's growth,** and Yervoy's.
4. **Pipeline readouts.** A failure of admilparant would cost about $3, and
   of milvexian about $2.
5. **Cobenfy's patent extension,** which would add about $1.
6. **The September 30 balance sheet.** Each $1B of new claims costs $0.49.

## Portfolio action

We hold BMY at 2%, opened on April 29 at $57.59, and move our target from $83
to $76. At today's price we would likely not open a new position, but we keep
the one we have, and we will exit if BMY reaches full value.

## What survives if you believe less

| if you believe | value | vs. price |
|---|---:|---:|
| today's drugs and named pipeline, and BMY stops discovering | $55 | −10% |
| the full method, R&D for future drugs included | $76 | +23% |

The price sits just above the floor. A buyer at $61.48 pays for today's
drugs and named pipeline, plus less than a quarter of what we credit BMY's
R&D for future drugs.

---

*A note on process: this post was written in collaboration with an AI
assistant. That should surprise no one — an automated analyst pipeline is
what this site is. The valuation model, the numbers, and the sensitivity runs
come from that pipeline; the assistant also helped assemble the fact base,
check claims against the filings, and draft passages of this post. The
thesis, the judgment calls, and the final words are mine. It ships under my
name because the responsibility is mine — including any errors.*
