# Trade Log

## Day 0 — EOD Snapshot (pre-launch baseline)
**Portfolio:** $100,000.00 | **Cash:** $100,000.00 (100%) | **Day P&L:** $0 | **Phase P&L:** $0

No positions yet. Bot launches tomorrow. (Alpaca paper account funded at $100k.)
No positions yet. Bot launches tomorrow.

---

### Apr 27 — EOD Snapshot (Day 1, Monday)
**Portfolio:** $100,000.00 | **Cash:** $100,000.00 (100%) | **Day P&L:** $0 (0.00%) | **Phase P&L:** $0 (0.00%)
**Portfolio:** $100,000.00 | **Cash:** $100,000.00 (100%) | **Day P&L:** $0.00 (0.00%) | **Phase P&L:** $0.00 (0.00%)

| Ticker | Shares | Entry | Close | Day Chg | Unrealized P&L | Stop |
|--------|--------|-------|-------|---------|----------------|------|
| —      | —      | —     | —     | —       | —              | —    |

**Notes:** Day 1, first live trading day. Market open but no positions entered — bot is in pre-deployment research phase. Account confirmed active on Alpaca paper trading with $100,000 equity (corrected from $10k placeholder in Day 0 log). Zero trades executed, zero open positions, zero open orders. Tomorrow: conduct pre-market scan, identify 1-2 candidates with strong catalysts and sector momentum, target 75-85% deployment across 3-5 positions within the week.
**Notes:** Day 1 of the challenge. Account confirmed active at $100,000 paper equity (note: TRADE-LOG Day 0 baseline was a pre-funding estimate of $10,000; resetting phase baseline to actual funded equity of $100,000). No positions entered today — no signals met entry criteria. Cash 100% deployed into dry powder. Market scan pending tomorrow pre-market for first entries.

---

### May 01 — EOD Snapshot (Day 5, Friday)
**Portfolio:** $105,528.15 | **Cash:** $42,606.45 (40.4%) | **Day P&L:** +$1,313.42 (+1.26%) | **Phase P&L:** +$5,528.15 (+5.53%)

| Ticker | Shares | Entry    | Close   | Day Chg | Unrealized P&L       | Stop     |
|--------|--------|----------|---------|---------|----------------------|----------|
| AMZN   | 78     | $260.30  | $267.43 | +0.89%  | +$555.92 (+2.74%)    | $245.98 (10% trail) |
| INTC   | 225    | $81.69   | $99.80  | +5.63%  | +$4,074.67 (+22.17%) | $95.11 (5% trail)   |
| TXN    | 70     | $267.28  | $280.10 | -0.35%  | +$897.56 (+4.80%)    | $253.73 (10% trail) |

**Notes:** Strong Friday close led by INTC (+5.63% day, +22.17% from entry) on continued semis momentum. Portfolio up +5.53% phase after just 5 days. INTC stop correctly tightened to 5% trail per strategy rule (+20% threshold). TXN slightly red on the day but thesis intact. Weekly trade cap reached (3/3 — AMZN, INTC, TXN entered this week). Under-deployed at ~60% vs 75-85% target; 2-3 positions available to add Monday. No new trades today. Stops all live as GTC trailing orders.

---

### May 05 — EOD Snapshot (Day 7, Tuesday)
**Portfolio:** $108,375.79 | **Cash:** $42,606.45 (39.3%) | **Day P&L:** +$2,759.16 (+2.61%) | **Phase P&L:** +$8,375.79 (+8.38%)

| Ticker | Shares | Entry    | Close    | Day Chg  | Unrealized P&L        | Stop     |
|--------|--------|----------|----------|----------|-----------------------|----------|
| AMZN   | 78     | $260.30  | $272.53  | +0.18%   | +$953.72 (+4.70%)     | $250.70 (10% trail) |
| INTC   | 225    | $81.69   | $110.77  | +15.65%  | +$6,542.76 (+35.60%)  | $104.96 (5% trail)  |
| TXN    | 70     | $267.28  | $280.00  | -0.32%   | +$890.56 (+4.76%)     | $255.41 (10% trail) |

