# FIBONACCI CONFLUENCE ZONE PROTOCOL - OPERATIONAL RULEBOOK (SLM DETERMINISTIC EDITION)
## SYSTEM SCOPE: Fibonacci Support/Resistance Zones, Trend Pullbacks, Symmetry Reversals, Two-Leg Patterns, Breakout Gaps, Entry Triggers, Execution Buffers & Quantitative Risk Control
**Edition:** 20261103-SLM-Final · Fully Deterministic, Mathematically Complete & Formally Verified

---

## FUNDAMENTAL PRINCIPLE

**Price may react at structural areas where multiple independent Fibonacci measurements of prior swings converge. These areas identify potential decision zones, not guaranteed reversal points. Trades are taken as reversals or continuations according to each setup's explicit entry confirmation rules.**

Fibonacci ratios provide a standardized geometric measurement framework for swing expansions and contractions. An isolated level carries negligible edge; 3 or more structurally distinct levels clustering within a defined volatility-based boundary form a Confluence Zone. Each setup in this system is a deterministic structure that delivers price to or through a Confluence Zone: a trend pullback, a symmetrical swing, a three-ratio stack, a two-leg pattern, a 200-day average fake-out, an extension trap, or a breakout across a level-free corridor. Every standard setup requires a completed price-action trigger before execution. Pre-trade Risk-to-Reward (R:R) must be confirmed prior to order placement. Stops sit beyond structural invalidation points, initial targets bank partial profits to de-risk exposure, and trailing mechanisms protect accrued gains. Fixed per-trade, daily, and portfolio-level risk limits strictly govern all activity.

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

**RULE 006-SWING HIGH:** A swing high is a bar high with at least one bar with a strictly lower high on both its immediate left and right. In the case of equal highs, the right-most bar of the equal sequence is designated as the pivot candidate once a bar with a lower high closes to its right.

**RULE 007-SWING LOW:** A swing low is a bar low with at least one bar with a strictly higher low on both its immediate left and right. In the case of equal lows, the right-most bar of the equal sequence is designated as the pivot candidate once a bar with a higher low closes to its right.

**RULE 008-CONSOLIDATION LOWS:** When several swing lows sit within 0.5 × ATR(14) in price inside a consolidation range, treat them as a single structural base and anchor calculations strictly from the swing low furthest to the right.

**RULE 009-CONSOLIDATION HIGHS:** When several swing highs sit within 0.5 × ATR(14) in price inside a consolidation range, treat them as a single structural ceiling and anchor calculations strictly from the swing high furthest to the right.

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

**RULE 014-ANCHOR CONFIRMATION:** Calculate levels only after the current swing point is fully confirmed by the completed CLOSE of the right-hand confirming bar. An intrabar high or low is never an anchor until its confirming candle has completely closed.

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

**RULE 031-EXPANSION CONFIRMS ONLY:** Apply retracements, extensions, and projections first; expansions serve solely as secondary confirmation. An expansion level may NEVER count as one of the mandatory 3 qualifying levels required to establish a valid Confluence Zone (RULE 033). It may only be added as a 4th+ confirming study.

---

## MODULE 04: CONFLUENCE ZONES

### Definition: Confluence Zone

**RULE:** A Confluence Zone is a relatively tight price range where at least 3 Fibonacci levels from any combination of the four studies cluster.

**CONTEXT:** Nearly every setup in this system is a market reaching a support or resistance Confluence Zone. The zone tells where to look; an entry pattern inside it tells when to act.

**RULE 032-ZONE POLARITY:** A Confluence Zone above current price is resistance; a Confluence Zone below current price is support.

**RULE 033-ZONE MINIMUM:** A Confluence Zone requires a cluster of at least 3 qualifying Fibonacci levels from at least two distinct, non-collinear swing anchor pairs. Levels derived from identical swing anchors do not count as independent levels.

### How to Build a Support Confluence Zone (uptrend; reverse every step for a resistance zone in a downtrend)

**RULE 034-ZONE BUILD SEQUENCE:**
1. Identify the current confirmed swing high and all valid prior swing lows (RULE 006 to RULE 016).
2. Retracements: from each valid swing low up to the current swing high.
3. Extensions: from swing lows that sit ABOVE current price up to the current swing high.
4. Projections: subtract each prior countertrend decline in the trend from the current swing high (RULE 027).
5. Expansions: last, and only if the structure allows (RULE 031).

**RULE 035-VIOLATED LEVEL DELETE:** Delete any Fibonacci level where a candle has closed beyond it by more than 0.25 × ATR(14) (or 2 minimum price ticks, whichever is larger). An intrabar penetration (wick) that closes back inside does not invalidate the level during zone construction if other levels cluster with it.

**RULE 036-VIOLATED ANCHOR SWITCH:** When a prior swing low sits above current price (market has traded below it), drop retracement measurements from that low. Instead, calculate countertrend extensions (1.272 and 1.618) of the swing that broke below that low (measured from the preceding swing high down to the broken swing low, projected downward from the broken swing low) to identify lower extension support.

**RULE 037-ISOLATED LEVEL DELETE:** Delete any level that has no other Fibonacci levels near it to form a zone.

**RULE 038-ZONE WIDTH & CLUSTERING ALGORITHM:** Confluence Zone construction is governed by an explicit sliding-window clustering algorithm:
1. Candidate Pool: Collect all calculated price levels from the active four studies within 4.0 × ATR(14) of current price.
2. Deduplication: Group levels derived from identical swing anchors; only one level per anchor pair may contribute to the mandatory 3-level count.
3. Sliding Window Cluster: Scan the candidate pool with a sliding window of width W = 1.0 × ATR(14) (for equities: W = min(1.0 × ATR(14), 2.5% of nominal price)). If ≥ 3 distinct structural levels fall within window W, a candidate Confluence Zone is formed.
4. Boundaries: Zone boundaries are strictly set to [Minimum contributing level, Maximum contributing level]. Zone width (Zone High − Zone Low) must satisfy: 0.15 × ATR(14) ≤ Width ≤ 1.50 × ATR(14). (Clusters < 0.15 × ATR(14) are merged into a single price line; clusters > 1.50 × ATR(14) are invalid and skipped).
5. Cluster Overlap: If two candidate clusters overlap by > 50% of their span, merge them only if the combined span remains ≤ 1.50 × ATR(14); otherwise, retain only the cluster with the higher distinct level count.

**RULE 039-NO ZONE-ONLY TRADE:** Never trade on a Confluence Zone alone, whatever its level count. Enter only on a valid entry pattern that forms inside the zone (defined in RULE 187).

**RULE 040-ZONE STRENGTH:** Confluence strength is classified ordinally by distinct structural level count: 3 levels = Standard Zone; 4–5 levels = High-Density Zone; 6+ levels = Institutional Confluence. Probability values are not mathematically assigned; strength dictates setup priority (RULE 043), not blind entry aggression.

**RULE 041-NO RATIO PREFERENCE:** A generic Confluence Zone requires no specific ratio; any confluence counts. Specific strategies that require specific ratios state them in their own rules.

**RULE 042-NO STUDY PREFERENCE:** No study outranks another; level density in a tight range is the only measure.

**RULE 043-MULTIPLE ZONES:** When multiple Confluence Zones exist along the path of price, prioritize the zone that: (1) has the highest level density (RULE 040), (2) aligns with the higher-timeframe trend (RULE 186), and (3) yields a valid completed entry trigger (RULE 202) with a pre-trade R:R ≥ 1.5 (RULE 177).

**RULE 044-ZONE RECALCULATION:** In an uptrend, recalculate the active Support Confluence Zone only after price closes above the prior confirmed swing high and establishes a new confirmed swing high (RULE 014). An existing zone is invalidated immediately if price closes through its far edge by > 0.5 × ATR(14), even if no new high has formed.

**RULE 045-CHARTING TOOL REQUIREMENTS:** The charting tool must run all four studies, delete individual levels, annotate charts, display candlesticks, and run other technical studies.

**SKIP A CONFLUENCE ZONE WHEN:**
- Fewer than 3 structurally distinct levels cluster (RULE 033).
- Width exceeds 1.5 × ATR(14) (or > 3.0% of price for equities) (RULE 038).
- No valid entry pattern forms inside it (RULE 039).
- Price has cleanly closed through its levels (RULE 035).
## MODULE 05: CONFIRMATION LAW FOR ALL SETUPS

**RULE 046-TRIGGER REQUIRED:** Confirmation is mandatory for every standard reversal and continuation setup. A trade order may be executed ONLY after an explicit entry trigger (defined in Module 13) has completed at the Confluence Zone. Zone-touch limit entries are strictly prohibited in automated execution. Zone-Gap Momentum Breakouts (Module 12) operate under their own defined breakout/retest gate.

**RULE 047-ENTRY MEANS PATTERN:** Every "entry" across all setup rules denotes a completed, confirmed trigger pattern (RULE 187, RULE 188, RULE 202). A zone touch, probe, or test alone is never an entry.

**RULE 047A-UNIVERSAL NET REWARD-TO-RISK GATE:** Every trade across all modules must satisfy a mandatory pre-trade Net Reward-to-Risk filter prior to order submission:
`Net Planned R:R = Total Planned Net Profit ($) / Maximum Initial Dollar Risk ($)`
Where:
- Maximum Initial Dollar Risk ($) = Total position size × ((|Entry − Stop Price| × Unit Multiplier) + Round-Turn Fees + 2 ticks slippage).
- Total Planned Net Profit ($) for two-stage exits = [0.50 × Position Size × (|Entry − First Target| × Unit Multiplier)] + [0.50 × Position Size × (|Entry − Final Target| × Unit Multiplier)] − Total Transaction Fees.
- Universal Requirement: Net Planned R:R must be ≥ 1.50 across the combined position. (If evaluating First Target alone in fast intraday setups, Net Reward to First Target / Initial Risk must be ≥ 1.00). If Net Planned R:R < 1.50, REJECT THE TRADE outright.

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

**RULE 049-ZONE TIMING:** For longs, calculate the Support Confluence Zone once the second higher swing high is confirmed (RULE 014); for shorts, calculate the Resistance Confluence Zone once the second lower swing low is confirmed.

### How to Trade Trend Pullback

**ENTRY CONDITIONS:**
- Trend structure confirmed (RULE 048).
- Current bar low touches at least the TOP of the Support Confluence Zone (shorts: bar high touches at least the BOTTOM of the Resistance Confluence Zone).
- An entry pattern forms at the zone (RULE 046).

