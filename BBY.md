
================================================================================
 ANTIGRAVITY PIPELINE: SINGLE STOCK ENGINE V2 | TARGET: BBY
================================================================================
Report Generated: 2026-08-11 04:33:27 HST

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
Current Price of BBY: $83.74
Fetching options chain from 2026-08-11 to 2026-09-25...
Days to Earnings  : 16 Days (Date: 2026-08-27)
Near-Term ATM IV  : 📉 35% `[██░░░░░░]`

================================================================================
 TACTICAL RADAR (0-14 DTE) FOR BBY
================================================================================
Strike     | Put OI     | Call OI    | Put GEX      | Call GEX     | Net GEX     
--------------------------------------------------------------------------------
$67.50         | 1090       | 95         | -1,090       | 95           | -995        
$72.50         | 197        | 689        | -335         | 1,171        | 836         
$75.00         | 1105       | 470        | -2,314       | 979          | -1,335      
$76.00         | 721        | 297        | -1,753       | 791          | -962        
$77.50         | 268        | 199        | -938         | 697          | -242        
$78.00         | 377        | 23         | -1,417       | 79           | -1,338      
$79.00         | 97         | 169        | -436         | 760          | 324         
$80.00  <-- EM LOWER BOUND | 6349       | 864        | -35,060      | 4,818        | -30,242     
$81.00         | 354        | 46         | -2,458       | 383          | -2,075      
$82.00         | 164        | 103        | -1,710       | 1,092        | -618        
$82.50         | 763        | 278        | -5,799       | 2,085        | -3,714      
$83.00  <-- PRICE | 31         | 251        | -356         | 3,571        | 3,216       
$84.00  <-- PRICE | 132        | 106        | -1,569       | 1,437        | -133        
$85.00         | 907        | 1994       | -7,435       | 16,297       | 8,862       
$86.00         | 42         | 190        | -376         | 1,923        | 1,546       
$87.00         | 62         | 67         | -487         | 457          | -30         
$87.50  <-- EM UPPER BOUND | 338        | 678        | -2,231       | 4,204        | 1,973       
$88.00         | 97         | 155        | -551         | 854          | 303         
$90.00         | 43         | 1719       | -197         | 7,202        | 7,005       
$93.00         | 0          | 517        | 0            | 1,272        | 1,272       
$95.00         | 1          | 2124       | 0            | 3,160        | 3,160       
================================================================================

[ STATISTICAL EXPECTED MOVE ]
Calculated EM: +/- $3.91
Expected Range: $79.83 to $87.65

[ SUGGESTED STRIKES (TACTICAL) ]
Major Support (Lower Bound)    : $80.00 (Put GEX: -35,060)
Major Resistance (Upper Bound) : $85.00 (Call GEX: 16,297)

Action: Monitor these levels for immediate volatility and Gamma squeeze potential.
================================================================================

[+] Successfully exported clean data to gex_tactical.csv


================================================================================
 STRUCTURAL ANCHOR (30-45 DTE) FOR BBY
================================================================================
Strike     | Put OI     | Call OI    | Put GEX      | Call GEX     | Net GEX     
--------------------------------------------------------------------------------
$60.00         | 623        | 103        | -436         | 72           | -364        
$65.00         | 400        | 241        | -320         | 193          | -127        
$67.50         | 114        | 1613       | -125         | 1,774        | 1,649       
$70.00         | 576        | 1097       | -806         | 1,536        | 730         
$72.50  <-- EM LOWER BOUND | 91         | 519        | -164         | 934          | 770         
$75.00         | 1505       | 353        | -3,462       | 777          | -2,685      
$77.50         | 105        | 735        | -284         | 1,984        | 1,701       
$80.00         | 3206       | 821        | -9,618       | 2,469        | -7,149      
$82.50         | 323        | 1027       | -1,066       | 3,389        | 2,323       
$85.00         | 137        | 1106       | -465         | 3,760        | 3,295       
$87.50         | 32         | 219        | -109         | 723          | 614         
$90.00         | 87         | 528        | -270         | 1,638        | 1,368       
$92.50         | 10         | 121        | -29          | 339          | 310         
$95.00  <-- EM UPPER BOUND | 10         | 913        | -25          | 2,192        | 2,167       
$100.00        | 2          | 348        | -3           | 626          | 623         
================================================================================

