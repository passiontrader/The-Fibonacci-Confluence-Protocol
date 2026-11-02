# FIBONACCI CONFLUENCE ZONE PROTOCOL - OPERATIONAL RULEBOOK
## SYSTEM SCOPE: Fibonacci Support/Resistance Zones, Trend Pullbacks, Symmetry Reversals, Two-Leg Patterns, Breakout Gaps, Entry Triggers & Risk Control

---

## FUNDAMENTAL PRINCIPLE

**Price reverses where several independent Fibonacci measurements of prior swings converge. Every trade is taken against such a confluence zone, and only after price action confirms the turn.**

Fibonacci ratios measure how far crowd interest expands and contracts, so measured swings mark where optimism turns to pessimism and back. One level is noise; 3 or more levels in a tight range form a decision zone (Confluence Zone). Each setup in this system is a specific structure that delivers price into a Confluence Zone: a trend pullback, a symmetrical swing, a three-ratio stack, a two-leg pattern, a 200-day average fake-out, an extension trap, or a break into an empty gap. A lower-timeframe trigger confirms entry. The stop sits beyond the zone, the first target banks half, and the remainder is trailed. Fixed per-trade and portfolio risk limits apply to every setup.

---

## GLOSSARY

| Term | Operational definition |
|---|---|
| Swing high / swing low | Bar high with a lower high on each side / bar low with a higher low on each side (RULE 006, RULE 007) |
| X, A, B, C, D | Labels for consecutive swing points used in calculations; their meaning is fixed inside each setup block |
| Retracement | Countertrend move recapturing < 100% of X:A; ratios 0.382, 0.500, 0.618, 0.786 |
| Extension | Countertrend move recapturing > 100% of X:A; ratios 1.272, 1.618 (2.618 when in range) |
| Projection | Prior swing X:A applied from B in the same direction; ratios 0.618, 1.000, 1.618 |
| Expansion | Swing X:A extended from A; ratios 0.618, 1.000, 1.618; confirming study only |
| Symmetry level | Price where the current swing equals the prior comparable swing in points (1.000 projection) |
| Confluence Zone | Tight price range holding 3+ Fibonacci levels; support below price, resistance above |
| TRZ | Three-Ratio Zone: 0.500 and 0.618 of A:C with 0.786 of B:C stacked between them |
| TLP | Two-Leg Pattern: A:B, pullback B:C, then C:D beyond B |
| AB=CD / Gartley / Butterfly TLP | TLP variants defined by A:B = C:D / D at 0.618-0.786 of X:A / D at 1.272-1.618 of X:A beyond X |
| Trend Pullback | Pullback entry into a Confluence Zone within a confirmed trend (Module 06) |
| Symmetry Reversal | Symmetrical pullback into a Confluence Zone inside a strong ADX/DI trend (Module 07) |
| 200-SMA Fake-Out | TLP completing just beyond the 200-day SMA into a Confluence Zone, fading the crowd (Module 10) |
| Extension Trap | Break of the 0.786 to a 1.272-1.618 extension that traps breakout traders, then reverses (Module 11) |
| Zone Gap (RGB / CGB) | Empty gap between two Confluence Zones; reversal or continuation breakout variant (Module 12) |
| ADX | Average Directional Index; trend strength 0-100, no direction |
| +DI / −DI | Directional Indicators; the higher line gives trend direction |
| SMA | Simple moving average |
| Trigger | Price-action confirmation that permits entry (Module 13) |
| Breakeven (BE) | Stop placed at the entry price |
| Half 1 / Half 2 | The two halves of a position managed separately by the exit plan |

---

## MODULE 01: RATIO SET AND SCOPE

### Definition: Fibonacci Ratio Set

**RULE:** Every level in this system is built from one fixed set of Fibonacci ratios applied to measured price swings.

**CONTEXT:** Dividing any number in the series 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89... by the number before it converges on 1.618. The ratios mark where crowd interest in a market expands and contracts, so they locate the turning points between optimism and pessimism.

**RULE 001-CORE RATIOS:** The two core ratios are 0.618 and 1.618.

**RULE 002-DERIVED RATIOS:** Use these derived ratios alongside the core pair:

| Ratio | Derivation |
|---|---|
| 0.382 | 0.618²; also the inverse of 2.618 (ratio between alternate series numbers) |
| 0.500 | 2nd series number divided by the 3rd |
| 0.786 | √0.618 |
| 1.000 | 1.618 × 0.618; also used for symmetry measurement |
| 1.272 | √1.618 |
| 2.618 | 1.618² |

**RULE 003-MARKET SCOPE:** Apply the method to stocks, futures, and commodities, for day, swing, and position trading.

**RULE 004-TIMEFRAME SCOPE:** Apply identical analysis on any time frame that has enough volume and data to form a measurable price bar.

**RULE 005-LEVEL PURPOSE:** Fibonacci levels project price zones where a trend reversal has a high probability; they are decision points, never trade signals by themselves (see RULE 039).

---

## MODULE 02: SWING POINT SELECTION

### Definition: Swing Point

**RULE:** A swing point is a high or low where price reverses direction; it is the anchor for every Fibonacci calculation.

**CONTEXT:** Wrong anchors produce wrong levels. Selection follows a short set of objective tests rather than a complex definition.

**RULE 006-SWING HIGH:** A swing high is a bar high with a lower high on each side of it.

**RULE 007-SWING LOW:** A swing low is a bar low with a higher low on each side of it.

**RULE 008-CONSOLIDATION LOWS:** When several lows sit relatively close in price inside a consolidation, use only the low furthest to the right.

**RULE 009-CONSOLIDATION HIGHS:** When several highs sit relatively close in price inside a consolidation, use only the high furthest to the right.

**RULE 010-INVALID SWING LOW:** When calculating support, a swing low is invalid if a lower swing low exists to its right.

**RULE 011-INVALID SWING HIGH:** When calculating resistance, a swing high is invalid if a higher swing high exists to its right.

```text
VALID / INVALID SWINGS (support case)
 L1 = low ............ USE (no lower low to its right)
 L2 = higher low, then a LOWER low L3 prints to its right => L2 INVALID
 L3 = low ............ USE
 H-final = highest high on the right ..... USE for resistance
```

**RULE 012-SUPPORT ANCHORS:** To calculate support in an uptrend after a new swing high, use ONE swing high (the current one) and MULTIPLE prior swing lows.

**RULE 013-RESISTANCE ANCHORS:** To calculate resistance in a downtrend after a new swing low, use ONE swing low (the current one) and MULTIPLE prior swing highs.

**RULE 014-ANCHOR CONFIRMATION:** Calculate levels only after the current swing point is confirmed: a lower high on each side of a high, a higher low on each side of a low.

**RULE 015-SWING LOOKBACK LIMIT:** Use up to 8 consecutive swing points; to go further back, move to a higher time frame (e.g., from 30-minute to daily).

**RULE 016-FOUR KEY SWINGS:** In a trending market the four highest-weight swings are:
- A: the swing point just made.
- B: the swing point made immediately before price reversed into the current trend (trend origin).
- C, D: the two most recent with-trend swing points preceding A (in an uptrend, the last two higher lows).

```text
FOUR KEY SWINGS (uptrend)
                         A  <- current swing high
              /\  D /\  /
         /\  /  \/  \/      C, D = last two higher lows before A
    \/\ /  \/ C
       B                    B = low that launched the trend
```

**RULE 017-SWING VISUAL CHECK:** View the whole chart at once; significant swings stand out. Selection speed improves with repetition and is not a reason to skip a calculation.

---

## MODULE 03: THE FOUR PRICE STUDIES

### Definition: Price Study

**RULE:** Four studies generate every support and resistance level: retracements, extensions, projections, and expansions.

**CONTEXT:** Each study measures a prior swing and applies ratios to it from a defined point. Studies differ only in which ratio set is used and which point the measurement is applied from.

```text
STUDY MAP            SUPPORT case            RESISTANCE case
RETRACEMENT      X up to A, B pulls back   X down to A, B bounces
EXTENSION        X up to A, B falls BELOW X   X down to A, B rises ABOVE X
PROJECTION       X:A down, B bounce, C = B - (X:A × r)   mirror for resistance
EXPANSION        X:A down, C = A - (X:A × r)  (B ignored) mirror for resistance
```

### Retracements

**RULE 018-RETRACEMENT DEFINITION:** A retracement is a countertrend move (A to B) that recaptures less than 100% of the prior swing X:A.

**RULE 019-RETRACEMENT RATIOS:** Retracement ratios are 0.382, 0.500, 0.618, and 0.786.

**RULE 020-RETRACEMENT FORMULA:**
- Input: swing X and swing A.
- Calculation: Range = |A − X|; Points = Range × ratio.
- Output: support (X:A up) = A − Points; resistance (X:A down) = A + Points.
- CHECK: X = 10, A = 30 → 0.382 = 22.36, 0.500 = 20.00, 0.618 = 17.64, 0.786 = 14.28. Reverse (X = 30, A = 10) → 17.64, 20.00, 22.36, 25.72.

### Extensions

**RULE 021-EXTENSION DEFINITION:** An extension is a countertrend move that recaptures MORE than 100% of X:A; B travels beyond X.

**RULE 022-EXTENSION RATIOS:** Extension ratios are 1.272 and 1.618. The 2.618 extension is also plotted during zone construction when it falls in range.

**RULE 023-EXTENSION FORMULA:**
- Input: swing X and swing A.
- Calculation: Range = |A − X|; Points = Range × ratio.
- Output: support (X:A up) = A − Points; resistance (X:A down) = A + Points.
- CHECK: X = 20, A = 30 → 1.272 = 17.28, 1.618 = 13.82. Reverse (X = 30, A = 20) → 32.72, 36.18.

### Projections

**RULE 024-PROJECTION DEFINITION:** A projection measures a prior swing X:A and applies it from point B in the SAME direction as X:A; three points (X, A, B) must exist.

**RULE 025-PROJECTION RATIOS:** Projection ratios are 0.618, 1.000, and 1.618.

**RULE 026-PROJECTION FORMULA:**
- Input: swings X, A, B.
- Calculation: Range = |A − X|; Points = Range × ratio.
- Output: support (X:A down) = B − Points; resistance (X:A up) = B + Points.
- CHECK: X = 40, A = 30, B = 35 → 0.618 = 28.82, 1.000 = 25.00, 1.618 = 18.82. Resistance (X = 30, A = 40, B = 35) → 41.18, 45.00, 51.18.

**RULE 027-SYMMETRY PROJECTION:** In an uptrend, measure each prior countertrend decline and subtract its full size (1.000) from the current swing high; in a downtrend, add each prior countertrend rally to the current swing low.

### Expansions

**RULE 028-EXPANSION DEFINITION:** An expansion measures X:A and extends it from A in the direction price is heading; only two points (X, A) are needed and B is ignored.

**RULE 029-EXPANSION RATIOS:** Expansion ratios are 0.618, 1.000, and 1.618.

**RULE 030-EXPANSION FORMULA:**
- Input: swing X and swing A.
- Calculation: Range = |A − X|; Points = Range × ratio.
- Output: support (X:A down) = A − Points; resistance (X:A up) = A + Points.
- CHECK: X = 50, A = 45 → 0.618 = 41.91, 1.000 = 40.00, 1.618 = 36.91. Resistance (X = 30, A = 40) → 46.18, 50.00, 56.18.

**RULE 031-EXPANSION CONFIRMS ONLY:** Apply retracements, extensions, and projections first; use expansions only to confirm a zone those three studies already form. Skip expansions when the chart structure gives no valid X:A for them.

---

## MODULE 04: CONFLUENCE ZONES

### Definition: Confluence Zone

**RULE:** A Confluence Zone is a relatively tight price range where at least 3 Fibonacci levels from any combination of the four studies cluster.

**CONTEXT:** Nearly every setup in this system is a market reaching a support or resistance Confluence Zone. The zone tells where to look; an entry pattern inside it tells when to act.

**RULE 032-ZONE POLARITY:** A Confluence Zone above current price is resistance; a Confluence Zone below current price is support.

**RULE 033-ZONE MINIMUM:** A cluster of fewer than 3 levels is not a Confluence Zone.

### How to Build a Support Confluence Zone (uptrend; reverse every step for a resistance zone in a downtrend)

**RULE 034-ZONE BUILD SEQUENCE:**
1. Identify the current confirmed swing high and all valid prior swing lows (RULE 006 to RULE 016).
2. Retracements: from each valid swing low up to the current swing high.
3. Extensions: from swing lows that sit ABOVE current price up to the current swing high.
4. Projections: subtract each prior countertrend decline in the trend from the current swing high (RULE 027).
5. Expansions: last, and only if the structure allows (RULE 031).

**RULE 035-VIOLATED LEVEL DELETE:** Delete any level that current price has cleanly passed through; it is no longer valid. If a level is penetrated only by a few cents intrabar during zone construction, retain it if other levels cluster with it.

**RULE 036-VIOLATED ANCHOR SWITCH:** When a swing low already sits above current price, drop its retracements and use its 1.272/1.618 extensions instead.

