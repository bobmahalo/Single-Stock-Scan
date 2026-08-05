
================================================================================
 ANTIGRAVITY PIPELINE: SINGLE STOCK ENGINE V2 | TARGET: SEZL
================================================================================
Fetching fundamental data... (This may take 15-20 seconds)

================================================================================
 THE TRADING DASHBOARD (Macro & Options)
================================================================================
  [ MACRO EVENT RADAR (45-Day) ]
  ⚠️ Non-Farm Payrolls (NFP) & Unemployment in 2 Days (2026-08-07)
  ⚠️ Core CPI Inflation Data in 7 Days (2026-08-12)
  ⚠️ Non-Farm Payrolls (NFP) & Unemployment in 30 Days (2026-09-04)
  ⚠️ Core CPI Inflation Data in 37 Days (2026-09-11)
  ⚠️ FOMC Rate Decision & Press Conference in 42 Days (2026-09-16)

  [ GAMMA EXPOSURE (GEX) & EXPECTED MOVE ]

Initializing Schwab Client...
Debug: Client initialized with Key: 2Hy2...
Debug: Token expired, refreshing...
Current Price of SEZL: $183.31
Fetching options chain from 2026-08-05 to 2026-09-19...

[!] No options found for TACTICAL RADAR (0-14 DTE)

================================================================================
 STRUCTURAL ANCHOR (30-45 DTE) FOR SEZL
================================================================================
Strike     | Put OI     | Call OI    | Put GEX      | Call GEX     | Net GEX     
--------------------------------------------------------------------------------
$105.00        | 54         | 72         | -11          | 0            | -11         
$110.00        | 2          | 99         | -0           | 10           | 10          
$120.00        | 20         | 18         | -4           | 4            | -0          
$125.00        | 36         | 9          | -11          | 2            | -9          
$130.00        | 37         | 34         | -11          | 10           | -1          
$135.00        | 105        | 3          | -42          | 1            | -41         
$140.00  <-- EM LOWER BOUND | 29         | 29         | -12          | 12           | 0           
$145.00        | 10         | 20         | -4           | 8            | 4           
$150.00        | 14         | 15         | -7           | 8            | 0           
$155.00        | 189        | 32         | -94          | 16           | -78         
$160.00        | 268        | 17         | -161         | 10           | -151        
$165.00        | 109        | 12         | -65          | 7            | -58         
$170.00        | 76         | 35         | -46          | 21           | -25         
$175.00        | 6          | 48         | -4           | 29           | 25          
$180.00        | 32         | 154        | -22          | 108          | 85          
$185.00        | 48         | 87         | -34          | 61           | 27          
$190.00        | 35         | 127        | -24          | 89           | 64          
$195.00        | 9          | 278        | -6           | 195          | 188         
$200.00        | 12         | 300        | -8           | 210          | 202         
$210.00        | 3          | 568        | -2           | 341          | 339         
$220.00        | 0          | 19         | 0            | 11           | 11          
$230.00  <-- EM UPPER BOUND | 1          | 179        | -1           | 107          | 107         
$240.00        | 2          | 150        | -1           | 75           | 74          
$280.00        | 23         | 1          | -7           | 0            | -7          
================================================================================

[ STATISTICAL EXPECTED MOVE ]
Calculated EM: +/- $44.58
Expected Range: $138.73 to $227.88

[ SUGGESTED STRIKES (STRUCTURAL) ]
Major Support (Lower Bound)    : $160.00 (Put GEX: -161)
Major Resistance (Upper Bound) : $210.00 (Call GEX: 341)

Action: Sell the Put spread below the support, and sell the Call spread above the resistance.
================================================================================

[+] Successfully exported clean data to gex_structural.csv

Debug: Client initialized with Key: 2Hy2...

================================================================================
 TACTICAL BWB (BROKEN WING BUTTERFLY) FOR SEZL
================================================================================
  *What is this? We find the invisible Gamma Wall where Market Makers will defend
  the stock from crashing. We build a trap right at that wall. If it crashes,
  we collect max profit. If it goes up instead, the trap breaks and we still
  keep a small credit. You literally cannot lose money on the upside.*
--------------------------------------------------------------------------------
  [!] No short-term options chain found for SEZL within 7 days.
Debug: Client initialized with Key: 2Hy2...

================================================================================
 CASH-SECURED PUTS (14-45 DTE) FOR SEZL
================================================================================
  *What is this? You sign a contract promising to buy this stock next month
  if it drops in price, but you get paid cash right now for that promise.
  If it drops, you buy the stock on sale. If it doesn't drop, you keep the cash.*
