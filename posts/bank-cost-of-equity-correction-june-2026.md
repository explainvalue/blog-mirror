---
title: "Correcting our bank cost of equity — exiting HBAN and USB"
slug: bank-cost-of-equity-correction-june-2026
date: 2026-06-30
summary: "We found that our cost-of-equity input for banks was too low: a 0.76 beta where the realized figure is about 1.1, which lifts Ke from about 7.7% to 9.1%. At the corrected rate HBAN trades above its fair value and USB's discount is gone, so we are exiting both positions."
author: Bobak Farzin
tags: [HBAN, USB, residual-income, Financials, portfolio-update]
hero_ticker: HBAN
portfolio_update: true

agent_context:
  "@context": "https://explainvalue.ai/schema/v1/agent-context"
  "@type": "PortfolioUpdatePost"
  publication_date: "2026-06-30"
  correction: "Bank cost-of-equity revised: beta 0.76 -> ~1.1 (realized), Ke ~7.7% -> ~9.1%."
  positions:
    - ticker: "HBAN"
      corrected_fair_value_usd_per_share: 15.98
      prior_fair_value_usd_per_share: 19.48
      reference_market_usd_per_share: 17.80
      action: "exit"
      supersedes_post: "hban-near-book-may-2026"
    - ticker: "USB"
      corrected_fair_value_usd_per_share: 62.44
      prior_fair_value_usd_per_share: 75.04
      reference_market_usd_per_share: 61.31
      action: "exit"
      supersedes_post: "usb-franchise-discount-may-2026"
---

We found an error in how we set the cost of equity - a key input for any discounting valuation model. It changed our view on two positions we hold and so we want to give an update on our choice to exit those positions today. 

## HBAN

### Estimated Cost of Equity Revision

When we initiated our valuation on HBAN we computed a cost of equity of 7.66%.  This was based on a beta of **0.76** sourced from Damodaran's "Bank (Money Center)" industry average.  In a review of all our valuation methods, we realized this value is not the correct input.  

Looking at HBAN's own realized beta over multiple instances we come to a value of about 1.11.  The cost of equity with that corrected beta is then 9.1%.  We took a few orthogonal methods and they all land at about 9%:

| Cost-of-equity lens | Estimate |
|---|---|
| CAPM, HBAN's own realized beta (~1.11) | ~9.1% |
| CAPM, calibrated bank-cohort beta (~1.12) | 9.14% |
| Cost-of-debt build-up (Kd ~5.3% + equity premium) | ~9.0% |
| Market-implied (invert the dividend-discount identity) | ~9.4% |

Two of these do not use the market price at all (CAPM on the realized beta; the debt build-up), so the result is not circular.  The old 7.66% is not defensible and it changes our estimate of fair value.  

### Earning the cost of capital removes the upside

We value banks with our residual-income method.  Beginning with book value we present value every year the bank earns **above** its cost of equity.  HBAN's ~14% return on *tangible* equity is equal to ~9.1% on *book* equity (because goodwill and intangibles are ~35% of book). Given that we estimate the cost of equity at 9%, that means that there is no residual to PV and so we value the company at the book value right now.  Correcting our cost of equity, we get these valuations today:

| Method | Original (Ke 7.66%) | Corrected (Ke 9.14%) |
|---|---|---|
| Residual income (book basis) | $19.48 | **$15.98** |
| Justified P/B (book basis) | $21.63 | **$15.79** |
| Consensus analyst target | $19.25 | $20.00 |
| Book value per share | $16.05 | $16.05 |
| Market price | $15.51 | ~$17.80 |

Given our correction the fair value is about $16, which is below the ~$17.80 the stock trades at today, so we see no reason to hold a position where we don't see value and we exit today at the close.  We bought HBAN at $15.57 in May, so even though the thesis did not work out, we exit with a 14% gain.  

## USB

We made the same beta error with USB that we made with HBAN: our estimate was too low. We revised it from 0.76 to about 1.1, which raises our cost of equity from 7.7% to 9.1%. Several methods all converge on a cost of equity of ~9.0% so we are confident this is accurate now.  The update changes our valuations:

| Method | Original (Ke 7.67%) | Corrected (Ke 9.14%) |
|---|---|---|
| Residual income | $75.04 | **$62.44** |
| Consensus analyst target | $62.00 | $63.00 |
| Market price | $53.42 | ~$61.31 |
| Book value per share | $41.92 | $42.38 |

Unlike HBAN, the call still worked. We bought USB at $53.45 in May and it is now about $61. We were right that it was undervalued, just by less than we said: part of the discount was our low beta, not the market.

USB remains a real franchise with a high ROTCE of ~17%. However, we don't see the deep discount that we saw before. Our original post said we would hold toward $70-75.

> "Hold until either method-convergent fair value is approached ($70-75 range) or any of the four falsifiers triggers."

But that target carried the same beta error; the corrected fair value was always closer to $62.

We are at the fair value our system predicts and so we will close out the position with the 13% gain we achieved so far.  Like with all names, we will continue to review prices versus our fair value estimates and could initiate a new position if we find a sufficient margin of safety.  