**RULE 037-ISOLATED LEVEL DELETE:** Delete any level that has no other Fibonacci levels near it to form a zone.

**RULE 038-ZONE WIDTH LIMIT:** Preferred Confluence Zone width (zone low to zone high) is ≤ 10% of the security's price (commonly ~5%). When a zone spans wider (up to ~15%, e.g., 2 points on a 14.00 stock), it remains tradable ONLY because entry is governed by an entry pattern forming inside the zone, never by zone boundaries alone. CHECK: on a 40.00 stock, the zone is not much more than 4 points deep.

**RULE 039-NO ZONE-ONLY TRADE:** Never trade on a Confluence Zone alone, whatever its level count. Enter only on a valid entry pattern that forms inside the zone (defined in RULE 187).

**RULE 040-ZONE STRENGTH:** The more levels a Confluence Zone contains in a tight range, the more important it is. Strength is graded by level count only; no probability value is defined.

**RULE 041-NO RATIO PREFERENCE:** A generic Confluence Zone requires no specific ratio; any confluence counts. Specific strategies that require specific ratios state them in their own rules.

**RULE 042-NO STUDY PREFERENCE:** No study outranks another; level density in a tight range is the only measure.

**RULE 043-MULTIPLE ZONES:** When more than one zone exists, trade the zone in which an entry trigger actually forms (see RULE 201).

**RULE 044-ZONE RECALCULATION:** In an uptrend, build a new support zone only after the current high is exceeded and a new confirmed swing high forms. In a downtrend, build a new resistance zone only after the current low is broken and a new confirmed swing low forms.

**RULE 045-CHARTING TOOL REQUIREMENTS:** The charting tool must run all four studies, delete individual levels, annotate charts, display candlesticks, and run other technical studies.

**SKIP A CONFLUENCE ZONE WHEN:**
- Fewer than 3 levels cluster (RULE 033).
- Width exceeds 10% of price (RULE 038).
- No entry pattern forms inside it (RULE 039).
- Price has already traded through its levels (RULE 035).
## MODULE 05: CONFIRMATION LAW FOR ALL SETUPS

**RULE 046-TRIGGER REQUIRED:** Every setup in Modules 06 onward requires confirmation: wait for an entry trigger to form in price action against the Confluence Zone before entering long or short.

**RULE 047-ENTRY MEANS PATTERN:** Every "entry" in a setup rule means one of the entry patterns defined in RULE 187 (or another explicit trigger); a zone touch alone is never an entry.

---

## MODULE 06: TREND PULLBACK ENTRY

### Definition: Trend Pullback

**RULE:** A Trend Pullback trade buys a normal pullback in an uptrend (or sells a normal rally in a downtrend) where the pullback stops inside a Confluence Zone and reverses back in the trend direction.

**CONTEXT:** It is the simplest Confluence Zone setup. The trade is with the immediate trend, so the zone only has to hold a routine countertrend move.

```text
TREND PULLBACK LONG
 1.272 ext of H->L swing into zone ------  <- (6) FINAL TARGET
 .618 retr -------  ]  (4)/(5) FIRST TARGET range: exit half
 .50  retr -------  ]
 H1 < H2 < H3 (2+ higher highs), L1 < L2 (1+ higher low)  (1)
 bar low touches TOP of [CONFLUENCE ZONE] => look for ENTRY pattern (2)
 SL = just below [CONFLUENCE ZONE] (3)
```

**RULE 048-TREND STRUCTURE:** For longs, require at least 2 higher swing highs and at least 1 higher swing low. For shorts, require at least 2 lower swing lows and at least 1 lower swing high.

**RULE 049-ZONE TIMING:** For shorts, calculate the Resistance Confluence Zone once the second lower swing low is made; for longs, once the second higher swing high is made.

### How to Trade Trend Pullback

**ENTRY CONDITIONS:**
- Trend structure confirmed (RULE 048).
- Current bar low touches at least the TOP of the Support Confluence Zone (shorts: bar high touches at least the BOTTOM of the Resistance Confluence Zone).
- An entry pattern forms at the zone (RULE 046).

**RULE 050-ZONE TOUCH ENTRY:** When the current bar reaches the near edge of the Confluence Zone, enter using one of two variants:
- VARIANT A (Conservative, default): wait for an entry pattern to form in price action against the zone (RULE 046).
- VARIANT B (Aggressive): enter directly on the first touch of the near edge of the Confluence Zone (e.g., resting limit order at the zone boundary). Trade-off: offers an optimal entry price and minimal point risk to the stop, but lacks structural confirmation that the zone will hold. ⚠ CONFLICT with RULE 046.

**STOP PLACEMENT:**

**RULE 051-STOP BEYOND ZONE:** Place the initial stop just beyond the far edge of the Confluence Zone (longs: just below the zone; shorts: just above it).

**RULE 052-ZONE TOO DEEP:** If risking the full zone breaks money-management limits, choose one:
1. Wait until price moves deep enough into the zone for the stop distance to fit the limit.
2. Reduce position size until the full-zone risk fits the limit.
3. Skip the trade.

**TARGET:**

**RULE 053-TARGET CALCULATION:** Once a swing point forms against the Confluence Zone, measure the swing from the last trend extreme into the zone (high-to-low for longs, low-to-high for shorts) and calculate its 0.500 and 0.618 retracements and its 1.272 extension.

**RULE 054-FIRST TARGET:** Take the first profit between the 0.500 and 0.618 retracement of that swing; exit half the position there.

**RULE 055-TRAIL AFTER FIRST:** After the first profit is booked, trail the stop to reduce risk; move it to breakeven (entry price), especially on intraday trades.

**RULE 056-FINAL TARGET:** Exit the remainder at the 1.272 extension of the swing into the Confluence Zone.

**RULE 057-BREAKEVEN STOP CAUTION:** When trailing to breakeven, account for the instrument's volatility; do not place stops on round numbers or too close to current price.

### Trade Management

**RULE 058-HOVER SCRATCH:** The strongest trades bounce out of the Confluence Zone immediately and turn profitable quickly. If price keeps printing bars that hover around the zone after entry, scratch the trade. Holding time is not otherwise fixed.

**RULE 059-ADX CONFIRMATION:** Use a 14-period ADX reading of 20 or greater as a scan and confirmation filter; prefer an upsloping ADX line (trend strengthening). A downsloping ADX shows a trend losing strength.

**PROBABILITY:** not quantified.

**SKIP TREND PULLBACK WHEN:**
- Fewer than 2 higher highs or no higher low (longs), or the mirror for shorts (RULE 048).
- Price has not reached the Confluence Zone edge (RULE 050).
- No entry pattern forms (RULE 046).
- Full-zone risk exceeds money-management limits and neither waiting nor resizing fixes it (RULE 052).
- ADX(14) is below 20 or downsloping (RULE 059).

---

## MODULE 07: SYMMETRY REVERSAL WITH TREND STRENGTH

### Definition: Symmetry

**RULE:** Symmetry exists when the current swing matches the previous comparable swing in price size, in time duration, or both; a symmetrical swing has a high likelihood of reversing.

**CONTEXT:** Markets repeat the size and length of their countertrend swings. When a pullback reaches the same size or bar count as the prior pullback inside a Confluence Zone, the reversal point is sharply defined.

**RULE 060-PRICE SYMMETRY:** Price symmetry: the current swing covers the same number of points as the previous swing in the same direction.

**RULE 061-TIME SYMMETRY:** Time symmetry: the current swing lasts the same number of bars as the previous swing in the same direction; it is a precursor to strong reversals.

**RULE 062-SYMMETRY SCAN:** No mechanical scan for price symmetry is defined; measure it manually on the chart.

### Definition: Directional Indicator (DI) and ADX

**RULE 063-DI DIRECTION:** Use a 21-period DI. +DI above −DI = uptrend; −DI above +DI = downtrend.

**RULE 064-ADX STRENGTH:** ADX measures trend strength from 0 to 100, never direction:
- Below 20 = weak trend.
- Above 35 = strong trend.
- 50 to 60 = rare; signals a short-lived climax move.
- Above 60 = rare.

**RULE 065-SYMMETRY REVERSAL ADX SETTING:** For this setup use an 8-period ADX with a reference line at 50.

### Definition: Symmetry Reversal

**RULE:** A Symmetry Reversal trade enters a strong short- to intermediate-term trend that is pulling back into a Confluence Zone where the pullback matches the prior countertrend swing in size, duration, or both.

```text
SYMMETRY REVERSAL LONG (8-ADX > 50, 21 +DI > -DI)
 1.272 ext of C:D ---------------------  <- FINAL TARGET
 C = swing high after ADX(8) > 50
 .50-.618 retr of C:D ---------------  <- FIRST TARGET, trail to BE
 A:B = prior countertrend decline (points + bars)
 [SUPPORT CONFLUENCE ZONE] contains C - (A:B points) = SYMMETRY level
 D = low into zone; ENTRY = trade above prior bar high
 SL = just below [SUPPORT CONFLUENCE ZONE]
```

### How to Trade Symmetry Reversal (longs; reverse every step for shorts)

**RULE 066-ADX TRIGGER:** The 8-period ADX crosses above 50.

**RULE 067-POINT C:** After the ADX cross, wait for a swing high to form; label it C (shorts: a swing low).

**RULE 068-DI CHECK AT C:** At point C, the 21-period +DI is above −DI (shorts: −DI above +DI). If not, there is no setup.

**RULE 069-MEASURE A:B:** From C, find the previous significant countertrend decline: A = its high, B = its low (shorts: the prior countertrend rally, A = low, B = high). Record both its size in points and its duration in bars.

**RULE 070-ZONE FROM C:** Build a Support Confluence Zone from high point C using all four studies (RULE 034); shorts build a Resistance Confluence Zone from low point C.

**RULE 071-SYMMETRY LEVEL:** Project the A:B size from C (longs: C − A:B points; shorts: C + A:B points). The Confluence Zone that contains this symmetry level is the one to trade.

**RULE 072-SYMMETRY TOLERANCE:** Price symmetry is approximate. Swings are accepted as symmetrical when the pullback terminates inside the Confluence Zone holding the 1.000 symmetry projection; observed point differences between A:B and C:D span between 5% and 17%.

**RULE 073-DUAL AXIS SYMMETRY:** Measure and track symmetry across both axes: price distance (points) and time duration (trading days or bar count). Swings matching closely in both price and bar count produce the highest-probability reversals.

**ENTRY CONDITIONS:**
- RULE 066, RULE 068 satisfied.
- Price reaches the Confluence Zone that holds the symmetry level (RULE 070).

**RULE 074-SYMMETRY REVERSAL ENTRY:** After price hits the zone, buy when price exceeds the prior bar's high (previous day's high on daily charts). Shorts: sell when price undercuts the prior bar's low.

**STOP PLACEMENT:**

**RULE 075-SYMMETRY REVERSAL STOP:** Initial stop just below the Support Confluence Zone (shorts: just above the Resistance Confluence Zone).

**TARGET:**

**RULE 076-SYMMETRY REVERSAL FIRST TARGET:** Label the extreme made into the zone D. The first objective is the 0.500 to 0.618 retracement of C:D; take partial profit there and move the stop to entry, or as near entry as the structure permits (alternative: trail to the previous swing point).

**RULE 077-LOW-TIMEFRAME EXCEPTION:** On lower time frames, when the 0.500-0.618 band offers no meaningful gain over entry, skip the partial exit, only trail the stop higher, and exit the full position at the final target.

**RULE 078-SYMMETRY REVERSAL FINAL TARGET:** Final target: the 1.272 extension of C:D.

**RULE 079-RUNNER OPTION:** Optional: at the 1.272 level, hold part of the position for a larger move. Trade-off: it keeps a winner open but can give back gains.

**RULE 080-PARTIAL EXIT PURPOSE:** The 0.500-0.618 partial exit with a trailed stop is mandatory risk control. Price reverses at that band in a large share of trades; booking there removes the loss outcome while the remainder targets the full move.

**PROBABILITY:** not quantified.

**SKIP SYMMETRY REVERSAL WHEN:**
- ADX(8) has not crossed above 50 (RULE 066).
- DI direction at C disagrees with the trade direction (RULE 068).
- No Confluence Zone contains the symmetry level (RULE 070).
- No trade through the prior bar's high/low after the zone touch (RULE 073).

---

## MODULE 08: THREE-RATIO PULLBACK ZONE

### Definition: Three-Ratio Zone (TRZ)

**RULE:** A TRZ is a three-level retracement zone built from three specific swing points, in which the levels stack in the fixed order 0.500, 0.786, 0.618 (top to bottom for longs).

**CONTEXT:** This specific stack marks high-energy reversal areas in any liquid market. It also coincides with consolidations ready to break, head-and-shoulders pullbacks to the neckline, cup-and-handle and triangle structures. Risk is tight and defined, and the trailing plan lets winners run.