**Notes:** Exceptional day led by INTC exploding +15.65% on the session, now +35.60% from entry — semis momentum accelerating. Portfolio hit +8.38% phase return by Day 7. AMZN edged up slightly (+0.18%), TXN modestly red (-0.32%) but well above stop. No new trades; weekly cap reset (0/3 this week). Still under-deployed at ~61% vs 75-85% target with cash $42.6K available. INTC 5% trailing stop auto-updated with new HWM at $110.77; watch for continued semis strength. Pre-market scan Wednesday for 2 new entries to close deployment gap.
### May 06 — Midday Scan
**Portfolio:** $108,499.93 | **Cash:** $66,844.78 (61.6%) | **Day P&L:** +$552.83 (+0.51%) | **Phase P&L:** +$8,499.93 (+8.50%)**

#### Trade Exit — INTC (5% trailing stop triggered, automated)
| Field        | Value                                        |
|--------------|----------------------------------------------|
| Shares       | 225                                          |
| Entry        | $81.69                                       |
| Exit         | $107.73 (5% trail, HWM $113.50, filled 14:17 UTC) |
| Realized P&L | **+$5,857.81 (+31.87%)**                    |
| Reason       | 5% trailing stop triggered on pullback       |

INTC ran $81.69 → $113.50 HWM (+38.9%); stops tightened 10%→7%→5% per rules; stopped out on pullback. Exit working as designed.

#### Open Positions (midday)
| Ticker | Shares | Entry   | Now     | Unreal P&L       | Stop                    |
|--------|--------|---------|---------|------------------|-------------------------|
| AMZN   | 78     | $260.30 | $274.86 | +$1,135 (+5.59%) | 10% trail, HWM $278.56  |
| TXN    | 70     | $267.28 | $288.78 | +$1,505 (+8.04%) | 10% trail, HWM $289.95  |

**Actions:**
- Losers: None — both positive, no cuts
- Stop tighten: None — AMZN +5.6%, TXN +8.0% (need +15% threshold)
- Thesis: AMZN intact (AWS momentum); TXN intact (Q1 beat, monitor SVP selling)
- Research: Perplexity unavailable (key not set)
- **Deployment: 38.4% — critically underdeployed. AMD at ~$416 post-earnings; evaluate entry pre-market May 7. Need 2-3 new positions.**

---

### May 07 — EOD Snapshot (Day 9, Thursday)
**Portfolio:** $107,626.34 | **Cash:** $46,097.24 (42.8%) | **Day P&L:** -$928.42 (-0.86%) | **Phase P&L:** +$7,626.34 (+7.63%)

| Ticker | Shares | Entry    | Close   | Day Chg | Unrealized P&L        | Stop     |
|--------|--------|----------|---------|---------|-----------------------|----------|
| AMD    | 50     | $414.95  | $407.50 | -3.30%  | -$372.50 (-1.79%)     | $379.54 (10% trail, HWM $421.71) |
| AMZN   | 78     | $260.30  | $270.95 | -1.47%  | +$830.48 (+4.09%)     | $250.70 (10% trail, HWM $278.56) |
| TXN    | 70     | $267.28  | $286.00 | -1.19%  | +$1,310.56 (+7.01%)   | $263.38 (10% trail, HWM $292.64) |

**Notes:** Down day across the board — AMD entered today at $414.95 (50sh) on post-earnings semis thesis; closed -3.30% at $407.50, now -1.79% from entry, well above -7% manual cut and -10% stop at $379.54. AMZN and TXN both pulled back modestly (-1.47%, -1.19%) but remain well above stops with positive unrealized P&L. Portfolio dipped -0.86% on the day, phase returns eased from 8.38% peak to +7.63%. Trades this week: 1/3 (AMD). Still underdeployed at 57.2% vs 75-85% target; cash $46K available for 1-2 more entries. Pre-market Friday: scan for 1 additional position to close deployment gap. All GTC trailing stops confirmed live.
### May 07 — New Entry: AMD
| Field   | Value                                                   |
|---------|---------------------------------------------------------|
| Symbol  | AMD                                                     |
| Shares  | 50                                                      |
| Entry   | $414.95                                                 |
| Stop    | 10% trailing GTC (HWM $421.71, stop $379.54)           |
| Thesis  | Q1 earnings beat (May 5 after close); semis momentum continuation; pre-planned entry from May 6 scan |
| Week    | 1/3 trades this week                                    |

