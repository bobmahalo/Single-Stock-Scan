
================================================================================
 ANTIGRAVITY PIPELINE: SINGLE STOCK ENGINE V2 | TARGET: EXEL
================================================================================
Report Generated: 2026-08-11 08:07:33 HST

Fetching fundamental data... (This may take 15-20 seconds)

================================================================================
 THE TRADING DASHBOARD (Macro & Options)
================================================================================
  [ MACRO EVENT RADAR (45-Day) ]
  ⚠️ Core CPI Inflation Data TOMORROW (2026-08-12)
  ⚠️ Non-Farm Payrolls (NFP) & Unemployment in 24 Days (2026-09-04)
  ⚠️ Core CPI Inflation Data in 31 Days (2026-09-11)
  ⚠️ FOMC Rate Decision & Press Conference in 36 Days (2026-09-16)

  [ GAMMA EXPOSURE (GEX) & EXPECTED MOVE ]

Initializing Schwab Client...
Debug: Client initialized with Key: 2Hy2...
Debug: Token expired, refreshing...
Current Price of EXEL: $51.83
Fetching options chain from 2026-08-11 to 2026-09-25...
Days to Earnings  : 77 Days (Date: 2026-10-27)
Near-Term ATM IV  : 📉 33% `[██░░░░░░]`

================================================================================
 TACTICAL RADAR (0-14 DTE) FOR EXEL
================================================================================
Strike     | Put OI     | Call OI    | Put GEX      | Call GEX     | Net GEX     
--------------------------------------------------------------------------------
$44.00         | 666        | 311        | -1,532       | 560          | -972        
$46.00         | 486        | 111        | -1,701       | 377          | -1,324      
$48.00         | 320        | 356        | -1,536       | 1,673        | 137         
$49.00         | 366        | 125        | -2,891       | 962          | -1,929      
$50.00  <-- EM LOWER BOUND | 6621       | 183        | -72,831      | 1,995        | -70,836     
$55.00  <-- EM UPPER BOUND | 446        | 970        | -3,523       | 7,663        | 4,140       
$60.00         | 7          | 3367       | -20          | 9,428        | 9,408       
$65.00         | 0          | 2174       | 0            | 2,826        | 2,826       
================================================================================

[ STATISTICAL EXPECTED MOVE ]
Calculated EM: +/- $2.03
Expected Range: $49.79 to $53.86

[ SUGGESTED STRIKES (TACTICAL) ]
Major Support (Lower Bound)    : $50.00 (Put GEX: -72,831)
Major Resistance (Upper Bound) : $60.00 (Call GEX: 9,428)

Action: Monitor these levels for immediate volatility and Gamma squeeze potential.
================================================================================

[+] Successfully exported clean data to gex_tactical.csv


================================================================================
 STRUCTURAL ANCHOR (30-45 DTE) FOR EXEL
================================================================================
Strike     | Put OI     | Call OI    | Put GEX      | Call GEX     | Net GEX     
--------------------------------------------------------------------------------
$50.00  <-- EM LOWER BOUND | 1387       | 12         | -8,738       | 76           | -8,662      
$55.00  <-- EM UPPER BOUND | 35         | 47         | -213         | 282          | 69          
$60.00         | 4          | 1122       | -14          | 3,927        | 3,913       
================================================================================

[ STATISTICAL EXPECTED MOVE ]
Calculated EM: +/- $3.67
Expected Range: $48.15 to $55.50

[ SUGGESTED STRIKES (STRUCTURAL) ]
Major Support (Lower Bound)    : $50.00 (Put GEX: -8,738)
Major Resistance (Upper Bound) : $60.00 (Call GEX: 3,927)

Action: Sell the Put spread below the support, and sell the Call spread above the resistance.
================================================================================

[+] Successfully exported clean data to gex_structural.csv

Debug: Client initialized with Key: 2Hy2...

================================================================================
 TACTICAL BWB (BROKEN WING BUTTERFLY) FOR EXEL
================================================================================
  *What is this? We find the invisible Gamma Wall where Market Makers will defend
  the stock from crashing. We build a trap right at that wall. If it crashes,
  we collect max profit. If it goes up instead, the trap breaks and we still
  keep a small credit. You literally cannot lose money on the upside.*
--------------------------------------------------------------------------------
  [!] No short-term options chain found for EXEL within 7 days.
Debug: Client initialized with Key: 2Hy2...

================================================================================
 CASH-SECURED PUTS (14-45 DTE) FOR EXEL
================================================================================
  *What is this? You sign a contract promising to buy this stock next month
  if it drops in price, but you get paid cash right now for that promise.
  If it drops, you buy the stock on sale. If it doesn't drop, you keep the cash.*
--------------------------------------------------------------------------------

  [ CAPITAL PRESERVATION: THE ULTRA-SAFE CSP ]
  SELL 1x 2026-09-18 (38-DTE) $50.00 Put
  Premium Collected: $1.20
  Annualized Yield : 23.1%
  Safety Margin    : 5.8% (Breakeven: $48.80)
  Max Pain Anchor  : $55.00 (Strike is protected)

  *Note: The High-Yield scanner identified the exact same strike as the optimal setup.*
================================================================================

Debug: Client initialized with Key: 2Hy2...
Debug: Client initialized with Key: 2Hy2...

================================================================================
 THE BULL RISK REVERSAL (ZEBRA) FOR EXEL
