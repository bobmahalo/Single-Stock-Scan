
================================================================================
 ANTIGRAVITY PIPELINE: SINGLE STOCK ENGINE V2 | TARGET: KO
================================================================================
Report Generated: 2026-08-13 06:22:28 HST

Fetching fundamental data... (This may take 15-20 seconds)

================================================================================
 THE TRADING DASHBOARD (Macro & Options)
================================================================================
  [ MACRO EVENT RADAR (45-Day) ]
  ⚠️ Non-Farm Payrolls (NFP) & Unemployment in 22 Days (2026-09-04)
  ⚠️ PPI Inflation Data in 28 Days (2026-09-10)
  ⚠️ Core CPI Inflation Data in 29 Days (2026-09-11)
  ⚠️ FOMC Rate Decision & Press Conference in 34 Days (2026-09-16)

  [ GAMMA EXPOSURE (GEX) & EXPECTED MOVE ]

Initializing Schwab Client...
Debug: Client initialized with Key: 2Hy2...
Current Price of KO: $87.57
Fetching options chain from 2026-08-13 to 2026-09-27...
Days to Earnings  : 68 Days (Date: 2026-10-20)
Near-Term ATM IV  : 📉 18% `[█░░░░░░░]`

================================================================================
 TACTICAL RADAR (0-14 DTE) FOR KO
================================================================================
Strike     | Put OI     | Call OI    | Put GEX      | Call GEX     | Net GEX     
--------------------------------------------------------------------------------
$80.00         | 6245       | 7146       | -4,438       | 5,012        | 574         
$82.50         | 2038       | 6495       | -4,687       | 14,938       | 10,251      
$83.00         | 1829       | 2070       | -4,304       | 5,047        | 742         
$84.00         | 2189       | 484        | -7,518       | 1,953        | -5,566      
$85.00         | 6308       | 20807      | -47,173      | 177,096      | 129,923     
$86.00  <-- EM LOWER BOUND | 4825       | 1660       | -63,050      | 21,310       | -41,740     
$87.00  <-- PRICE | 6172       | 5032       | -170,591     | 139,077      | -31,514     
$87.50  <-- PRICE | 652        | 7748       | -12,649      | 150,311      | 137,662     
$88.00  <-- PRICE | 1330       | 10047      | -43,007      | 369,640      | 326,633     
$89.00  <-- EM UPPER BOUND | 2448       | 7177       | -40,224      | 110,673      | 70,450      
$90.00         | 1504       | 19638      | -15,423      | 164,462      | 149,039     
================================================================================

[ STATISTICAL EXPECTED MOVE ]
Calculated EM: +/- $1.47
Expected Range: $86.10 to $89.04

[ SUGGESTED STRIKES (TACTICAL) ]
Major Support (Lower Bound)    : $87.00 (Put GEX: -170,591)
Major Resistance (Upper Bound) : $88.00 (Call GEX: 369,640)

Action: Monitor these levels for immediate volatility and Gamma squeeze potential.
================================================================================

[+] Successfully exported clean data to gex_tactical.csv


================================================================================
 STRUCTURAL ANCHOR (30-45 DTE) FOR KO
================================================================================
Strike     | Put OI     | Call OI    | Put GEX      | Call GEX     | Net GEX     
--------------------------------------------------------------------------------
$75.00         | 4473       | 1897       | -2,710       | 0            | -2,710      
$77.50         | 6429       | 1805       | -8,358       | 0            | -8,358      
$80.00         | 4645       | 3938       | -12,079      | 11,820       | -259        
$82.50  <-- EM LOWER BOUND | 2425       | 8839       | -11,640      | 48,614       | 36,974      
$85.00         | 3693       | 11566      | -27,326      | 92,528       | 65,202      
$87.50  <-- PRICE | 707        | 7812       | -6,151       | 70,308       | 64,157      
$90.00         | 1976       | 13695      | -13,634      | 94,489       | 80,854      
$92.50  <-- EM UPPER BOUND | 47         | 2601       | -230         | 12,745       | 12,515      
$95.00         | 12         | 24611      | -34          | 68,911       | 68,877      
================================================================================

[ STATISTICAL EXPECTED MOVE ]
Calculated EM: +/- $3.83
Expected Range: $83.74 to $91.40