```text
THREE-RATIO ZONE LONG
 C = swing high (lower high each side)
 ---- .50  of A->C ----  ]
 ---- .786 of B->C ----  ]  TRZ (order must be .50 / .786 / .618)
 ---- .618 of A->C ----  ]
 B = nearest prior low below current bar low; A = lower low before B
 ENTRY = trade above prior bar high after TRZ touch ; SL = just below TRZ
 1.272 of C:D = trailing-stop trigger (not a fixed exit)
```

### How to Build the TRZ (longs; shorts reversed)

**RULE 081-POINT C:** Point C is a swing high with a lower high on each side (shorts: a swing low with a higher low on each side).

**RULE 082-POINTS A AND B:** Identify the two previous swing lows below the current bar's low. B = the one closest to C; A = the lower swing low before B (shorts: the two prior swing highs above the current bar's high; B closest to C, A = the higher one).

**RULE 083-TRZ RATIOS:** Calculate the 0.500 and 0.618 retracements of A:C and the 0.786 retracement of B:C. Use no other ratios.

**RULE 084-TRZ ORDER TEST:** The TRZ is valid only when the B:C 0.786 level falls between the A:C 0.500 and 0.618 levels.

**RULE 085-NEAR-MISS TOLERANCE:** Accept a 0.786 level that sits just outside the 0.500 (within a few cents) only when a 1.000 symmetry projection (RULE 027) also lands in the zone.

**RULE 086-SYMMETRY STRENGTHENS:** A 1.000 symmetry projection inside the TRZ strengthens the zone.

**RULE 087-SYMMETRY TOUCH VALIDATION:** When a 1.000 symmetry projection lies just outside the near edge of the TRZ, price reaching that symmetry level satisfies the zone-touch requirement for entry even if price stops pennies short of the 0.500 boundary.

### How to Trade the TRZ

**ENTRY CONDITIONS:**
- Valid TRZ (RULE 083 or RULE 084).
- Price touches the TRZ.

**RULE 088-TRZ ENTRY:** After price touches the TRZ, buy when price exceeds the prior bar's high (shorts: sell when price undercuts the prior bar's low).

**STOP PLACEMENT:**

**RULE 089-TRZ STOP:** Initial stop just below the TRZ (shorts: just above it).

**RULE 090-EXTERIOR SYMMETRY STOP:** When a 1.000 symmetry projection sits just outside the far edge of the TRZ (e.g., below the 0.618 bottom for longs), place the initial stop just beyond the symmetry projection rather than the 0.618 retracement.

**RULE 091-TRZ PENETRATION:** A slight intraday overshoot of the zone keeps it valid. Price gets one test only: a second dip through the zone invalidates it. If an adjacent 1.000 symmetry projection sits just beyond the far edge, price holding above that symmetry level confirms the overshoot is within tolerance.

**TARGET / TRAILING STOP PLAN:**

**RULE 092-POINT D AND TRIGGER LEVEL:** Label the swing made into the TRZ D. Calculate the 1.272 extension of C:D; it is the trigger for the trailing-stop plan, not a fixed exit.

**RULE 093-TRAIL ACTIVATION:** When price reaches the 1.272 extension of C:D:
- Half 1: stop at the higher of the prior bar's low or the entry price (shorts: the lower of the prior bar's high or the entry).
- Half 2: stop at the entry price (breakeven).

**RULE 094-HALF 1 TRAIL:** Each time a new high is made, trail Half 1's stop to the prior bar's low (shorts: each new low, to the prior bar's high). Move it only on new extremes. ⚠ CONFLICT with RULE 094.

**RULE 095-HALF 1 TRAIL VARIANT:** VARIANT B: trail Half 1's stop to the prior bar's high as higher highs are made (longs). VARIANT A (RULE 093) is the bar-low trail; treat VARIANT B as discretionary.

**RULE 096-HALF 2 TRAIL:** After Half 1 is stopped out, trail Half 2's stop to successive higher swing lows (shorts: lower swing highs). This stop is discretionary: give the trade room to absorb volatility, but never let a winner turn into a loss.

**RULE 097-TRAIL PLAN PURPOSE:** The plan books part of the gain early, moves risk to breakeven, and keeps a runner for large moves; worst case (no gap) is a breakeven stop on the remainder.

**RULE 098-BROKEN TRZ:** When a TRZ is broken, expect a momentum move in the direction of the break.

**PROBABILITY:** not quantified.

**SKIP THREE-RATIO ZONE WHEN:**
- The 0.786 of B:C falls outside the 0.500-0.618 band of A:C with no symmetry support (RULE 083, RULE 084).
- Price breaks through the zone a second time (RULE 087).
- No trade through the prior bar's high/low after the touch (RULE 087).

---

## MODULE 09: TWO-LEG PATTERNS (TLP)

### Definition: Two-Leg Pattern

**RULE:** A TLP is two swings in the same direction (A:B and C:D) separated by a smaller opposite pullback (B:C), where C:D carries price beyond B to a new extreme.

**CONTEXT:** Price trades inside a channel. Point D hits the channel edge, and price is expected to retrace a similar distance to the B:C move. The pattern exploits weak hands exiting at D and late entries chasing the move. The three TLP variants differ only in the size relationship between A:B and C:D.

```text
BULLISH TLP (expect UP from D)      BEARISH TLP (expect DOWN from D)
 A                                               D
  \    C                                 B      /
   \  / \                               / \    /
    B    \                             /   C  /
          D  <- channel support       A        <- D at channel resistance
```

**RULE 099-TLP STRUCTURE:** Step 1 = A:B. Pullback = B:C (opposite direction, smaller). Step 2 = C:D, which must trade beyond B.

**RULE 100-TLP DIRECTION:** Bullish TLP: A:B and C:D are down; expect a rise from D. Bearish TLP: A:B and C:D are up; expect a decline from D.

**RULE 101-TLP SIZE CLASS:** Pattern size relative to price and trend sets the trade type. A large TLP against a prior move is a REVERSAL setup. A small TLP inside a major trend is a micro-pullback for a CONTINUATION/MOMENTUM trade. Both occur on all time frames.

**RULE 102-TLP VISUAL TEST:** Bar counts of A:B and C:D need not match, but the pattern must pass a visual test; a grossly mismatched pair (e.g., A:B = 5 bars, C:D = 40 bars) is not a TLP.

### Variant 1: AB=CD TLP

**RULE:** An AB=CD TLP has C:D equal in price size to A:B (A:B = C:D).

```text
AB=CD TLP LONG
 A
  \        C  (C <= .786 of A:B ideal; never beyond A)
   \      / \
    B----/---\---- B must be broken
              D = C - (A:B points) = SYMMETRY LEVEL inside [SUPPORT CONFLUENCE ZONE]
 ENTRY = trade above prior bar high ; SL = below zone
 TARGET = 1.272 to 1.618 ext of A:D
```

**RULE 103-AB=CD STEP 1:** A swing down forms; label it A:B (shorts: a swing up).

**RULE 104-AB=CD POINT C LIMIT:** The B:C pullback ideally does not exceed the 0.786 retracement of A:B; the hard requirement is that C never trades beyond A.

**RULE 105-AB=CD BREAK OF B:** After C forms, price reverses and must trade beyond B (below B for longs, above B for shorts). No break of B = no setup.

**RULE 106-AB=CD SYMMETRY LEVEL:** After B is broken, measure A:B and project it from C (longs: C − A:B; shorts: C + A:B). This is the symmetry level.

**RULE 107-AB=CD ZONE MATCH:** Build a Confluence Zone in the direction of travel (support for longs, resistance for shorts). The setup is valid when the symmetry level sits inside that Confluence Zone.

### How to Trade the AB=CD TLP

**ENTRY CONDITIONS:**
- RULE 102 to RULE 106 met.
- Price reaches the symmetry level inside the Confluence Zone.

**RULE 108-AB=CD ENTRY:** Enter on an entry pattern at the symmetry level; the default trigger is price exceeding the prior bar's high (shorts: below the prior bar's low).

**STOP PLACEMENT:**

**RULE 109-AB=CD STOP:** Initial stop beyond the far side of the Confluence Zone (longs: below; shorts: above).

**TARGET:**

**RULE 110-AB=CD TARGET:** The objective is the 1.272-1.618 extension band of swing A:D.

**RULE 111-INTERMEDIATE ZONE EXIT:** If a Confluence Zone with a significant number of levels sits between entry and the 1.272-1.618 objective, take a portion off at that intermediate zone and trail the stop. Apply this especially in choppy, non-trending markets; in a strong trend, skip it.

**RULE 112-TARGET DOUBLE BOTTOM WARNING:** A double bottom (shorts) or double top (longs) forming at the 1.272 extension is a warning to take profits.

**PROBABILITY:** not quantified.

**SKIP AB=CD TLP WHEN:**
- C trades beyond A (RULE 103).
- Price never trades beyond B (RULE 104).
- The symmetry level is outside any Confluence Zone (RULE 106).
- Step durations fail the visual test (RULE 101).

### Variant 2: Gartley TLP

**RULE:** A Gartley TLP is a TLP anchored to an extra reference point X, where B and D are gauged as Fibonacci retracements of X:A. It is defined by ratios, not symmetry; A:B and C:D need not be equal.

```text
BULLISH GARTLEY TLP
          A  (highest high; break above A before D = VOID)
         / \      C (<= A; .382-.786 of A:B)
        /   \    / \
       /     B  /   \     B = .382-.618 of X:A
      /       \/     \
     /                D   D = .618-.786 of X:A  (+ 1.272-1.618 of B:C = stronger)
    X  (lowest low; break below X = VOID)
 ENTRY = trade above prior bar high ; SL = below zone
```

**RULE 113-GARTLEY POINT X:** X is the lowest low of the entire pattern (bearish: the highest high). Price beyond X voids the pattern.

**RULE 114-GARTLEY POINT A:** The rally from X ends at swing high A, the highest high of the pattern (bearish: A = the lowest low). Price beyond A before completion voids the pattern.

**RULE 115-GARTLEY POINT B:** B retraces X:A. VARIANT A: B falls between the 0.382 and 0.618 retracement of X:A. VARIANT B (stricter): B falls between the 0.382 and 0.500 retracement. ⚠ CONFLICT: treat 0.382-0.500 as the preferred band and 0.500-0.618 as acceptable.

**RULE 116-GARTLEY POINT C:** The B:C pullback ideally reaches between the 0.382 and 0.786 retracement of A:B. Hard limit: C never exceeds A. Bearish: C does not exceed the 0.786 of A:B and reaches at least its 0.382.

**RULE 117-GARTLEY COMPLETION:** After C, price must trade beyond B into the 0.618 to 0.786 retracement of X:A. Arrival in that band completes the pattern as point D.

**RULE 118-GARTLEY D CONFLUENCE:** D is stronger when it also equals a 1.272 or 1.618 extension of B:C.

**RULE 119-GARTLEY CONFLUENCE ZONE REQUIRED:** Trade only when at least 3 Fibonacci levels form a Confluence Zone around the completion level.

**RULE 120-GARTLEY DEPTH:** The pattern is officially complete at the 0.618 of X:A and stays valid down to the 0.786. On higher time frames and larger patterns, the 0.618-0.786 gap is wider, so entering at 0.618 carries more point risk; waiting for a trigger lets price move deeper into the zone and cuts risk.

### How to Trade the Gartley TLP

**ENTRY CONDITIONS:**
- RULE 112 to RULE 118 met.
- An entry pattern forms in the completion Confluence Zone.

**RULE 121-GARTLEY ENTRY:** Default trigger: buy when price exceeds the prior bar's high after completion (bearish: sell when price undercuts the prior bar's low).

**STOP PLACEMENT:**

**RULE 122-GARTLEY STOP:** Initial stop just beyond the completion Confluence Zone: below the Support Confluence Zone for longs, above the Resistance Confluence Zone for shorts.

**TARGET:**

**RULE 123-GARTLEY FIRST TARGET:** The first objective is the first major opposing Confluence Zone, preferably the one that contains the B:C symmetry level. After price touches that zone, exit half when price undercuts the prior bar's low (shorts: above the prior bar's high); then move the stop to breakeven.

**RULE 124-GARTLEY FINAL TARGET:** VARIANT A: the final target is the 1.272 extension of A:D. VARIANT B: the final objective is the 1.272 to 1.618 extension band of A:D. ⚠ CONFLICT: after the 1.272 is touched, exit the remainder when price undercuts the prior bar's low (shorts: above the prior bar's high); this exit satisfies both variants.

**RULE 125-GARTLEY TIMEFRAMES:** The pattern works from 5-minute to monthly charts. Choose the time frame by the point risk the money-management plan allows per trade.

**RULE 126-OWN THE STOP METHOD:** Use the stop method only if it fits the trader's style; otherwise adopt a defined alternative stop program and apply it consistently.

**PROBABILITY:** not quantified.

**SKIP GARTLEY TLP WHEN:**
- Price breaks X, or breaks A before D (RULE 112, RULE 113).
- B lies outside 0.382-0.618 of X:A (RULE 114).
- C exceeds A (RULE 115).
- D does not reach the 0.618-0.786 band of X:A (RULE 116).
- Fewer than 3 levels form a zone at completion (RULE 118).

