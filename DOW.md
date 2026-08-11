
================================================================================
 ANTIGRAVITY PIPELINE: SINGLE STOCK ENGINE V2 | TARGET: DOW
================================================================================
Report Generated: 2026-08-11 05:09:20 HST

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
Current Price of DOW: $31.21
Fetching options chain from 2026-08-11 to 2026-09-25...
Days to Earnings  : 72 Days (Date: 2026-10-22)
Near-Term ATM IV  : 📉 43% `[███░░░░░]`

================================================================================
 TACTICAL RADAR (0-14 DTE) FOR DOW
================================================================================
Strike     | Put OI     | Call OI    | Put GEX      | Call GEX     | Net GEX     
--------------------------------------------------------------------------------
$27.50         | 4679       | 1973       | -21,553      | 9,077        | -12,477     
$28.00         | 5028       | 75         | -29,216      | 348          | -28,867     
$28.50         | 7946       | 197        | -63,530      | 1,497        | -62,033     
$29.00         | 3032       | 667        | -29,602      | 6,168        | -23,434     
$29.50  <-- EM LOWER BOUND | 972        | 308        | -11,918      | 3,400        | -8,517      
$30.00         | 9345       | 16814      | -145,532     | 261,088      | 115,557     
$30.50  <-- PRICE | 174        | 1306       | -3,298       | 29,797       | 26,498      
$31.00  <-- PRICE | 197        | 1729       | -5,341       | 44,041       | 38,700      
$31.50  <-- PRICE | 16         | 1386       | -296         | 38,157       | 37,861      
$32.00  <-- PRICE | 1042       | 1328       | -17,994      | 27,741       | 9,747       
$32.50         | 556        | 3933       | -8,618       | 62,683       | 54,065      
$33.00  <-- EM UPPER BOUND | 17         | 1258       | -225         | 16,654       | 16,429      
$35.00         | 1227       | 3407       | -5,234       | 19,363       | 14,128      
================================================================================

[ STATISTICAL EXPECTED MOVE ]
Calculated EM: +/- $1.54
Expected Range: $29.68 to $32.75

[ SUGGESTED STRIKES (TACTICAL) ]
Major Support (Lower Bound)    : $30.00 (Put GEX: -145,532)
Major Resistance (Upper Bound) : $32.50 (Call GEX: 62,683)

Action: Monitor these levels for immediate volatility and Gamma squeeze potential.
================================================================================

[+] Successfully exported clean data to gex_tactical.csv


================================================================================
 STRUCTURAL ANCHOR (30-45 DTE) FOR DOW
================================================================================
Strike     | Put OI     | Call OI    | Put GEX      | Call GEX     | Net GEX     
--------------------------------------------------------------------------------
$20.00         | 6027       | 479        | -4,219       | 0            | -4,219      
$22.50         | 3139       | 305        | -3,767       | 0            | -3,767      
$25.00         | 11471      | 2111       | -30,974      | 5,911        | -25,063     
$27.50  <-- EM LOWER BOUND | 10559      | 3471       | -63,354      | 23,256       | -40,098     
$30.00         | 9467       | 8937       | -87,108      | 87,692       | 584         
$32.50         | 1995       | 4135       | -17,556      | 37,215       | 19,659      
$35.00  <-- EM UPPER BOUND | 3781       | 9878       | -24,576      | 65,181       | 40,605      
$37.50         | 2529       | 4095       | -9,610       | 15,561       | 5,951       
$40.00         | 2779       | 6465       | -6,114       | 14,223       | 8,109       
$42.50         | 251        | 5975       | -351         | 8,365        | 8,014       
$45.00         | 27         | 6959       | -27          | 6,959        | 6,932       
================================================================================

[ STATISTICAL EXPECTED MOVE ]
Calculated EM: +/- $3.16
Expected Range: $28.05 to $34.38

[ SUGGESTED STRIKES (STRUCTURAL) ]
Major Support (Lower Bound)    : $30.00 (Put GEX: -87,108)
Major Resistance (Upper Bound) : $35.00 (Call GEX: 65,181)