[ SUGGESTED STRIKES (STRUCTURAL) ]
Major Support (Lower Bound)    : $85.00 (Put GEX: -27,326)
Major Resistance (Upper Bound) : $90.00 (Call GEX: 94,489)

Action: Sell the Put spread below the support, and sell the Call spread above the resistance.
================================================================================

[+] Successfully exported clean data to gex_structural.csv

Debug: Client initialized with Key: 2Hy2...

================================================================================
 TACTICAL BWB (BROKEN WING BUTTERFLY) FOR KO
================================================================================
  *What is this? We find the invisible Gamma Wall where Market Makers will defend
  the stock from crashing. We build a trap right at that wall. If it crashes,
  we collect max profit. If it goes up instead, the trap breaks and we still
  keep a small credit. You literally cannot lose money on the upside.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-08-14 (1-DTE)
  Implied Volatility (ATM): 18.23%
  Tactical Expected Move: ±$0.84
  Mathematical Danger Zone (Lower Bound): $86.75
  Short-Term Gamma Support (MM Wall): $87.00

  [ SUGGESTED TACTICAL BWB SETUP ]
  BUY  1x  $92.00 Put
  SELL 2x  $87.00 Put  <-- (Pinned at Gamma Wall)
  BUY  1x  $77.00 Put  <-- (Broken Wing for Credit)

  *Note: Ensure this is entered for a NET CREDIT.*
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 CASH-SECURED PUTS (14-45 DTE) FOR KO
================================================================================
  *What is this? You sign a contract promising to buy this stock next month
  if it drops in price, but you get paid cash right now for that promise.
  If it drops, you buy the stock on sale. If it doesn't drop, you keep the cash.*
--------------------------------------------------------------------------------

  [ CAPITAL PRESERVATION: THE ULTRA-SAFE CSP ]
  SELL 1x 2026-09-25 (43-DTE) $83.00 Put
  Premium Collected: $0.54
  Annualized Yield : 5.5%
  Safety Margin    : 5.9% (Breakeven: $82.46)
  Max Pain Anchor  : $86.00 (Strike is protected)

  [ INCOME ACCUMULATOR: THE HIGH-YIELD CSP ]
  SELL 1x 2026-09-25 (43-DTE) $85.00 Put
  Premium Collected: $0.96
  Annualized Yield : 9.6%
  Safety Margin    : 4.0% (Breakeven: $84.04)
================================================================================

Debug: Client initialized with Key: 2Hy2...
Debug: Client initialized with Key: 2Hy2...

================================================================================
 THE BULL RISK REVERSAL (ZEBRA) FOR KO
================================================================================
  *What is this? You sell a Put at the exact floor where Market Makers are
  defending the stock, getting paid cash. You immediately use that cash to
  buy a Call at the ceiling. If the stock crashes, you buy it on sale at the
  floor. If it rips through the ceiling, you have unlimited profit for zero cost.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-09-18 (36-DTE)

  [ SUGGESTED RISK REVERSAL SETUP ]
  SELL 1x  $85.00 Put  (Credit: $0.93)  <-- Gamma Support Wall
  BUY  1x  $92.50 Call (Debit : $0.44)  <-- Gamma Resistance Wall
  Total Net Credit : $0.49 (You get PAID to enter this)
  Capital Required : $8,500.00 (To secure the put assignment if it crashes)
  Max Upside Profit: UNLIMITED
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 JADE LIZARD SETUP (30-45 DTE) FOR KO
================================================================================
  *What is this? You collect massive income from selling a put, and use that
  cash to fully finance a call spread above the stock. Zero upside risk.
  If the stock crashes, you buy it on sale. If it rips to the moon,
  you still make money even if the call spread blows up.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-09-25 (43-DTE)

  [ SUGGESTED JADE LIZARD SETUP (ZERO UPSIDE RISK) ]
  SELL 1x  $85.00 Put   (Credit: $0.96)
  SELL 1x  $90.00 Call
  BUY  1x  $91.00 Call
  Call Spread Credit: $0.06

  Total Premium Collected : $1.02
  Max Call Spread Risk    : $1.00
  Net Upside Edge         : +$0.02 (Guaranteed profit if stock rips upward!)
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 LEAPS HUNTER (300+ DTE) FOR KO
================================================================================
  *What is this? Instead of paying $32,000 to buy 100 shares of stock, you
  pay $500 to rent the *rights* to 100 shares for two years. If it goes up,
  your $500 agreement goes up exactly as if you owned the $32,000 in shares.*
