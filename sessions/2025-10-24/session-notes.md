# Session Notes - October 24, 2025

## Session Overview
- **Date**: 2025-10-24
- **Duration**: ~60 minutes
- **Format**: Practice problems - Investment Planning focus (bond valuation, technical analysis, stock valuation)
- **Main Topics**: Preferred stock valuation, zero-coupon bond taxation, technical analysis (support/resistance), bond yields (YTM/YTC), bond yield rankings
- **Days Until Exam**: 17 days

---

## Practice Problems Completed

### Question 1: Preferred Stock Intrinsic Value (D.32)

**Topic**: D.32 Bond and stock valuation - Investment Planning domain (17% of exam)

**Problem Given**: What is the intrinsic value of a preferred stock yielding a 7% dividend, par value of $35, currently priced at $33, if the required rate of return is 9%?

**Options**:
- A) $25.67
- B) $27.22 ✓
- C) $33
- D) $35

**Student's Initial Knowledge**: "No ideas about this at all"

**Student's Understanding After Teaching**:
- ✓ Preferred stock has fixed dividends (like bonds)
- ✓ Common stock dividends are optional
- ✓ Preferred stock acts more like bonds than stocks
- ✓ Priority in bankruptcy: Bonds → Preferred → Common

**Correct Answer**: **B) $27.22**

---

**Key Concept Taught: Preferred Stock Valuation**

**Formula**:
**Intrinsic Value = Annual Dividend ÷ Required Rate of Return**

This is a **perpetuity formula** because preferred stocks pay dividends forever.

---

**Step-by-Step Solution**:

**Step 1: Calculate Annual Dividend**
- Par value: $35
- Dividend yield: 7% of par
- Annual Dividend = $35 × 7% = **$2.45 per year**

**Step 2: Calculate Intrinsic Value**
- Intrinsic Value = $2.45 ÷ 0.09
- Intrinsic Value = **$27.22**

---

**Why Not the Other Answers?**

**A) $25.67** ❌
- Wrong calculation

**C) $33** ❌ - Common trap!
- This is the **current market price**
- Intrinsic value ≠ Market price
- Intrinsic value = What it SHOULD be worth
- Market price = What people are currently paying

**D) $35** ❌ - Another trap!
- This is the **par value**
- Not the same as intrinsic value

---

**Investment Analysis**:

**Current Price**: $33
**Intrinsic Value**: $27.22

**Conclusion**: Stock is **OVERVALUED**
- If you buy at $33 when it's only worth $27.22, you're overpaying
- Your actual return: $2.45 ÷ $33 = 7.4% (less than your 9% requirement)

**Decision**: Don't buy at current price (wait for price to drop to $27.22 or below)

---

**Understanding Level**: EXCELLENT - Student had no prior knowledge, understood perpetuity formula perfectly after explanation

---

### Question 2: Zero-Coupon Bond Taxation - OID Accretion (D.27, E.37)

**Topics**: D.27 Investment vehicles, E.37 Income tax calculations

**Problem Given**: On January 1, client purchased 10-year zero-coupon bond for $445 (par $1,000). Assuming annual compounding, what is the taxable interest in Year 2?

**Options**:
- A) 0%
- B) 37.53%
- C) 40.69% ✓
- D) 55.50%

**Student's Initial Understanding**:
- ✓ Buy at discount ($445), get $1,000 at maturity
- ✓ No coupon payments during life of bond
- ✓ Have to pay tax every year on "phantom income"
- ✗ Thought calculation was straight-line: ($1,000 - $445) ÷ 10 = $55.50/year

**Correct Answer**: **C) $40.69** (closest to calculated $40.57)

---

**The Critical Error: Straight-Line vs. Compound Interest**

**Student's Method** (WRONG for IRS):
- ($1,000 - $445) ÷ 10 years = $55.50 per year
- Same amount every year
- This is straight-line amortization

**IRS Required Method** (CORRECT):
- Use **compound interest accretion**
- Bond grows at its yield-to-maturity rate each year
- Taxable amount increases each year

---

**Step-by-Step Solution**:

