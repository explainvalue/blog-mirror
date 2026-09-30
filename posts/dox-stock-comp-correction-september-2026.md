---
title: "Correcting how we treat stock compensation: exiting DOX"
slug: dox-stock-comp-correction-september-2026
date: 2026-09-29
summary: "When we published on Amdocs we valued its cash flow with stock compensation added back, and treated the charge as a haircut to test. We have since applied one rule across every company we value: stock compensation is a cost. With that correction the margin of safety on DOX is not there, so we are exiting the position."
author: Bobak Farzin
tags: [DOX, dcf-fcff, Technology, portfolio-update]
hero_ticker: DOX
portfolio_update: true

agent_context:
  "@context": "https://explainvalue.ai/schema/v1/agent-context"
  "@type": "PortfolioUpdatePost"
  publication_date: "2026-09-29"
  correction: "Stock-based compensation charged as a cost in the free cash flow we value: trailing FCF $638.8M as filed -> $528.4M after a $110.4M charge (17.3%)."
  positions:
    - ticker: "DOX"
      corrected_fair_value_usd_per_share: 68.67
      prior_fair_value_usd_per_share: 94.4
      reference_market_usd_per_share: 57.59
      action: "exit"
      supersedes_post: "dox-priced-for-zero-growth-september-2026"
---

We did not handle stock compensation properly when we valued Amdocs (DOX). We have corrected it, the correction removes our margin of safety, and we are exiting the position.

## What we got wrong

In [our September post](/blog/dox-priced-for-zero-growth-september-2026) we valued Amdocs on its free cash flow as filed, $638.8M over the trailing twelve months. That number adds stock compensation back, which is the standard convention. We listed the charge as one of three wrinkles and showed it as a haircut: charge it, and the flat value drops about 16%.

Since then we have valued a couple of hundred companies with the same process, and we set one rule for all of them: stock compensation is a real cost, and it comes out of every company's cash flow before anything is projected. Amdocs does not get an exception.

We also had the size of the charge wrong, at about $87M a year. The filings show $110.4M over the trailing twelve months, which is 17% of the cash flow we valued, and it is still rising. One of the things we said you had to believe was that stock compensation stops climbing. Its own filings already say otherwise.

## What the correction does

| | Original (stock comp added back) | Corrected (stock comp charged) |
|---|---|---|
| Trailing twelve-month FCF | $638.8M | $528.4M |
| Value if FCF stays flat forever | $63 | $50 |
| Model fair value | $94 | $74 |
| Value we can defend after our own review | | **$69** |
| Market price | $63.06 (Aug 31) | $57.59 (Sep 29) |

*(Flat values use the same inputs as the original table: WACC 8.4%, net debt $881M, 107.6M shares. Estimates are rounded to the dollar.)*

Our original thesis was that the price paid for the flat case and any growth came free. With the charge the flat case is worth about $50, which is below the price. The market is already paying for some growth, so that argument no longer holds.

The value we can defend is about $69 but that does not leave a sufficient margin of safety for our work. On our own rule DOX is fairly valued and we are closing the position.

## The position

We opened a 1% position at $62.46 on September 2. At the latest close of $57.59 it is down about 8%. We will close it at the close of the next trading day after this post, per our standard convention.

This exit is on our correction and not on a result from the company.

## What replaces it

DOX was the first name from a screening process we were still building. We have since applied that process across the S&P 1500, with the stock compensation rule built in, and we will describe it in a coming post. The names that come out of it will be published one theme at a time.

Like all names, we will keep comparing the price of DOX with our estimate of its value, and we could open a new position if a sufficient margin of safety appears.

---

*A note on process: this post was written in collaboration with an AI assistant. That should surprise no one — an automated analyst pipeline is what this site is. The valuation model, the numbers, and the review of the filings come from that pipeline; the assistant also helped assemble the fact base and draft passages of this post. The thesis, the judgment calls, and the final words are mine. It ships under my name because the responsibility is mine — including any errors.*