---

### May 09 — Midday Scan (Saturday — market closed; prices = Friday May 8 close)
**Portfolio:** ~$110,272 | **Cash:** ~$46,097 (41.8%) | **Deployment:** 58.2% | **Phase P&L:** ~+$10,272 (+10.27%)**

#### Open Positions
| Ticker | Shares | Entry   | Fri Close | Unreal P&L       | Stop                            |
|--------|--------|---------|-----------|------------------|---------------------------------|
| AMD    | 50     | $414.95 | $455.19   | +$2,012 (+9.70%) | 10% trail, HWM $456.29, stop $410.66 |
| AMZN   | 78     | $260.30 | $272.68   | +$965 (+4.76%)   | 10% trail, HWM $278.56, stop $250.70 |
| TXN    | 70     | $267.28 | $287.80   | +$1,437 (+7.68%) | 10% trail, HWM $292.64, stop $263.38 |

**Actions:**
- Losers: None — all positions positive. No cuts.
- Stop tighten: None — AMD +9.70%, AMZN +4.76%, TXN +7.68% (all below +15% threshold)
- Thesis: AMD intact (semis momentum, Friday +9.8% session — AMD ran from ~$414 to $455 on day); AMZN intact (AWS); TXN intact but heavy insider selling (CEO + 2 SVPs sold ~$17M combined in May) remains watch risk
- Research: Market closed; no Perplexity (key not set)
- **Deployment: 58.2% — still underdeployed vs 75-85% target. 1-2 positions needed. Pre-market Monday: evaluate new entries.**

---

### May 07 — Midday Scan
**Portfolio:** ~$107,505 | **Cash:** ~$46,097 (42.9%) | **Day P&L:** ~-$995 (-0.92%) | **Phase P&L:** ~+$7,505 (+7.50%)**

#### Open Positions (midday)
| Ticker | Shares | Entry   | Now     | Unreal P&L        | Stop                    |
|--------|--------|---------|---------|-------------------|-------------------------|
| AMD    | 50     | $414.95 | $405.67 | -$464 (-2.24%)    | 10% trail, HWM $421.71  |
| AMZN   | 78     | $260.30 | $272.94 | +$986 (+4.86%)    | 10% trail, HWM $278.56  |
| TXN    | 70     | $267.28 | $283.35 | +$1,125 (+6.01%)  | 10% trail, HWM $292.64  |

**Actions:**
- Losers: None — no position at -7% (AMD -2.24%, within range)
- Stop tighten: None — AMD -2.24%, AMZN +4.86%, TXN +6.01% (all below +15% threshold)
- Thesis: AMD intact (post-earnings semis momentum, stop provides risk control); AMZN intact (AWS); TXN intact (Q1 beat)
- Research: Perplexity unavailable (key not set)
- **Deployment: 57.1% — still below 75-85% target. 2 positions available. Watch for entries.**
### May 07 — New Trade Entry

#### Buy: AMD
| Field        | Value                                                                                        |
|--------------|----------------------------------------------------------------------------------------------|
| Date         | 2026-05-07                                                                                   |
| Ticker       | AMD                                                                                          |
| Side         | BUY                                                                                          |
| Shares       | 50                                                                                           |
| Entry Price  | $414.95                                                                                      |
| Stop Level   | $372.77 (10% trailing, HWM $414.19, order f91d16c7)                                         |
| Thesis       | Q1 earnings beat ($10.25B +38% YoY, Data Center +57%, Q2 guide $11.2B above consensus); post-earnings semiconductor momentum; closes deployment gap |
| Target       | $498 (+20%)                                                                                  |
| R:R          | 2.0:1                                                                                        |
| Week Trades  | 1/3                                                                                          |

#### Portfolio After Trade
**Equity:** ~$108,140 | **Cash:** ~$45,595 | **Deployment:** ~57.8% (↑ from 38.2%)