**Step 1: Find the Implied Interest Rate (Yield to Maturity)**

The bond grows from $445 to $1,000 in 10 years.

**Formula**: FV = PV × (1 + r)^n

$1,000 = $445 × (1 + r)^10

Solving:
- (1 + r)^10 = $1,000 ÷ $445 = 2.247
- 1 + r = 2.247^(1/10) = 1.0841
- **r = 8.41%** (yield to maturity)

---

**Step 2: Calculate Year 1 Taxable Interest**

Beginning of Year 1: **$445.00**

Year 1 interest = $445.00 × 8.41% = **$37.42**

End of Year 1: $445.00 + $37.42 = **$482.42**

---

**Step 3: Calculate Year 2 Taxable Interest**

Beginning of Year 2: **$482.42**

Year 2 interest = $482.42 × 8.41% = **$40.57**

End of Year 2: $482.42 + $40.57 = **$522.99**

**Answer**: Closest to **$40.69** (Option C)

---

**Year-by-Year Accretion Table**:

| Year | Beginning Value | Interest (8.41%) | Ending Value | Tax Owed |
|------|----------------|------------------|--------------|----------|
| 1 | $445.00 | $37.42 | $482.42 | $37.42 |
| 2 | $482.42 | $40.57 | $522.99 | $40.57 |
| 3 | $522.99 | $43.98 | $566.97 | $43.98 |
| ... | ... | ... | ... | ... |
| 10 | ~$922 | ~$78 | $1,000.00 | ~$78 |

**Notice**: Tax owed **increases each year** because the bond's value grows!

---

**Why Not the Other Answers?**

**A) 0%** ❌
- Completely wrong! You definitely pay tax on zero-coupon bonds

**B) 37.53%** ❌
- This is close to Year 1 interest ($37.42)
- Question asks for Year 2, not Year 1

**D) 55.50%** ❌
- This is the straight-line calculation: $555 ÷ 10
- Would be correct if interest didn't compound
- But IRS requires compound interest method

---

**Key Concept: OID (Original Issue Discount)**

**OID** = Original Issue Discount = $1,000 - $445 = **$555 total**

**OID Accretion Rules**:
- Must use **compound interest** method (not straight-line)
- Each year's accretion is taxable as ordinary interest income
- Taxable amount increases each year
- This is called "phantom income" - you pay tax on money you didn't receive!

---

**Comparison: Straight-Line vs. Compound**

**Straight-Line** (Student's method - WRONG):
- Every year: $55.50 tax
- Total over 10 years: $555 ✓

**Compound Interest** (IRS method - CORRECT):
- Year 1: $37.42
- Year 2: $40.57
- Year 3: $43.98
- ... increases each year
- Total over 10 years: $555 ✓

**Same total, different timing!** (Timing matters for taxes)

---

**The Painful Reality of Zero-Coupon Bonds**:

**What You Receive**: $0 cash each year
**What You Pay Tax On**: $37.42 (Year 1), $40.57 (Year 2), etc.

This is **"phantom income"** - paying tax on money you didn't receive!

**Why Would Anyone Buy These?**
- **Tax-deferred accounts** (IRA, 401k) - no annual tax problem!
- **Predictable future value** - know exactly what you'll get
- **No reinvestment risk** - no coupons to worry about reinvesting

---

**Understanding Level**: VERY GOOD - Student understood concept of phantom income but needed correction on calculation method (compound vs. straight-line)

---

### Question 3: Technical Analysis - Support and Resistance (D.29, D.34)

**Topics**: D.29 Market cycles, D.34 Investment strategies

**Problem Given**: CFP professional using technical analysis to purchase 500 shares of XYZ stock. Stock has been trading between $20 and $26. How would a technician refer to these pricing levels?

**Options**:
- A) $20 is support; $26 is resistance ✓
- B) $20 is resistance; $26 is support
- C) $20 is resistance; $26 is breakout
- D) $20 is support; $26 is breakout

**Student's Initial Knowledge**: "No idea about support, breakout, resistance - all these things at all"

