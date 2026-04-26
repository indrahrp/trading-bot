# Trading Strategy

## Mission
Beat the S&P 500 over the challenge window. Stocks only — no options, ever.

## Capital & Constraints
- Starting capital: ~$10,000
- Platform: Alpaca
- Instruments: Stocks ONLY
- PDT limit: 3 day trades per 5 rolling days (account < $25k)

## Core Rules
1. NO OPTIONS — ever
2. 75-85% deployed
3. 5-6 positions at a time, max 20% each
4. 10% trailing stop on every position as a real GTC order
5. Cut losers at -7% manually
6. Tighten trail: 7% at +15%, 5% at +20%
7. Never within 3% of current price; never move a stop down
8. Max 3 new trades per week
9. Follow sector momentum
10. Exit a sector after 2 consecutive failed trades
11. Patience > activity

## Entry Checklist
- Specific catalyst?
- Sector in momentum?
- Stop level (7-10% below entry)
- Target (min 2:1 R:R)

## Buy-Side Gate (all must pass before any order)
- Total positions after fill <= 6
- Total trades this week <= 3
- Position cost <= 20% of account equity
- Position cost <= available cash
- daytrade_count < 3 (PDT: 3/5 rolling business days)
- Specific catalyst documented in today's research log
- Instrument is a stock (not an option)

## Sell-Side Rules
- Unrealized loss <= -7%: close immediately
- Thesis broken (catalyst invalid, sector rolling over, news event): close even if not at -7%
- Up >= +20%: tighten trailing stop to 5%
- Up >= +15%: tighten trailing stop to 7%
- Sector has 2 consecutive failed trades: exit all positions in that sector

## Order Shapes
```json
// Market buy
{"symbol":"XOM","qty":"12","side":"buy","type":"market","time_in_force":"day"}

// 10% trailing stop (default for every new position)
{"symbol":"XOM","qty":"12","side":"sell","type":"trailing_stop","trail_percent":"10","time_in_force":"gtc"}

// Fixed stop (fallback if PDT blocks trailing stop)
{"symbol":"XOM","qty":"12","side":"sell","type":"stop","stop_price":"140.00","time_in_force":"gtc"}
```

## Alpaca Gotchas
- `trail_percent` and `qty` are strings in JSON, not numbers
- Market data: data.alpaca.markets; trading: api.alpaca.markets
- Quote response: quote.ap = ask, quote.bp = bid
- Trailing stops only work during market hours
- Env var ALPACA_API_KEY → HTTP header APCA-API-KEY-ID (wrapper handles this)
- Timestamps are UTC
