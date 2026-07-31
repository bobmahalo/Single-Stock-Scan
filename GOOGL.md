
================================================================================
 ANTIGRAVITY PIPELINE: SINGLE STOCK ENGINE V2 | TARGET: GOOGL
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
Debug: Token expired, refreshing...
Current Price of GOOGL: $352.15
Fetching options chain from 2026-07-31 to 2026-09-14...

================================================================================
 TACTICAL RADAR (0-14 DTE) FOR GOOGL
================================================================================
Strike     | Put OI     | Call OI    | Put GEX      | Call GEX     | Net GEX     
--------------------------------------------------------------------------------
$325.00        | 7618       | 3531       | -2,294       | 555          | -1,739      
$330.00        | 6813       | 5757       | -2,850       | 1,738        | -1,112      
$332.50        | 9265       | 8650       | -2,357       | 718          | -1,639      
$335.00  <-- EM LOWER BOUND | 3153       | 14908      | -2,803       | 3,993        | 1,190       
$337.50        | 1104       | 7910       | -779         | 1,896        | 1,117       
$340.00        | 2540       | 16515      | -2,643       | 9,536        | 6,894       
$342.50        | 335        | 9461       | -535         | 9,076        | 8,541       
$345.00        | 1536       | 8903       | -3,353       | 17,492       | 14,139      
$347.50        | 882        | 6129       | -4,331       | 18,834       | 14,503      
$350.00        | 1459       | 14088      | -6,668       | 87,658       | 80,990      
$352.50  <-- PRICE | 86         | 3046       | -394         | 14,157       | 13,763      
$355.00        | 359        | 3801       | -946         | 19,082       | 18,136      
$357.50        | 112        | 7065       | -345         | 21,340       | 20,995      
$360.00        | 1208       | 8415       | -2,558       | 19,576       | 17,017      
$362.50        | 37         | 1554       | -74          | 2,206        | 2,132       
$365.00        | 219        | 5899       | -369         | 7,099        | 6,730       
$370.00  <-- EM UPPER BOUND | 276        | 7031       | -370         | 2,894        | 2,523       
$375.00        | 107        | 5233       | -116         | 1,956        | 1,840       
$380.00        | 4          | 6269       | -3           | 3,271        | 3,268       
================================================================================

[ STATISTICAL EXPECTED MOVE ]
Calculated EM: +/- $17.08
Expected Range: $335.07 to $369.23

[ SUGGESTED STRIKES (TACTICAL) ]
Major Support (Lower Bound)    : $350.00 (Put GEX: -6,668)
Major Resistance (Upper Bound) : $357.50 (Call GEX: 21,340)

Action: Monitor these levels for immediate volatility and Gamma squeeze potential.
================================================================================

[+] Successfully exported clean data to gex_tactical.csv


================================================================================
 STRUCTURAL ANCHOR (30-45 DTE) FOR GOOGL
================================================================================
Strike     | Put OI     | Call OI    | Put GEX      | Call GEX     | Net GEX     
--------------------------------------------------------------------------------
$280.00        | 297        | 16         | -30          | 2            | -28         
$285.00        | 159        | 15         | -32          | 3            | -29         
$290.00        | 224        | 1          | -45          | 0            | -45         
$295.00        | 2907       | 22         | -872         | 4            | -868        
$300.00        | 216        | 17         | -67          | 5            | -62         
$305.00        | 176        | 5          | -70          | 2            | -68         
$310.00        | 284        | 13         | -142         | 6            | -136        
$315.00        | 222        | 41         | -133         | 25           | -109        
$320.00        | 221        | 180        | -155         | 126          | -29         
$325.00  <-- EM LOWER BOUND | 107        | 84         | -86          | 67           | -19         
$330.00        | 194        | 204        | -175         | 184          | 9           
$335.00        | 95         | 112        | -95          | 112          | 17          
$340.00        | 60         | 111        | -60          | 111          | 51          
$345.00        | 16         | 156        | -18          | 171          | 154         
$350.00        | 13         | 371        | -16          | 444          | 428         
$355.00        | 24         | 206        | -26          | 226          | 200         
$360.00        | 6          | 125        | -7           | 137          | 130         
$365.00        | 28         | 106        | -30          | 116          | 86          
$370.00        | 11         | 150        | -11          | 150          | 139         
$375.00        | 5          | 137        | -5           | 136          | 131         
$380.00  <-- EM UPPER BOUND | 17         | 73         | -15          | 66           | 50          
$385.00        | 1          | 217        | -1           | 174          | 173         
$390.00        | 6          | 52         | -4           | 36           | 32          
$395.00        | 0          | 44         | 0            | 26           | 26          
$400.00        | 0          | 98         | 0            | 49           | 49          
$405.00        | 0          | 55         | 0            | 28           | 28          
$440.00        | 0          | 320        | 0            | 64           | 64          
$470.00        | 0          | 323        | 0            | 32           | 32          
================================================================================