**Student's Understanding After Teaching**:
- ✓ Technical analysis focuses on price movements and charts
- ✓ Fundamental analysis focuses on company financials
- ✓ Support = floor where price bounces up
- ✓ Resistance = ceiling where price bounces down
- ✓ Breakout = breaking through support or resistance

**Correct Answer**: **A) $20 is support; $26 is resistance**

---

**Key Concepts Taught**:

### Technical Analysis vs. Fundamental Analysis

**Technical Analysis**:
- Focuses on **price movements** and chart patterns
- Believes past price patterns repeat
- Studies: Charts, volume, trend lines, support/resistance

**Fundamental Analysis**:
- Focuses on **company financials**
- Studies: Earnings, P/E ratio, revenue, balance sheet
- Determines intrinsic value

---

### Support = The Floor

**SUPPORT** is a price level where stock tends to **STOP FALLING** and **BOUNCE UP**.

**Why?**
- Buyers think: "Wow, $20 is a great price! I'll buy!"
- Lots of buying demand at $20 → price stops falling
- Acts as a **FLOOR** holding the price up

**In the Question**: $20 is SUPPORT
- Stock has bounced up from $20 multiple times

---

### Resistance = The Ceiling

**RESISTANCE** is a price level where stock tends to **STOP RISING** and **BOUNCE DOWN**.

**Why?**
- Sellers think: "Great! It hit $26 again, time to take profits!"
- Lots of selling pressure at $26 → price stops rising
- Acts as a **CEILING** holding the price down

**In the Question**: $26 is RESISTANCE
- Stock has bounced down from $26 multiple times

---

### Breakout = Breaking Through

**BREAKOUT** happens when price **breaks through** support or resistance.

**Two Types**:

**1. Upward Breakout** (breaks through resistance):
- Stock breaks ABOVE $26 (old resistance)
- Seen as **bullish** signal (price going higher)
- Technical analysts might buy

**2. Downward Breakout** (breaks through support):
- Stock breaks BELOW $20 (old support)
- Seen as **bearish** signal (price going lower)
- Technical analysts might sell

---

### Visual Representation

```
Price Chart for XYZ Stock:

$28 |
$27 |
$26 |------------------------● ← RESISTANCE (ceiling)
$25 |              ●        /|\
$24 |         ●   / \      / | \
$23 |    ●   / \ /   \    /  |  \
$22 |   / \ /   ●     \  /   |   ●
$21 |  /   ●           \/    |  / \
$20 |●--------------------●--------● ← SUPPORT (floor)
$19 |
    └─────────────────────────────────→ Time
```

Stock is **trading in a range** between $20 (support) and $26 (resistance).

---

### Memory Trick

Think of a **ball bouncing in a room**:

**SUPPORT** = **FLOOR** (ball bounces UP when it hits floor)

**RESISTANCE** = **CEILING** (ball bounces DOWN when it hits ceiling)

**BREAKOUT** = Ball **breaks through** floor or ceiling

---

**Why Not the Other Answers?**

**B) $20 is resistance; $26 is support** ❌
- **BACKWARDS!**
- $20 can't be resistance (stock bounces UP from there)
- $26 can't be support (stock bounces DOWN from there)

**C) $20 is resistance; $26 is breakout** ❌
- Wrong on both counts
- $20 is support, not resistance
- $26 is resistance, not breakout (it's holding price down, not being broken through)

**D) $20 is support; $26 is breakout** ❌
- $20 is support ✓ (correct!)
- But $26 is resistance, not breakout
- A breakout would only happen if price went ABOVE $26 or BELOW $20

---

**Technical Analysis Strategies**:

**Strategy 1 - Range Trading**:
- Buy near support ($20) ← "Buy low"
- Sell near resistance ($26) ← "Sell high"
- Repeat while stock bounces in range

**Strategy 2 - Breakout Trading**:
- Wait for stock to break above $26 → BUY (bullish momentum)
- Or wait for stock to break below $20 → SELL (bearish)

---

**Understanding Level**: EXCELLENT - Student had zero prior knowledge, grasped all three concepts (support, resistance, breakout) perfectly

---