[ STATISTICAL EXPECTED MOVE ]
Calculated EM: +/- $10.44
Expected Range: $73.30 to $94.18

[ SUGGESTED STRIKES (STRUCTURAL) ]
Major Support (Lower Bound)    : $80.00 (Put GEX: -9,618)
Major Resistance (Upper Bound) : $85.00 (Call GEX: 3,760)

Action: Sell the Put spread below the support, and sell the Call spread above the resistance.
================================================================================

[+] Successfully exported clean data to gex_structural.csv

Debug: Client initialized with Key: 2Hy2...

================================================================================
 TACTICAL BWB (BROKEN WING BUTTERFLY) FOR BBY
================================================================================
  *What is this? We find the invisible Gamma Wall where Market Makers will defend
  the stock from crashing. We build a trap right at that wall. If it crashes,
  we collect max profit. If it goes up instead, the trap breaks and we still
  keep a small credit. You literally cannot lose money on the upside.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-08-14 (3-DTE)
  Implied Volatility (ATM): 35.20%
  Tactical Expected Move: ±$2.67
  Mathematical Danger Zone (Lower Bound): $80.96
  Short-Term Gamma Support (MM Wall): $82.00

  [ SUGGESTED TACTICAL BWB SETUP ]
  BUY  1x  $87.00 Put
  SELL 2x  $82.00 Put  <-- (Pinned at Gamma Wall)
  BUY  1x  $72.00 Put  <-- (Broken Wing for Credit)

  *Note: Ensure this is entered for a NET CREDIT.*
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 CASH-SECURED PUTS (14-45 DTE) FOR BBY
================================================================================
  *What is this? You sign a contract promising to buy this stock next month
  if it drops in price, but you get paid cash right now for that promise.
  If it drops, you buy the stock on sale. If it doesn't drop, you keep the cash.*
--------------------------------------------------------------------------------

  [ CAPITAL PRESERVATION: THE ULTRA-SAFE CSP ]
  SELL 1x 2026-08-28 (17-DTE) $78.00 Put
  Premium Collected: $1.50
  Annualized Yield : 41.3%
  Safety Margin    : 8.5% (Breakeven: $76.50)
  Max Pain Anchor  : $83.00 (Strike is protected)

  *Note: The High-Yield scanner identified the exact same strike as the optimal setup.*
================================================================================

Debug: Client initialized with Key: 2Hy2...
Debug: Client initialized with Key: 2Hy2...

================================================================================
 THE BULL RISK REVERSAL (ZEBRA) FOR BBY
================================================================================
  *What is this? You sell a Put at the exact floor where Market Makers are
  defending the stock, getting paid cash. You immediately use that cash to
  buy a Call at the ceiling. If the stock crashes, you buy it on sale at the
  floor. If it rips through the ceiling, you have unlimited profit for zero cost.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-09-11 (31-DTE)

  [ SUGGESTED RISK REVERSAL SETUP ]
  SELL 1x  $80.00 Put  (Credit: $2.00)  <-- Gamma Support Wall
  BUY  1x  $94.00 Call (Debit : $2.00)  <-- Gamma Resistance Wall
  Total Net Credit : $0.00 (Literally a free trade)
  Capital Required : $8,000.00 (To secure the put assignment if it crashes)
  Max Upside Profit: UNLIMITED
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 JADE LIZARD SETUP (30-45 DTE) FOR BBY
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
 LEAPS HUNTER (300+ DTE) FOR BBY
================================================================================
  *What is this? Instead of paying $32,000 to buy 100 shares of stock, you
  pay $500 to rent the *rights* to 100 shares for two years. If it goes up,
  your $500 agreement goes up exactly as if you owned the $32,000 in shares.*
