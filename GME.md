
================================================================================
 ANTIGRAVITY PIPELINE: SINGLE STOCK ENGINE V2 | TARGET: GME
================================================================================
Fetching fundamental data... (This may take 15-20 seconds)

================================================================================
 THE TRADING DASHBOARD (Macro & Options)
================================================================================
  [ MACRO EVENT RADAR (45-Day) ]
  ⚠️ Non-Farm Payrolls (NFP) & Unemployment in 7 Days (2026-08-07)
  ⚠️ Core CPI Inflation Data in 12 Days (2026-08-12)
  ⚠️ Non-Farm Payrolls (NFP) & Unemployment in 35 Days (2026-09-04)
  ⚠️ Core CPI Inflation Data in 42 Days (2026-09-11)

  [ GAMMA EXPOSURE (GEX) & EXPECTED MOVE ]

Initializing Schwab Client...
Debug: Client initialized with Key: 2Hy2...
Current Price of GME: $21.73
Fetching options chain from 2026-07-31 to 2026-09-14...

================================================================================
 TACTICAL RADAR (0-14 DTE) FOR GME
================================================================================
Strike     | Put OI     | Call OI    | Put GEX      | Call GEX     | Net GEX     
--------------------------------------------------------------------------------
$21.00  <-- EM LOWER BOUND | 4622       | 2091       | -104,918     | 39,680       | -65,239     
$21.50  <-- PRICE | 3767       | 9200       | -332,815     | 923,392      | 590,577     
$22.00  <-- PRICE | 3457       | 24203      | -227,058     | 1,868,292    | 1,641,234   
$22.50  <-- EM UPPER BOUND | 1060       | 15268      | -27,511      | 352,483      | 324,972     
$23.00         | 1247       | 25493      | -19,240      | 327,205      | 307,965     
$23.50         | 356        | 6443       | -2,712       | 63,002       | 60,289      
$24.00         | 230        | 14461      | -1,708       | 95,995       | 94,287      
$25.00         | 688        | 13409      | -3,945       | 53,378       | 49,433      
================================================================================

[ STATISTICAL EXPECTED MOVE ]
Calculated EM: +/- $0.76
Expected Range: $20.98 to $22.49

[ SUGGESTED STRIKES (TACTICAL) ]
Major Support (Lower Bound)    : $21.50 (Put GEX: -332,815)
Major Resistance (Upper Bound) : $22.00 (Call GEX: 1,868,292)

Action: Monitor these levels for immediate volatility and Gamma squeeze potential.
================================================================================

[+] Successfully exported clean data to gex_tactical.csv


================================================================================
 STRUCTURAL ANCHOR (30-45 DTE) FOR GME
================================================================================
Strike     | Put OI     | Call OI    | Put GEX      | Call GEX     | Net GEX     
--------------------------------------------------------------------------------
$19.00         | 63         | 0          | -402         | 0            | -402        
$20.00  <-- EM LOWER BOUND | 87         | 1          | -957         | 11           | -946        
$21.00  <-- PRICE | 60         | 24         | -1,103       | 413          | -690        
$21.50  <-- PRICE | 94         | 13         | -2,181       | 273          | -1,908      
$22.00  <-- PRICE | 109        | 191        | -2,511       | 3,873        | 1,362       
$22.50  <-- PRICE | 6          | 48         | -139         | 931          | 793         
$23.00         | 56         | 733        | -1,477       | 14,660       | 13,183      
$23.50  <-- EM UPPER BOUND | 57         | 75         | -1,226       | 1,208        | -18         
$24.00         | 25         | 705        | -373         | 9,658        | 9,286       
$25.00         | 1          | 450        | -8           | 4,405        | 4,397       
$27.00         | 0          | 71         | 0            | 390          | 390         
$28.00         | 0          | 174        | 0            | 766          | 766         
$32.00         | 0          | 209        | 0            | 752          | 752         
$35.00         | 0          | 268        | 0            | 509          | 509         
================================================================================

[ STATISTICAL EXPECTED MOVE ]
Calculated EM: +/- $1.65
Expected Range: $20.09 to $23.38