--------------------------------------------------------------------------------
  Target Expiration: 2028-06-16 (673-DTE)

  [ CAPITAL PRESERVATION: STOCK REPLACEMENT (DITM) ]
  BUY 1x $45.00 Call (Price: $42.60)
  Delta: 1.00 (Moves 1:1 with stock)
  Leverage: 2.1x (Cheaper than 100 shares)
  Time Rent (Extrinsic): 0.02%
  Breakeven: $87.60

  [ HIGH REWARD: THE LOTTERY TICKET (OTM) ]
  BUY 1x $120.00 Call (Price: $2.14)
  Delta: 0.17 (Explosive Convexity)
  Leverage: 40.9x
  *Note: High probability of expiring worthless. Small size only.*
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 HIGHLY SPECULATIVE PLAYS FOR KO (HIGH RISK / HIGH REWARD)
================================================================================
  *What is this? Pure directional lottery tickets. You are betting that the
  stock explodes violently, or that it breaks a resistance wall forcing
  Market Makers to panic buy millions of shares to cover their short calls.*
--------------------------------------------------------------------------------

  [ VOLATILITY ERUPTION: THE ATM STRADDLE ]
  Target Expiration: 2026-08-28 (15-DTE)
  BUY 1x $88.00 Call (Price: $1.10)
  BUY 1x $88.00 Put  (Price: $1.34)
  Total Premium Risk: $2.45
  Implied Move Needed: ±2.80%
  Breakevens: < $85.55 OR > $90.45
  *Logic: You don't care about direction, only velocity. Best played before earnings.*

  [ THE GAMMA SQUEEZE HUNTER (LOTTERY TICKET) ]
  Identified Resistance Wall: 12,442 Open Contracts at $90.00
  Target Expiration: 2026-08-21 (8-DTE)
  BUY 1x $90.00 Call (Price: $0.18)
  *Logic: If the stock breaks $90.00, Market Makers must aggressively buy shares.*
  *Warning: Extremely high probability of 100% loss. Size accordingly.*
================================================================================


================================================================================
 PRONG 1: THE COMPANY (Critical Fundamentals)
================================================================================
  Price:             $87.58
  Market Cap:        $376,838,750,208
  Next Earnings:     N/A
  Directly Registered: N/A

  [ VALUATION & GROWTH ]
  P/E Ratio:         26.39
  PEG Ratio:         3.02
  P/TBV:             45.99
  Shareholder Yield: 3.09% (Div: 2.4% | Buybacks: 0.1%)

  [ FINANCIAL HEALTH ]
  Altman Z-Score:    4.73 (>3.0 is Safe)
  Current Ratio:     1.30
  Piotroski F-Score: 6 / 9
  ROIC (Annualized): 28.37%
  FCF Yield:         5.42%

  [ SEC FINANCIAL TRAJECTORY ]
  Verdict:           ELIMINATE (Score: 0)
  FCF Grade:         F - Severe decline -251%
  Net Income Grade:  A - Strong growth +28%, 71% quarters improving
  Revenue Grade:     C - Flat trend 2%

  [ MANAGEMENT & BOARD (SKIN IN THE GAME) ]
  Insider Score:     0/100
  Net Insider Trade: $-239,242,634
  Comp Score:        0/100 (Equity vs Cash)
  Overall Integrity: 20/100

================================================================================
 PRONG 2: THE MARKET (Structural & Derivatives)
================================================================================

  [ MARKET REGIME & TREND ]
  [ MARKET REGIME & TREND ]
  VIX Regime:        🟢 CALM (VIX: 14.67)
  Trend Verdict:     🔥 STRONG CANDIDATE — Trend + liquidity align with your scanner.

  [ ACCUMULATION / DISTRIBUTION ]
  Verdict:           HOLD / WATCH
  Insider Signal:    WHALE ACTIVITY
  Whale Alerts:      2 Active 13D/A Filings Found!

  [ OFF-EXCHANGE & SHORT INTEREST ]
  Avg Dark Short Vol: 1,633,962 shares/day
  Avg Dark Short %:   37.2% of Off-Exchange Volume

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
 Report Saved: ~/Desktop/antigravity/Single_Stock_Pipeline/reports/KO_V2_Master_Report.md
================================================================================