| Ticker | Shares | Entry    | Now     | Unrealized P&L   | Stop                                 |
|--------|--------|----------|---------|------------------|--------------------------------------|
| AMD    | 50     | $414.95  | $414.28 | -$34 (-0.2%)     | 10% trail, HWM $414.19, stop $372.77 |
| AMZN   | 78     | $260.30  | $274.58 | +$1,114 (+5.5%)  | 10% trail, HWM $278.56, stop $250.70 |
| TXN    | 70     | $267.28  | $285.01 | +$1,241 (+6.6%)  | 10% trail, HWM $292.64, stop $263.38 |

---

### May 08 — EOD Snapshot (Day 10, Friday)
**Portfolio:** $110,271.78 | **Cash:** $46,097.24 (41.8%) | **Day P&L:** +$2,645.44 (+2.46%) | **Phase P&L:** +$10,271.78 (+10.27%)

| Ticker | Shares | Entry    | Close   | Day Chg  | Unrealized P&L        | Stop     |
|--------|--------|----------|---------|----------|-----------------------|----------|
| AMD    | 50     | $414.95  | $455.19 | +11.71%  | +$2,012.00 (+9.70%)   | $410.66 (10% trail, HWM $456.29) |
| AMZN   | 78     | $260.30  | $272.68 | +0.64%   | +$965.42 (+4.76%)     | $250.70 (10% trail, HWM $278.56) |
| TXN    | 70     | $267.28  | $287.80 | +0.63%   | +$1,436.56 (+7.68%)   | $263.38 (10% trail, HWM $292.64) |

**Notes:** Strong Friday — AMD surged +11.71% on broad tech/semis rally, pushing phase P&L through +10% milestone (+10.27%). AMZN and TXN up modestly (+0.64%, +0.63%). AMD HWM moved to $456.29 with stop now at $410.66 (+9.70% from entry, below the +15% tightening threshold). No stop tightening needed on any position yet. Trades this week: 1/3 (AMD May 7). Still underdeployed at 58.2% vs 75-85% target — cash $46K ready for 1-2 new entries. Pre-market Monday: scan for momentum entries to close deployment gap.
### May 11 — New Trade Entry

#### Buy: NVDA
| Field        | Value                                                                                        |
|--------------|----------------------------------------------------------------------------------------------|
| Date         | 2026-05-11                                                                                   |
| Ticker       | NVDA                                                                                         |
| Side         | BUY                                                                                          |
| Shares       | 101                                                                                          |
| Entry Price  | $218.04                                                                                      |
| Stop Level   | $196.30 (10% trailing GTC, HWM $218.11, order 3adf28ac)                                     |
| Thesis       | AI inference demand supercycle (2/3 global AI compute = inference by 2026); Goldman Sachs Buy; datacenter capex cycle intact; semis sector leading |
| Target       | $261.64 (+20%)                                                                               |
| R:R          | 2.0:1                                                                                        |
| Week Trades  | 1/3                                                                                          |

#### Portfolio After Trade
**Equity:** ~$110,881 | **Cash:** ~$24,065 | **Deployment:** ~78.2% (target 75-85% ✓)

| Ticker | Shares | Entry    | Now     | Unrealized P&L    | Stop                                  |
|--------|--------|----------|---------|-------------------|---------------------------------------|
| NVDA   | 101    | $218.04  | $218.14 | +$11 (+0.05%)     | 10% trail, HWM $218.11, stop $196.30  |
| AMD    | 50     | $414.95  | $459.44 | +$2,225 (+10.7%)  | 10% trail, HWM $467.68, stop $420.91  |
| AMZN   | 78     | $260.30  | $274.38 | +$886 (+4.4%)     | 10% trail, HWM $278.56, stop $250.70  |
| TXN    | 70     | $267.28  | $306.45 | +$2,744 (+14.6%)  | 10% trail, HWM $295.90, stop $266.31  |
### May 10 — EOD Snapshot (Day 10, Sunday)
**Portfolio:** $110,271.78 | **Cash:** $46,097.24 (41.8%) | **Day P&L:** +$2,645.44 (+2.46%) [covers May 08 Fri — last trading day; May 08 EOD not captured] | **Phase P&L:** +$10,271.78 (+10.27%)