================================================================================
  *What is this? You sell a Put at the exact floor where Market Makers are
  defending the stock, getting paid cash. You immediately use that cash to
  buy a Call at the ceiling. If the stock crashes, you buy it on sale at the
  floor. If it rips through the ceiling, you have unlimited profit for zero cost.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-09-18 (38-DTE)

  [ SUGGESTED RISK REVERSAL SETUP ]
  SELL 1x  $50.00 Put  (Credit: $1.20)  <-- Gamma Support Wall
  BUY  1x  $60.00 Call (Debit : $0.75)  <-- Gamma Resistance Wall
  Total Net Credit : $0.45 (You get PAID to enter this)
  Capital Required : $5,000.00 (To secure the put assignment if it crashes)
  Max Upside Profit: UNLIMITED
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 JADE LIZARD SETUP (30-45 DTE) FOR EXEL
================================================================================
  *What is this? You collect massive income from selling a put, and use that
  cash to fully finance a call spread above the stock. Zero upside risk.
  If the stock crashes, you buy it on sale. If it rips to the moon,
  you still make money even if the call spread blows up.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-09-18 (38-DTE)

  [!] NO SAFE JADE LIZARD FOUND (Insufficient Premium).
  *Mathematical Rule: Total premium collected must exceed call spread width to eliminate upside risk.*
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 LEAPS HUNTER (300+ DTE) FOR EXEL
================================================================================
  *What is this? Instead of paying $32,000 to buy 100 shares of stock, you
  pay $500 to rent the *rights* to 100 shares for two years. If it goes up,
  your $500 agreement goes up exactly as if you owned the $32,000 in shares.*
--------------------------------------------------------------------------------
  Target Expiration: 2028-01-21 (528-DTE)

  [ CAPITAL PRESERVATION: STOCK REPLACEMENT (DITM) ]
  BUY 1x $20.00 Call (Price: $33.00)
  Delta: 0.97 (Moves 1:1 with stock)
  Leverage: 1.6x (Cheaper than 100 shares)
  Time Rent (Extrinsic): 2.26%
  Breakeven: $53.00

  [ HIGH REWARD: THE LOTTERY TICKET (OTM) ]
  BUY 1x $85.00 Call (Price: $2.05)
  Delta: 0.20 (Explosive Convexity)
  Leverage: 25.3x
  *Note: High probability of expiring worthless. Small size only.*
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 HIGHLY SPECULATIVE PLAYS FOR EXEL (HIGH RISK / HIGH REWARD)
================================================================================
  *What is this? Pure directional lottery tickets. You are betting that the
  stock explodes violently, or that it breaks a resistance wall forcing
  Market Makers to panic buy millions of shares to cover their short calls.*
--------------------------------------------------------------------------------

  [!] No valid Straddle setup found.

  [ THE GAMMA SQUEEZE HUNTER (LOTTERY TICKET) ]
  Identified Resistance Wall: 970 Open Contracts at $55.00
  Target Expiration: 2026-08-21 (10-DTE)
  BUY 1x $55.00 Call (Price: $0.40)
  *Logic: If the stock breaks $55.00, Market Makers must aggressively buy shares.*
  *Warning: Extremely high probability of 100% loss. Size accordingly.*
================================================================================


================================================================================
 PRONG 1: THE COMPANY (Critical Fundamentals)
================================================================================
  Price:             $51.83
  Market Cap:        $12,842,525,696
  Next Earnings:     N/A
  Directly Registered: 288 Shareholders (High Conviction Base)

  [ VALUATION & GROWTH ]
  P/E Ratio:         16.28
  PEG Ratio:         0.88
  P/TBV:             7.21
  Shareholder Yield: 8.68% (Div: 0.0% | Buybacks: 6.4%)

  [ FINANCIAL HEALTH ]
  Altman Z-Score:    12.71 (>3.0 is Safe)
  Current Ratio:     3.46
  Piotroski F-Score: 7 / 9
  ROIC (Annualized): 46.41%
  FCF Yield:         9.29%

  [ SEC FINANCIAL TRAJECTORY ]
  Verdict:           PASS (Score: 78.2)
  FCF Grade:         B - Good growth +55%, mixed consistency
  Net Income Grade:  A - Strong growth +48%, 86% quarters improving
  Revenue Grade:     B - Moderate growth +16%, 57% quarters improving

  [ MANAGEMENT & BOARD (SKIN IN THE GAME) ]
  Insider Score:     2/100
  Net Insider Trade: $-40,528,598
  Comp Score:        0/100 (Equity vs Cash)
  Overall Integrity: 21/100

================================================================================
 PRONG 2: THE MARKET (Structural & Derivatives)
================================================================================

  [ MARKET REGIME & TREND ]
  [ MARKET REGIME & TREND ]
  VIX Regime:        🟡 NORMAL (VIX: 15.27)
  Trend Verdict:     ❌ PASS — Scanner likes it, but the trend engine says no.

  [ ACCUMULATION / DISTRIBUTION ]
  Verdict:           GREEN LIGHT (Strong Accumulation)
  Insider Signal:    WHALE ACTIVITY
  Whale Alerts:      4 Active 13D/A Filings Found!

  [ OFF-EXCHANGE & SHORT INTEREST ]
  Avg Dark Short Vol: 754,397 shares/day
  Avg Dark Short %:   62.6% of Off-Exchange Volume

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
 Report Saved: ~/Desktop/antigravity/Single_Stock_Pipeline/reports/EXEL_V2_Master_Report.md
================================================================================