### Question 4: Bond Yields - YTM vs. YTC for Callable Bonds (D.32)

**Topic**: D.32 Bond and stock valuation

**Problem Given**: QRP Company has 25-year bond, 10% coupon paid annually, trading at par. Bond can be called in 5 years at $105. What are YTM and YTC?

**Options**:
- A) YTM 10.80%, YTC 10.00%
- B) YTM 10.00%, YTC 10.50%
- C) YTM 10.00%, YTC 10.80% ✓
- D) YTM 9.47%, YTC 10.80%

**Student's Understanding**:
- ✓ Trading at par = trading at $1,000
- ✓ Coupon rate = annual payment
- ✓ Callable = company can buy back early
- ✓ Why call: Refinance at lower rate when interest rates drop
- ✗ Small error: Said 10% of $1,000 = $10 (corrected to $100)

**Correct Answer**: **C) YTM = 10.00%, YTC = 10.80%**

---

**Part 1: Yield-to-Maturity (YTM) - The Easy Shortcut**

**Given**:
- Bond trading at par ($1,000)
- Coupon rate: 10%
- Maturity: 25 years

**The Magic Rule**:
**When a bond trades AT PAR, YTM = Coupon Rate**

**YTM = 10.00%** ← Super easy!

**Why?**
- You pay $1,000 (par)
- You get $100/year for 25 years (10% coupon)
- You get $1,000 back at maturity
- Your total return = exactly 10%

**This immediately eliminated Answers A and D** (wrong YTM)

---

**Part 2: Yield-to-Call (YTC) - The Calculation**

**Callable Bond Scenario**:
- Can be called in 5 years
- Call price: $105 = **$1,050** (5% premium!)
- Still get $100/year coupons until then

**What Changes?**
- Instead of holding 25 years and getting $1,000 back
- You might only hold 5 years and get **$1,050** back
- That extra $50 is a bonus!

---

**YTC Calculation (Conceptual)**:

**What You Pay**: $1,000

**What You Get (if called)**:
- $100/year for 5 years (coupons)
- $1,050 at year 5 (call price - **bonus $50!**)

**Rough Approximation**:
- Regular return: $100/year = 10% ✓
- **PLUS**: Extra $50 gain spread over 5 years = $10/year additional
- Total: $100 + $10 = $110/year
- Approximate YTC: $110 ÷ $1,000 = 11%

**Exact YTC = 10.80%** (from financial calculator/formula)

---

**Key Insight: Why YTC > YTM**

**YTM scenario** (hold to maturity):
- Hold 25 years
- Get $1,000 back (par)
- Return = 10%

**YTC scenario** (called in 5 years):
- Hold only 5 years
- Get **$1,050** back (that's $50 extra!)
- This $50 bonus boosts your return
- Return = 10.80%

**Rule**: **YTC > YTM when call price > current price**

---

**Why Not the Other Answers?**

**A) YTM 10.80%, YTC 10.00%** ❌
- Backwards!
- YTM must be 10% (trading at par)
- YTC must be higher (getting $1,050 instead of $1,000)

**B) YTM 10.00%, YTC 10.50%** ❌
- YTM correct ✓
- But YTC too low (should be 10.80%)

**D) YTM 9.47%, YTC 10.80%** ❌
- YTC correct ✓
- But YTM wrong (should be 10% when trading at par)

---

**Key Bond Yield Relationships (Shortcuts)**:

**Trading at Par** (Price = $1,000):
- **YTM = Coupon Rate** ← MEMORIZE THIS!

**Trading at Premium** (Price > $1,000):
- YTM < Coupon Rate

**Trading at Discount** (Price < $1,000):
- YTM > Coupon Rate

**For Callable Bonds**:
- If call price > current price → **YTC > YTM**
- If call price < current price → **YTC < YTM**

---

**Real-World Implication: Call Risk**

**Investor's Dilemma**:
- YTC = 10.80% (looks good if called!)
- **BUT**: If called, you must reinvest at NEW lower rates (maybe 6%!)
- You lose the high 10% coupon payments