### Variant 3: Butterfly TLP

**RULE:** A Butterfly TLP is a Gartley-type TLP whose point D completes BEYOND X, inside the 1.272-1.618 extension band of X:A.

**CONTEXT:** Connecting X-A, X-B, A-B, B-C, B-D, C-D draws a butterfly whose right wing reaches past the left (lower for bullish, higher for bearish). D marks major turning points on the higher time frame. Within a larger trend, a small Butterfly is a continuation setup (RULE 100).

```text
BULLISH BUTTERFLY TLP
        A  (highest high)
       / \     C (< A; at .382/.50/.618/.786 of A:B)
      /   \   / \
     /     B /   \    B = .382-.786 of X:A, never below X
    X           \     X = 2nd-lowest point (anchor)
                 D    D = 1.272-1.618 ext of X:A, must be BELOW X
 ENTRY = trade above prior bar high ; SL = below zone
```

**RULE 127-BUTTERFLY POINT X:** X is the pattern start and the second-lowest point of the pattern (bearish: the second-highest); it anchors the completion calculation.

**RULE 128-BUTTERFLY POINT A:** A is the highest high of the pattern (bearish: the lowest low).

**RULE 129-BUTTERFLY POINT B:** B ideally falls between the 0.382 and 0.786 retracement of X:A. Hard rule: B never goes beyond X. B can go deeper than in a Gartley.

**RULE 130-BUTTERFLY POINT C:** Hard rule: C stays below A (bearish: above A). C ideally lands on the 0.382, 0.500, 0.618, or 0.786 retracement of A:B.

**RULE 131-BUTTERFLY COMPLETION:** After C, once price trades beyond B, calculate the 1.272-1.618 extension band of X:A. That band is the completion zone, and D must lie beyond X.

**RULE 132-BUTTERFLY STEP SIZE:** C:D is longer than A:B in most cases. When A:B equals C:D, the setup is an AB=CD TLP and a Butterfly TLP at the same time.

**RULE 133-BUTTERFLY VISUAL TEST:** The connected swings must resemble a butterfly with the right wing extending past the left; mild distortion from uneven swing timing is acceptable.

### How to Trade the Butterfly TLP

**ENTRY CONDITIONS:**
- RULE 126 to RULE 132 met.
- Price reaches the completion zone inside a Confluence Zone of at least 3 levels (RULE 118).

**RULE 134-BUTTERFLY TRIGGER REQUIRED:** Do not enter on the bare touch of the 1.272 extension. On daily and higher charts the pattern forms against a strong trend, so wait for a trigger. Default trigger: buy when price exceeds the prior bar's high (shorts: below the prior bar's low).

**RULE 135-TOUCH ENTRY VARIANT:** VARIANT B: enter at the 1.272 touch for less point risk. It carries no structural confirmation of reversal and a higher stop-out rate; treat it as discretionary. A stop is mandatory under any entry method.

**STOP PLACEMENT:**

**RULE 136-BUTTERFLY STOP:** Initial stop just beyond the completion Confluence Zone (longs: below the Support Confluence Zone; shorts: above the Resistance Confluence Zone).

**TARGET:**

**RULE 137-BUTTERFLY OPPOSING ZONE:** Once D is confirmed, immediately calculate the opposing Confluence Zone levels that mark the next decision points.

**RULE 138-BUTTERFLY FIRST TARGET:** The first objective is the 0.618 to 0.786 retracement of C:D; exit half there and move the stop to reduce or remove risk. When the move to that level came very fast and small, optionally tighten the stop instead of exiting.

**RULE 139-BUTTERFLY FINAL TARGET:** VARIANT A: the final target is the 1.272 extension of A:D. VARIANT B: the final objective is the 1.272 to 1.618 extension band of A:D. ⚠ CONFLICT: treat the band as the exit zone, with the 1.272 as its near edge.

**RULE 140-BUTTERFLY RUNNER:** Optional: once the final zone is hit, trail the stop to the prior bar's extreme (shorts: prior bar's high) on each new extreme to ride a larger move.

**RULE 141-TWO-STAGE EXIT PRINCIPLE:** For all TLPs, exit half at the first ("base hit") objective and trail the rest, ideally to breakeven. Most trades are base hits; the trailed remainder captures the rare large move at little or no added risk.

**RULE 142-HTF CONTEXT CHECK:** When a higher-time-frame chart shows a major peak or trough forming, drill down to the daily chart to look for a Butterfly TLP against a Confluence Zone at that point.

**PROBABILITY:** not quantified.

**SKIP BUTTERFLY TLP WHEN:**
- B goes beyond X (RULE 128).
- C goes beyond A (RULE 129).
- D does not go beyond X or misses the 1.272-1.618 band of X:A (RULE 130).
- No trigger forms after completion (RULE 133).
- Fewer than 3 levels form a zone at completion (RULE 118).

---

## MODULE 10: 200-DAY AVERAGE FAKE-OUT

### Definition: 200-SMA Fake-Out

**RULE:** A 200-SMA Fake-Out trade fades a crowd reaction to a 200-day SMA cross: a TLP completes just beyond the 200-day SMA into a Confluence Zone, then reverses back through the average.

**CONTEXT:** Many participants buy above the 200-day SMA and sell below it. When price pokes through the average, stops trigger and new positions open on the wrong side. Once the TLP reverses price back across the average, those traders exit, adding fuel to the move.

```text
BEARISH 200-SMA FAKE-OUT
 [RESISTANCE CONFLUENCE ZONE]   D  <- TLP completes ABOVE 200 SMA
 ---------- 200-day SMA ---------  (crowd buys the cross-up)
       B         C                 bearish TLP A-B-C-D
 A
 ENTRY = trade below prior bar low ; SL = just above zone
 crowd forced out as price falls back below SMA => fuel
```

**RULE 143-FAKE-OUT PATTERN:** A Bearish TLP (AB=CD, Gartley, or Butterfly) completes; longs: a Bullish TLP.

**RULE 144-FAKE-OUT CONFLUENCE ZONE:** Point D hits a Confluence Zone of at least 3 Fibonacci levels (resistance for shorts, support for longs).

**RULE 145-FAKE-OUT SMA CONDITION:** Point D completes ABOVE the 200-day SMA for shorts, BELOW it for longs.

**RULE 146-FAKE-OUT TREND CONTEXT:** Prefer setups inside an established trend (2-3 higher highs and higher lows before the poke through the SMA, or the mirror) over choppy markets. Mechanical filter: 13-period ADX above 20 and rising.

### How to Trade 200-SMA Fake-Out

**ENTRY CONDITIONS:**
- RULE 142 to RULE 144 met.
- An entry trigger forms.

**RULE 147-FAKE-OUT ENTRY:** Default trigger: short when price undercuts the prior bar's low (longs: above the prior bar's high), or use an entry pattern (RULE 187).

**STOP PLACEMENT:**

**RULE 148-FAKE-OUT STOP:** Initial stop just above the Resistance Confluence Zone (longs: just below the Support Confluence Zone).

**RULE 149-FAKE-OUT WIDE ZONE SIZING:** When the stop-to-entry distance is large (e.g., about 15% of price), reduce position size to keep risk within money-management limits.

**TARGET:**

**RULE 150-FAKE-OUT FIRST TARGET:** Take profit on half at the 0.500-0.618 retracement of A:D, then trail the stop to a recent swing point (swing high for shorts, swing low for longs); breakeven is the ideal minimum.

**RULE 151-FAKE-OUT FINAL TARGET:** The second objective is the 1.272 extension of A:D. Do not exit at the touch; trail the stop to the prior bar's extreme (shorts: prior bar's high; longs: prior bar's low) and keep trailing on each new extreme until stopped out.

**RULE 152-FAKE-OUT TIMEFRAME:** Trade it on daily charts only, with the 200-day SMA. Weekly equivalent: 40-period SMA. No intraday version is defined.

**RULE 153-FAKE-OUT SCAN:** Scan for liquid stocks (volume) trading near their 200-day SMA, build a watch list, and wait for a TLP to form.

**PROBABILITY:** not quantified.

**SKIP 200-SMA FAKE-OUT WHEN:**
- No completed TLP (RULE 142).
- Fewer than 3 levels at D (RULE 143).
- D does not finish on the far side of the 200-day SMA (RULE 144).
- The market is choppy with no trend structure, or the 13-ADX is below 20 or falling (RULE 145).
- Applied to an intraday chart (RULE 151).

---

## MODULE 11: EXTENSION TRAP REVERSAL

### Definition: Extension Trap

**RULE:** A Extension Trap is a failed break of a swing extreme: price breaks the 0.786 retracement of the prior swing, runs to that swing's 1.272-1.618 extension (a slightly lower low or higher high), then reverses.

**CONTEXT:** Price returning to a prior swing extreme faces a decision at the 0.786 retracement. A break of it runs quickly to the 1.272-1.618 extensions. The new extreme stops out early reversal traders and pulls in late trend followers. That flow is the last exhaustion push before the real turn. It is a double top/bottom with a defined Fibonacci completion point for the second peak or trough.

```text
EXTENSION TRAP LONG
      B  (swing high after A)
     / \
 A  /   \ .786 of A:B -- break => fast run (momentum short optional)
  \/     \
          C = 1.272-1.618 ext of A:B (slightly lower low than A)
 ENTRY = trade above prior bar high ; SL = below zone / 1.618
 TARGETS = .50-.618 of B:C (half), then 1.272 ext of B:C + trail
```

**RULE 154-TRAP POINTS:** Longs: identify swing low A, then the rally to swing high B. Shorts: swing high A, then the decline to swing low B.

**RULE 155-TRAP 786 DECISION:** As price returns toward A, the 0.786 retracement of A:B is the decision level. A break of it projects a fast move to the 1.272-1.618 extension of A:B.

**RULE 156-TRAP MOMENTUM OPTION:** Optional short-term momentum trade: trade the break of the 0.786 in its direction, targeting the 1.272-1.618 extension of A:B. This is secondary to the reversal trade.

**RULE 157-TRAP COMPLETION:** Price reaching the 1.272-1.618 extension band of A:B completes the pattern; label that extreme C.

**RULE 158-TRAP ZONE QUALITY:** Prefer completion zones holding multiple 1.272/1.618 extensions from several swings. With 4+ extension levels in a tight range, the probability of at least a short-term tradable reversal is extremely high (no numeric value defined).

### How to Trade the Extension Trap

**ENTRY CONDITIONS:**
- RULE 153 to RULE 156 met.
- A trigger bar forms after the extension zone is hit.

**RULE 159-TRAP ENTRY:** Go long on the first bar that trades above the prior bar's high after price hits the extension band (shorts: the first bar below the prior bar's low).

**STOP PLACEMENT:**

**RULE 160-TRAP STOP:** Initial stop just beyond the Support Confluence Zone / 1.618 extension of A:B (shorts: just above the Resistance Confluence Zone / 1.618).

**RULE 161-TRAP TIGHT STOP:** If the stop beyond the 1.618 is too far, place it just beyond the extreme (C) made into the extension area before the trigger.

**TARGET:**

**RULE 162-TRAP FIRST TARGET:** Exit half at the 0.500-0.618 retracement of B:C. On intraday charts, optionally skip this partial exit and hold for the 1.272.