Action: Sell the Put spread below the support, and sell the Call spread above the resistance.
================================================================================

[+] Successfully exported clean data to gex_structural.csv

Debug: Client initialized with Key: 2Hy2...

================================================================================
 TACTICAL BWB (BROKEN WING BUTTERFLY) FOR DOW
================================================================================
  *What is this? We find the invisible Gamma Wall where Market Makers will defend
  the stock from crashing. We build a trap right at that wall. If it crashes,
  we collect max profit. If it goes up instead, the trap breaks and we still
  keep a small credit. You literally cannot lose money on the upside.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-08-14 (3-DTE)
  Implied Volatility (ATM): 43.73%
  Tactical Expected Move: ±$1.24
  Mathematical Danger Zone (Lower Bound): $29.97
  Short-Term Gamma Support (MM Wall): $28.50

  [ SUGGESTED TACTICAL BWB SETUP ]
  BUY  1x  $29.50 Put
  SELL 2x  $28.50 Put  <-- (Pinned at Gamma Wall)
  BUY  1x  $26.50 Put  <-- (Broken Wing for Credit)

  *Note: Ensure this is entered for a NET CREDIT.*
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 CASH-SECURED PUTS (14-45 DTE) FOR DOW
================================================================================
  *What is this? You sign a contract promising to buy this stock next month
  if it drops in price, but you get paid cash right now for that promise.
  If it drops, you buy the stock on sale. If it doesn't drop, you keep the cash.*
--------------------------------------------------------------------------------

  [ CAPITAL PRESERVATION: THE ULTRA-SAFE CSP ]
  SELL 1x 2026-09-18 (38-DTE) $27.50 Put
  Premium Collected: $0.40
  Annualized Yield : 14.0%
  Safety Margin    : 13.2% (Breakeven: $27.10)
  Max Pain Anchor  : $30.00 (Strike is protected)

  [ INCOME ACCUMULATOR: THE HIGH-YIELD CSP ]
  SELL 1x 2026-09-18 (38-DTE) $30.00 Put
  Premium Collected: $1.15
  Annualized Yield : 36.8%
  Safety Margin    : 7.5% (Breakeven: $28.85)
================================================================================

Debug: Client initialized with Key: 2Hy2...
Debug: Client initialized with Key: 2Hy2...

================================================================================
 THE BULL RISK REVERSAL (ZEBRA) FOR DOW
================================================================================
  *What is this? You sell a Put at the exact floor where Market Makers are
  defending the stock, getting paid cash. You immediately use that cash to
  buy a Call at the ceiling. If the stock crashes, you buy it on sale at the
  floor. If it rips through the ceiling, you have unlimited profit for zero cost.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-09-11 (31-DTE)

  [ SUGGESTED RISK REVERSAL SETUP ]
  SELL 1x  $30.00 Put  (Credit: $0.80)  <-- Gamma Support Wall
  BUY  1x  $35.00 Call (Debit : $0.50)  <-- Gamma Resistance Wall
  Total Net Credit : $0.30 (You get PAID to enter this)
  Capital Required : $3,000.00 (To secure the put assignment if it crashes)
  Max Upside Profit: UNLIMITED
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 JADE LIZARD SETUP (30-45 DTE) FOR DOW
================================================================================
  *What is this? You collect massive income from selling a put, and use that
  cash to fully finance a call spread above the stock. Zero upside risk.
  If the stock crashes, you buy it on sale. If it rips to the moon,
  you still make money even if the call spread blows up.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-09-25 (45-DTE)

  [!] NO SAFE JADE LIZARD FOUND (Insufficient Premium).
  *Mathematical Rule: Total premium collected must exceed call spread width to eliminate upside risk.*
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 LEAPS HUNTER (300+ DTE) FOR DOW
================================================================================
  *What is this? Instead of paying $32,000 to buy 100 shares of stock, you
  pay $500 to rent the *rights* to 100 shares for two years. If it goes up,
  your $500 agreement goes up exactly as if you owned the $32,000 in shares.*