**Company's Perspective**:
- Rates dropped from 10% to 6%
- Call the old 10% bonds (pay $1,050)
- Issue new bonds at 6% (save 4% per year forever!)

**This is why callable bonds pay slightly higher coupons** (to compensate for call risk)

---

**Understanding Level**: EXCELLENT - Student understood bond basics perfectly, learned YTM shortcut and YTC calculation

---

### Topic 5: Bond Yield Rankings - Premium, Par, Discount (D.32)

**Topic**: D.32 Bond and stock valuation - Comprehensive yield relationships

**Student Request**: "Tell me the ranking when trading at premium - there is CY, CR, YTM, YTC and all these things together"

**This is a CRITICAL CFP exam pattern!**

---

## The Four Yield Measures Explained

**1. Coupon Rate (CR or Nominal Yield)**
- The stated interest rate on the bond
- **Formula**: Annual Coupon ÷ Par Value
- **Example**: $80 coupon on $1,000 bond = 8%
- **NEVER CHANGES** (it's printed on the bond!)

**2. Current Yield (CY)**
- What you earn per year based on what you PAID
- **Formula**: Annual Coupon ÷ Current Market Price
- **Example**: $80 coupon ÷ $900 price = 8.89%

**3. Yield-to-Maturity (YTM)**
- Total return if you hold to maturity
- Includes: Coupons + capital gain/loss at maturity
- Most comprehensive measure

**4. Yield-to-Call (YTC)**
- Total return if bond is called early
- Includes: Coupons + capital gain/loss at call date

---

## THE MASTER RANKING TABLE

| Bond Price | Lowest → Highest Yield |
|------------|------------------------|
| **PREMIUM** (> $1,000) | **YTC < YTM < CY < CR** |
| **PAR** (= $1,000) | **YTC = YTM = CY = CR** |
| **DISCOUNT** (< $1,000) | **CR < CY < YTM < YTC** |

---

## SCENARIO 1: Bond Trading at PREMIUM (Price > $1,000)

**Example**: 8% coupon, $1,000 par, trading at **$1,100**

**Ranking from LOWEST to HIGHEST**:

**YTC < YTM < CY < CR**

**The Numbers**:
- **CR** = $80 ÷ $1,000 = **8.00%** ← Highest (never changes)
- **CY** = $80 ÷ $1,100 = **7.27%** (lower because you paid more)
- **YTM** = ~**6.50%** (even lower - you lose $100 at maturity)
- **YTC** = ~**6.00%** ← Lowest (you lose $100 even sooner!)

**Why this order?**
- CR is fixed at 8%
- CY is lower (you paid premium for the bond)
- YTM is even lower (you have **capital loss** at maturity: paid $1,100, get back $1,000)
- YTC is lowest (you lose the premium SOONER if called early)

---

## SCENARIO 2: Bond Trading at PAR (Price = $1,000)

**Example**: 8% coupon, $1,000 par, trading at **$1,000**

**Ranking**: **ALL EQUAL!**

**YTC = YTM = CY = CR = 8.00%**

**Why?**
- No capital gain or loss
- All yields equal the coupon rate
- Super simple!

---

## SCENARIO 3: Bond Trading at DISCOUNT (Price < $1,000)

**Example**: 8% coupon, $1,000 par, trading at **$900**

**Ranking from LOWEST to HIGHEST**:

**CR < CY < YTM < YTC**

**The Numbers**:
- **CR** = $80 ÷ $1,000 = **8.00%** ← Lowest (never changes)
- **CY** = $80 ÷ $900 = **8.89%** (higher because you paid less)
- **YTM** = ~**10.00%** (even higher - you gain $100 at maturity)
- **YTC** = ~**11.00%** ← Highest (you gain $100 even sooner!)

**Why this order?**
- CR is fixed at 8%
- CY is higher (you paid discount for the bond)
- YTM is even higher (you have **capital gain** at maturity: paid $900, get back $1,000)
- YTC is highest (you get the gain SOONER if called early)

---

## MEMORY TRICKS 🧠

**For PREMIUM bonds**: Think "**Call Yields Terrible Misery**"
- YT**C** < YT**M** < C**Y** < C**R**
- Call is worst (lowest yield)

**For DISCOUNT bonds**: Think "**Can't You Try Calling?**"
- C**R** < C**Y** < YT**M** < YT**C**
- Call is best (highest yield)

**For PAR bonds**: "**Everyone's Equal!**"
- All the same

---

## Why YTC Changes Position

**The Pattern**:

**Premium bonds**: **YTC is LOWEST**
- Getting called means you lose your premium SOONER
- **BAD for you!** (you want to keep collecting high coupons)

**Discount bonds**: **YTC is HIGHEST**
- Getting called means you get your gain SOONER
- **GOOD for you!** (you get the capital gain faster)

**The Rule**:
- YTC assumes bond is called early (5-10 years typically)
- YTM assumes you hold to maturity (20-30 years)
- Whichever scenario gets you to the capital gain/loss FASTER = more extreme yield

---

## Visual Example with Real Numbers

**8% Coupon, $1,000 Par Bond**

### Premium ($1,100):
```
CR:  8.00% ← Highest (fixed)
CY:  7.27%
YTM: 6.50%
YTC: 6.00% ← Lowest
```
**YTC < YTM < CY < CR** ✓

### Par ($1,000):
```
CR:  8.00%
CY:  8.00%
YTM: 8.00%
YTC: 8.00%
```
**All Equal** ✓

### Discount ($900):
```
CR:  8.00% ← Lowest (fixed)
CY:  8.89%
YTM: 10.00%
YTC: 11.00% ← Highest
```
**CR < CY < YTM < YTC** ✓

---

## CFP Exam Quick Check Method

**Step 1**: Identify bond price status
- Price > $1,000 = Premium
- Price = $1,000 = Par
- Price < $1,000 = Discount

**Step 2**: Apply ranking
- Premium: YTC < YTM < CY < CR
- Par: All equal
- Discount: CR < CY < YTM < YTC

**Step 3**: Remember
- Coupon Rate NEVER changes
- For callable bonds:
  - Premium: You DON'T want it called (YTC lowest)
  - Discount: You DO want it called (YTC highest)

---

**Understanding Level**: EXCELLENT - Student requested comprehensive overview, received master ranking table with memory tricks

---

## Topics Covered Today

| Topic | CFP Code | Confidence | Notes |
|-------|----------|------------|-------|
| Preferred Stock Valuation | D.32 | High | Perpetuity formula mastered |
| Zero-Coupon Bond Taxation (OID) | D.27, E.37 | High | Compound accretion vs. straight-line understood |
| Technical Analysis - Support/Resistance | D.29, D.34 | High | Floor/ceiling concept mastered |
| Bond Yields - YTM vs YTC | D.32 | High | Shortcuts and relationships learned |
| Bond Yield Rankings | D.32 | High | Premium/Par/Discount master table learned |

---

## Key Concepts Mastered

### Preferred Stock Valuation (D.32)
- **Formula**: Intrinsic Value = Annual Dividend ÷ Required Return
- Perpetuity calculation (pays forever)
- Annual Dividend = Par Value × Dividend Yield
- Intrinsic value ≠ Current market price
- Compare to determine if overvalued or undervalued

### Zero-Coupon Bond Taxation - OID Accretion (D.27, E.37)
- **Original Issue Discount (OID)**: Par value - Purchase price
- **IRS Method**: Compound interest accretion (NOT straight-line)
- Calculate implied interest rate (YTM)
- Apply rate to growing basis each year
- Taxable amount increases each year
- "Phantom income" - pay tax on money not received
- Best held in tax-deferred accounts (IRA, 401k)

### Technical Analysis - Support and Resistance (D.29, D.34)
- **Technical analysis**: Focus on price patterns, charts
- **Fundamental analysis**: Focus on company financials
- **Support**: Floor where price bounces UP (buying demand)
- **Resistance**: Ceiling where price bounces DOWN (selling pressure)
- **Breakout**: Price breaks through support or resistance
- **Trading strategies**:
  - Range trading: Buy at support, sell at resistance
  - Breakout trading: Buy when breaks above resistance (bullish)

### Bond Yields - YTM vs YTC (D.32)
- **YTM**: Total return if held to maturity
- **YTC**: Total return if called early
- **Shortcut**: When trading at par, YTM = Coupon Rate
- **Callable bonds**: YTC > YTM when call price > current price
- **Call risk**: Bond called when rates drop (must reinvest at lower rates)

### Bond Yield Rankings (D.32) - MASTER PATTERN
**Premium bonds** (> par): **YTC < YTM < CY < CR**
- YTC lowest (lose premium soonest)
- Getting called is BAD (lose high coupon)

**Par bonds** (= par): **YTC = YTM = CY = CR**
- All equal to coupon rate

**Discount bonds** (< par): **CR < CY < YTM < YTC**
- YTC highest (gain capital appreciation soonest)
- Getting called is GOOD (get gain faster)

**Memory tricks**:
- Premium: "Call Yields Terrible Misery"
- Discount: "Can't You Try Calling?"
- Par: "Everyone's Equal"

---

## Progress Assessment

**New Topics Added**:
- D.27 Investment vehicles (zero-coupon bonds)
- D.29 Market cycles (technical analysis)
- D.32 Bond/stock valuation (preferred stocks, bond yields)
- D.34 Investment strategies (technical analysis)
- E.37 Income tax calculations (OID taxation)

**Domain Progress Update**:
- **Investment Planning (D)**: 44% → Moving toward completion
  - D.27 ✓ (partial - zero-coupon bonds)
  - D.29 ✓ (partial - technical analysis)
  - D.32 ✓ (NEW - comprehensive bond/stock valuation)
  - D.34 ✓ (partial - technical analysis strategies)

---

## Strengths Observed

- Quick learner - grasped new concepts without prior knowledge
- Good foundation (understood bonds, stocks, callable features)
- Asked clarifying questions when confused
- Requested comprehensive overview (yield rankings) showing desire for complete understanding
- Corrected own errors (10% of $1,000 = $10 → $100)

---

## Areas for Continued Practice

- D.27: Continue with investment vehicles (REITs, ETFs, mutual funds, etc.)
- D.30: Quantitative concepts (standard deviation, beta, Sharpe ratio)
- D.31: Asset allocation and MPT
- D.32: Continue with dividend discount model, P/E ratios, duration
- D.33: Portfolio development and IPS

---

## Session Statistics

**Session Duration**: ~60 minutes
**Practice Problems Completed**: 5 topics (preferred stock, zero-coupon, technical analysis, YTM/YTC, yield rankings)
**Topics Covered**: D.27, D.29, D.32, D.34, E.37
**Performance**: Excellent - strong understanding of new material with no prior knowledge
**Coverage**: Investment Planning domain deepening (17% of exam - HIGH PRIORITY)

**Days Until Exam**: 17 days

---

## Notes

**Day 5 of Study Plan - October 24, 2025**

Focused Investment Planning session covering bond and stock valuation, technical analysis, and tax implications. Student demonstrated excellent ability to learn new concepts from scratch.

**Major Learning Achievements**:
- Mastered preferred stock perpetuity valuation
- Understood zero-coupon bond compound accretion (corrected straight-line misconception)
- Learned technical analysis fundamentals (support, resistance, breakout)
- Grasped YTM vs YTC for callable bonds
- **Mastered comprehensive bond yield rankings** (premium/par/discount)

**Key Patterns Learned**:
- Trading at par → YTM = Coupon Rate (critical shortcut)
- Premium bonds: YTC < YTM < CY < CR
- Discount bonds: CR < CY < YTM < YTC
- Support = floor (bounces up), Resistance = ceiling (bounces down)
- OID must use compound interest, not straight-line

**Ready for**: Continue Investment Planning domain (D.30 quantitative concepts, D.31 asset allocation) OR move to General Principles (B domain at 30% - needs attention)

**Investment Planning Progress**: 4/9 topics → Moving toward 5-6/9 with today's additions

---

**Session Status**: COMPLETE - Ready to save