--------------------------------------------------------------------------------

  [ CAPITAL PRESERVATION: THE ULTRA-SAFE CSP ]
  SELL 1x 2026-09-18 (44-DTE) $145.00 Put
  Premium Collected: $6.50
  Annualized Yield : 37.2%
  Safety Margin    : 24.4% (Breakeven: $138.50)
  Max Pain Anchor  : $160.00 (Strike is protected)

  [ INCOME ACCUMULATOR: THE HIGH-YIELD CSP ]
  SELL 1x 2026-08-21 (16-DTE) $175.00 Put
  Premium Collected: $11.50
  Annualized Yield : 149.9%
  Safety Margin    : 10.7% (Breakeven: $163.50)
================================================================================

Debug: Client initialized with Key: 2Hy2...
Debug: Client initialized with Key: 2Hy2...

================================================================================
 THE BULL RISK REVERSAL (ZEBRA) FOR SEZL
================================================================================
  *What is this? You sell a Put at the exact floor where Market Makers are
  defending the stock, getting paid cash. You immediately use that cash to
  buy a Call at the ceiling. If the stock crashes, you buy it on sale at the
  floor. If it rips through the ceiling, you have unlimited profit for zero cost.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-09-18 (44-DTE)

  [ SUGGESTED RISK REVERSAL SETUP ]
  SELL 1x  $160.00 Put  (Credit: $11.00)  <-- Gamma Support Wall
  BUY  1x  $230.00 Call (Debit : $11.00)  <-- Gamma Resistance Wall
  Total Net Credit : $0.00 (Literally a free trade)
  Capital Required : $16,000.00 (To secure the put assignment if it crashes)
  Max Upside Profit: UNLIMITED
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 JADE LIZARD SETUP (30-45 DTE) FOR SEZL
================================================================================
  *What is this? You collect massive income from selling a put, and use that
  cash to fully finance a call spread above the stock. Zero upside risk.
  If the stock crashes, you buy it on sale. If it rips to the moon,
  you still make money even if the call spread blows up.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-09-18 (44-DTE)

  [!] NO SAFE JADE LIZARD FOUND (Insufficient Premium).
  *Mathematical Rule: Total premium collected must exceed call spread width to eliminate upside risk.*
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 LEAPS HUNTER (300+ DTE) FOR SEZL
================================================================================
  *What is this? Instead of paying $32,000 to buy 100 shares of stock, you
  pay $500 to rent the *rights* to 100 shares for two years. If it goes up,
  your $500 agreement goes up exactly as if you owned the $32,000 in shares.*
--------------------------------------------------------------------------------
  Target Expiration: 2028-01-21 (534-DTE)

  [ CAPITAL PRESERVATION: STOCK REPLACEMENT (DITM) ]
  BUY 1x $25.00 Call (Price: $160.50)
  Delta: 1.00 (Moves 1:1 with stock)
  Leverage: 1.1x (Cheaper than 100 shares)
  Time Rent (Extrinsic): 1.30%
  Breakeven: $185.50

  [!] No suitable Lottery Ticket LEAPS found.
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 HIGHLY SPECULATIVE PLAYS FOR SEZL (HIGH RISK / HIGH REWARD)
================================================================================
  *What is this? Pure directional lottery tickets. You are betting that the
  stock explodes violently, or that it breaks a resistance wall forcing
  Market Makers to panic buy millions of shares to cover their short calls.*
--------------------------------------------------------------------------------

  [ VOLATILITY ERUPTION: THE ATM STRADDLE ]
  Target Expiration: 2026-08-21 (16-DTE)
  BUY 1x $185.00 Call (Price: $15.65)
  BUY 1x $185.00 Put  (Price: $17.95)
  Total Premium Risk: $33.60
  Implied Move Needed: ±18.35%
  Breakevens: < $151.40 OR > $218.60
  *Logic: You don't care about direction, only velocity. Best played before earnings.*

  [!] No valid Gamma Squeeze target found.
================================================================================


================================================================================
 PRONG 1: THE COMPANY (Critical Fundamentals)