--------------------------------------------------------------------------------
  Target Expiration: 2028-01-21 (528-DTE)

  [ CAPITAL PRESERVATION: STOCK REPLACEMENT (DITM) ]
  BUY 1x $15.00 Call (Price: $15.62)
  Delta: 1.00 (Moves 1:1 with stock)
  Leverage: 2.0x (Cheaper than 100 shares)
  Time Rent (Extrinsic): 0.00%
  Breakeven: $30.62

  [ HIGH REWARD: THE LOTTERY TICKET (OTM) ]
  BUY 1x $55.00 Call (Price: $1.06)
  Delta: 0.15 (Explosive Convexity)
  Leverage: 29.3x
  *Note: High probability of expiring worthless. Small size only.*
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 HIGHLY SPECULATIVE PLAYS FOR DOW (HIGH RISK / HIGH REWARD)
================================================================================
  *What is this? Pure directional lottery tickets. You are betting that the
  stock explodes violently, or that it breaks a resistance wall forcing
  Market Makers to panic buy millions of shares to cover their short calls.*
--------------------------------------------------------------------------------

  [ VOLATILITY ERUPTION: THE ATM STRADDLE ]
  Target Expiration: 2026-08-28 (17-DTE)
  BUY 1x $31.00 Call (Price: $1.27)
  BUY 1x $31.00 Put  (Price: $0.99)
  Total Premium Risk: $2.25
  Implied Move Needed: ±7.23%
  Breakevens: < $28.75 OR > $33.26
  *Logic: You don't care about direction, only velocity. Best played before earnings.*

  [ THE GAMMA SQUEEZE HUNTER (LOTTERY TICKET) ]
  Identified Resistance Wall: 3,574 Open Contracts at $32.50
  Target Expiration: 2026-08-21 (10-DTE)
  BUY 1x $32.50 Call (Price: $0.40)
  *Logic: If the stock breaks $32.50, Market Makers must aggressively buy shares.*
  *Warning: Extremely high probability of 100% loss. Size accordingly.*
================================================================================


================================================================================
 PRONG 1: THE COMPANY (Critical Fundamentals)
================================================================================
  Price:             $31.20
  Market Cap:        $22,540,642,304
  Next Earnings:     N/A
  Directly Registered: N/A

  [ VALUATION & GROWTH ]
  P/E Ratio:         None
  PEG Ratio:         None
  P/TBV:             3.44
  Shareholder Yield: 4.46% (Div: 4.6% | Buybacks: 0.0%)

  [ FINANCIAL HEALTH ]
  Altman Z-Score:    1.11 (>3.0 is Safe)
  Current Ratio:     1.75
  Piotroski F-Score: 2 / 9
  ROIC (Annualized): 12.62%
  FCF Yield:         12.40%

  [ SEC FINANCIAL TRAJECTORY ]
  Verdict:           ELIMINATE (Score: 0)
  FCF Grade:         F - Severe decline -44%
  Net Income Grade:  F - Final quarter negative (-533,000,000)
  Revenue Grade:     D - Mild decline -7%

  [ MANAGEMENT & BOARD (SKIN IN THE GAME) ]
  Insider Score:     50/100
  Net Insider Trade: $0
  Comp Score:        0/100 (Equity vs Cash)
  Overall Integrity: 50/100

================================================================================
 PRONG 2: THE MARKET (Structural & Derivatives)
================================================================================

  [ MARKET REGIME & TREND ]
  [ MARKET REGIME & TREND ]
  VIX Regime:        🟡 NORMAL (VIX: 15.23)
  Trend Verdict:     ❌ PASS — Scanner likes it, but the trend engine says no.

  [ ACCUMULATION / DISTRIBUTION ]
  Verdict:           YELLOW LIGHT (Stealth Accumulation)
  Insider Signal:    WHALE ACTIVITY
  Whale Alerts:      3 Active 13D/A Filings Found!

  [ OFF-EXCHANGE & SHORT INTEREST ]
  Avg Dark Short Vol: 2,364,548 shares/day
  Avg Dark Short %:   71.6% of Off-Exchange Volume

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
 Report Saved: ~/Desktop/antigravity/Single_Stock_Pipeline/reports/DOW_V2_Master_Report.md
================================================================================