[ SUGGESTED STRIKES (STRUCTURAL) ]
Major Support (Lower Bound)    : $21.50 (Put GEX: -2,181)
Major Resistance (Upper Bound) : $23.00 (Call GEX: 14,660)

Action: Sell the Put spread below the support, and sell the Call spread above the resistance.
================================================================================

[+] Successfully exported clean data to gex_structural.csv

Debug: Client initialized with Key: 2Hy2...

================================================================================
 TACTICAL BWB (BROKEN WING BUTTERFLY) FOR GME
================================================================================
  *What is this? We find the invisible Gamma Wall where Market Makers will defend
  the stock from crashing. We build a trap right at that wall. If it crashes,
  we collect max profit. If it goes up instead, the trap breaks and we still
  keep a small credit. You literally cannot lose money on the upside.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-07-31 (0-DTE)
  Implied Volatility (ATM): 50.56%
  Tactical Expected Move: ±$0.58
  Mathematical Danger Zone (Lower Bound): $21.16
  Short-Term Gamma Support (MM Wall): $21.50

  [ SUGGESTED TACTICAL BWB SETUP ]
  BUY  1x  $22.50 Put
  SELL 2x  $21.50 Put  <-- (Pinned at Gamma Wall)
  BUY  1x  $19.50 Put  <-- (Broken Wing for Credit)

  *Note: Ensure this is entered for a NET CREDIT.*
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 CASH-SECURED PUTS (14-45 DTE) FOR GME
================================================================================
  *What is this? You sign a contract promising to buy this stock next month
  if it drops in price, but you get paid cash right now for that promise.
  If it drops, you buy the stock on sale. If it doesn't drop, you keep the cash.*
--------------------------------------------------------------------------------

  [ CAPITAL PRESERVATION: THE ULTRA-SAFE CSP ]
  SELL 1x 2026-08-28 (28-DTE) $20.00 Put
  Premium Collected: $0.14
  Annualized Yield : 9.1%
  Safety Margin    : 8.6% (Breakeven: $19.86)
  Max Pain Anchor  : $22.00 (Strike is protected)

  [ INCOME ACCUMULATOR: THE HIGH-YIELD CSP ]
  SELL 1x 2026-08-21 (21-DTE) $21.00 Put
  Premium Collected: $0.26
  Annualized Yield : 21.5%
  Safety Margin    : 4.6% (Breakeven: $20.74)
================================================================================

Debug: Client initialized with Key: 2Hy2...
Debug: Client initialized with Key: 2Hy2...

================================================================================
 THE BULL RISK REVERSAL (ZEBRA) FOR GME
================================================================================
  *What is this? You sell a Put at the exact floor where Market Makers are
  defending the stock, getting paid cash. You immediately use that cash to
  buy a Call at the ceiling. If the stock crashes, you buy it on sale at the
  floor. If it rips through the ceiling, you have unlimited profit for zero cost.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-09-04 (35-DTE)

  [ SUGGESTED RISK REVERSAL SETUP ]
  SELL 1x  $21.50 Put  (Credit: $0.04)  <-- Gamma Support Wall
  BUY  1x  $35.00 Call (Debit : $0.21)  <-- Gamma Resistance Wall
  Total Net Cost   : $0.17 (Could not find a zero-cost setup)
  Capital Required : $2,150.00 (To secure the put assignment if it crashes)
  Max Upside Profit: UNLIMITED
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 JADE LIZARD SETUP (30-45 DTE) FOR GME
================================================================================
  *What is this? You collect massive income from selling a put, and use that
  cash to fully finance a call spread above the stock. Zero upside risk.
  If the stock crashes, you buy it on sale. If it rips to the moon,
  you still make money even if the call spread blows up.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-09-11 (42-DTE)

  [!] NO SAFE JADE LIZARD FOUND (Insufficient Premium).
  *Mathematical Rule: Total premium collected must exceed call spread width to eliminate upside risk.*
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 LEAPS HUNTER (300+ DTE) FOR GME
================================================================================
  *What is this? Instead of paying $32,000 to buy 100 shares of stock, you
  pay $500 to rent the *rights* to 100 shares for two years. If it goes up,
  your $500 agreement goes up exactly as if you owned the $32,000 in shares.*