**RULE 163-TRAP FINAL TARGET:** Second target: B:C's 1.272 extension. When price reaches it, trail the stop on the remainder to the prior bar's low (shorts: prior bar's high) on each new extreme.

**PROBABILITY:** not quantified.

**SKIP EXTENSION TRAP WHEN:**
- Price does not break the 0.786 of A:B (RULE 154).
- Price stalls short of the 1.272 extension of A:B (RULE 156).
- No trigger bar follows the extension touch (RULE 158).

---

## MODULE 12: ZONE-GAP MOMENTUM BREAKOUTS

### Definition: Zone Gap

**RULE:** An Zone Gap is a tradable price gap between two Confluence Zones that contains no Fibonacci levels. When price breaks through the near zone, it moves through the empty gap to the far zone.

**CONTEXT:** These are momentum trades: buy the violation of a Resistance Confluence Zone, sell the violation of a Support Confluence Zone. An ADX drop through the 20 line signals the shift that makes the break likely. A reversal variant (RGBs) trades a trend that is turning. A continuation variant (CGBs) trades a resting trend that resumes.

**RULE 164-ADX READING SCALE:** Read the ADX as follows:

| ADX | State |
|---|---|
| 0-15 | No trend present |
| 16-20 | Emerging trend, strength building |
| 21-40 | Established, fully powered trend |
| > 40 | Overextended strength; ADX turn-down expected |

**RULE 165-ZONE GAP ADX SETTING:** Use a 14-period ADX with a reference level of 20.

**RULE 166-CLEAR THE GAP:** Delete any 1 or 2 isolated levels sitting between two Confluence Zones; fewer than 3 levels never form a zone (RULE 033), so the gap counts as clear.

**RULE 167-GAP TIMEFRAMES:** Trade Zone Gaps on 60-minute to weekly charts; the daily chart is the primary frame. Below 60 minutes, the gaps are too small to trade.

**RULE 168-PRIOR TESTS STRENGTHEN:** One or more prior bars testing the near edge of Confluence Zone #1 before the breaking bar make the break more explosive.

### Variant 1: Reversal Gap Breakout (RGB)

```text
RGB LONG
 [RESISTANCE CONFLUENCE ZONE #2]  <- TARGET (near edge)
        (empty gap = ZONE GAP, no levels)
 [RESISTANCE CONFLUENCE ZONE #1]  <- break of its HIGHEST level as ADX(14) < 20 => ENTRY
  \  /\  /
   \/  \/   downtrend low made with ADX(14) > 20 => build resistance levels here
 SL = below zone #1 / breaking bar low / prior bar low
```

**RULE 169-RGB ANCHOR:** Longs: price has been trending down and makes a swing low while the 14-ADX is above 20. Calculate resistance levels from that low with all four studies. Shorts: a swing high in an uptrend with ADX above 20; calculate support levels.

**RULE 170-RGB TWO ZONES:** Identify two Confluence Zones in the trade direction: Confluence Zone #1 nearest price, Confluence Zone #2 beyond it, with a tradable Zone Gap between them (RULE 165).

**RULE 171-RGB TRIGGER:** Price pushes through the far edge of Confluence Zone #1 (longs: above its highest level; shorts: below its lowest) while the 14-ADX crosses below 20.

### Variant 2: Continuation Gap Breakout (CGB)

```text
CGB LONG (trend is UP)
 [RESISTANCE CONFLUENCE ZONE #2]  <- TARGET
        ZONE GAP
 [RESISTANCE CONFLUENCE ZONE #1]  <- break as ADX(14) < 20 => ENTRY
   (1) high made with ADX(14) > 20 -> do NOT build support
   (2) wait for pullback low, then build RESISTANCE levels from (2)
 SL = below zone #1 / breaking bar low / prior bar low
```

**RULE 172-CGB ANCHOR:** Longs: price trends up and makes a swing high while the 14-ADX is above 20. Do not build support levels; wait for a pullback swing low (point 2) and a renewed rally, then calculate resistance levels from point 2. Shorts: in a downtrend, after a swing low with ADX above 20, wait for a bounce high, then calculate support levels from it.

**RULE 173-CGB TWO ZONES:** Identify Confluence Zone #1 (nearest) and Confluence Zone #2 in the trend direction with a tradable Zone Gap between them (RULE 165).

**RULE 174-CGB TRIGGER:** Price pushes through the far edge of Confluence Zone #1 after the 14-ADX has dropped below 20, i.e., an above/below-20 shakeout inside a resting trend.

**RULE 175-RGB VS CGB:** The prior path of price decides the variant. Coming out of an opposite trend into Confluence Zone #1 = RGB; already trending in the trade direction = CGB.

### How to Trade Zone Gaps (both variants)

**ENTRY METHODS:**
1. Aggressive: enter immediately on the violation of Confluence Zone #1's far edge.
2. Conservative: wait for a small pullback that retests the broken Confluence Zone #1, then enter in the breakout direction.

**RULE 176-GAP STOP OPTIONS:** Choose one initial stop (longs; reverse for shorts):
- a) below Confluence Zone #1 (shorts: above its highest level);
- b) below the low of the bar that violates Confluence Zone #1;
- c) below the prior bar's low.

**RULE 177-STOP VS GAP SIZE:** Choose the stop by comparing its risk to the Zone Gap's profit potential. Do not take trades where risk exceeds the gap (e.g., 3 points of risk for 1 point of gap). Tighten the stop (e.g., to the current bar's low) or cut size.

**RULE 178-POSITION SIZE FORMULA:**
- Input: capital allowed at risk per trade; points of risk (entry − stop).
- Calculation: shares/contracts = per-trade risk amount ÷ points of risk.
- Output: position size.

**TARGET:**

**RULE 179-GAP TARGET:** The objective is the near edge of Confluence Zone #2.

**RULE 180-GAP HOLD OPTION:** Optional, mainly for CGBs (with-trend): take half off at Confluence Zone #2, move the stop to breakeven on the rest, and hold it for further movement.

**RULE 181-GAP STALL EXIT:** After the breakout, if price moves sideways for more than 2-3 bars short of the target, consider exiting.

**PROBABILITY:** not quantified.

**SKIP ZONE GAPS WHEN:**
- No clear gap free of levels between the two zones (RULE 165, RULE 169).
- The 14-ADX does not cross below 20 at the break (RULE 170, RULE 173).
- Stop risk exceeds the gap's profit potential (RULE 176).
- The chart is below 60-minute or above weekly (RULE 166).

---

## MODULE 13: ENTRY TRIGGERS AND TIMEFRAME DRILL-DOWN

### Definition: Entry Trigger

**RULE:** An entry trigger is price action that confirms a tradable move has started at a setup's zone; a setup only shows a possible move, and a trade is entered only after a trigger completes.

**CONTEXT:** Entering on the setup alone is the most common execution error. The preferred method finds the trigger on a lower time frame than the setup, which gives confirmation with a tighter structural reference.

**RULE 182-CONFIRM THEN ENTER:** Never enter because a setup indicates a possible move; enter only after a trigger confirms it.

**RULE 183-LOWER TIMEFRAME TRIGGER:** After a setup forms, look for its trigger on a lower time frame per this table:

| Setup time frame | Trigger time frames |
|---|---|
| Weekly | Daily and 60-minute |
| Daily | 60-minute and 30-minute |
| 30-minute | 13-minute and 8-minute |
| 13-minute | 5-minute |

**RULE 184-SAME TIMEFRAME OPTION:** A candlestick trigger on the setup's own time frame is also valid.

**RULE 185-DRILL DEPTH LIMIT:** Drill down only 1-2 time frames below the setup; triggers taken far below it (e.g., 5-minute for a weekly setup) cause frequent whipsaws.

**RULE 186-HTF AWARENESS:** Always check at least one time frame above the setup; higher time frames carry more weight. If it is setting up in the opposite direction, stop looking for triggers until that conflict clears.

**RULE 187-DEFAULT SIMPLE TRIGGER:** The simplest trigger is price exceeding the prior bar's high (longs) or below the prior bar's low (shorts) after the setup completes.

### Trigger Catalog

**RULE 188-TRIGGER FAMILIES:** Valid triggers are:
1. Candlestick patterns (RULE 185 to RULE 200).
2. Two-leg patterns on the lower time frame: AB=CD, Gartley, Butterfly TLP (Module 09).
3. Extension Trap on the lower time frame (Module 11).
4. Classic patterns: double top, double bottom, head and shoulders, reverse head and shoulders.

### Candlestick Definitions

A white body closes above its open; a black (dark) body closes below its open. Tails (wicks, shadows) mark the period's high and low.

**RULE 189-FOLLOW THROUGH BARS:** When a reversal candlestick (such as a Doji or Hanging Man) forms at a zone on a lower time frame, entry confirmation requires two consecutive follow-through bars closing in the trade direction before entering.

**RULE 190-DOJI:** Open equals close (no body). Longer tails give it more significance. It marks indecision; after it completes, reversal likelihood is high.

**RULE 191-BEARISH ENGULFING:** A small white body followed by a larger black body that contains it. Top reversal; it starts a selloff.

**RULE 192-BULLISH ENGULFING:** A small black body followed by a larger white body that contains it. Bottom reversal; it starts a rally.

**RULE 193-EVENING STAR:** A large white body, then a small body gapping above it, then a black body closing 50%+ into the white body. Top reversal.

**RULE 194-MORNING STAR:** A large black body, then a small body gapping below it, then a white body closing 50%+ into the black body. Bottom reversal.

**RULE 195-HANGING MAN:** Small body near the high, long lower tail, little or no upper tail. Bearish when it appears in an uptrend.

**RULE 196-SHOOTING STAR:** Small body at or near the low, long upper tail, little or no lower tail. Bearish when it appears in an uptrend.

**RULE 197-MORNING DOJI STAR:** A large black body, then a doji gapping below it, then a white body closing at least 50% into the black body. Bottom reversal.

**RULE 198-EVENING DOJI STAR:** A large white body, then a doji gapping above it, then a black body closing at least 50% into the white body. Top reversal.

**RULE 199-TWEEZER BOTTOM:** Two candles with matching lows; ideally a black candle closing at its low, then a white candle opening at that low. Marks at least a short-term low.

**RULE 200-TWEEZER TOP:** Two or more candles with matching highs; ideally a white candle closing at or near its high, then a candle opening at that high with an upper tail and a body of either color below. Marks at least a short-term top.

**RULE 201-THREE METHODS:** Bullish 3 Method: a long white body, a few small bodies held mostly inside its range, then another long white body; bullish continuation. Bearish 3 Method: the mirror with black bodies; bearish continuation.

### How to Apply Triggers

**RULE 202-TRIGGER PROCEDURE:**
1. Identify the setup and its Confluence Zone on the setup time frame.
2. Drill down 1-2 time frames (RULE 182) around the completion zone.
3. Wait for a candlestick or pattern trigger to complete there.
4. Enter on completion; apply the setup's own stop and targets.

**RULE 203-TRIGGER STACKING:** Two triggers completing together (e.g., a lower-timeframe Extension Trap plus a tweezer bottom and bullish engulfing at its 1.272 extension) give stronger confirmation; either one alone is still a valid trigger.

**RULE 204-AGAINST-TREND CONFIRMATION:** When the setup reverses a fast, strong move, always require a lower-timeframe trigger before entering against that move.

**SKIP ENTRY WHEN:**
- No trigger has completed (RULE 181).
- The trigger is more than 2 time frames below the setup (RULE 184).
- The next higher time frame is setting up in the opposite direction (RULE 185).

---

## MODULE 14: EXECUTION DISCIPLINE AND PORTFOLIO RISK

### Definition: Execution Standard

**RULE:** Performance is measured by flawless execution of every prescribed step and management rule on every trade, never by win rate.

**CONTEXT:** No method is 100% accurate. Traders who chase a perfect win rate change rules after a short losing streak, and losses compound. Consistent results come from strategy + execution + money management + psychology applied together.

**RULE 205-EXECUTION OVER OUTCOME:** Grade each trade on whether every setup, entry, stop, and exit rule was followed exactly; a rule-compliant loss is a correct trade.

**RULE 206-NO RULE CHANGES ON STREAKS:** A run of 2-3 losses is not grounds to change rules or switch systems; keep executing the defined process unchanged.

**RULE 207-EMOTION-PROOF FRAMEWORK:** Execute from pre-defined written rules and checklists so emotional state cannot alter entry, stop, or exit decisions.

**RULE 208-SUCCESS FORMULA:** Trading success = Strategy + Execution + Money Management + Psychology; none is optional.

### Nightly Risk Review

**RULE 209-NIGHTLY REVIEW:** Before every session, review all open and planned positions against RULE 209 to RULE 215.

**RULE 210-DIRECTIONAL EXPOSURE:** Count long vs short positions; correct any overweighting relative to the overall market's position.

**RULE 211-SECTOR EXPOSURE:** Do not concentrate positions in one sector (e.g., 3 open longs all in one industry group is excess concentration).

**RULE 212-RISK PER TRADE:** Risk a maximum of 2-3% of account equity per trade; set a lower percentage if it suits the account better.

**RULE 213-NEWS EXPOSURE:** Avoid holding trades through scheduled news (e.g., earnings releases) that can move price unpredictably.

**RULE 214-PATTERN EXPOSURE:** When the broad market and many individual stocks form the same pattern at once, treat it as ONE trade: take a single position, preferably through an index proxy (ETF or index futures). If the index pattern fails, all the related patterns fail with it.

**RULE 215-TIMEFRAME DIVERSIFICATION:** Do not base all trades on one time frame; hold a mix of longer- and shorter-term trades (30-minute to monthly).

**RULE 216-TOTAL PORTFOLIO RISK:** If every open position were stopped out at once, the total loss must not exceed 20-25% of the account; reduce exposure if it does.

**RULE 217-AGGRESSION INSIDE LIMITS:** Once risk is identified and the limits in RULE 209 to RULE 215 are in place, trade setups decisively and in full size within those limits.

**SKIP ANY NEW TRADE WHEN:**
- It would push risk per trade above 2-3% (RULE 211).
- It adds another position in an already concentrated direction, sector, or market-wide pattern (RULE 209, RULE 210, RULE 213).
- A scheduled news event falls inside the expected holding period (RULE 212).
- Total open risk would exceed 20-25% of the account (RULE 215).

---

## PRE-TRADE CHECKLISTS