**RULE 050-ZONE TOUCH ENTRY:** When price reaches the near edge of the Confluence Zone, execution is governed by:
- CANONICAL (Mandatory for SLM): Wait for price to touch the zone and print a completed entry trigger pattern (RULE 046, RULE 187, RULE 202) before executing.
- VARIANT B (Discretionary Manual Only): Entering on a blind limit order at the near edge is strictly classified as an Out-of-System Discretionary Technique and must NEVER be executed by an automated agent, as it carries no structural confirmation of zone stability.

**STOP PLACEMENT:**

**RULE 051-STOP BEYOND ZONE:** Place the initial protective stop beyond the far edge of the Confluence Zone with an explicit volatility buffer: Stop Price = Zone Far Edge ± (0.25 × ATR(14) + 2 ticks) (below the zone for longs; above the zone for shorts).

**RULE 052-ZONE TOO DEEP:** If risking the full zone breaks money-management limits, choose one:
1. Wait until price moves deep enough into the zone for the stop distance to fit the limit.
2. Reduce position size until the full-zone risk fits the limit.
3. Skip the trade.

**TARGET:**

**RULE 053-TARGET CALCULATION:** Pre-trade target estimates are calculated using the estimated zone entry level and the last trend extreme. Upon completed entry trigger confirmation, measure the verified swing leg from the prior trend extreme to the confirmed pivot low/high inside the zone (swing into the zone). Compute targets in the trade direction: First Target = 0.500–0.618 retracement of that pullback leg; Final Target = 1.272 extension beyond the prior trend extreme.

**RULE 054-FIRST TARGET:** Take first profit at the 0.618 retracement of the swing into the zone (or conservative 0.500 in lower-volatility conditions); close exactly 50% of position volume (for single-contract accounts: close entire position or trail full stop).

**RULE 055-TRAIL AFTER FIRST:** After First Target profit is booked, immediately trail the protective stop on the remaining position to Breakeven plus a cost friction buffer converted to price points:
- Price Offset in Points = (Estimated Round-Turn Commission & Fees per Contract or Share / Dollar Value of 1 Point) + (2 ticks × Price Increment per Tick).
- Adjusted Breakeven Stop = Entry Price + Price Offset (for longs); Entry Price − Price Offset (for shorts).
This mathematically guarantees that a stopped-out remainder covers all transaction costs without creating dimensional mixing of currency and points.

**RULE 056-FINAL TARGET:** Exit the remainder at the 1.272 extension of the swing into the Confluence Zone.

**RULE 057-BREAKEVEN STOP CAUTION:** When trailing to breakeven, account for the instrument's volatility; do not place stops on round numbers or too close to current price.

### Trade Management

**RULE 058-HOVER SCRATCH:** A valid trade is expected to initiate trend resumption within 4 completed candles following entry. If price prints 4 consecutive candles that fail to advance at least 0.5 × ATR(14) in the trade direction and remain hovering within the zone boundary, exit the trade at market (Scratch Exit) to preserve capital.

**RULE 059-ADX CONFIRMATION:** Filter Trend Pullback setups using a 14-period ADX: ADX(14) must be ≥ 20.0 AND the ADX line must be strictly rising (ADX[0] > ADX[1]). If ADX < 20 or downsloping, skip the setup.

**PROBABILITY:** not quantified.

**SKIP TREND PULLBACK WHEN:**
- Fewer than 2 higher highs or no higher low (longs), or the mirror for shorts (RULE 048).
- Price has not reached the Confluence Zone edge (RULE 050).
- No confirmed entry pattern forms (RULE 046, RULE 187).
- Full-zone risk exceeds money-management limits or R:R < 1.5 (RULE 052, RULE 177).
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

**RULE 064-ADX STRENGTH:** ADX measures non-directional trend strength (0 to 100):
- 0 to 20 = Weak or absent trend (consolidation/ranging).
- 20 to 35 = Established, healthy trending environment.
- 35 to 50 = Highly energized, powerful trend.
- > 50 = Parabolic/Climactic expansion (trend maturity warning on standard 14-period ADX).

**RULE 065-SYMMETRY REVERSAL ADX SETTING:** For Symmetry Reversal setups, calculate ADX using an 8-period lookback (fast trend sensitivity). The qualifying strength threshold is ADX(8) ≥ 35.0 (with ADX(8) ≥ 50.0 representing elite high-momentum momentum swings).

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

**RULE 066-ADX TRIGGER:** The 8-period ADX must be ≥ 35.0 (or cross above 35.0) during the swing into point C, verifying that the preceding trend leg had substantial directional impulse.

**RULE 067-POINT C:** After the ADX cross, wait for a swing high to form; label it C (shorts: a swing low).

**RULE 068-DI CHECK AT C:** At point C, the 21-period +DI is above −DI (shorts: −DI above +DI). If not, there is no setup.

**RULE 069-MEASURE A:B:** From point C, identify the immediately preceding confirmed countertrend swing A:B: A = swing high, B = swing low (shorts: A = swing low, B = swing high). The swing must have a minimum amplitude of at least 1.0 × ATR(14) to qualify as significant. Record both its price range |A − B| in points and its duration in bar count.

**RULE 070-ZONE FROM C:** Build a Support Confluence Zone from high point C using all four studies (RULE 034); shorts build a Resistance Confluence Zone from low point C.

**RULE 071-SYMMETRY LEVEL:** Project the A:B size from C (longs: C − A:B points; shorts: C + A:B points). The Confluence Zone that contains this symmetry level is the one to trade.

**RULE 072-SYMMETRY TOLERANCE:** Price symmetry is satisfied when the current swing leg C:D terminates inside the Confluence Zone containing the 1.000 symmetry projection (C ± |A − B|), with the absolute price difference ||C − D| − |A − B|| not exceeding 15% of |A − B|.

**RULE 073-DUAL AXIS SYMMETRY:** Time symmetry is evaluated alongside price symmetry: the duration of swing C:D in bar count must fall within ± 25% of the bar count of A:B (e.g., if A:B took 10 bars, C:D should take 7 to 13 bars). If time duration exceeds 1.5 × A:B bar count, momentum has deteriorated; skip the setup.

**ENTRY CONDITIONS:**
- RULE 066, RULE 068 satisfied.
- Price reaches the Confluence Zone that holds the symmetry level (RULE 070).

**RULE 074-SYMMETRY REVERSAL ENTRY:** After price touches the Confluence Zone holding the symmetry level, execute entry when a candle closes beyond the prior bar's extreme in the trade direction (buy on close above prior bar high for longs; sell on close below prior bar low for shorts).

**STOP PLACEMENT:**

**RULE 075-SYMMETRY REVERSAL STOP:** Initial stop just below the Support Confluence Zone (shorts: just above the Resistance Confluence Zone).

**TARGET:**

**RULE 076-SYMMETRY REVERSAL FIRST TARGET:** Label the extreme made into the zone D. The first objective is the 0.500 to 0.618 retracement of C:D; take partial profit there and move the stop to entry, or as near entry as the structure permits (alternative: trail to the previous swing point).

**RULE 077-LOW-TIMEFRAME EXCEPTION:** On lower timeframes (≤ 15m), if the distance from entry to the 0.500–0.618 First Target is less than 1.0 × ATR(14), skip the partial exit, maintain full position size, and trail the protective stop to breakeven once price exceeds the 0.618 retracement, targeting the 1.272 final objective.

**RULE 078-SYMMETRY REVERSAL FINAL TARGET:** Final target: the 1.272 extension of C:D.

**RULE 079-RUNNER OPTION:** Optional: at the 1.272 level, hold part of the position for a larger move. Trade-off: it keeps a winner open but can give back gains.

**RULE 080-PARTIAL EXIT PURPOSE:** The 0.500–0.618 partial exit with a trailed stop serves as mandatory capital protection: booking 50% profit mitigates adverse downside and finances the trade, allowing the trailed remainder to pursue the full extension target without downside monetary risk once the stop is moved past cost.

**PROBABILITY:** not quantified.

**SKIP SYMMETRY REVERSAL WHEN:**
- ADX(8) is below 35 during swing into C (RULE 066).
- DI direction at C disagrees with trade direction (RULE 068).
- No Confluence Zone contains the symmetry level within tolerance (RULE 070, RULE 072).
- Time symmetry duration exceeds 1.5 × prior swing (RULE 073).
- No candle closes beyond prior bar extreme after zone touch (RULE 074).

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

**RULE 084-TRZ ORDER TEST:** The TRZ is structurally valid if and only if the three calculated price levels strictly satisfy: for longs, Price(0.500 A:C) > Price(0.786 B:C) > Price(0.618 A:C); for shorts, Price(0.500 A:C) < Price(0.786 B:C) < Price(0.618 A:C). Geometrically, this requires swing low B to sit between 21.4% and 36.4% of the vertical range of A:C.

**RULE 085-NEAR-MISS TOLERANCE:** If the 0.786 level of B:C misses the 0.500 level of A:C by ≤ 0.25 × ATR(14) (or ≤ 3 ticks), accept the zone as valid ONLY IF a 1.000 symmetry projection also lands within the 0.500–0.618 boundary.

**RULE 086-SYMMETRY STRENGTHENS:** A 1.000 symmetry projection inside the TRZ strengthens the zone.

**RULE 087-SYMMETRY TOUCH VALIDATION:** When a 1.000 symmetry projection sits within 0.25 × ATR(14) of the near edge of the TRZ, price reaching that symmetry level satisfies the zone-touch requirement, permitting trigger evaluation even if price stops short of the 0.500 boundary.

### How to Trade the TRZ

**ENTRY CONDITIONS:**
- Valid TRZ (RULE 083 or RULE 084).
- Price touches the TRZ.

**RULE 088-TRZ ENTRY:** After price touches the TRZ, buy when price exceeds the prior bar's high (shorts: sell when price undercuts the prior bar's low).

**STOP PLACEMENT:**

**RULE 089-TRZ STOP:** Initial protective stop is placed beyond the far edge of the TRZ (below 0.618 of A:C for longs; above 0.618 of A:C for shorts) plus an ATR buffer: Stop Price = TRZ Far Edge ± (0.25 × ATR(14) + 2 ticks).

**RULE 090-EXTERIOR SYMMETRY STOP:** When a 1.000 symmetry projection sits just outside the far edge of the TRZ (e.g., below the 0.618 bottom for longs), place the initial stop just beyond the symmetry projection rather than the 0.618 retracement.

**RULE 091-TRZ PENETRATION:** An overshoot of the TRZ boundary by ≤ 0.25 × ATR(14) on an intrabar wick retains zone validity. However, the TRZ permits exactly ONE test: any second penetration or close beyond the far edge permanently invalidates the setup.