================================================================================
  Price:             $183.12
  Market Cap:        $6,157,612,032
  Next Earnings:     N/A
  Directly Registered: 5,561 Shareholders (High Conviction Base)

  [ VALUATION & GROWTH ]
  P/E Ratio:         43.59
  PEG Ratio:         1.04
  P/TBV:             31.91
  Shareholder Yield: 1.43% (Div: 0.0% | Buybacks: 0.0%)

  [ FINANCIAL HEALTH ]
  Altman Z-Score:    16.00 (>3.0 is Safe)
  Current Ratio:     3.65
  Piotroski F-Score: 6 / 9
  ROIC (Annualized): 92.72%
  FCF Yield:         5.71%

  [ SEC FINANCIAL TRAJECTORY ]
  Verdict:           PASS (Score: 84.8)
  FCF Grade:         A - Strong growth +8065%, 80% quarters improving
  Net Income Grade:  B - Good growth +160%, mixed consistency
  Revenue Grade:     A - Strong growth +113%, 86% quarters improving

  [ MANAGEMENT & BOARD (SKIN IN THE GAME) ]
  Insider Score:     0/100
  Net Insider Trade: $-29,575,869
  Comp Score:        0/100 (Equity vs Cash)
  Overall Integrity: 20/100

================================================================================
 PRONG 2: THE MARKET (Structural & Derivatives)
================================================================================

  [ MARKET REGIME & TREND ]
  [ MARKET REGIME & TREND ]
  VIX Regime:        🟡 NORMAL (VIX: 16.99)
  Trend Verdict:     🟡 CONDITIONAL — Some signals good, watch the weak spots.

  [ ACCUMULATION / DISTRIBUTION ]
  Verdict:           HOLD / WATCH
  Insider Signal:    WHALE ACTIVITY
  Whale Alerts:      2 Active 13D/A Filings Found!

  [ OFF-EXCHANGE & SHORT INTEREST ]
  Avg Dark Short Vol: 143,507 shares/day
  Avg Dark Short %:   68.9% of Off-Exchange Volume