### Pre-Trade Checklist: Confluence Zone Construction (all setups)
- [ ] Current swing point confirmed by a lower high / higher low on each side (RULE 014)
- [ ] Only valid swings used: right-most in consolidations, none invalidated by a further extreme (RULE 008, RULE 009, RULE 010, RULE 011)
- [ ] Lookback ≤ 8 swings, otherwise move up a time frame (RULE 015)
- [ ] Studies run in order: retracements, extensions, projections, expansions last (RULE 034, RULE 031)
- [ ] Violated and isolated levels deleted (RULE 035, RULE 037)
- [ ] Zone holds 3+ levels (RULE 033)
- [ ] Zone width ≤ 10% of price (RULE 038)
- [ ] No trade on the zone alone; trigger still required (RULE 039)

### Pre-Trade Checklist: Trend Pullback
- [ ] 2+ higher highs and 1+ higher low (shorts mirrored) (RULE 048)
- [ ] Bar reaches the near edge of the Confluence Zone (RULE 050)
- [ ] 14-ADX ≥ 20 and rising (RULE 059)
- [ ] Trigger formed (RULE 046)
- [ ] Stop just beyond the zone; full-zone risk fits limits or size reduced (RULE 051, RULE 052)
- [ ] Targets set: 0.500-0.618 of the swing into the zone for half, 1.272 extension final (RULE 053, RULE 054, RULE 056)
- [ ] Plan to scratch if price hovers in the zone (RULE 058)

### Pre-Trade Checklist: Symmetry Reversal
- [ ] 8-ADX crossed above 50 (RULE 066)
- [ ] Point C formed after the cross (RULE 067)
- [ ] 21-DI agrees with trade direction at C (RULE 068)
- [ ] Prior countertrend A:B measured in points and bars (RULE 069)
- [ ] Symmetry level C ± A:B lies inside the Confluence Zone (RULE 069, RULE 070)
- [ ] Entry on trade through prior bar's high/low after zone touch (RULE 073)
- [ ] Stop beyond zone; targets 0.500-0.618 and 1.272 of C:D (RULE 074, RULE 075, RULE 077)

### Pre-Trade Checklist: Three-Ratio Zone
- [ ] C is a confirmed swing; A and B are the two prior swings beyond the current bar (RULE 080, RULE 081)
- [ ] B:C 0.786 sits between A:C 0.500 and 0.618 (or near-miss with symmetry) (RULE 083, RULE 084)
- [ ] Price touched the TRZ; first test only (RULE 087, RULE 087)
- [ ] Entry on trade through prior bar's high/low (RULE 087)
- [ ] Stop just beyond the TRZ (RULE 086)
- [ ] 1.272 of C:D marked as trailing trigger; two-half trailing plan ready (RULE 091, RULE 092, RULE 093, RULE 095)

### Pre-Trade Checklist: AB=CD TLP
- [ ] A:B formed; C stays inside A, ideally ≤ 0.786 of A:B (RULE 102, RULE 103)
- [ ] Price traded beyond B (RULE 104)
- [ ] Symmetry level C ± A:B inside a Confluence Zone (RULE 105, RULE 106)
- [ ] Step durations pass the visual test (RULE 101)
- [ ] Trigger; stop beyond zone; target 1.272-1.618 of A:D (RULE 107, RULE 108, RULE 109)
- [ ] Intermediate opposing zone noted for a partial exit (RULE 110)

### Pre-Trade Checklist: Gartley TLP
- [ ] X and A hold as the pattern extremes (RULE 112, RULE 113)
- [ ] B within 0.382-0.618 of X:A (RULE 114)
- [ ] C within 0.382-0.786 of A:B, never beyond A (RULE 115)
- [ ] D reached 0.618-0.786 of X:A after breaking B (RULE 116)
- [ ] 3+ levels form a Confluence Zone at D (RULE 118)
- [ ] Trigger; stop beyond zone (RULE 120, RULE 121)
- [ ] First target: first opposing zone, half off, BE stop; final 1.272 of A:D (RULE 122, RULE 123)

### Pre-Trade Checklist: Butterfly TLP
- [ ] X second extreme, A pattern extreme (RULE 126, RULE 127)
- [ ] B within 0.382-0.786 of X:A, never beyond X (RULE 128)
- [ ] C never beyond A (RULE 129)
- [ ] D beyond X at 1.272-1.618 of X:A (RULE 130)
- [ ] 3+ levels form a Confluence Zone at D (RULE 118)
- [ ] Trigger formed; no bare-touch entry by default (RULE 133)
- [ ] Stop beyond zone; first target 0.618-0.786 of C:D; final 1.272-1.618 of A:D (RULE 135, RULE 137, RULE 138)

### Pre-Trade Checklist: 200-SMA Fake-Out
- [ ] Daily chart (or 40-SMA weekly) (RULE 151)
- [ ] Completed TLP of any variant (RULE 142)
- [ ] D in a Confluence Zone of 3+ levels (RULE 143)
- [ ] D finished beyond the 200-day SMA (above for shorts, below for longs) (RULE 144)
- [ ] Trend context present; 13-ADX > 20 and rising (RULE 145)
- [ ] Trigger; stop beyond zone; size cut if the stop is wide (RULE 146, RULE 147, RULE 148)
- [ ] Targets: half at 0.500-0.618 of A:D, trail from 1.272 of A:D (RULE 149, RULE 150)

### Pre-Trade Checklist: Extension Trap
- [ ] A and B swings identified (RULE 153)
- [ ] 0.786 of A:B broken (RULE 154)
- [ ] Price reached 1.272-1.618 of A:B (point C) (RULE 156)
- [ ] Multiple extensions cluster at C (4+ is strongest) (RULE 157)
- [ ] First bar through prior bar's high/low after the touch (RULE 158)
- [ ] Stop beyond 1.618/zone or beyond C (RULE 159, RULE 160)
- [ ] Targets: half at 0.500-0.618 of B:C, trail from 1.272 of B:C (RULE 161, RULE 162)

### Pre-Trade Checklist: Zone Gaps (RGB / CGB)
- [ ] 60-minute to weekly chart (RULE 166)
- [ ] Anchor swing made with 14-ADX > 20 (RGB: from the extreme; CGB: from the pullback point) (RULE 168, RULE 171)
- [ ] Two zones with a clear level-free gap (RULE 165, RULE 169, RULE 172)
- [ ] Break of Confluence Zone #1's far edge as 14-ADX is below 20 (RULE 170, RULE 173)
- [ ] Stop chosen so risk ≤ gap size; size from formula (RULE 175, RULE 176, RULE 177)
- [ ] Target: near edge of Confluence Zone #2 (RULE 178)

### Pre-Trade Checklist: Entry Trigger
- [ ] Setup complete and zone touched (RULE 181)
- [ ] Trigger sought 1-2 time frames lower per the table (RULE 182, RULE 184)
- [ ] Next higher time frame not opposing (RULE 185)
- [ ] Trigger completed: candlestick, lower-TF TLP, Extension Trap, or classic pattern (RULE 187, RULE 201)

### Risk & Trade Management Checklist
- [ ] Risk ≤ 2-3% of equity (RULE 211)
- [ ] Position size = risk amount ÷ points of risk (RULE 177)
- [ ] Wide-zone risk handled by waiting deeper or cutting size (RULE 052, RULE 148)
- [ ] Direction, sector, and same-pattern concentration checked (RULE 209, RULE 210, RULE 213)
- [ ] No scheduled news during the hold (RULE 212)
- [ ] Total open risk ≤ 20-25% (RULE 215)
- [ ] Half exits at the first target, remainder trailed; breakeven stop not on round numbers or too close to price (RULE 140, RULE 057)
- [ ] Rules followed unchanged regardless of recent results (RULE 204, RULE 205)

---

## MASTER DECISION TREE

```
START: Is the current swing point confirmed? (RULE 014)
│
├─ NO → No Trade (wait for confirmation)
└─ YES → Build zones with all four studies (RULE 034)
   │
   ├─ Is there a Confluence Zone of 3+ levels, width ≤ 10% of price? (RULE 033, RULE 038)
   │  ├─ NO → No Trade
   │  └─ YES → Classify the structure delivering price into the zone
   │
   ├─ STRUCTURE 1: Trend pullback (2+ HH and 1+ HL, or mirror) (RULE 048)
   │  ├─ 8-ADX > 50, DI aligned at C, symmetry level in zone?
   │  │  └─ YES → SYMMETRY REVERSAL: entry RULE 073, stop RULE 074, targets RULE 075 / RULE 077
   │  ├─ 0.786 of B:C between 0.500 and 0.618 of A:C?
   │  │  └─ YES → THREE-RATIO ZONE: entry RULE 087, stop RULE 086, trail plan RULE 091-RULE 095
   │  └─ Otherwise, 14-ADX ≥ 20 rising?
   │     ├─ YES → TREND PULLBACK: entry RULE 050, stop RULE 051, targets RULE 054 / RULE 056
   │     └─ NO → No Trade
   │
   ├─ STRUCTURE 2: Two-leg pattern A-B-C-D, C:D beyond B (RULE 098)
   │  ├─ Daily chart and D beyond the 200-day SMA?
   │  │  └─ YES → 200-SMA FAKE-OUT: entry RULE 146, stop RULE 147, targets RULE 149 / RULE 150
   │  ├─ D beyond X at 1.272-1.618 of X:A?
   │  │  └─ YES → BUTTERFLY TLP: entry RULE 133, stop RULE 135, targets RULE 137 / RULE 138
   │  ├─ D at 0.618-0.786 of X:A, B at 0.382-0.618?
   │  │  └─ YES → GARTLEY TLP: entry RULE 120, stop RULE 121, targets RULE 122 / RULE 123
   │  ├─ C:D = A:B and symmetry level in zone?
   │  │  └─ YES → AB=CD TLP: entry RULE 107, stop RULE 108, target RULE 109
   │  └─ None fits → No Trade
   │
   ├─ STRUCTURE 3: 0.786 of A:B broken, price at 1.272-1.618 of A:B (RULE 154, RULE 156)
   │  └─ → EXTENSION TRAP: entry RULE 158, stop RULE 159 / RULE 160, targets RULE 161 / RULE 162
   │
   ├─ STRUCTURE 4: Two zones with a clear gap, anchor made with 14-ADX > 20 (RULE 165)
   │  ├─ Price breaks Confluence Zone #1 far edge as 14-ADX < 20?
   │  │  ├─ Coming from an opposite trend → RGB (RULE 168-RULE 170)
   │  │  └─ Already trending in trade direction → CGB (RULE 171-RULE 173)
   │  │     → entry: break or retest; stop RULE 175; target RULE 178
   │  └─ NO break / no ADX cross → No Trade
   │
   └─ No structure matches → No Trade
      │
      ▼
   TRIGGER GATE (all setups except Zone Gap breaks)
   ├─ Trigger completed 1-2 time frames lower or on setup TF? (RULE 182, RULE 183)
   │  ├─ NO → No Trade
   │  └─ YES → Higher time frame opposing? (RULE 185)
   │     ├─ YES → No Trade
   │     └─ NO → RISK GATE
   │        ├─ Risk ≤ 2-3% and total risk ≤ 20-25%? (RULE 211, RULE 215)
   │        │  ├─ NO → Reduce size (RULE 177) or No Trade
   │        │  └─ YES → ENTER with the setup's stop and targets
```

---

## PARAMETER TABLE