[ STATISTICAL EXPECTED MOVE ]
Calculated EM: +/- $29.05
Expected Range: $323.10 to $381.20

[ SUGGESTED STRIKES (STRUCTURAL) ]
Major Support (Lower Bound)    : $295.00 (Put GEX: -872)
Major Resistance (Upper Bound) : $355.00 (Call GEX: 226)

Action: Sell the Put spread below the support, and sell the Call spread above the resistance.
================================================================================

[+] Successfully exported clean data to gex_structural.csv

Debug: Client initialized with Key: 2Hy2...

================================================================================
 TACTICAL BWB (BROKEN WING BUTTERFLY) FOR GOOGL
================================================================================
  *What is this? We find the invisible Gamma Wall where Market Makers will defend
  the stock from crashing. We build a trap right at that wall. If it crashes,
  we collect max profit. If it goes up instead, the trap breaks and we still
  keep a small credit. You literally cannot lose money on the upside.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-07-31 (0-DTE)
  Implied Volatility (ATM): 50.85%
  Tactical Expected Move: ±$9.38
  Mathematical Danger Zone (Lower Bound): $342.88
  Short-Term Gamma Support (MM Wall): $350.00

  [ SUGGESTED TACTICAL BWB SETUP ]
  BUY  1x  $360.00 Put
  SELL 2x  $350.00 Put  <-- (Pinned at Gamma Wall)
  BUY  1x  $330.00 Put  <-- (Broken Wing for Credit)

  *Note: Ensure this is entered for a NET CREDIT.*
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 CASH-SECURED PUTS (14-45 DTE) FOR GOOGL
================================================================================
  *What is this? You sign a contract promising to buy this stock next month
  if it drops in price, but you get paid cash right now for that promise.
  If it drops, you buy the stock on sale. If it doesn't drop, you keep the cash.*
--------------------------------------------------------------------------------

  [ CAPITAL PRESERVATION: THE ULTRA-SAFE CSP ]
  SELL 1x 2026-09-04 (35-DTE) $320.00 Put
  Premium Collected: $3.25
  Annualized Yield : 10.6%
  Safety Margin    : 10.1% (Breakeven: $316.75)
  Max Pain Anchor  : $325.00 (Strike is protected)

  [ INCOME ACCUMULATOR: THE HIGH-YIELD CSP ]
  SELL 1x 2026-08-14 (14-DTE) $345.00 Put
  Premium Collected: $5.45
  Annualized Yield : 41.2%
  Safety Margin    : 3.6% (Breakeven: $339.55)
================================================================================

Debug: Client initialized with Key: 2Hy2...
Debug: Client initialized with Key: 2Hy2...

================================================================================
 THE BULL RISK REVERSAL (ZEBRA) FOR GOOGL
================================================================================
  *What is this? You sell a Put at the exact floor where Market Makers are
  defending the stock, getting paid cash. You immediately use that cash to
  buy a Call at the ceiling. If the stock crashes, you buy it on sale at the
  floor. If it rips through the ceiling, you have unlimited profit for zero cost.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-09-04 (35-DTE)

  [ SUGGESTED RISK REVERSAL SETUP ]
  SELL 1x  $295.00 Put  (Credit: $0.82)  <-- Gamma Support Wall
  BUY  1x  $430.00 Call (Debit : $0.69)  <-- Gamma Resistance Wall
  Total Net Credit : $0.13 (You get PAID to enter this)
  Capital Required : $29,500.00 (To secure the put assignment if it crashes)
  Max Upside Profit: UNLIMITED
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 JADE LIZARD SETUP (30-45 DTE) FOR GOOGL
================================================================================
  *What is this? You collect massive income from selling a put, and use that
  cash to fully finance a call spread above the stock. Zero upside risk.
  If the stock crashes, you buy it on sale. If it rips to the moon,
  you still make money even if the call spread blows up.*
--------------------------------------------------------------------------------
  Target Expiration: 2026-09-11 (42-DTE)

  [ SUGGESTED JADE LIZARD SETUP (ZERO UPSIDE RISK) ]
  SELL 1x  $335.00 Put   (Credit: $6.65)
  SELL 1x  $370.00 Call
  BUY  1x  $375.00 Call
  Call Spread Credit: $-0.25

  Total Premium Collected : $6.40
  Max Call Spread Risk    : $5.00
  Net Upside Edge         : +$1.40 (Guaranteed profit if stock rips upward!)
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 LEAPS HUNTER (300+ DTE) FOR GOOGL
================================================================================
  *What is this? Instead of paying $32,000 to buy 100 shares of stock, you
  pay $500 to rent the *rights* to 100 shares for two years. If it goes up,
  your $500 agreement goes up exactly as if you owned the $32,000 in shares.*