| Ticker | Shares | Entry    | Close   | Day Chg  | Unrealized P&L        | Stop                                     |
|--------|--------|----------|---------|----------|-----------------------|------------------------------------------|
| AMD    | 50     | $414.95  | $455.19 | +11.72%  | +$2,012.00 (+9.70%)   | 10% trail, HWM $456.29, stop $410.66    |
| AMZN   | 78     | $260.30  | $272.68 | +0.64%   | +$965.42 (+4.76%)     | 10% trail, HWM $278.56, stop $250.70    |
| TXN    | 70     | $267.28  | $287.80 | +0.63%   | +$1,436.56 (+7.68%)   | 10% trail, HWM $292.64, stop $263.38    |

**Notes:** Weekend check-in; May 08 EOD was not captured on Friday. AMD surged +11.72% on Friday May 08 (lifted by semis momentum/macro tailwinds), bringing phase P&L to +10.27%. HWM on AMD updated to $456.29, stop tightened to $410.66 — still below +15% entry-gain threshold so trail remains at 10%. AMZN and TXN modest gains on the week. Portfolio still underdeployed at 58.2% vs 75-85% target; $46K cash available for 1-2 new positions. Trades this week: 1/3 (AMD entered May 07). Pre-market Monday: scan for 1-2 entries to close deployment gap; watch AMD at +15% (+$62.24 from entry, target ~$477) for trail tighten trigger.
### May 08 — EOD Snapshot (Day 10, Friday)
**Portfolio:** $110,128.04 | **Cash:** $46,097.24 (41.9%) | **Day P&L:** +$2,489.74 (+2.31%) | **Phase P&L:** +$10,128.04 (+10.13%)

| Ticker | Shares | Entry    | Close   | Day Chg  | Unrealized P&L         | Stop                                    |
|--------|--------|----------|---------|----------|------------------------|-----------------------------------------|
| AMD    | 50     | $414.95  | $455.11 | +11.42%  | +$2,008.00 (+9.68%)    | $410.66 (10% trail, HWM $456.29)        |
| AMZN   | 78     | $260.30  | $272.45 | +0.47%   | +$947.48 (+4.67%)      | $250.70 (10% trail, HWM $278.56)        |
| TXN    | 70     | $267.28  | $286.06 | +0.29%   | +$1,314.76 (+7.03%)    | $263.38 (10% trail, HWM $292.64)        |

**Notes:** Strong recovery day led by AMD surging +11.42% on continued semiconductor momentum; AMD unrealized P&L flipped from -$372.50 yesterday to +$2,008.00 today with HWM updated to $456.29 and trailing stop now at $410.66. Portfolio crossed +10% phase gain milestone ($110,128). AMZN and TXN both held steady with modest gains (+0.47%, +0.29%). No trades today. 1/3 trades this week (AMD entered Thursday). Deployment still at 58.1% — below 75-85% target; 1-2 new positions needed. Stop tighten watch: AMD needs $477.19 (+15% from entry) to trigger 7% trail. All GTC trailing stops confirmed active.

---

### May 11 — Midday Scan
**Portfolio:** $111,624.47 | **Cash:** $24,075.66 (21.6%) | **Deployment:** 78.4% ✓ | **Day P&L:** +$1,352.69 (+1.23%) | **Phase P&L:** +$11,624.47 (+11.62%)**

#### Open Positions (midday)
| Ticker | Shares | Entry   | Now     | Unreal P&L        | Stop                             |
|--------|--------|---------|---------|-------------------|----------------------------------|
| AMD    | 50     | $414.95 | $465.17 | +$2,511 (+12.10%) | 10% trail, HWM $467.68, stop $420.91 |
| AMZN   | 78     | $260.30 | $272.91 | +$983 (+4.84%)    | 10% trail, HWM $278.56, stop $250.70 |
| NVDA   | 101    | $218.04 | $221.85 | +$385 (+1.75%)    | 10% trail, HWM $222.29, stop $200.06 |
| TXN    | 70     | $267.28 | $294.01 | +$1,871 (+10.00%) | 10% trail, HWM $296.30, stop $266.67 |