**TARGET / TRAILING STOP PLAN:**

**RULE 092-POINT D AND TRIGGER LEVEL:** Label the swing made into the TRZ D. Calculate the 1.272 extension of C:D; it is the trigger for the trailing-stop plan, not a fixed exit.

**RULE 093-TRAIL ACTIVATION:** When price reaches the 1.272 extension of C:D:
- Half 1: immediately trail stop to the higher of the prior completed candle's low or entry price (shorts: lower of prior candle high or entry).
- Half 2: trail stop to Breakeven plus cost buffer (RULE 055).

**RULE 094-HALF 1 TRAIL:** Following trail activation (RULE 093), each time a new swing high prints on a completed candle, trail Half 1's stop to the low of the prior completed candle (shorts: on each new swing low, trail stop to the high of the prior completed candle). The stop moves only in the direction of the trade on confirmed new extremes.

**RULE 095-HALF 1 TRAIL VARIANT:** VARIANT A (Canonical Rule 094): completed bar-low trailing. In fast parabolic climax moves where ADX(14) > 40, traders may optionally tighten Half 1's stop to the low of the current active bar once it closes, but NEVER to the prior bar's high on long positions.

**RULE 096-HALF 2 TRAIL:** After Half 1 is stopped out, trail Half 2's stop to successive higher swing lows (shorts: lower swing highs). This stop is discretionary: give the trade room to absorb volatility, but never let a winner turn into a loss.

**RULE 097-TRAIL PLAN PURPOSE:** The TRZ management plan systematically shifts risk: initial risk is full zone width; once 1.272 is tagged, stops shift to protect capital and lock partial gains on Half 1, while Half 2 is trailed to capture extended trends. Prior to 1.272 activation, full initial risk applies.

**RULE 098-BROKEN TRZ:** When price closes through the TRZ far edge by > 0.5 × ATR(14), the zone is broken. Do not fade the break. The setup is invalidated; any momentum continuation must be evaluated strictly under Module 12 criteria.

**PROBABILITY:** not quantified.

**SKIP THREE-RATIO ZONE WHEN:**
- The 0.786 of B:C falls outside the 0.500–0.618 band of A:C with no symmetry support (RULE 083, RULE 084).
- Price tests or breaks through the zone a second time (RULE 091).
- No confirmed entry trigger forms after zone touch (RULE 088, RULE 187).

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

**RULE 102-TLP VISUAL TEST:** Bar counts of legs A:B and C:D need not be identical, but the ratio of their durations (Duration(C:D) / Duration(A:B)) must fall within the range 0.50 to 2.50. A pair exceeding 2.50 or below 0.50 is structurally mismatched and invalid.

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

**RULE 104-AB=CD POINT C LIMIT:** Point C must retrace between 0.382 and 0.786 of leg A:B. Under no circumstances may point C trade beyond the origin point A (close beyond A permanently invalidates the pattern).

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

**RULE 110-AB=CD TARGET:** Targets for AB=CD are structured in two stages: First Target = 0.618 retracement of leg C:D (exit 50% and move stop to breakeven + cost); Final Target = 1.272–1.618 extension band of total swing A:D.

**RULE 111-INTERMEDIATE ZONE EXIT:** If an opposing Confluence Zone of ≥ 3 levels sits between entry and the final target band, take 50% partial profit upon testing that zone and trail remaining stop to breakeven + cost.

**RULE 112-TARGET DOUBLE BOTTOM WARNING:** A double bottom (shorts) or double top (longs) forming at the 1.272 extension is a warning to take profits.

**PROBABILITY:** not quantified.

**SKIP AB=CD TLP WHEN:**
- Point C trades beyond origin point A (RULE 104).
- Price fails to trade decisively beyond point B (RULE 105).
- The symmetry level falls outside any valid Confluence Zone (RULE 107).
- Step duration ratio is outside 0.50–2.50 or price equality variance exceeds 12.0% (RULE 102).

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

**RULE 115-GARTLEY POINT B:** Point B must terminate within the 0.382 to 0.618 retracement band of leg X:A. Swings with B terminating between 0.500 and 0.618 are fully valid standard Protocol Gartley setups.

**RULE 116-GARTLEY POINT C:** For both bullish and bearish Gartley setups, point C must terminate within the 0.382 to 0.786 retracement band of leg A:B. Hard limit: point C must never exceed extreme point A.

**RULE 117-GARTLEY COMPLETION:** After C, price must trade beyond B into the 0.618 to 0.786 retracement of X:A. Arrival in that band completes the pattern as point D.

**RULE 118-GARTLEY D CONFLUENCE:** D is stronger when it also equals a 1.272 or 1.618 extension of B:C.

**RULE 119-GARTLEY CONFLUENCE ZONE REQUIRED:** Trade only when at least 3 Fibonacci levels form a Confluence Zone around the completion level.

**RULE 120-GARTLEY DEPTH:** The pattern is officially complete when price enters the 0.618 to 0.786 retracement zone of X:A. Waiting for a completed candle trigger (RULE 121) within this band ensures execution occurs with structural confirmation and tighter stop distance.

### How to Trade the Gartley TLP

**ENTRY CONDITIONS:**
- RULE 112 to RULE 118 met.
- An entry pattern forms in the completion Confluence Zone.

**RULE 121-GARTLEY ENTRY:** Default trigger: buy when price exceeds the prior bar's high after completion (bearish: sell when price undercuts the prior bar's low).

**STOP PLACEMENT:**

**RULE 122-GARTLEY STOP:** Initial stop just beyond the completion Confluence Zone: below the Support Confluence Zone for longs, above the Resistance Confluence Zone for shorts.

**TARGET:**

**RULE 123-GARTLEY FIRST TARGET:** The first objective is the first major opposing Confluence Zone, preferably the one that contains the B:C symmetry level. After price touches that zone, exit half when price undercuts the prior bar's low (shorts: above the prior bar's high); then move the stop to breakeven.

**RULE 124-GARTLEY FINAL TARGET:** Final target is the 1.272 to 1.618 extension band of swing A:D. Upon price reaching the 1.272 extension, trail the stop on the remainder to the low of each prior completed candle (shorts: prior candle high) until stopped out or 1.618 is reached.

**RULE 125-GARTLEY TIMEFRAMES:** The pattern works from 5-minute to monthly charts. Choose the time frame by the point risk the money-management plan allows per trade.

**RULE 126-OWN THE STOP METHOD:** The canonical stop placement for all Gartley setups is RULE 122 (beyond the completion Confluence Zone by 0.25 × ATR(14) + 2 ticks). For SLM execution, this is the sole permissible automated stop method.

**PROBABILITY:** not quantified.

**SKIP GARTLEY TLP WHEN:**
- Price breaks X, or breaks A before D (RULE 113, RULE 114).
- B lies outside 0.382–0.618 of X:A (RULE 115).
- C exceeds A or falls outside 0.382–0.786 of A:B (RULE 116).
- D does not reach the 0.618–0.786 band of X:A (RULE 117).
- Fewer than 3 levels form a zone at completion (RULE 119).

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

**RULE 129-BUTTERFLY POINT B:** Point B must terminate within the mandatory valid band of 0.382 to 0.786 retracement of leg X:A. Hard invalidation: point B must never close beyond origin point X.

**RULE 130-BUTTERFLY POINT C:** Point C must terminate within the mandatory valid band of 0.382 to 0.786 retracement of leg A:B. Hard invalidation: point C must never trade beyond extreme point A (close beyond A permanently voids pattern).

**RULE 131-BUTTERFLY COMPLETION:** After point C forms and price breaks beyond B, point D must decisively extend beyond extreme X into the 1.272 to 1.618 extension band of leg X:A.

**RULE 132-BUTTERFLY CONFLUENCE & PRIORITY:** When leg C:D equals A:B within ± 12% and D completes in the 1.272–1.618 band beyond X, the structure qualifies as both an AB=CD and a Butterfly TLP. In this case, classify the setup primarily as a Butterfly TLP (due to the higher-order structural extension beyond X) and execute using Butterfly stop and target parameters.

**RULE 133-BUTTERFLY GEOMETRY & DURATION:** Duration ratio Duration(C:D) / Duration(X:A) must strictly fall between 0.50 and 2.50. Swings outside this duration range are invalid.

### How to Trade the Butterfly TLP

**ENTRY CONDITIONS:**
- All conditions in RULE 127 through RULE 133 strictly met.
- Price reaches the 1.272–1.618 extension band inside a qualified Confluence Zone of ≥ 3 distinct levels (RULE 033).
- Completed trigger candle forms (RULE 134, RULE 187, RULE 202).

**RULE 134-BUTTERFLY TRIGGER REQUIRED:** Do not enter on the bare touch of the 1.272 extension. Entry requires a completed trigger candle (RULE 187/RULE 202) reversing from the 1.272–1.618 completion zone.

**RULE 135-TOUCH ENTRY VARIANT:** Entering at the 1.272 touch without confirmation is classified as an Out-of-System Discretionary Variant and is forbidden in automated SLM execution.

**STOP PLACEMENT:**

**RULE 136-BUTTERFLY STOP:** Initial stop just beyond the completion Confluence Zone (longs: below the Support Confluence Zone; shorts: above the Resistance Confluence Zone).

**TARGET:**

**RULE 137-BUTTERFLY OPPOSING ZONE:** Once D is confirmed, immediately calculate the opposing Confluence Zone levels that mark the next decision points.

**RULE 138-BUTTERFLY FIRST TARGET:** First Target is the 0.618 retracement of swing C:D. Exit 50% of the position and move the stop on the remainder to Breakeven + cost buffer (RULE 055).

**RULE 139-BUTTERFLY FINAL TARGET:** Final target is the 1.272 to 1.618 extension band of total swing A:D. Upon reaching 1.272, trail the stop to the prior completed candle extreme on each new high/low until closed.

**RULE 140-BUTTERFLY RUNNER:** Optional: once the final zone is hit, trail the stop to the prior bar's extreme (shorts: prior bar's high) on each new extreme to ride a larger move.

**RULE 141-TWO-STAGE EXIT PRINCIPLE:** All TLP setups (AB=CD, Gartley, Butterfly) adhere strictly to two-stage exit management: exit 50% at First Target (0.618 of the final leg), move stop to breakeven + cost, and trail the remaining 50% toward the 1.272–1.618 final extension band.

