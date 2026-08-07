---
title: "Bigger banks earn less: the regulatory capital ladder"
slug: bank-regulatory-tiers-may-2026
date: 2026-05-18
summary: "The Fed's tailoring rule sorts US banks into four categories. As a bank grows across category boundaries, the minimum capital it must hold goes up — same earnings divided by a bigger denominator means a lower return on equity. This is the structural reason a $700B bank cannot earn what a $200B bank earns, even on identical underlying franchises. We explain the four tiers, what changes at each boundary, and why USB sitting near the Cat III/II boundary is a load-bearing input to our valuation."
author: Bobak Farzin
tags: [methodology, Financials, regulation]
hero_ticker: null
portfolio_update: false

agent_context:
  "@context": "https://explainvalue.ai/schema/v1/agent-context"
  "@type": "MethodologyPost"
  topic: "US bank regulatory capital tiers (Fed tailoring framework)"
  publication_date: "2026-05-18"
  audience: "practitioner"

  framework_summary: "The Federal Reserve's 2019 tailoring rule sorts US bank holding companies into four categories by asset size and complexity. Each category has different minimum capital ratios, stress-testing requirements, liquidity floors, and AOCI-inclusion rules. As a bank grows across a boundary, the regulatory cost steps up — mechanically reducing ROE on the same underlying earnings."

  categories:
    - tier: "Category I"
      threshold: "G-SIBs"
      examples: ["JPM", "BAC", "WFC", "C", "GS", "MS", "BK", "STT"]
      key_costs: ["G-SIB capital surcharge 1.0-3.5%", "Full LCR + NSFR", "Annual CCAR", "AOCI inclusion", "Advanced approaches RWA"]
    - tier: "Category II"
      threshold: ">=$700B assets OR >=$75B cross-jurisdictional activity"
      examples: ["USB (approaching)", "TFC"]
      key_costs: ["AOCI inclusion in CET1", "Full LCR + NSFR", "Annual CCAR", "Advanced approaches RWA"]
    - tier: "Category III"
      threshold: "$250B-$700B"
      examples: ["USB (current)", "PNC", "MTB", "SCHW"]
      key_costs: ["AOCI opt-out available", "Reduced LCR", "Biennial CCAR", "Standardized approach RWA"]
    - tier: "Category IV"
      threshold: "$100B-$250B"
      examples: ["HBAN", "FITB", "RF", "KEY", "CFG"]
      key_costs: ["AOCI opt-out available", "Reduced LCR", "Biennial CCAR (limited)", "Standardized approach RWA"]

  load_bearing_application:
    ticker: "USB"
    discussion: "USB sits at the Cat III/II boundary. AOCI-inclusion transition is the largest single mechanical effect — ~50-100bps CET1 hit when triggered. Until clarity, market discounts the buyback ramp pace and the franchise multiple. Modeled as ~$5/share of fair value at risk."
    linked_thesis_posts: ["/blog/usb-franchise-discount-may-2026"]

  source_artifacts:
    - kind: "regulation"
      label: "Federal Reserve Regulation YY tailoring framework"
      description: "Final rule 84 Fed. Reg. 59230 (November 1, 2019); subsequent amendments"
---

A bank's return on equity is net income divided by equity. The numerator is the earnings power of the franchise. The denominator — equity — is partly chosen by management and partly set by regulators. **The Federal Reserve raises the regulatory minimum as the bank gets bigger.** Same earnings, larger required denominator, lower ROE.

This is the structural reason a $700 billion bank cannot earn what a $200 billion bank earns, even on identical underlying franchises. It is why the largest US banks have spent the last decade trying to use up excess capital through dividends and buybacks rather than chasing growth. It is also why a bank like USB, sitting at the boundary between two categories, carries a real overhang on its valuation until the transition resolves.

This post explains the four tiers, what changes at each boundary, and why the tier mix matters when reading any bank's residual-income valuation.

## The four categories

The Fed's 2019 "tailoring rule" sorts US bank holding companies as follows:

| Category | Asset threshold | Examples | What it costs |
|---|---|---|---|
| **I — G-SIBs** | Designated globally systemically important | JPM, BAC, WFC, C, GS, MS, BK, STT | G-SIB capital surcharge (1.0-3.5% of RWA on top of all other requirements); full LCR + NSFR liquidity; annual CCAR; AOCI fully included in CET1; advanced-approaches RWA |
| **II** | ≥$700B assets or large cross-border activity | TFC; USB approaching | AOCI fully included in CET1; full LCR + NSFR; annual CCAR; advanced-approaches RWA |
| **III** | $250B–$700B | USB (current), PNC, MTB | AOCI **opt-out** available; reduced LCR; biennial CCAR; standardized RWA |
| **IV** | $100B–$250B | HBAN, FITB, RF, KEY, CFG | AOCI **opt-out** available; reduced LCR; biennial CCAR (limited); standardized RWA |

Below $100B in assets, banks fall outside the tailoring framework and face community-bank rules — a different regime not covered here.

## What actually changes at each boundary

Four mechanical things, in roughly decreasing order of capital impact:

**1. AOCI inclusion in CET1 (the biggest one).** Banks classified Cat I or II *must* include unrealized AFS securities losses and pension AOCI in their regulatory capital calculation. Cat III and IV banks can elect to opt out, which most do. When a bank crosses from Cat III to Cat II, AFS securities that lost value during a rate-hike cycle suddenly count against capital. For a bank carrying a few billion in net unrealized losses on its securities book, this can shave **50-100 basis points off the CET1 ratio** on the day the transition formally triggers — without anything changing about the underlying franchise.

**2. Stress testing cadence and the Stress Capital Buffer (SCB).** Cat I and II banks file CCAR annually; Cat III biennially; Cat IV has lighter requirements. Annual testing means the SCB — added to the 4.5% CET1 minimum to produce the effective floor — recalibrates each year off a more recent severe-stress scenario. In practice this often pushes the SCB up for larger banks. The cohort SCBs in our nine-bank super-regional screen range from 2.5% (HBAN, PNC, MTB, RF, TFC) to 4.5% (CFG) — a two-percentage-point spread in required capital that has nothing to do with the underlying franchise.

**3. Liquidity coverage and net stable funding ratios.** Cat I and II need the full Liquidity Coverage Ratio and Net Stable Funding Ratio. Cat III gets a "reduced" LCR (85% of full). Cat IV is more flexible still. The practical effect is more high-quality liquid assets held in the regulatory portfolio for larger banks — assets that earn less than the loans and securities they substitute for, again compressing ROE.

**4. Risk-weighted-asset methodology.** Cat I and II use the "advanced approaches" — internal models for credit and operational risk RWA, subject to Fed approval. Cat III and IV use the standardized approach. The advanced approaches can produce either higher or lower RWA depending on the bank's book composition; the variability is enough that some Cat III banks have actively delayed crossing the $700B threshold to avoid the methodology change.

## The math

For a bank with $4 billion of annual net income and $30 billion of common equity, ROE is 13.3%. If a regulatory transition raises the required CET1 from $25 billion to $28 billion — and the bank is held to that floor — then management has to either hold more capital (denominator grows) or generate less near-term earnings (numerator shrinks while the build happens). Either way, ROE compresses.

In residual-income terms, that compression flows directly into the fair-value math. RI fair value is book value plus the present value of all years of excess returns above the cost of equity. When the regulatory tier raises the floor on required capital, the **excess** returns above cost of equity shrink. The franchise might be the same; the value isn't.

This effect is the structural reason the Fed's tailoring categories are a load-bearing input to bank valuation. We do not adjust the cost-of-equity assumption across tiers (we use one industry beta for the cohort). What changes is the achievable ROE on regulatory capital — and through it, the terminal residual income that drives our fair value.

## USB at the Cat III/II boundary

USB is the working example in our current portfolio. The bank has about $680 billion in assets as of Q1 2026 and is trending up. Once their 4-quarter trailing average crosses $700 billion and stays there, Cat II classification triggers. At that point AOCI inclusion in CET1 becomes automatic.

The market knows this. The market also doesn't know:
- The exact quarter Cat II triggers
- The size of the AOCI hit when it does (depends on AFS securities marks at transition date)
- How USB management responds (pause buyback to rebuild capital? hold pace? raise capital?)

Until any of those three resolves, the stock carries an overhang. We modeled the bear case at approximately $5/share of fair value at risk (around 7% of our $75 RI fair value), which is the difference between a clean buyback ramp toward the disclosed 70-75% capital distribution target and a constrained ramp that defers the cap-return story by 4-6 quarters.

There is also a regulatory tailwind possibility: the current OCC and Fed have signaled willingness to revise Basel III Endgame rules. If AOCI-inclusion treatment for Cat I/II banks gets softened, the USB overhang dissolves substantially. USB management explicitly named this on the Q1 2026 call as "constructive Basel III proposal supportive of resuming long-term capital returns."

## What this means for reading any bank's valuation

When you look at a US bank's residual-income fair value, three things from this framework matter:

1. **Which category the bank is in.** A Cat I G-SIB earns less ROE on the same earnings power than a Cat IV regional bank. That isn't a bug in your valuation model; it's a real regulatory cost.

2. **Whether the bank is at a category boundary.** USB approaching Cat II is the live case in our current portfolio. Schwab is another (in Cat III pending Cat II implications). Boundary banks carry a transition discount in the market that reflects the uncertainty.

3. **Whether regulatory rules are themselves about to change.** Basel III Endgame revisions are in scope under the current administration. Specific changes to AOCI-inclusion treatment, the G-SIB surcharge calibration, or the SCB methodology can re-rate entire categories of banks. Watch the regulatory calendar, not just the earnings calendar.

We apply this framework explicitly in our [USB at $53.42 thesis](/blog/usb-franchise-discount-may-2026) — where the Cat II overhang is a named, quantified part of the bear case — and implicitly across the rest of our super-regional cohort, where the AOCI opt-out preserved for Cat III and IV is the reason CET1 ratios look more comfortable than they would under Cat II rules.

The framework is also why no single bank's ROE — current or projected — is interpretable without knowing what regulatory tier the bank is in. Same number, different meaning.