================================================================================
 APPENDIX: HOW TO READ THIS REPORT (THE PLUMBER'S VERSION)
================================================================================
# SINGLE STOCK ENGINE V2 — MASTER METHODOLOGY

This document outlines every section of the `Single_Stock_Engine_V2.py` report, providing both a "Plumber's Version" (simple terms) and the "Meat & Potatoes" (technical mechanics) for each engine.

---

## 1. TACTICAL BWB (0-7 DTE)
**The Plumber's Version:** Market Makers (the house) don't want to lose money. They build invisible walls (Gamma walls) to stop the stock from crashing. We build a trap right exactly at that wall. If the stock crashes, it hits the wall, bounces, and we collect maximum profit. If the stock goes up instead, the trap just breaks and we still keep a small credit. You literally can't lose money on the upside.

**Meat & Potatoes (Technical Mechanics):**
*   **Target:** 0-7 Days to Expiration (DTE).
*   **Logic:** The engine calculates the Expected Move (EM) using At-The-Money (ATM) Implied Volatility (IV). It then scans the massive Put Gamma (GEX) data to find the largest negative GEX strike below the current price (the Market Maker support wall). 
*   **Structure:** It constructs a Broken Wing Butterfly (BWB) by selling 2x Puts exactly at the Gamma wall, buying 1x closer Put for protection, and buying 1x further Put (the broken wing) to finance the trade. The trade must be entered for a net credit, eliminating all upside risk.

---

## 2. CASH-SECURED PUTS (14-45 DTE)
**The Plumber's Version:** You want to buy a house, but you think the price is too high right now. Instead of buying it today, you sign a contract saying "I promise to buy this house next month if the price drops by 10%, but you have to pay me $500 right now for that promise." If the price drops, you buy the house on sale (which you wanted anyway). If it doesn't drop, you keep the $500 for free. 

**Meat & Potatoes (Technical Mechanics):**
*   **Target:** 14-45 DTE.
*   **Logic (Ultra-Safe):** Mathematically optimizes for `Yield * Safety^2`. It hunts for the deepest Out-Of-The-Money put that still provides acceptable yield. It then cross-references the option chain's Max Pain level, applying a mathematical boost to strikes protected *below* the Max Pain wall.
*   **Logic (High-Yield):** Optimizes for `Yield^2 * Safety` to find a strike closer to the money, maximizing the annualized yield for aggressive accumulation.

---

## 3. THE BULL RISK REVERSAL / ZEBRA (30-45 DTE)
**Goal:** Pure directional leverage funded by market makers, with zero upfront cost.
**The Play:** Sell an OTM Put exactly at the Gamma Support Wall. Use 100% of the premium collected to immediately Buy an OTM Call at the Gamma Resistance Wall.
**The Logic:** If you believe in a stock and want to own it, you shouldn't mind being assigned on a short put. By selling that put, you generate cash. Instead of keeping the cash, you buy a lottery ticket (Long Call) on the upside.
*   **If it crashes:** You buy 100 shares of a company you love, on sale, at the support wall.
*   **If it stays flat:** Both options expire worthless. You lose nothing, because the short put paid for the long call.
*   **If it rips:** You capture infinite upside from the Long Call, exactly as if you owned 100 shares, but you paid $0.00 to enter the trade.
*   **Note:** The engine explicitly forces a setup that results in a Net Credit or $0.00 cost.

## 4. JADE LIZARD (30-45 DTE)
**The Plumber's Version:** You want to collect income from a stock you think will trade sideways or go up, but you are terrified of it ripping higher and blowing up your short call. A Jade Lizard solves this. You sell a Put to collect fat premium, and use that cash to fully finance a Call spread above the stock. If the stock crashes, you buy it at a discount. If the stock rips to the moon, the premium you collected is mathematically larger than the width of the Call spread, meaning you still make money even if the spread blows up. Zero upside risk.

**Meat & Potatoes (Technical Mechanics):**
*   **Target:** 30-45 DTE.
*   **Logic:** The engine finds the Expected Move (EM) boundaries. It sells an OTM Put below the stock to collect a large credit. It then builds a Call Credit Spread (selling a call at EM upper bound, buying a call further out). 
*   **Safety Rule:** The algorithm strictly enforces that the total premium collected must be *greater* than the width of the Call Spread. This mathematically eliminates upside risk, creating a "Net Upside Edge."

---

## 5. LEAPS HUNTER (300+ DTE)
**The Plumber's Version:** Instead of paying $32,000 to buy 100 shares of Google, you pay $500 to rent the *rights* to 100 shares of Google for the next two years. If Google goes up, your $500 rent agreement goes up in value exactly as if you owned the $32,000 in shares. It's just massive leverage for pennies.

**Meat & Potatoes (Technical Mechanics):**
*   **Target:** 300+ DTE.
*   **Logic (Stock Replacement):** Hunts for Deep In-The-Money (DITM) options with a Delta of 0.80 - 1.00. It calculates the "Time Rent" (Extrinsic Premium %) for every option in the chain, finding the exact strike that provides maximum leverage for the lowest cost of time decay.
*   **Logic (Lottery Ticket):** Hunts Out-Of-The-Money (OTM) options (Delta 0.15 - 0.35) to find the absolute highest leverage possible for the lowest absolute cash outlay, providing asymmetric convexity.

---

## 6. SPECULATIVE PLAYS
**The Plumber's Version (Straddle):** You don't know if the stock is going to moon or crash, but you know it's going to do *something* massive (like earnings). You bet on both horses. As long as the stock explodes in one direction, the winning horse pays for the losing horse and then some.
**The Plumber's Version (Gamma Squeeze):** You find the massive wall Market Makers built above the stock. You buy a cheap lottery ticket right below the wall. If retail pushes the stock hard enough to break the wall, the Market Makers panic, buy millions of shares to cover their asses, and accidentally launch your lottery ticket to the moon.

**Meat & Potatoes (Technical Mechanics):**
*   **Straddle (14-30 DTE):** Dynamically finds the cheapest At-The-Money Call and Put. Combines them into a Straddle and calculates exactly how much of a percentage move is required to break even. Highly reliant on Volatility Expansion.
*   **Gamma Squeeze (0-14 DTE):** Scans the short-term options chain for massive OTM Call Open Interest walls. Targets a cheap call slightly below the wall to front-run the MM delta-hedging feedback loop (Gamma Squeeze).

---

## 7. THE FUNDAMENTALS
**The Plumber's Version:** You are kicking the tires on a used car before you buy it. You check the engine (ROIC), make sure it's not leaking oil (Piotroski Score), ensure the dealer isn't going bankrupt next week (Altman Z-Score), and check if the previous owners actually liked the car (Insider Buying).

**Meat & Potatoes (Technical Mechanics):**
*   **Altman Z-Score:** A 5-factor model predicting bankruptcy risk. Anything > 3.0 is exceptionally safe.
*   **Piotroski F-Score:** A 9-point accounting checklist scoring profitability, leverage, and operating efficiency. 
*   **ROIC:** Return on Invested Capital. The ultimate moat metric.
*   **Shareholder Yield:** Dividend Yield + Buyback Yield. Shows if management is returning capital to owners.
*   **SEC Trajectory:** Scrapes actual SEC EDGAR filings to grade the multi-year trajectory of Revenue, Net Income, and Free Cash Flow.


================================================================================
 SCAN COMPLETE.
 Report Saved: ~/Desktop/antigravity/Single_Stock_Pipeline/reports/SEZL_V2_Master_Report.md
================================================================================