**RULE 142-HTF CONTEXT CHECK:** When a higher-time-frame chart shows a major peak or trough forming, drill down to the daily chart to look for a Butterfly TLP against a Confluence Zone at that point.

**PROBABILITY:** not quantified.

**SKIP BUTTERFLY TLP WHEN:**
- B goes beyond X (RULE 129).
- C goes beyond A (RULE 130).
- D does not go beyond X or misses the 1.272–1.618 band of X:A (RULE 131).
- Geometry duration ratio is outside 0.50–2.50 (RULE 133).
- No confirmed trigger candle forms after completion (RULE 134).
- Fewer than 3 levels form a zone at completion (RULE 119).

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

**RULE 146-FAKE-OUT TREND CONTEXT:** Setups require an established prior trend (at least 2 higher highs/lows for longs; lower lows/highs for shorts) prior to the 200-SMA poke. Filter: 14-period ADX must be ≥ 20.0 and rising (ADX[0] > ADX[1]).

### How to Trade 200-SMA Fake-Out

**ENTRY CONDITIONS:**
- RULE 142 to RULE 144 met.
- An entry trigger forms.

**RULE 147-FAKE-OUT ENTRY & CONFIRMATION OVERRIDE:** Entry confirmation requires a two-step sequence:
1. Pattern & Zone Completion: Price completes point D of a TLP at a Confluence Zone beyond the 200-day SMA (above 200-SMA for shorts; below for longs).
2. SMA Cross Back Confirmation: A candle decisively CLOSES back across the 200-day SMA in the reversal direction (close below 200-SMA for shorts; close above for longs).
3. Maximum Distance from Zone: The candle close back across the 200-SMA serves as an explicit, rule-governed override to the generic zone-proximity requirement of RULE 046, provided that the closing price is no further than 2.0 × ATR(14) from the Confluence Zone far edge. If price has traveled > 2.0 × ATR(14) away from the zone before closing across the SMA, the entry is stale and must be rejected.

**STOP PLACEMENT:**

**RULE 148-FAKE-OUT STOP:** Initial stop just above the Resistance Confluence Zone (longs: just below the Support Confluence Zone).

**RULE 149-FAKE-OUT WIDE ZONE SIZING:** When the stop-to-entry distance is large (e.g., about 15% of price), reduce position size to keep risk within money-management limits.

**TARGET:**

**RULE 150-FAKE-OUT FIRST TARGET:** Take profit on half at the 0.500-0.618 retracement of A:D, then trail the stop to a recent swing point (swing high for shorts, swing low for longs); breakeven is the ideal minimum.

**RULE 151-FAKE-OUT FINAL TARGET:** The second objective is the 1.272 extension of A:D. Do not exit at the touch; trail the stop to the prior bar's extreme (shorts: prior bar's high; longs: prior bar's low) and keep trailing on each new extreme until stopped out.

**RULE 152-FAKE-OUT TIMEFRAME:** Canonical setup operates on Daily charts using the 200-day SMA (Weekly equivalent: 40-period SMA). On intraday charts (60m / 4h), a 200-period SMA fake-out is permissible ONLY IF the Confluence Zone holds ≥ 4 levels and pre-trade R:R ≥ 2.0.

**RULE 153-FAKE-OUT SCAN:** Scan for liquid stocks (volume) trading near their 200-day SMA, build a watch list, and wait for a TLP to form.

**PROBABILITY:** not quantified.

**SKIP 200-SMA FAKE-OUT WHEN:**
- No completed TLP (RULE 143).
- Fewer than 3 levels at D (RULE 144).
- D does not finish on the far side of the 200-day SMA (RULE 145).
- The market is choppy, or ADX(14) is below 20 or falling (RULE 146).
- Price fails to close back across the 200-SMA (RULE 147).
- Applied to an intraday chart without meeting Rule 152 qualifications.

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

**RULE 155-TRAP 786 DECISION:** As price returns toward extreme A, the 0.786 retracement of A:B is the decision level. A confirmed break of the 0.786 projects an impulse run through extreme A into the 1.272–1.618 extension band of A:B.

**RULE 156-TRAP MOMENTUM OPTION:** Trading the breakout of the 0.786 retracement toward the extension is classified as an Out-of-System Breakout Variant. Automated SLM engines must ignore this breakout and focus strictly on the canonical Extension Trap reversal at point C.

**RULE 157-TRAP COMPLETION:** The setup completes when price penetrates past extreme point A and reaches the 1.272 to 1.618 extension band of swing A:B (trading 27.2% to 61.8% of swing range beyond point A); label this trap extreme point C.

**RULE 158-TRAP ZONE QUALITY:** Priority is given to completion zones holding ≥ 3 distinct Fibonacci extension levels from multiple swings. High density indicates major institutional exhaustion.

### How to Trade the Extension Trap

**ENTRY CONDITIONS:**
- RULE 153 to RULE 156 met.
- A trigger bar forms after the extension zone is hit.

**RULE 159-TRAP ENTRY:** Go long on the first bar that trades above the prior bar's high after price hits the extension band (shorts: the first bar below the prior bar's low).

**STOP PLACEMENT:**

**RULE 160-TRAP STOP:** Place initial protective stop beyond the 1.618 extension of A:B (or the far edge of the Confluence Zone, whichever is furthest) plus an ATR buffer: Stop Price = Level ± (0.25 × ATR(14) + 2 ticks).

**RULE 161-TRAP TIGHT STOP:** For tighter risk control, the stop may be placed beyond the verified extreme point C with a strict buffer: Stop Price = Extreme C ± (0.25 × ATR(14) + 2 ticks). If this buffered stop is closer than 1.0 × ATR(14) to entry, it is too tight for market noise and must be rejected.

**TARGET:**

**RULE 162-TRAP FIRST TARGET:** Exit half at the 0.500-0.618 retracement of B:C. On intraday charts, optionally skip this partial exit and hold for the 1.272.