--------------------------------------------------------------------------------
  Target Expiration: 2028-01-21 (528-DTE)

  [ CAPITAL PRESERVATION: STOCK REPLACEMENT (DITM) ]
  BUY 1x $30.00 Call (Price: $53.75)
  Delta: 1.00 (Moves 1:1 with stock)
  Leverage: 1.6x (Cheaper than 100 shares)
  Time Rent (Extrinsic): 0.14%
  Breakeven: $83.75

  [ HIGH REWARD: THE LOTTERY TICKET (OTM) ]
  BUY 1x $135.00 Call (Price: $3.55)
  Delta: 0.20 (Explosive Convexity)
  Leverage: 23.6x
  *Note: High probability of expiring worthless. Small size only.*
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 HIGHLY SPECULATIVE PLAYS FOR BBY (HIGH RISK / HIGH REWARD)
================================================================================
  *What is this? Pure directional lottery tickets. You are betting that the
  stock explodes violently, or that it breaks a resistance wall forcing
  Market Makers to panic buy millions of shares to cover their short calls.*
--------------------------------------------------------------------------------

  [ VOLATILITY ERUPTION: THE ATM STRADDLE ]
  Target Expiration: 2026-08-28 (17-DTE)
  BUY 1x $84.00 Call (Price: $3.85)
  BUY 1x $84.00 Put  (Price: $3.62)
  Total Premium Risk: $7.47
  Implied Move Needed: ±8.94%
  Breakevens: < $76.53 OR > $91.47
  *Logic: You don't care about direction, only velocity. Best played before earnings.*

  [ THE GAMMA SQUEEZE HUNTER (LOTTERY TICKET) ]
  Identified Resistance Wall: 2,087 Open Contracts at $95.00
  Target Expiration: 2026-08-21 (10-DTE)
  BUY 1x $95.00 Call (Price: $0.10)
  *Logic: If the stock breaks $95.00, Market Makers must aggressively buy shares.*
  *Warning: Extremely high probability of 100% loss. Size accordingly.*
================================================================================


================================================================================
 PRONG 1: THE COMPANY (Critical Fundamentals)
================================================================================
  Price:             $83.63
  Market Cap:        $17,626,454,016
  Next Earnings:     N/A
  Directly Registered: 1,769 Shareholders (High Conviction Base)

  [ VALUATION & GROWTH ]
  P/E Ratio:         15.48
  PEG Ratio:         2.0
  P/TBV:             nan
  Shareholder Yield: 5.53% (Div: 4.7% | Buybacks: 2.0%)

  [ FINANCIAL HEALTH ]
  Altman Z-Score:    1.91 (>3.0 is Safe)
  Current Ratio:     1.12
  Piotroski F-Score: 6 / 9
  ROIC (Annualized): 20.81%
  FCF Yield:         4.88%

  [ SEC FINANCIAL TRAJECTORY ]
  Verdict:           ELIMINATE (Score: 0)
  FCF Grade:         B - Good growth +63%, mixed consistency
  Net Income Grade:  F - Severe decline -25%
  Revenue Grade:     D - Mild decline -8%

  [ MANAGEMENT & BOARD (SKIN IN THE GAME) ]
  Insider Score:     0/100
  Net Insider Trade: $-297,789,129
  Comp Score:        0/100 (Equity vs Cash)
  Overall Integrity: 20/100

================================================================================
 PRONG 2: THE MARKET (Structural & Derivatives)
================================================================================

  [ MARKET REGIME & TREND ]
  [ MARKET REGIME & TREND ]
  VIX Regime:        🟡 NORMAL (VIX: 15.43)
  Trend Verdict:     🔥 STRONG CANDIDATE — Trend + liquidity align with your scanner.

  [ ACCUMULATION / DISTRIBUTION ]
  Verdict:           GREEN LIGHT (Strong Accumulation)
  Insider Signal:    WHALE ACTIVITY
  Whale Alerts:      3 Active 13D/A Filings Found!

  [ OFF-EXCHANGE & SHORT INTEREST ]
  Avg Dark Short Vol: 580,554 shares/day
  Avg Dark Short %:   47.9% of Off-Exchange Volume

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
 Report Saved: ~/Desktop/antigravity/Single_Stock_Pipeline/reports/BBY_V2_Master_Report.md
================================================================================