--------------------------------------------------------------------------------
  Target Expiration: 2028-12-15 (868-DTE)

  [ CAPITAL PRESERVATION: STOCK REPLACEMENT (DITM) ]
  BUY 1x $13.00 Call (Price: $11.65)
  Delta: 0.87 (Moves 1:1 with stock)
  Leverage: 1.9x (Cheaper than 100 shares)
  Time Rent (Extrinsic): 13.41%
  Breakeven: $24.65

  [!] No suitable Lottery Ticket LEAPS found.
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 HIGHLY SPECULATIVE PLAYS FOR GME (HIGH RISK / HIGH REWARD)
================================================================================
  *What is this? Pure directional lottery tickets. You are betting that the
  stock explodes violently, or that it breaks a resistance wall forcing
  Market Makers to panic buy millions of shares to cover their short calls.*
--------------------------------------------------------------------------------

  [ VOLATILITY ERUPTION: THE ATM STRADDLE ]
  Target Expiration: 2026-08-14 (14-DTE)
  BUY 1x $21.50 Call (Price: $0.59)
  BUY 1x $21.50 Put  (Price: $0.34)
  Total Premium Risk: $0.93
  Implied Move Needed: ±4.30%
  Breakevens: < $20.57 OR > $22.43
  *Logic: You don't care about direction, only velocity. Best played before earnings.*

  [ THE GAMMA SQUEEZE HUNTER (LOTTERY TICKET) ]
  Identified Resistance Wall: 7,434 Open Contracts at $23.00
  Target Expiration: 2026-08-07 (7-DTE)
  BUY 1x $23.00 Call (Price: $0.08)
  *Logic: If the stock breaks $23.00, Market Makers must aggressively buy shares.*
  *Warning: Extremely high probability of 100% loss. Size accordingly.*
================================================================================


================================================================================
 PRONG 1: THE COMPANY (Critical Fundamentals)
================================================================================
  Price:             $21.73
  Market Cap:        $9,752,304,640
  Next Earnings:     N/A
  Directly Registered: 177,522 Shareholders (High Conviction Base)

  [ VALUATION & GROWTH ]
  P/E Ratio:         16.56
  PEG Ratio:         None
  P/TBV:             1.67
  Shareholder Yield: 0.00% (Div: 0.0% | Buybacks: 0.0%)

  [ FINANCIAL HEALTH ]
  Altman Z-Score:    2.41 (>3.0 is Safe)
  Current Ratio:     12.40
  Piotroski F-Score: 5 / 9
  ROIC (Annualized): 15.33%
  FCF Yield:         13.65%

  [ SEC FINANCIAL TRAJECTORY ]
  Verdict:           ELIMINATE (Score: 0)
  FCF Grade:         A - Strong growth +127%, 71% quarters improving
  Net Income Grade:  A - Strong growth +21353%, 71% quarters improving
  Revenue Grade:     D - Mild decline -7%

  [ MANAGEMENT & BOARD (SKIN IN THE GAME) ]
  Insider Score:     93/100
  Net Insider Trade: $20,354,636
  Comp Score:        0/100 (Equity vs Cash)
  Overall Integrity: 75/100

================================================================================
 PRONG 2: THE MARKET (Structural & Derivatives)
================================================================================

  [ MARKET REGIME & TREND ]
  [ MARKET REGIME & TREND ]
  VIX Regime:        🟡 NORMAL (VIX: 17.32)
  Trend Verdict:     ❌ PASS — Scanner likes it, but the trend engine says no.

  [ ACCUMULATION / DISTRIBUTION ]
  Verdict:           HOLD / WATCH
  Insider Signal:    WHALE ACTIVITY
  Whale Alerts:      13 Active 13D/A Filings Found!

  [ OFF-EXCHANGE & SHORT INTEREST ]
  Avg Dark Short Vol: 966,218 shares/day
  Avg Dark Short %:   66.7% of Off-Exchange Volume

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
 Report Saved: ~/Desktop/antigravity/Single_Stock_Pipeline/reports/GME_V2_Master_Report.md
================================================================================