**Actions:**
- Losers: None — all 4 positive. No cuts.
- Stop tighten: None — AMD +12.1% (need $477.19 for +15%), TXN +10.0% (need $307.37), AMZN +4.84%, NVDA +1.75%
- Thesis: All 4 intact — semis/AI (AMD, NVDA), AWS (AMZN), analog recovery (TXN)
- Research: Perplexity unavailable (key not set)
- **Deployment: 78.4% — within 75-85% target ✓ (NVDA entry this morning closed the gap)**

---

### May 15 — EOD Snapshot (Day 15, Friday)
**Portfolio:** $109,706.96 | **Cash:** $24,075.66 (21.97%) | **Day P&L:** -$3,078.50 (-2.73%) | **Phase P&L:** +$9,706.96 (+9.71%)

| Ticker | Shares | Entry    | Close    | Day Chg  | Unrealized P&L         | Stop                                      |
|--------|--------|----------|----------|----------|------------------------|-------------------------------------------|
| AMD    | 50     | $414.95  | $423.56  | -5.81%   | +$430.50 (+2.08%)      | 10% trail, HWM $469.21, stop $422.29 ⚠️  |
| AMZN   | 78     | $260.30  | $263.27  | -1.48%   | +$231.44 (+1.14%)      | 10% trail, HWM $278.56, stop $250.70     |
| NVDA   | 101    | $218.04  | $225.16  | -4.49%   | +$719.56 (+3.27%)      | 10% trail, HWM $236.54, stop $212.89     |
| TXN    | 70     | $267.28  | $302.53  | -1.83%   | +$2,467.66 (+13.19%)   | 7% trail, HWM $310.29, stop $288.57      |

**Notes:** Broad red day across semis/tech — AMD -5.81%, NVDA -4.49%, TXN -1.83%, AMZN -1.48%. Day P&L -$3,078.50 (-2.73%) pulls phase gains back to +$9,706.96 (+9.71%). Critical alert: AMD stop at $422.29 with current price $423.56 — only $1.27 cushion (0.3%); AMD is on the verge of being stopped out. TXN stop was tightened to 7% trail (HWM $310.29, stop $288.57) after breaching +15% from entry ($307.37 threshold hit during the week). NVDA still on 10% trail (HWM $236.54, +8.5% from entry). No trades today. 1/3 trades this week (NVDA entered May 11). Portfolio deployment 78.0% (within 75-85% target), but AMD stop-out risk could drop deployment to ~59% if triggered Monday.

---

### May 17 — Midday Scan (Weekend / Market Closed)
**Portfolio:** $109,832.00 | **Cash:** $24,075.66 (21.9%) | **Deployment:** 78.1% ✓ | **Phase P&L:** +$9,832 (+9.83%)**

| Ticker | Shares | Entry    | Price    | Unrealized P&L        | Stop (GTC, live)                         |
|--------|--------|----------|----------|-----------------------|------------------------------------------|
| AMD    | 50     | $414.95  | $424.10  | +$457.50 (+2.21%)     | 10% trail, HWM $469.21, stop $422.29 ⚠️ |
| AMZN   | 78     | $260.30  | $264.14  | +$299.30 (+1.47%)     | 10% trail, HWM $278.56, stop $250.70    |
| NVDA   | 101    | $218.04  | $225.32  | +$735.74 (+3.34%)     | 10% trail, HWM $236.54, stop $212.89    |
| TXN    | 70     | $267.28  | $302.73  | +$2,481.66 (+13.26%)  | 7% trail, HWM $310.29, stop $288.57     |

**Actions:**
- Losers: None — all 4 positive. No cuts.
- Stop tighten: None — TXN +13.26% on 7% trail already; next threshold +20% ($320.74). AMD/AMZN/NVDA below +15%.
- Thesis: All 4 intact — semis/AI (AMD, NVDA), AWS (AMZN), analog recovery (TXN).
- No actions taken — no ClickUp notification sent.

**AMD Watch (Monday open):** Stop $422.29 vs Friday close $424.10 — $1.81 cushion (0.43%). Gap-down risk at open could trigger stop. If stopped out, deployment drops to ~59%; plan 1 new entry to restore 75-85% target.
**TXN next trigger:** $320.74 (+20% from entry) → tighten to 5% trail. Current HWM $310.29; order id 79f4e463.