| Parameter | Value | Rule |
|---|---|---|
| Core ratios | 0.618, 1.618 | RULE 001 |
| Derived ratios | 0.382, 0.500, 0.786, 1.000, 1.272, 2.618 | RULE 002 |
| Retracement ratios | 0.382, 0.500, 0.618, 0.786 | RULE 019 |
| Extension ratios | 1.272, 1.618 (2.618 in range) | RULE 022 |
| Projection / expansion ratios | 0.618, 1.000, 1.618 | RULE 025, RULE 029 |
| Max swing lookback | 8 consecutive swings | RULE 015 |
| Confluence Zone minimum | 3 levels | RULE 033 |
| Confluence Zone max width | ≤ 10% of price (commonly ~5%) | RULE 038 |
| Trend Pullback structure | 2+ higher highs, 1+ higher low | RULE 048 |
| Trend Pullback ADX | 14-period ≥ 20, upsloping | RULE 059 |
| Partial exit size | Half the position | RULE 054, RULE 122, RULE 149 |
| Symmetry Reversal ADX | 8-period, cross above 50 | RULE 065, RULE 066 |
| Symmetry Reversal DI | 21-period | RULE 063 |
| ADX strength bands (Symmetry Reversal) | < 20 weak, > 35 strong, 50-60 rare blow-off | RULE 064 |
| TRZ ratios | 0.500 & 0.618 of A:C, 0.786 of B:C | RULE 082 |
| TRZ test limit | 1 test; 2nd break invalidates | RULE 087 |
| AB=CD TLP C limit | ≤ 0.786 of A:B (ideal), never beyond A | RULE 103 |
| AB=CD TLP target | 1.272-1.618 of A:D | RULE 109 |
| Gartley B | 0.382-0.618 of X:A (0.382-0.500 preferred) | RULE 114 |
| Gartley C | 0.382-0.786 of A:B | RULE 115 |
| Gartley D | 0.618-0.786 of X:A | RULE 116 |
| Gartley D confluence | 1.272 or 1.618 of B:C | RULE 117 |
| Butterfly B | 0.382-0.786 of X:A | RULE 128 |
| Butterfly C | 0.382 / 0.500 / 0.618 / 0.786 of A:B | RULE 129 |
| Butterfly D | 1.272-1.618 of X:A, beyond X | RULE 130 |
| Butterfly first target | 0.618-0.786 of C:D | RULE 137 |
| FAKE-OUT average | 200-day SMA (weekly: 40-period) | RULE 144, RULE 151 |
| FAKE-OUT trend filter | 13-period ADX > 20, rising | RULE 145 |
| FAKE-OUT wide stop example | ~15% of price → cut size | RULE 148 |
| Extension Trap decision level | 0.786 of A:B | RULE 154 |
| Extension Trap completion | 1.272-1.618 of A:B | RULE 156 |
| Extension Trap zone strength | 4+ extension levels | RULE 157 |
| Zone Gap ADX | 14-period, threshold 20 | RULE 164 |
| ADX scale (Zone Gaps) | 0-15 / 16-20 / 21-40 / > 40 | RULE 163 |
| Zone Gap time frames | 60-minute to weekly (daily primary) | RULE 166 |
| Zone Gap stall limit | 2-3 sideways bars | RULE 180 |
| Trigger drill-down | Weekly→Daily/60m; Daily→60/30m; 30m→13/8m; 13m→5m | RULE 182 |
| Drill depth limit | 1-2 time frames | RULE 184 |
| Candle star close-in | ≥ 50% into first body | RULE 192, RULE 193, RULE 196, RULE 197 |
| Risk per trade | 2-3% of equity max | RULE 211 |
| Total portfolio risk | ≤ 20-25% of account | RULE 215 |
| Loss streak, no rule change | 2-3 losses | RULE 205 |

---

## SETUP SUMMARY TABLE

| Setup | Context | Trigger | Entry | Stop | Target | Probability | Skip |
|---|---|---|---|---|---|---|---|
| Trend Pullback | 2+ HH, 1+ HL; 14-ADX ≥ 20 | Bar touches zone edge + pattern | Pattern at zone | Just beyond zone | Half 0.500-0.618 of swing; 1.272 ext | not quantified | Weak structure, ADX < 20, hover |
| Symmetry Reversal | 8-ADX > 50, DI aligned | Zone holding symmetry level | Trade through prior bar | Just beyond zone | 0.500-0.618 of C:D; 1.272 of C:D | not quantified | No ADX cross, DI mismatch |
| Three-Ratio Zone | Swings A, B, C | TRZ order valid, touch | Trade through prior bar | Just beyond TRZ | Trail plan from 1.272 of C:D | not quantified | Wrong order, 2nd break |
| AB=CD TLP | A:B, C inside A, B broken | Symmetry level in zone | Trade through prior bar | Beyond zone | 1.272-1.618 of A:D | not quantified | C beyond A, no zone |
| Gartley TLP | X, A extremes; B 0.382-0.618 | D at 0.618-0.786 of X:A | Trade through prior bar | Beyond zone | First opposing zone; 1.272 of A:D | not quantified | X or A broken |
| Butterfly TLP | B ≥ X; C < A | D at 1.272-1.618 of X:A | Trigger (no bare touch) | Beyond zone | 0.618-0.786 of C:D; 1.272-1.618 of A:D | not quantified | D not beyond X |
| 200-SMA Fake-Out | Daily; TLP; trend | D beyond 200-SMA in zone | Trade through prior bar | Beyond zone | 0.500-0.618 of A:D; trail from 1.272 | not quantified | Choppy, intraday |
| Extension Trap | A, B swings | 0.786 break → 1.272-1.618 | First bar through prior bar | Beyond 1.618 / C | 0.500-0.618 of B:C; 1.272 of B:C | not quantified | No 0.786 break |
| Zone Gap (RGB/CGB) | Anchor with 14-ADX > 20 | Break of zone #1 as ADX < 20 | Break or retest | Zone #1 / bar / prior bar | Near edge of zone #2 | not quantified | No gap, risk > gap |

---

## UNDEFINED PARAMETERS (DISCRETION REQUIRED)

- "Relatively tight range" for a Confluence Zone has no lower bound; only the ≤ 10% width cap is defined (RULE 038).
- Stop offset for "just beyond the zone" is not defined in ticks or percent (RULE 051, RULE 074, RULE 086).
- "Significant" prior countertrend swing for Symmetry Reversal is not quantified (RULE 069).
- Allowed overshoot for a TRZ on its single test is discretionary (RULE 087).
- Half 2 swing-point trailing in the Three-Ratio Zone is discretionary (RULE 095).
- Minimum Zone Gap size is not defined beyond "tradable" (RULE 169, RULE 172).
- Symmetry Reversal time symmetry (bar count) is measured but no tolerance is defined (RULE 061, RULE 069).
- Expansion structure needed when no clean X:A exists is discretionary (RULE 031).

---

## OPEN CONFLICTS

- RULE 046 / RULE 050: Confirmation Law requires waiting for an entry trigger pattern (RULE 046), whereas aggressive Trend Pullback entry allows buying/selling the direct touch of the Confluence Zone boundary without waiting for a pattern (RULE 050 Variant B).
- RULE 093 / RULE 094: In the Three-Ratio Zone trailing stop plan, Half 1 stop is trailed to the prior bar's low (VARIANT A) or to the prior bar's high (VARIANT B) on subsequent new extremes. Default sequence is prior bar low at initial activation, prior bar high on extended trend continuation.
- RULE 116: Gartley point B band is 0.382-0.618 (VARIANT A) or 0.382-0.500 (VARIANT B) of X:A.
- RULE 125: Gartley final objective is the 1.272 of A:D (VARIANT A) or the 1.272-1.618 band (VARIANT B).
- RULE 135 / RULE 136: Butterfly entry on a trigger (default) or on the bare 1.272 touch (VARIANT B, discretionary).
- RULE 140: Butterfly final objective is the 1.272 of A:D (VARIANT A) or the 1.272-1.618 band (VARIANT B).

---

## RULE INDEX