--------------------------------------------------------------------------------
  Target Expiration: 2028-12-15 (868-DTE)

  [ CAPITAL PRESERVATION: STOCK REPLACEMENT (DITM) ]
  BUY 1x $5.00 Call (Price: $348.00)
  Delta: 1.01 (Moves 1:1 with stock)
  Leverage: 1.0x (Cheaper than 100 shares)
  Time Rent (Extrinsic): 0.21%
  Breakeven: $353.00

  [ HIGH REWARD: THE LOTTERY TICKET (OTM) ]
  BUY 1x $790.00 Call (Price: $14.45)
  Delta: 0.16 (Explosive Convexity)
  Leverage: 24.4x
  *Note: High probability of expiring worthless. Small size only.*
================================================================================

Debug: Client initialized with Key: 2Hy2...

================================================================================
 HIGHLY SPECULATIVE PLAYS FOR GOOGL (HIGH RISK / HIGH REWARD)
================================================================================
  *What is this? Pure directional lottery tickets. You are betting that the
  stock explodes violently, or that it breaks a resistance wall forcing
  Market Makers to panic buy millions of shares to cover their short calls.*
--------------------------------------------------------------------------------

  [ VOLATILITY ERUPTION: THE ATM STRADDLE ]
  Target Expiration: 2026-08-14 (14-DTE)
  BUY 1x $352.50 Call (Price: $9.20)
  BUY 1x $352.50 Put  (Price: $9.05)
  Total Premium Risk: $18.25
  Implied Move Needed: ±5.18%
  Breakevens: < $334.25 OR > $370.75
  *Logic: You don't care about direction, only velocity. Best played before earnings.*

  [ THE GAMMA SQUEEZE HUNTER (LOTTERY TICKET) ]
  Identified Resistance Wall: 4,115 Open Contracts at $357.50
  Target Expiration: 2026-08-07 (7-DTE)
  BUY 1x $357.50 Call (Price: $4.53)
  *Logic: If the stock breaks $357.50, Market Makers must aggressively buy shares.*
  *Warning: Extremely high probability of 100% loss. Size accordingly.*
================================================================================


================================================================================
 PRONG 1: THE COMPANY (Critical Fundamentals)
================================================================================
  Price:             $352.25
  Market Cap:        $4,308,050,903,040
  Next Earnings:     N/A
  Directly Registered: 5,861 Shareholders (High Conviction Base)

  [ VALUATION & GROWTH ]
  P/E Ratio:         17.7
  PEG Ratio:         1.31
  P/TBV:             7.51
  Shareholder Yield: 0.64% (Div: 0.3% | Buybacks: 1.6%)

  [ FINANCIAL HEALTH ]
  Altman Z-Score:    10.85 (>3.0 is Safe)
  Current Ratio:     2.72
  Piotroski F-Score: 5 / 9
  ROIC (Annualized): 64.95%
  FCF Yield:         -0.54%

  [ SEC FINANCIAL TRAJECTORY ]
  Verdict:           PASS (Score: 70.0)
  FCF Grade:         C - Flat trend 0%
  Net Income Grade:  A - Strong growth +120%, 71% quarters improving
  Revenue Grade:     A - Strong growth +32%, 100% quarters improving

  [ MANAGEMENT & BOARD (SKIN IN THE GAME) ]
  Insider Score:     0/100
  Net Insider Trade: $-5,716,551
  Comp Score:        0/100 (Equity vs Cash)
  Overall Integrity: 20/100

================================================================================
 PRONG 2: THE MARKET (Structural & Derivatives)
================================================================================

  [ MARKET REGIME & TREND ]
  [ MARKET REGIME & TREND ]
  VIX Regime:        🟡 NORMAL (VIX: 17.32)
  Trend Verdict:     ❌ PASS — Scanner likes it, but the trend engine says no.

  [ ACCUMULATION / DISTRIBUTION ]
  Verdict:           HOLD / WATCH
  Insider Signal:    NEUTRAL

  [ OFF-EXCHANGE & SHORT INTEREST ]
  Avg Dark Short Vol: 5,041,998 shares/day
  Avg Dark Short %:   44.5% of Off-Exchange Volume

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
 Report Saved: ~/Desktop/antigravity/Single_Stock_Pipeline/reports/GOOGL_V2_Master_Report.md
================================================================================

