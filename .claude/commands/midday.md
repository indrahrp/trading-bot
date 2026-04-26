---
description: Run midday scan workflow locally (uses local .env)
---

Run the midday scan workflow. Source credentials from local .env.

DATE=$(date +%Y-%m-%d)

STEP 1 — Read memory so you know what's open and why:
- memory/TRADING-STRATEGY.md (exit rules)
- tail of memory/TRADE-LOG.md (entries, original thesis per position, stops)
- today's memory/RESEARCH-LOG.md entry

STEP 2 — Pull current state:
  bash scripts/alpaca.sh positions
  bash scripts/alpaca.sh orders

STEP 3 — Cut losers immediately. For every position where unrealized_plpc <= -0.07:
  bash scripts/alpaca.sh close SYM
  bash scripts/alpaca.sh cancel ORDER_ID
Log the exit to TRADE-LOG: exit price, realized P&L, "cut at -7% per rule".

STEP 4 — Tighten trailing stops on winners. Cancel old stop, place new one:
- Up >= +20% -> trail_percent: "5"
- Up >= +15% -> trail_percent: "7"
Never tighten within 3% of current price. Never move a stop down.

STEP 5 — Thesis check. Cut any position whose thesis broke intraday.

STEP 6 — Optional intraday Perplexity research if something is moving sharply.

STEP 7 — Notification: only if action was taken.
  bash scripts/clickup.sh "<action summary>"