**RULE 163-TRAP FINAL TARGET:** Second target: B:C's 1.272 extension. When price reaches it, trail the stop on the remainder to the prior bar's low (shorts: prior bar's high) on each new extreme.

**PROBABILITY:** not quantified.

**SKIP EXTENSION TRAP WHEN:**
- Price does not break the 0.786 of A:B (RULE 155).
- Price stalls short of the 1.272 extension of A:B (RULE 157).
- No confirmed trigger candle follows the extension touch (RULE 159).

---

## MODULE 12: ZONE-GAP MOMENTUM BREAKOUTS

### Definition: Level-Free Corridor (Zone Gap)

**RULE:** A Zone Gap is a tradable price corridor between two Confluence Zones that contains no qualifying Confluence Zone (no cluster of ≥ 3 distinct levels). Isolated 1 or 2 Fibonacci levels may exist within the corridor and are marked as intermediate friction points. When price decisively closes through the near zone, momentum drives price across the corridor to the far zone.

**CONTEXT:** These are momentum continuation and reversal breakouts: buy the confirmed breakout of a Resistance Confluence Zone, sell the confirmed breakout of a Support Confluence Zone. Breakouts require both low directional trend persistence (ADX ≤ 22) AND volatility compression (measured via ATR or Bollinger Bandwidth) prior to expansion across the corridor.

**RULE 164-ADX & VOLATILITY COMPRESSION:** Standardize breakout market regime indicators:
1. Trend Strength (ADX 14-period): ADX(14) ≤ 22.0 indicates absence of entrenched countertrend momentum, permitting breakout energy to release.
2. Volatility Compression Filter: Breakout qualification requires that ATR(14) on the setup timeframe is at or below its 20-period simple moving average (ATR(14) ≤ SMA(ATR(14), 20)), or Bollinger Bandwidth (20, 2) is compressed in the lower 25th percentile of its 50-bar range. Low ADX indicates directional exhaustion; ATR compression confirms volatility squeeze.

**RULE 165-ZONE GAP ADX SETTING:** Calculate ADX using a standard 14-period lookback with a compression threshold of 22.0.

**RULE 166-CLEAR THE GAP:** A corridor between Confluence Zone #1 and Confluence Zone #2 is verified as a Level-Free Corridor if and only if it contains no cluster of ≥ 3 Fibonacci levels. Any 1 or 2 isolated levels inside the corridor do not invalidate the setup but must be monitored for potential mid-gap hesitation.

**RULE 167-GAP TIMEFRAMES:** Trade Zone-Gap setups on 15-minute to Weekly timeframes (with Daily and 60-minute serving as primary frames; 15-minute is the absolute minimum timeframe). Timeframes below 15-minute are strictly prohibited due to excessive noise and insufficient corridor width.

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

**RULE 171-RGB TRIGGER:** Execution triggers when price closes beyond the far edge of Confluence Zone #1 into the Level-Free Corridor, provided ADX(14) is ≤ 22.0 (indicating the preceding countertrend move has completely exhausted its momentum).

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

**RULE 174-CGB TRIGGER:** Execution triggers when price closes beyond the far edge of Confluence Zone #1 in the direction of the primary trend following a volatility contraction where ADX(14) dipped below 22.0 and has begun turning upward.

**RULE 175-RGB VS CGB:** The prior path of price decides the variant. Coming out of an opposite trend into Confluence Zone #1 = RGB; already trending in the trade direction = CGB.

### How to Trade Zone Gaps (both variants)

**ENTRY EXECUTION GATE:**
- Canonical SLM Entry: Enter on the completed candle close that decisively penetrates beyond the far edge of Confluence Zone #1 into the Level-Free Corridor (by at least 0.10 × ATR(14)).
- Conservative Retest Entry: If the initial breakout candle is extended (> 1.5 × ATR), wait for a retest of the broken zone edge that holds, entering on a completed confirmation candle in the breakout direction.
- Intrabar touch entries without candle close are strictly prohibited in automated execution.

**RULE 176-GAP STOP SELECTION HIERARCHY:** Protective stop placement follows a strict deterministic priority order:
- Primary Canonical Stop (Default for SLM): Beyond the far edge of the broken Confluence Zone #1 plus buffer: Stop Price = Zone #1 Near Edge ∓ (0.25 × ATR(14) + 2 ticks) (below broken zone for longs; above broken zone for shorts).
- Tight Momentum Variant (Permitted ONLY if primary stop violates R:R ≥ 1.50): Placed beyond the extreme of the breakout candle: Stop Price = Low of Breakout Candle − (0.20 × ATR(14) + 2 ticks) for longs; High of Breakout Candle + (0.20 × ATR(14) + 2 ticks) for shorts.
- Arbitrary stops (prior bar low) without structural backing are prohibited.

**RULE 177-ZONE-GAP REWARD-TO-RISK GATE:** For Zone-Gap setups, Potential Reward is the exact distance from entry price to the near edge of Confluence Zone #2; Risk is the distance from entry price to the selected protective stop (RULE 176). The trade is permitted IF AND ONLY IF Net Reward / Net Risk ≥ 1.50 (incorporating estimated slippage and fees). If R:R < 1.50, the trade must be REJECTED. Reducing position size does not alter the R:R ratio and cannot repair an invalid setup.

**RULE 178-POSITION SIZE FORMULA:** Position sizing across all setups is governed by an exact mathematical formula incorporating tick value, contract multipliers, and transaction friction:
- For Equities & Stocks:
  `Shares = floor( Dollar Risk Budget / ((|Entry Price − Stop Price| × 1.0) + Estimated Round-Turn Costs per Share + Slippage Buffer) )`
- For Futures & Commodities (accounting for contract point multiplier and tick value):
  `Stop Distance in Ticks = ceil( |Entry Price − Stop Price| / Minimum Tick Size )`
  `Risk per Contract ($) = (Stop Distance in Ticks × Dollar Value per Tick) + Round-Turn Commission & Exchange Fees ($) + (2 ticks × Dollar Value per Tick slippage)`
  `Contracts = floor( Dollar Risk Budget / Risk per Contract ($) )`
- Currency Conversion: If account equity currency differs from contract quotation currency, convert Dollar Risk Budget into quotation currency at current exchange spot rate prior to calculation.
- Minimum Size Enforcement: If calculated position size is < 1 contract (or < 1 share), NO TRADE is permitted.

**TARGET:**

**RULE 179-GAP TARGET:** The objective is the near edge of Confluence Zone #2.

**RULE 180-GAP HOLD OPTION:** Optional, mainly for CGBs (with-trend): take half off at Confluence Zone #2, move the stop to breakeven on the rest, and hold it for further movement.

**RULE 181-GAP STALL EXIT:** Following breakout entry, if price prints 3 consecutive completed candles that fail to make progress toward Confluence Zone #2 and advance less than 0.25 × ATR(14), execute a market exit to eliminate capital lockup in false breakouts.

**PROBABILITY:** not quantified.

**SKIP ZONE GAPS WHEN:**
- Corridor between zones contains another Confluence Zone (RULE 166).
- ADX(14) is > 22.0 prior to breakout (RULE 171, RULE 174).
- Pre-trade R:R is < 1.50 (RULE 177).
- The chart is below 15-minute or above weekly (RULE 167).

---

## MODULE 13: ENTRY TRIGGERS AND TIMEFRAME DRILL-DOWN

### Definition: Entry Trigger

**RULE:** An entry trigger is price action that confirms a tradable move has started at a setup's zone; a setup only shows a possible move, and a trade is entered only after a trigger completes.

**CONTEXT:** Entering on the setup alone is the most common execution error. The preferred method finds the trigger on a lower time frame than the setup, which gives confirmation with a tighter structural reference.

**RULE 182-CONFIRM THEN ENTER:** Never enter because a setup indicates a possible move; enter only after a trigger confirms it.

**RULE 183-LOWER TIMEFRAME TRIGGER:** After a setup forms at a Confluence Zone, evaluate entry triggers on the corresponding drill-down timeframe:

| Setup Timeframe | Primary Trigger Timeframe | Secondary Trigger Timeframe |
|---|---|---|
| Weekly | Daily | 60-minute |
| Daily | 60-minute | 15-minute |
| 60-minute | 15-minute | 5-minute |
| 30-minute | 5-minute | 3-minute |
| 15-minute | 3-minute | 1-minute |
| 5-minute | 1-minute | Same (5-minute candle close) |

**RULE 184-SAME TIMEFRAME RECONCILIATION:** A candlestick trigger on the setup's own timeframe is valid ONLY when executing with-trend setups (Trend Pullback, CGB) in moderate volatility (ADX(14) ≤ 30). For countertrend setups (Symmetry Reversal, Gartley, Butterfly, Extension Trap, 200-SMA Fake-Out), lower-timeframe drill-down confirmation (RULE 183, RULE 202, RULE 204) is strictly mandatory.

**RULE 185-DRILL DEPTH LIMIT:** Drill down only 1-2 time frames below the setup; triggers taken far below it (e.g., 5-minute for a weekly setup) cause frequent whipsaws.

**RULE 186-HTF AWARENESS:** Evaluate the immediate higher timeframe (HTF) trend. For Trend Pullback and CGB setups, trading directly into an opposing HTF trend is prohibited. For countertrend reversal setups (Symmetry, Gartley, Butterfly, Trap), the trade is permitted if and only if the HTF is currently in an extended pullback toward major HTF support/resistance.

**RULE 187-DEFAULT SIMPLE TRIGGER:** The default entry trigger requires a candle to CLOSE beyond the prior candle's high (for longs) or prior candle's low (for shorts) on the trigger timeframe after touching the Confluence Zone. In fast markets, a stop order placed 1 tick beyond the prior bar's extreme upon candle close is acceptable.

### Trigger Catalog

**RULE 188-TRIGGER FAMILIES:** Valid triggers are restricted to mathematically verifiable patterns:
1. Candlestick patterns (RULE 189 to RULE 201).
2. Micro Two-Leg Patterns on the trigger timeframe (Module 09).
3. Micro Extension Trap on the trigger timeframe (Module 11).
4. Classic double bottom/top with confirmed neckline breakout on trigger timeframe.

### Candlestick Definitions

A white body closes above its open; a black (dark) body closes below its open. Tails (wicks, shadows) mark the period's high and low.

**RULE 189-FOLLOW THROUGH BARS:** Indecision candles (Doji, Spinning Top) and single-bar exhaustion candles (Hanging Man, Shooting Star, Hammer) require at least ONE decisive follow-through candle closing in the trade direction beyond the candle's extreme before entry is triggered.

**RULE 190-DOJI:** A Doji is defined as a candle where |Open − Close| ≤ 0.10 × (High − Low). It represents market equilibrium and requires follow-through confirmation (RULE 189).

**RULE 191-BEARISH ENGULFING:** A small white body followed by a larger black body that contains it. Top reversal; it starts a selloff.

**RULE 192-BULLISH ENGULFING:** A small black body followed by a larger white body that contains it. Bottom reversal; it starts a rally.

**RULE 193-EVENING STAR:** Three-candle top reversal: Candle 1 is a strong bullish body (|Close − Open| ≥ 0.60 × Range); Candle 2 is a small indecision body (|Close − Open| ≤ 0.30 × Range) whose body does not overlap Candle 1's body by more than 20% (on equity daily charts: gaps above; in 24-hour electronic futures: highs probe higher with small non-overlapping body); Candle 3 is a strong bearish candle closing at least 50% into Candle 1's body.

**RULE 194-MORNING STAR:** Three-candle bottom reversal: Candle 1 is a strong bearish body (|Close − Open| ≥ 0.60 × Range); Candle 2 is a small indecision body (|Close − Open| ≤ 0.30 × Range) with minimal body overlap; Candle 3 is a strong bullish candle closing at least 50% into Candle 1's body.

**RULE 195-HANGING MAN / HAMMER:** Small body (|Open − Close| ≤ 0.35 × Range) near one end of the candle, with a tail at least 2 × body length and little/no opposing tail. Bearish Hanging Man appears in uptrends; Bullish Hammer appears in downtrends at support.

**RULE 196-SHOOTING STAR / INVERTED HAMMER:** Small body (|Open − Close| ≤ 0.35 × Range) near the bottom (Shooting Star in uptrends, bearish) or near the top (Inverted Hammer at support, bullish), with an upper shadow at least 2 × body length.

**RULE 197-MORNING DOJI STAR:** Identical to Morning Star (RULE 194), with Candle 2 strictly satisfying the Doji body threshold: |Close − Open| ≤ 0.10 × Range.

**RULE 198-EVENING DOJI STAR:** Identical to Evening Star (RULE 193), with Candle 2 strictly satisfying the Doji body threshold: |Close − Open| ≤ 0.10 × Range.

**RULE 199-TWEEZER BOTTOM:** Two consecutive candles whose lows match within ≤ 0.10 × ATR(14) (or ≤ 2 ticks), where the second candle closes bullishly off the level.

**RULE 200-TWEEZER TOP:** Two consecutive candles whose highs match within ≤ 0.10 × ATR(14) (or ≤ 2 ticks), where the second candle closes bearishly off the level.

**RULE 201-THREE METHODS CONTINUATION:** Five-candle continuation pattern: Candle 1 is a long impulse body in trend direction (|Close − Open| ≥ 0.65 × Range); Candles 2, 3, and 4 are small countertrend bodies (|Close − Open| ≤ 0.35 × Range) completely contained within Candle 1's high-low range; Candle 5 is a strong impulse candle closing decisively beyond Candle 1's extreme in the primary trend direction.

### How to Apply Triggers

**RULE 202-TRIGGER PROCEDURE:**
1. Identify the setup and its Confluence Zone on the setup time frame.
2. Drill down 1-2 time frames (RULE 182) around the completion zone.
3. Wait for a candlestick or pattern trigger to complete there.
4. Enter on completion; apply the setup's own stop and targets.

**RULE 203-TRIGGER STACKING:** Two triggers completing together (e.g., a lower-timeframe Extension Trap plus a tweezer bottom and bullish engulfing at its 1.272 extension) give stronger confirmation; either one alone is still a valid trigger.

**RULE 204-AGAINST-TREND CONFIRMATION:** When executing a countertrend setup against an impulse leg where ADX(14) > 30, entry strictly requires a completed trigger on the primary trigger timeframe (RULE 183); same-timeframe aggressive triggers are prohibited.

**SKIP ENTRY WHEN:**
- No trigger pattern has completed (RULE 182, RULE 187, RULE 202).
- The trigger is more than 2 time frames below the setup (RULE 185).
- Higher timeframe structure is in conflicting trend alignment (RULE 186).

---

## MODULE 14: EXECUTION DISCIPLINE AND PORTFOLIO RISK

### Definition: Execution Standard

**RULE:** Performance is measured by flawless execution of every prescribed step and management rule on every trade, never by win rate.

**CONTEXT:** No method is 100% accurate. Traders who chase a perfect win rate change rules after a short losing streak, and losses compound. Consistent results come from strategy + execution + money management + psychology applied together.

**RULE 205-EXECUTION OVER OUTCOME:** Grade each trade on whether every setup, entry, stop, and exit rule was followed exactly; a rule-compliant loss is a correct trade.

**RULE 206-NO RULE CHANGES ON STREAKS:** Maintain disciplined rule execution through normal statistical variance. However, if an account incurs 4 consecutive losses or hits the Daily Max Loss Limit (RULE 216), trading is automatically halted for the remainder of the session.

**RULE 207-EMOTION-PROOF FRAMEWORK:** Execute from pre-defined written rules and checklists so emotional state cannot alter entry, stop, or exit decisions.

**RULE 208-SUCCESS FORMULA:** Trading success = Strategy + Execution + Money Management + Psychology; none is optional.

### Nightly Risk Review

**RULE 209-NIGHTLY REVIEW:** Before every trading session, review all open and planned positions against the exposure and risk limits defined in RULE 210 to RULE 216.

**RULE 210-DIRECTIONAL EXPOSURE:** Net directional delta: Calculate the net delta of all open positions. Total net directional risk in one direction (Long Risk − Short Risk) must not exceed 3.5% of total account equity. In a confirmed market downtrend (Benchmark Index below its 200-SMA), long directional risk is capped at ≤ 2.0%.

**RULE 211-SECTOR EXPOSURE:** Maximum open risk within a single market sector, currency group, or commodity complex must not exceed 3.0% of total account equity.

**RULE 212-RISK PER TRADE:** Maximum risk per trade is strictly capped at 1.0% of total account equity for intraday operations (maximum 1.5% for swing trading on daily charts). Any sizing exceeding 1.5% is prohibited.

**RULE 213-NEWS EXPOSURE & HIGH-IMPACT EVENTS:**
1. Blackout Window: Do not initiate new entries within 15 minutes before or 5 minutes after tier-1 economic announcements (FOMC Rate Decision/Minutes, NFP, CPI, PPI, GDP, or stock corporate earnings).
2. Existing Open Positions: If an open trade cannot have its stop moved to Breakeven + cost buffer (RULE 055) prior to the 15-minute pre-news window, the position must be closed at market prior to the release. Holding open unbuffered risk across tier-1 announcements is strictly prohibited.

**RULE 214-PATTERN EXPOSURE:** When an index and several constituent equities present simultaneous setups, treat them as a single correlated cluster. Maximum allocation to the entire cluster must not exceed 2.0% total account risk.

**RULE 215-TIMEFRAME DIVERSIFICATION:** Maintain awareness of timeframe correlation. An intraday portfolio may trade across approved timeframes (RULE 183), but trades in the same underlying asset must never take contradictory positions simultaneously.

**RULE 216-TOTAL PORTFOLIO RISK & CIRCUIT BREAKERS:** Total aggregate open risk across all simultaneous active positions must never exceed 5.0% of account equity. Mandatory multi-tiered circuit breakers:
1. Daily Max Loss Limit: 3.0% of starting session equity (both realized and unrealized). Once breached, all open orders are canceled, positions closed, and trading halted until the next daily session.
2. Weekly Max Drawdown: 6.0% calculated from the weekly starting equity (or rolling 5-day high-water mark). Once breached, trading is halted for the remainder of the calendar week.
3. Loss Streak Pause: 4 consecutive realized losses within a single session triggers an automated 2-hour cooling-off halt.

**RULE 217-EXECUTION INTEGRITY WITHIN PRESCRIBED LIMITS:** Execute the exact position quantity determined by the mathematical formula in RULE 178. Discretionary position inflation, "sizing up" after winning streaks, or taking "full size" beyond the formulaic output is strictly prohibited.

**SKIP ANY NEW TRADE WHEN:**
- It would push risk per trade above 1.0% intraday / 1.5% swing (RULE 212).
- It exceeds sector/complex limit of 3.0% (RULE 211).
- A tier-1 scheduled news release falls within 15m before or 5m after (RULE 213).
- Total open portfolio risk would exceed 5.0% of account equity (RULE 216).
- Daily Max Loss Limit of 3.0% has been reached for the session (RULE 216).

---

## PRE-TRADE CHECKLISTS

### Pre-Trade Checklist: Confluence Zone Construction (all setups)
- [ ] Current swing point confirmed by completed candle close on each side (RULE 014)
- [ ] Only valid swings used: right-most in consolidations, none invalidated by further extreme (RULE 008, RULE 009, RULE 010, RULE 011)
- [ ] Lookback ≤ 8 swings, otherwise move up a timeframe (RULE 015)
- [ ] Studies run in order: retracements, extensions, projections, expansions last (RULE 034, RULE 031)
- [ ] Violated levels (> 0.25 × ATR close through) deleted (RULE 035)
- [ ] Zone holds 3+ distinct levels from non-collinear swings (RULE 033)
- [ ] Zone width ≤ 1.5 × ATR(14) (and ≤ 3.0% of price for equities) (RULE 038)
- [ ] No trade on the zone alone; completed trigger pattern mandatory (RULE 039, RULE 046)

### Pre-Trade Checklist: Trend Pullback
- [ ] 2+ higher highs and 1+ higher low (shorts mirrored) (RULE 048)
- [ ] Bar touches the Confluence Zone boundary (RULE 050)
- [ ] ADX(14) ≥ 20.0 and rising (ADX[0] > ADX[1]) (RULE 059)
- [ ] Completed entry trigger confirmed (RULE 046, RULE 187)
- [ ] Stop placed beyond zone with 0.25 × ATR(14) + 2 ticks buffer (RULE 051)
- [ ] Pre-trade R:R to First Target ≥ 1.5 (RULE 177)
- [ ] Targets set: 0.500–0.618 for half, 1.272 extension final (RULE 053, RULE 054, RULE 056)
- [ ] Scratch plan active: exit if hovering without progress after 4 candles (RULE 058)

### Pre-Trade Checklist: Symmetry Reversal
- [ ] ADX(8) ≥ 35.0 during swing into C (RULE 066)
- [ ] Point C confirmed after strong momentum impulse (RULE 067)
- [ ] 21-DI agrees with trade direction at C (RULE 068)
- [ ] Prior countertrend swing A:B measured (amplitude ≥ 1.0 × ATR) in points and bars (RULE 069)
- [ ] Symmetry level C ± |A − B| lies inside Confluence Zone within 15% tolerance (RULE 070, RULE 072)
- [ ] Time duration C:D within ± 25% of A:B duration (RULE 073)
- [ ] Entry on completed candle close beyond prior bar extreme (RULE 074)
- [ ] Stop beyond zone + ATR buffer; targets 0.500–0.618 and 1.272 of C:D (RULE 075, RULE 076, RULE 078)

### Pre-Trade Checklist: Three-Ratio Zone (TRZ)
- [ ] Point C confirmed; swings A and B verified (RULE 081, RULE 082)
- [ ] Fixed order strictly valid: 0.500 > 0.786 > 0.618 (longs) (RULE 084)
- [ ] Price touched TRZ on first test only (never tested previously) (RULE 091)
- [ ] Entry on completed candle trigger (RULE 088, RULE 187)
- [ ] Stop placed beyond TRZ 0.618 far edge + ATR buffer (RULE 089)
- [ ] 1.272 extension of C:D designated as trailing activation point (RULE 092)
- [ ] Trailing plan ready: Half 1 to prior bar low; Half 2 to BE + cost (RULE 093, RULE 094, RULE 096)

### Pre-Trade Checklist: AB=CD TLP
- [ ] Swing A:B formed; C stays within 0.382–0.786 of A:B, never beyond A (RULE 103, RULE 104)
- [ ] Price traded beyond point B (RULE 105)
- [ ] Symmetry level C ± |A − B| sits inside Confluence Zone (RULE 106, RULE 107)
- [ ] Duration ratio Duration(C:D) / Duration(A:B) between 0.50 and 2.50 (RULE 102)
- [ ] Completed entry trigger confirmed; stop beyond zone + ATR buffer (RULE 108, RULE 109)
- [ ] Two-stage targets set: 50% at 0.618 C:D, final at 1.272–1.618 A:D (RULE 110, RULE 141)

### Pre-Trade Checklist: Gartley TLP
- [ ] X and A hold as pattern extremes (RULE 113, RULE 114)
- [ ] Point B terminates within 0.382–0.618 of X:A (RULE 115)
- [ ] Point C terminates within 0.382–0.786 of A:B, never beyond A (RULE 116)
- [ ] Point D reaches 0.618–0.786 retracement of X:A (RULE 117)
- [ ] 3+ distinct levels form Confluence Zone at D (RULE 119)
- [ ] Completed trigger candle confirmed; stop beyond zone + ATR buffer (RULE 121, RULE 122)
- [ ] Two-stage targets: 50% at 0.618 C:D / opposing zone; final 1.272–1.618 of A:D (RULE 123, RULE 124, RULE 141)

### Pre-Trade Checklist: Butterfly TLP
- [ ] Point X is second extreme; point A is absolute pattern extreme (RULE 127, RULE 128)
- [ ] Point B within 0.382–0.786 of X:A, never beyond X (RULE 129)
- [ ] Point C never beyond A (RULE 130)
- [ ] Point D decisively extends beyond X into 1.272–1.618 of X:A (RULE 131)
- [ ] Duration ratio Duration(C:D) / Duration(X:A) between 0.50 and 2.50 (RULE 133)
- [ ] 3+ distinct levels form Confluence Zone at D (RULE 119)
- [ ] Completed trigger candle confirmed; bare-touch entry strictly prohibited (RULE 134, RULE 135)
- [ ] Stop beyond zone + ATR buffer; First Target 0.618 C:D; final 1.272–1.618 A:D (RULE 136, RULE 138, RULE 139)

### Pre-Trade Checklist: 200-SMA Fake-Out
- [ ] Daily timeframe (or approved intraday timeframe meeting Rule 152) (RULE 152)
- [ ] Completed TLP pattern (RULE 143)
- [ ] Point D inside Confluence Zone of ≥ 3 levels (RULE 144)
- [ ] Point D completed beyond the 200-SMA (RULE 145)
- [ ] Established prior trend present; ADX(14) ≥ 20.0 and rising (RULE 146)
- [ ] Decisive candle close back across 200-SMA in reversal direction confirmed (RULE 147)
- [ ] Stop beyond zone + ATR buffer; size adjusted for risk budget (RULE 148, RULE 149)
- [ ] Targets: 50% at 0.500–0.618 A:D, trail remainder from 1.272 A:D (RULE 150, RULE 151)

### Pre-Trade Checklist: Extension Trap
- [ ] Swings A and B confirmed with amplitude ≥ 1.0 × ATR (RULE 154)
- [ ] 0.786 retracement of A:B decisively broken (RULE 155)
- [ ] Price reaches 1.272–1.618 extension band of A:B (point C) (RULE 157)
- [ ] Multiple extensions cluster at C (≥ 3 distinct levels) (RULE 158)
- [ ] Completed trigger candle confirmed reversing from point C (RULE 159)
- [ ] Stop placed beyond 1.618 / zone + ATR buffer (RULE 160, RULE 161)
- [ ] Targets: 50% at 0.500–0.618 B:C, trail remainder from 1.272 B:C (RULE 162, RULE 163)

### Pre-Trade Checklist: Zone Gaps (RGB / CGB)
- [ ] Timeframe between 15-minute and weekly (RULE 167)
- [ ] Anchor swing made with ADX(14) ≥ 20.0 (RULE 169, RULE 172)
- [ ] Level-Free Corridor verified between Confluence Zone #1 and Zone #2 (RULE 166, RULE 170, RULE 173)
- [ ] Breakout candle closes beyond Zone #1 with ADX(14) ≤ 22.0 (RULE 171, RULE 174)
- [ ] Pre-trade R:R filter confirmed: Potential Gap Reward / Risk ≥ 1.50 (RULE 177)
- [ ] Position size computed with tick value and commission formula (RULE 178)
- [ ] Target set at near edge of Confluence Zone #2 (RULE 179)
- [ ] Stall exit active: exit if 3 bars show no progress (RULE 181)

### Pre-Trade Checklist: Entry Trigger Gate
- [ ] Setup complete and Confluence Zone tested (RULE 182)
- [ ] Trigger identified on primary/secondary trigger timeframe per table (RULE 183)
- [ ] Higher timeframe alignment confirmed: no conflicting HTF impulse (RULE 186)
- [ ] Verified trigger candle completed: close beyond prior bar extreme or confirmed pattern (RULE 187, RULE 188, RULE 202)
- [ ] Countertrend setups confirm trigger on lower timeframe (RULE 204)
- [ ] All mandatory conditions in the specific setup module and checklist strictly satisfied

### Risk & Trade Management Checklist
- [ ] Pre-trade Net Reward / Risk ≥ 1.50 confirmed (RULE 177)
- [ ] Risk per trade capped at ≤ 1.0% intraday / ≤ 1.5% swing (RULE 212)
- [ ] Position size calculated from exact contract/share formula accounting for tick multiplier and fees (RULE 178)
- [ ] Sector/complex total open risk ≤ 3.0% (RULE 211)
- [ ] Aggregate portfolio open risk ≤ 5.0% across all trades (RULE 216)
- [ ] Daily Max Loss circuit breaker not breached (≤ 3.0% account loss) (RULE 216)
- [ ] No tier-1 news releases within 15m before or 5m after (RULE 213)
- [ ] First Target: exactly 50% exited; stop trailed to Breakeven + cost buffer (RULE 054, RULE 055, RULE 141)
- [ ] Discipline maintained: halt trading after 4 consecutive losses in session (RULE 206)

---
## MASTER DECISION TREE

```
START: Is the current swing point confirmed by completed candle close? (RULE 014)
│
├─ NO → NO TRADE (Wait for confirmation close)
└─ YES → Construct Confluence Zones with distinct anchor studies (RULE 034)
   │
   ├─ Does a valid Confluence Zone exist (≥ 3 distinct levels, width ≤ 1.5 × ATR)? (RULE 033, RULE 038)
   │  ├─ NO → NO TRADE
   │  └─ YES → Determine price structure delivering price to/through zone:
   │
   ├─ STRUCTURE 1: Trend Pullback (2+ HH and 1+ HL, or mirror) (RULE 048)
   │  ├─ ADX(8) ≥ 35.0, DI aligned at C, symmetry projection in zone?
   │  │  └─ YES → SYMMETRY REVERSAL (Verify all Module 07 Checklist items): entry RULE 074, stop RULE 075, targets RULE 076 / RULE 078
   │  ├─ Fixed ratio order strictly valid: 0.500 > 0.786 > 0.618 (first test)? (RULE 084, RULE 091)
   │  │  └─ YES → THREE-RATIO ZONE (Verify all Module 08 Checklist items): entry RULE 088, stop RULE 089, trail plan RULE 092-RULE 096
   │  └─ Standard pullback with ADX(14) ≥ 20.0 and rising? (RULE 059)
   │     ├─ YES → TREND PULLBACK (Verify all Module 06 Checklist items): entry RULE 046/050, stop RULE 051, targets RULE 054 / RULE 056
   │     └─ NO → NO TRADE
   │
   ├─ STRUCTURE 2: Two-Leg Pattern A-B-C-D, C:D beyond B (RULE 099, RULE 102)
   │  ├─ Daily/approved timeframe & D completes beyond 200-SMA with close back across? (RULE 145, RULE 147, RULE 152)
   │  │  └─ YES → 200-SMA FAKE-OUT (Verify all Module 10 Checklist items): entry RULE 147, stop RULE 148, targets RULE 150 / RULE 151
   │  ├─ D beyond X at 1.272-1.618 of X:A? (RULE 131)
   │  │  └─ YES → BUTTERFLY TLP (Verify all Module 09 Checklist items): entry RULE 134, stop RULE 136, targets RULE 138 / RULE 139
   │  ├─ D at 0.618-0.786 of X:A, B at 0.382-0.618? (RULE 115, RULE 117)
   │  │  └─ YES → GARTLEY TLP (Verify all Module 09 Checklist items): entry RULE 121, stop RULE 122, targets RULE 123 / RULE 124
   │  ├─ Leg C:D = A:B within ± 12% and symmetry level in zone? (RULE 102, RULE 106, RULE 107)
   │  │  └─ YES → AB=CD TLP (Verify all Module 09 Checklist items): entry RULE 108, stop RULE 109, targets RULE 110 / RULE 141
   │  └─ None fits → NO TRADE
   │
   ├─ STRUCTURE 3: 0.786 of A:B broken, price reaches 1.272-1.618 of A:B (RULE 155, RULE 157)
   │  └─ → EXTENSION TRAP: entry RULE 159, stop RULE 160 / RULE 161, targets RULE 162 / RULE 163
   │
   ├─ STRUCTURE 4: Level-Free Corridor between two zones, anchor ADX(14) ≥ 20.0 (RULE 166, RULE 169, RULE 172)
   │  ├─ Price closes beyond Zone #1 into corridor with ADX(14) ≤ 22.0? (RULE 171, RULE 174)
   │  │  ├─ Originating from prior countertrend → RGB (RULE 169-RULE 171)
   │  │  └─ Originating from primary resting trend → CGB (RULE 172-RULE 174)
   │  │     → Entry: breakout close; stop RULE 176; target RULE 179
   │  └─ NO breakout close / ADX not compressed → NO TRADE
   │
   └─ No setup structure matches → NO TRADE
      │
      ▼
   TRIGGER GATE (Mandatory for all standard setups; Zone Gaps use breakout close gate)
   ├─ Has a verified entry trigger candle completed on trigger timeframe? (RULE 182, RULE 183, RULE 187, RULE 202)
   │  ├─ NO → NO TRADE (Wait for trigger candle close)
   │  └─ YES → Do all setup-specific checklist conditions pass completely?
   │     ├─ NO → NO TRADE
   │     └─ YES → Does higher timeframe oppose setup alignment? (RULE 186)
   │        ├─ YES → NO TRADE
   │        └─ NO → PRE-TRADE RISK & REWARD GATE
   │           ├─ Does trade meet Universal Net Planned R:R ≥ 1.50? (RULE 047A, RULE 177)
   │           │  ├─ NO → NO TRADE (Do not force poor R:R)
   │           │  └─ YES → PORTFOLIO RISK & SIZING GATE
   │           │     ├─ Trade risk ≤ 1.0% intraday (≤ 1.5% swing), total open risk ≤ 5.0%, daily loss < 3.0%, weekly drawdown < 6.0%? (RULE 212, RULE 216)
   │           │     ├─ Net directional risk ≤ 3.5%, sector risk ≤ 3.0%, cluster risk ≤ 2.0%? (RULE 210, RULE 211, RULE 214)
   │           │     ├─ No tier-1 news release within 15m window? (RULE 213)
   │           │     │  ├─ NO → NO TRADE
   │           │     │  └─ YES → Calculate exact position size via formula (RULE 178) and EXECUTE ORDER
```

---
## PARAMETER TABLE

| Parameter | Value | Rule Reference |
|---|---|---|
| Core ratios | 0.618, 1.618 | RULE 001 |
| Derived ratios | 0.382, 0.500, 0.786, 1.000, 1.272, 2.618 | RULE 002 |
| Retracement ratios | 0.382, 0.500, 0.618, 0.786 | RULE 019 |
| Extension ratios | 1.272, 1.618 (2.618 in range) | RULE 022 |
| Projection / expansion ratios | 0.618, 1.000, 1.618 | RULE 025, RULE 029 |
| Max swing lookback | 8 consecutive confirmed swings | RULE 015 |
| Confluence Zone minimum | 3 distinct levels from ≥ 2 non-collinear swings | RULE 033 |
| Confluence Zone max width | ≤ 1.5 × ATR(14) (stocks: also capped ≤ 3.0% of price) | RULE 038 |
| Trend Pullback structure | 2+ higher highs, 1+ higher low (mirror for shorts) | RULE 048 |
| Trend Pullback ADX filter | 14-period ADX ≥ 20.0, strictly rising | RULE 059 |
| Partial exit size | Exactly 50% of position volume | RULE 054, RULE 123, RULE 150 |
| Symmetry Reversal ADX filter | 8-period ADX ≥ 35.0 during swing into C | RULE 065, RULE 066 |
| Symmetry Reversal DI filter | 21-period DI (+DI > −DI longs; −DI > +DI shorts) | RULE 063, RULE 068 |
| Symmetry price tolerance | Absolute point variance ≤ 15% of prior swing | RULE 072 |
| Symmetry time duration | C:D bar count within ± 25% of A:B bar count | RULE 073 |
| TRZ fixed ratios | 0.500 & 0.618 of A:C, 0.786 of B:C | RULE 083, RULE 084 |
| TRZ test limit | Exactly 1 test permitted; 2nd touch/penetration invalidates | RULE 091 |
| AB=CD duration ratio | Duration(C:D) / Duration(A:B) between 0.50 and 2.50 | RULE 102 |
| AB=CD Point C limit | Retraces 0.382–0.786 of A:B, never beyond A | RULE 104 |
| AB=CD targets | Stage 1: 0.618 of C:D (50%); Stage 2: 1.272–1.618 of A:D | RULE 110, RULE 141 |
| Gartley Point B | 0.382–0.618 of X:A | RULE 115 |
| Gartley Point C | 0.382–0.786 of A:B, never beyond A | RULE 116 |
| Gartley Point D | 0.618–0.786 of X:A | RULE 117 |
| Gartley D confluence | 1.272 or 1.618 extension of B:C | RULE 118 |
| Butterfly Point B | 0.382–0.786 of X:A, never beyond X | RULE 129 |
| Butterfly Point C | 0.382–0.786 of A:B, never beyond A | RULE 130 |
| Butterfly Point D | 1.272–1.618 of X:A, decisively beyond X | RULE 131 |
| Butterfly duration ratio | Duration(C:D) / Duration(X:A) between 0.50 and 2.50 | RULE 133 |
| Butterfly First Target | 0.618 retracement of C:D | RULE 138 |
| Butterfly Final Target | 1.272–1.618 extension band of A:D | RULE 139 |
| 200-SMA Fake-Out average | 200-day SMA (Weekly: 40-period; Intraday: per Rule 152) | RULE 145, RULE 152 |
| 200-SMA Fake-Out trend filter | ADX(14) ≥ 20.0 and rising | RULE 146 |
| 200-SMA Fake-Out entry gate | Decisive candle close back across 200-SMA | RULE 147 |
| Extension Trap decision level | Confirmed break of 0.786 retracement of A:B | RULE 155 |
| Extension Trap completion | 1.272–1.618 extension band of A:B (point C) | RULE 157 |
| Extension Trap zone quality | ≥ 3 distinct extension levels clustering at C | RULE 158 |
| Zone Gap ADX compression | ADX(14) ≤ 22.0 prior to breakout close | RULE 171, RULE 174 |
| Zone Gap timeframe scope | 15-minute to weekly (daily primary) | RULE 167 |
| Pre-trade Min R:R | Potential Reward / Risk ≥ 1.50 (Mandatory gate) | RULE 177 |
| Position sizing inputs | Account risk $, Stop ticks, Tick $ value, Fees | RULE 178 |
| Zone Gap stall exit limit | 3 consecutive completed candles without progress | RULE 181 |
| Trigger drill-down hierarchy | W: D/60m; D: 60m/15m; 60m: 15m/5m; 30m: 5m/3m; 15m: 3m/1m | RULE 183 |
| Reversal candle follow-through | ≥ 1 completed confirming candle closing beyond extreme | RULE 189 |
| Doji body threshold | |Open − Close| ≤ 0.10 × (High − Low) | RULE 190 |
| Max risk per trade | ≤ 1.0% intraday / ≤ 1.5% swing | RULE 212 |
| Max sector / complex risk | ≤ 3.0% of account equity | RULE 211 |
| Max total portfolio risk | ≤ 5.0% aggregate open risk | RULE 216 |
| Daily Max Loss circuit breaker | ≤ 3.0% of account equity (session trading halted) | RULE 216 |
| Loss streak pause | 4 consecutive losses triggers session halt | RULE 206 |

---
## SETUP SUMMARY TABLE

| Setup | Market Context | Trigger Condition | Entry Mechanism | Stop Placement | Target Structure | Sizing & R:R | Invalidation / Skip |
|---|---|---|---|---|---|---|---|
| Trend Pullback | 2+ HH, 1+ HL; ADX(14) ≥ 20 rising | Touch zone + completed trigger | Candle close beyond prior extreme | Zone far edge + 0.25 ATR + 2 ticks | 50% at 0.500-0.618; Final 1.272 ext | Min R:R ≥ 1.50; Size via Rule 178 | Structure broken, ADX < 20, 4-bar hover |
| Symmetry Reversal | ADX(8) ≥ 35; DI aligned at C | Symmetry level in zone ± 15% | Candle close beyond prior extreme | Zone far edge + 0.25 ATR + 2 ticks | 50% at 0.500-0.618; Final 1.272 ext | Min R:R ≥ 1.50; Size via Rule 178 | ADX < 35, DI mismatch, time > 1.5x |
| Three-Ratio Zone | Swings A, B, C; 0.500>0.786>0.618 | First test touch of TRZ | Candle close beyond prior extreme | TRZ far edge + 0.25 ATR + 2 ticks | Trail from 1.272 of C:D (Half 1 bar-low, Half 2 BE) | Min R:R ≥ 1.50; Size via Rule 178 | Wrong order, 2nd touch/penetration |
| AB=CD TLP | A:B formed; C 0.382-0.786; B broken | Symmetry level C ± |A-B| in zone | Candle close beyond prior extreme | Zone far edge + 0.25 ATR + 2 ticks | 50% at 0.618 C:D; Final 1.272-1.618 A:D | Min R:R ≥ 1.50; Size via Rule 178 | C beyond A, duration ratio outside 0.5-2.5 |
| Gartley TLP | X, A extremes; B 0.382-0.618 | D at 0.618-0.786 of X:A in zone | Candle close beyond prior extreme | Zone far edge + 0.25 ATR + 2 ticks | 50% at 0.618 C:D; Final 1.272-1.618 A:D | Min R:R ≥ 1.50; Size via Rule 178 | X or A broken, B/C out of bounds |
| Butterfly TLP | B ≤ 0.786 X:A; C < A; D > X | D at 1.272-1.618 of X:A in zone | Completed trigger candle (no bare touch) | Zone far edge + 0.25 ATR + 2 ticks | 50% at 0.618 C:D; Final 1.272-1.618 A:D | Min R:R ≥ 1.50; Size via Rule 178 | D not beyond X, duration ratio outside 0.5-2.5 |
| 200-SMA Fake-Out | Established trend; ADX(14) ≥ 20 | D beyond 200-SMA in zone | Candle close back across 200-SMA | Zone far edge + 0.25 ATR + 2 ticks | 50% at 0.500-0.618; Trail from 1.272 A:D | Min R:R ≥ 1.50; Size via Rule 178 | No close back across 200-SMA, ADX falling |
| Extension Trap | Swings A:B; 0.786 broken | Point C at 1.272-1.618 of A:B | Completed trigger candle at C | Beyond 1.618 ext + 0.25 ATR + 2 ticks | 50% at 0.500-0.618; Final 1.272 B:C | Min R:R ≥ 1.50; Size via Rule 178 | No 0.786 break, stalls short of 1.272 |
| Zone Gap (RGB/CGB) | Anchor ADX ≥ 20; Level-Free Corridor | Breakout close into corridor | Breakout candle close with ADX ≤ 22 | Zone #1 far edge + 0.25 ATR + 2 ticks | Near edge of Zone #2 (100% exit) | Min R:R ≥ 1.50; Size via Rule 178 | Corridor blocked, ADX > 22, 3-bar stall |

---
## OPERATIONAL DEFINITIONS (FORMALLY RESOLVED FOR SLM DEPLOYMENT)

All operational parameters are strictly bounded by mathematical formulas:
1. **Confluence Zone Width & Clustering:** Sliding window W = 1.0 × ATR(14); zone span bounded strictly between 0.15 × ATR(14) and 1.50 × ATR(14) (stocks: capped ≤ 2.5% of price) (RULE 038).
2. **Protective Stop Placement Buffers:** Canonical formula across all setups is `Stop Price = Structural Far Edge ± (0.25 × ATR(14) + 2 ticks)` (RULE 051, RULE 075, RULE 089, RULE 109, RULE 122, RULE 136, RULE 148, RULE 160, RULE 176).
3. **Breakeven Cost Offset:** `Offset in Points = (Round-Turn Fees / Point Dollar Value) + (2 ticks × Tick Size)` (RULE 055).
4. **Consolidation Anchor Proximity:** Swings within 0.50 × ATR(14) are clustered, selecting right-most pivot (RULE 008, RULE 009).
5. **Swing Amplitude Floor:** Minimum swing amplitude is 1.0 × ATR(14) (RULE 069, RULE 103, RULE 154).
6. **Time Symmetry Tolerance:** Swing duration C:D must fall within ± 25% of swing A:B duration (RULE 073).
7. **AB=CD Leg Equality Tolerance:** Price amplitude |D − C| must match |B − A| within ± 12.0% (RULE 102).
8. **Universal R:R Filter:** Net Planned Reward / Initial Risk must be ≥ 1.50 across all setups (RULE 047A, RULE 177).
9. **Position Sizing Formula:** Exactly calculated using tick value, tick size, and transaction fees (RULE 178).
10. **Timeout Invalidation:** Trend pullbacks must advance within 4 completed candles (RULE 058); Zone Gaps within 3 completed candles (RULE 181).
11. **Empirical Status of Hypotheses:** Explanatory narratives (institutional exhaustion, crowd stops) are classified as operational trading hypotheses, not established physical laws.

---

## RESOLVED CONFLICTS & SLM GOVERNANCE LAWS

1. **Confirmation Law vs Touch Entries (RULE 046 vs 050/135):** RESOLVED. Automated SLM execution strictly mandates completed trigger confirmation on all setups. Blind limit-order touches are designated as Out-of-System variants and prohibited in code.
2. **Trailing Plan Coherence (RULE 094 vs 095):** RESOLVED. Canonical Half 1 trail strictly follows the prior completed candle's LOW (for longs) on each new extreme. Trailing to the prior bar's high on longs is eliminated as a logic defect.
3. **Gartley Point B Range (RULE 115):** RESOLVED. Single authoritative valid band is 0.382 to 0.618 of leg X:A.
4. **TLP Target Architecture (RULE 110, 124, 139, 141):** RESOLVED. All TLPs adhere to a unified two-stage management model: Stage 1 = exit 50% at 0.618 retracement, move stop to Breakeven + cost buffer; Stage 2 = trail remaining 50% into the 1.272–1.618 final extension band.
5. **200-SMA Entry Confirmation (RULE 147):** RESOLVED. Requires a decisive completed candle close back across the 200-SMA before reversal entry is permitted.
6. **Pre-Trade Risk-to-Reward (RULE 177):** RESOLVED. Universal gate mandates Net Reward / Risk ≥ 1.50. Reducing position size does not alter R:R and cannot repair an invalid setup.
7. **Position Sizing Multiplier (RULE 178):** RESOLVED. Sizing formula incorporates tick value, tick size, contract multiplier, and round-turn transaction fees.
8. **Incomplete Information / Ambiguity Fallback:** If any required input, indicator, or structural condition is missing or ambiguous, the SLM must return `NO TRADE — INSUFFICIENT DATA`.

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