| RULE No. | LABEL | Module |
|---|---|---|
| 001 | CORE RATIOS | 01 Ratio Set And Scope |
| 002 | DERIVED RATIOS | 01 Ratio Set And Scope |
| 003 | MARKET SCOPE | 01 Ratio Set And Scope |
| 004 | TIMEFRAME SCOPE | 01 Ratio Set And Scope |
| 005 | LEVEL PURPOSE | 01 Ratio Set And Scope |
| 006 | SWING HIGH | 02 Swing Point Selection |
| 007 | SWING LOW | 02 Swing Point Selection |
| 008 | CONSOLIDATION LOWS | 02 Swing Point Selection |
| 009 | CONSOLIDATION HIGHS | 02 Swing Point Selection |
| 010 | INVALID SWING LOW | 02 Swing Point Selection |
| 011 | INVALID SWING HIGH | 02 Swing Point Selection |
| 012 | SUPPORT ANCHORS | 02 Swing Point Selection |
| 013 | RESISTANCE ANCHORS | 02 Swing Point Selection |
| 014 | ANCHOR CONFIRMATION | 02 Swing Point Selection |
| 015 | SWING LOOKBACK LIMIT | 02 Swing Point Selection |
| 016 | FOUR KEY SWINGS | 02 Swing Point Selection |
| 017 | SWING VISUAL CHECK | 02 Swing Point Selection |
| 018 | RETRACEMENT DEFINITION | 03 The Four Price Studies |
| 019 | RETRACEMENT RATIOS | 03 The Four Price Studies |
| 020 | RETRACEMENT FORMULA | 03 The Four Price Studies |
| 021 | EXTENSION DEFINITION | 03 The Four Price Studies |
| 022 | EXTENSION RATIOS | 03 The Four Price Studies |
| 023 | EXTENSION FORMULA | 03 The Four Price Studies |
| 024 | PROJECTION DEFINITION | 03 The Four Price Studies |
| 025 | PROJECTION RATIOS | 03 The Four Price Studies |
| 026 | PROJECTION FORMULA | 03 The Four Price Studies |
| 027 | SYMMETRY PROJECTION | 03 The Four Price Studies |
| 028 | EXPANSION DEFINITION | 03 The Four Price Studies |
| 029 | EXPANSION RATIOS | 03 The Four Price Studies |
| 030 | EXPANSION FORMULA | 03 The Four Price Studies |
| 031 | EXPANSION CONFIRMS ONLY | 03 The Four Price Studies |
| 032 | ZONE POLARITY | 04 Confluence Zones |
| 033 | ZONE MINIMUM | 04 Confluence Zones |
| 034 | ZONE BUILD SEQUENCE | 04 Confluence Zones |
| 035 | VIOLATED LEVEL DELETE | 04 Confluence Zones |
| 036 | VIOLATED ANCHOR SWITCH | 04 Confluence Zones |
| 037 | ISOLATED LEVEL DELETE | 04 Confluence Zones |
| 038 | ZONE WIDTH LIMIT | 04 Confluence Zones |
| 039 | NO ZONE-ONLY TRADE | 04 Confluence Zones |
| 040 | ZONE STRENGTH | 04 Confluence Zones |
| 041 | NO RATIO PREFERENCE | 04 Confluence Zones |
| 042 | NO STUDY PREFERENCE | 04 Confluence Zones |
| 043 | MULTIPLE ZONES | 04 Confluence Zones |
| 044 | ZONE RECALCULATION | 04 Confluence Zones |
| 045 | CHARTING TOOL REQUIREMENTS | 04 Confluence Zones |
| 046 | TRIGGER REQUIRED | 05 Confirmation Law For All Setups |
| 047 | ENTRY MEANS PATTERN | 05 Confirmation Law For All Setups |
| 048 | TREND STRUCTURE | 06 Trend Pullback Entry |
| 049 | ZONE TIMING | 06 Trend Pullback Entry |
| 050 | ZONE TOUCH ENTRY | 06 Trend Pullback Entry |
| 051 | STOP BEYOND ZONE | 06 Trend Pullback Entry |
| 052 | ZONE TOO DEEP | 06 Trend Pullback Entry |
| 053 | TARGET CALCULATION | 06 Trend Pullback Entry |
| 054 | FIRST TARGET | 06 Trend Pullback Entry |
| 055 | TRAIL AFTER FIRST | 06 Trend Pullback Entry |
| 056 | FINAL TARGET | 06 Trend Pullback Entry |
| 057 | BREAKEVEN STOP CAUTION | 06 Trend Pullback Entry |
| 058 | HOVER SCRATCH | 06 Trend Pullback Entry |
| 059 | ADX CONFIRMATION | 06 Trend Pullback Entry |
| 060 | PRICE SYMMETRY | 07 Symmetry Reversal With Trend Strength |
| 061 | TIME SYMMETRY | 07 Symmetry Reversal With Trend Strength |
| 062 | SYMMETRY SCAN | 07 Symmetry Reversal With Trend Strength |
| 063 | DI DIRECTION | 07 Symmetry Reversal With Trend Strength |
| 064 | ADX STRENGTH | 07 Symmetry Reversal With Trend Strength |
| 065 | SYMMETRY REVERSAL ADX SETTING | 07 Symmetry Reversal With Trend Strength |
| 066 | ADX TRIGGER | 07 Symmetry Reversal With Trend Strength |
| 067 | POINT C | 07 Symmetry Reversal With Trend Strength |
| 068 | DI CHECK AT C | 07 Symmetry Reversal With Trend Strength |
| 069 | MEASURE A:B | 07 Symmetry Reversal With Trend Strength |
| 070 | ZONE FROM C | 07 Symmetry Reversal With Trend Strength |
| 071 | SYMMETRY LEVEL | 07 Symmetry Reversal With Trend Strength |
| 072 | SYMMETRY TOLERANCE | 07 Symmetry Reversal With Trend Strength |
| 073 | DUAL AXIS SYMMETRY | 07 Symmetry Reversal With Trend Strength |
| 074 | SYMMETRY REVERSAL ENTRY | 07 Symmetry Reversal With Trend Strength |
| 075 | SYMMETRY REVERSAL STOP | 07 Symmetry Reversal With Trend Strength |
| 076 | SYMMETRY REVERSAL FIRST TARGET | 07 Symmetry Reversal With Trend Strength |
| 077 | LOW-TIMEFRAME EXCEPTION | 07 Symmetry Reversal With Trend Strength |
| 078 | SYMMETRY REVERSAL FINAL TARGET | 07 Symmetry Reversal With Trend Strength |
| 079 | RUNNER OPTION | 07 Symmetry Reversal With Trend Strength |
| 080 | PARTIAL EXIT PURPOSE | 07 Symmetry Reversal With Trend Strength |
| 081 | POINT C | 08 Three-Ratio Pullback Zone |
| 082 | POINTS A AND B | 08 Three-Ratio Pullback Zone |
| 083 | TRZ RATIOS | 08 Three-Ratio Pullback Zone |
| 084 | TRZ ORDER TEST | 08 Three-Ratio Pullback Zone |
| 085 | NEAR-MISS TOLERANCE | 08 Three-Ratio Pullback Zone |
| 086 | SYMMETRY STRENGTHENS | 08 Three-Ratio Pullback Zone |
| 087 | SYMMETRY TOUCH VALIDATION | 08 Three-Ratio Pullback Zone |
| 088 | TRZ ENTRY | 08 Three-Ratio Pullback Zone |
| 089 | TRZ STOP | 08 Three-Ratio Pullback Zone |
| 090 | EXTERIOR SYMMETRY STOP | 08 Three-Ratio Pullback Zone |
| 091 | TRZ PENETRATION | 08 Three-Ratio Pullback Zone |
| 092 | POINT D AND TRIGGER LEVEL | 08 Three-Ratio Pullback Zone |
| 093 | TRAIL ACTIVATION | 08 Three-Ratio Pullback Zone |
| 094 | HALF 1 TRAIL | 08 Three-Ratio Pullback Zone |
| 095 | HALF 1 TRAIL VARIANT | 08 Three-Ratio Pullback Zone |
| 096 | HALF 2 TRAIL | 08 Three-Ratio Pullback Zone |
| 097 | TRAIL PLAN PURPOSE | 08 Three-Ratio Pullback Zone |
| 098 | BROKEN TRZ | 08 Three-Ratio Pullback Zone |
| 099 | TLP STRUCTURE | 09 Two-Leg Patterns (Tlp) |
| 100 | TLP DIRECTION | 09 Two-Leg Patterns (Tlp) |
| 101 | TLP SIZE CLASS | 09 Two-Leg Patterns (Tlp) |
| 102 | TLP VISUAL TEST | 09 Two-Leg Patterns (Tlp) |
| 103 | AB=CD STEP 1 | 09 Two-Leg Patterns (Tlp) |
| 104 | AB=CD POINT C LIMIT | 09 Two-Leg Patterns (Tlp) |
| 105 | AB=CD BREAK OF B | 09 Two-Leg Patterns (Tlp) |
| 106 | AB=CD SYMMETRY LEVEL | 09 Two-Leg Patterns (Tlp) |
| 107 | AB=CD ZONE MATCH | 09 Two-Leg Patterns (Tlp) |
| 108 | AB=CD ENTRY | 09 Two-Leg Patterns (Tlp) |
| 109 | AB=CD STOP | 09 Two-Leg Patterns (Tlp) |
| 110 | AB=CD TARGET | 09 Two-Leg Patterns (Tlp) |
| 111 | INTERMEDIATE ZONE EXIT | 09 Two-Leg Patterns (Tlp) |
| 112 | TARGET DOUBLE BOTTOM WARNING | 09 Two-Leg Patterns (Tlp) |
| 113 | GARTLEY POINT X | 09 Two-Leg Patterns (Tlp) |
| 114 | GARTLEY POINT A | 09 Two-Leg Patterns (Tlp) |
| 115 | GARTLEY POINT B | 09 Two-Leg Patterns (Tlp) |
| 116 | GARTLEY POINT C | 09 Two-Leg Patterns (Tlp) |
| 117 | GARTLEY COMPLETION | 09 Two-Leg Patterns (Tlp) |
| 118 | GARTLEY D CONFLUENCE | 09 Two-Leg Patterns (Tlp) |
| 119 | GARTLEY CONFLUENCE ZONE REQUIRED | 09 Two-Leg Patterns (Tlp) |
| 120 | GARTLEY DEPTH | 09 Two-Leg Patterns (Tlp) |
| 121 | GARTLEY ENTRY | 09 Two-Leg Patterns (Tlp) |
| 122 | GARTLEY STOP | 09 Two-Leg Patterns (Tlp) |
| 123 | GARTLEY FIRST TARGET | 09 Two-Leg Patterns (Tlp) |
| 124 | GARTLEY FINAL TARGET | 09 Two-Leg Patterns (Tlp) |
| 125 | GARTLEY TIMEFRAMES | 09 Two-Leg Patterns (Tlp) |
| 126 | OWN THE STOP METHOD | 09 Two-Leg Patterns (Tlp) |
| 127 | BUTTERFLY POINT X | 09 Two-Leg Patterns (Tlp) |
| 128 | BUTTERFLY POINT A | 09 Two-Leg Patterns (Tlp) |
| 129 | BUTTERFLY POINT B | 09 Two-Leg Patterns (Tlp) |
| 130 | BUTTERFLY POINT C | 09 Two-Leg Patterns (Tlp) |
| 131 | BUTTERFLY COMPLETION | 09 Two-Leg Patterns (Tlp) |
| 132 | BUTTERFLY STEP SIZE | 09 Two-Leg Patterns (Tlp) |
| 133 | BUTTERFLY VISUAL TEST | 09 Two-Leg Patterns (Tlp) |
| 134 | BUTTERFLY TRIGGER REQUIRED | 09 Two-Leg Patterns (Tlp) |
| 135 | TOUCH ENTRY VARIANT | 09 Two-Leg Patterns (Tlp) |
| 136 | BUTTERFLY STOP | 09 Two-Leg Patterns (Tlp) |
| 137 | BUTTERFLY OPPOSING ZONE | 09 Two-Leg Patterns (Tlp) |
| 138 | BUTTERFLY FIRST TARGET | 09 Two-Leg Patterns (Tlp) |
| 139 | BUTTERFLY FINAL TARGET | 09 Two-Leg Patterns (Tlp) |
| 140 | BUTTERFLY RUNNER | 09 Two-Leg Patterns (Tlp) |
| 141 | TWO-STAGE EXIT PRINCIPLE | 09 Two-Leg Patterns (Tlp) |
| 142 | HTF CONTEXT CHECK | 09 Two-Leg Patterns (Tlp) |
| 143 | FAKE-OUT PATTERN | 10 200-Day Average Fake-Out |
| 144 | FAKE-OUT CONFLUENCE ZONE | 10 200-Day Average Fake-Out |
| 145 | FAKE-OUT SMA CONDITION | 10 200-Day Average Fake-Out |
| 146 | FAKE-OUT TREND CONTEXT | 10 200-Day Average Fake-Out |
| 147 | FAKE-OUT ENTRY | 10 200-Day Average Fake-Out |
| 148 | FAKE-OUT STOP | 10 200-Day Average Fake-Out |
| 149 | FAKE-OUT WIDE ZONE SIZING | 10 200-Day Average Fake-Out |
| 150 | FAKE-OUT FIRST TARGET | 10 200-Day Average Fake-Out |
| 151 | FAKE-OUT FINAL TARGET | 10 200-Day Average Fake-Out |
| 152 | FAKE-OUT TIMEFRAME | 10 200-Day Average Fake-Out |
| 153 | FAKE-OUT SCAN | 10 200-Day Average Fake-Out |
| 154 | TRAP POINTS | 11 Extension Trap Reversal |
| 155 | TRAP 786 DECISION | 11 Extension Trap Reversal |
| 156 | TRAP MOMENTUM OPTION | 11 Extension Trap Reversal |
| 157 | TRAP COMPLETION | 11 Extension Trap Reversal |
| 158 | TRAP ZONE QUALITY | 11 Extension Trap Reversal |
| 159 | TRAP ENTRY | 11 Extension Trap Reversal |
| 160 | TRAP STOP | 11 Extension Trap Reversal |
| 161 | TRAP TIGHT STOP | 11 Extension Trap Reversal |
| 162 | TRAP FIRST TARGET | 11 Extension Trap Reversal |
| 163 | TRAP FINAL TARGET | 11 Extension Trap Reversal |
| 164 | ADX READING SCALE | 12 Zone-Gap Momentum Breakouts |
| 165 | ZONE GAP ADX SETTING | 12 Zone-Gap Momentum Breakouts |
| 166 | CLEAR THE GAP | 12 Zone-Gap Momentum Breakouts |
| 167 | GAP TIMEFRAMES | 12 Zone-Gap Momentum Breakouts |
| 168 | PRIOR TESTS STRENGTHEN | 12 Zone-Gap Momentum Breakouts |
| 169 | RGB ANCHOR | 12 Zone-Gap Momentum Breakouts |
| 170 | RGB TWO ZONES | 12 Zone-Gap Momentum Breakouts |
| 171 | RGB TRIGGER | 12 Zone-Gap Momentum Breakouts |
| 172 | CGB ANCHOR | 12 Zone-Gap Momentum Breakouts |
| 173 | CGB TWO ZONES | 12 Zone-Gap Momentum Breakouts |
| 174 | CGB TRIGGER | 12 Zone-Gap Momentum Breakouts |
| 175 | RGB VS CGB | 12 Zone-Gap Momentum Breakouts |
| 176 | GAP STOP OPTIONS | 12 Zone-Gap Momentum Breakouts |
| 177 | STOP VS GAP SIZE | 12 Zone-Gap Momentum Breakouts |
| 178 | POSITION SIZE FORMULA | 12 Zone-Gap Momentum Breakouts |
| 179 | GAP TARGET | 12 Zone-Gap Momentum Breakouts |
| 180 | GAP HOLD OPTION | 12 Zone-Gap Momentum Breakouts |
| 181 | GAP STALL EXIT | 12 Zone-Gap Momentum Breakouts |
| 182 | CONFIRM THEN ENTER | 13 Entry Triggers And Timeframe Drill-Down |
| 183 | LOWER TIMEFRAME TRIGGER | 13 Entry Triggers And Timeframe Drill-Down |
| 184 | SAME TIMEFRAME OPTION | 13 Entry Triggers And Timeframe Drill-Down |
| 185 | DRILL DEPTH LIMIT | 13 Entry Triggers And Timeframe Drill-Down |
| 186 | HTF AWARENESS | 13 Entry Triggers And Timeframe Drill-Down |
| 187 | DEFAULT SIMPLE TRIGGER | 13 Entry Triggers And Timeframe Drill-Down |
| 188 | TRIGGER FAMILIES | 13 Entry Triggers And Timeframe Drill-Down |
| 189 | FOLLOW THROUGH BARS | 13 Entry Triggers And Timeframe Drill-Down |
| 190 | DOJI | 13 Entry Triggers And Timeframe Drill-Down |
| 191 | BEARISH ENGULFING | 13 Entry Triggers And Timeframe Drill-Down |
| 192 | BULLISH ENGULFING | 13 Entry Triggers And Timeframe Drill-Down |
| 193 | EVENING STAR | 13 Entry Triggers And Timeframe Drill-Down |
| 194 | MORNING STAR | 13 Entry Triggers And Timeframe Drill-Down |
| 195 | HANGING MAN | 13 Entry Triggers And Timeframe Drill-Down |
| 196 | SHOOTING STAR | 13 Entry Triggers And Timeframe Drill-Down |
| 197 | MORNING DOJI STAR | 13 Entry Triggers And Timeframe Drill-Down |
| 198 | EVENING DOJI STAR | 13 Entry Triggers And Timeframe Drill-Down |
| 199 | TWEEZER BOTTOM | 13 Entry Triggers And Timeframe Drill-Down |
| 200 | TWEEZER TOP | 13 Entry Triggers And Timeframe Drill-Down |
| 201 | THREE METHODS | 13 Entry Triggers And Timeframe Drill-Down |
| 202 | TRIGGER PROCEDURE | 13 Entry Triggers And Timeframe Drill-Down |
| 203 | TRIGGER STACKING | 13 Entry Triggers And Timeframe Drill-Down |
| 204 | AGAINST-TREND CONFIRMATION | 13 Entry Triggers And Timeframe Drill-Down |
| 205 | EXECUTION OVER OUTCOME | 14 Execution Discipline And Portfolio Risk |
| 206 | NO RULE CHANGES ON STREAKS | 14 Execution Discipline And Portfolio Risk |
| 207 | EMOTION-PROOF FRAMEWORK | 14 Execution Discipline And Portfolio Risk |
| 208 | SUCCESS FORMULA | 14 Execution Discipline And Portfolio Risk |
| 209 | NIGHTLY REVIEW | 14 Execution Discipline And Portfolio Risk |
| 210 | DIRECTIONAL EXPOSURE | 14 Execution Discipline And Portfolio Risk |
| 211 | SECTOR EXPOSURE | 14 Execution Discipline And Portfolio Risk |
| 212 | RISK PER TRADE | 14 Execution Discipline And Portfolio Risk |
| 213 | NEWS EXPOSURE | 14 Execution Discipline And Portfolio Risk |
| 214 | PATTERN EXPOSURE | 14 Execution Discipline And Portfolio Risk |
| 215 | TIMEFRAME DIVERSIFICATION | 14 Execution Discipline And Portfolio Risk |
| 216 | TOTAL PORTFOLIO RISK | 14 Execution Discipline And Portfolio Risk |
| 217 | AGGRESSION INSIDE LIMITS | 14 Execution Discipline And Portfolio Risk |

---

**END OF RULEBOOK**
