# Heyron Day Trading Plan

## My Edge (as an AI)
- No emotional trading (no FOMO, no revenge trading)
- Can process market data 24/7
- Can backtest strategies instantly
- No fatigue from staring at charts

## My Strategy: EMA Momentum Scalping

### Core Setup
- **Timeframe:** 5-minute charts
- **Indicators:**
  - EMA 9 (fast)
  - EMA 20 (medium)  
  - EMA 200 (trend filter)
  - RSI (14) - overbought >70, oversold <30
  - Volume (confirmation)

### Entry Rules (Long)
1. Price above EMA 200 (trend up)
2. EMA 9 crosses above EMA 20 (momentum shift)
3. RSI crossing up through 40-50 (gaining momentum)
4. Volume increasing on breakout
5. Wait for pullback to EMA 20 or EMA 9 for entry

### Entry Rules (Short)
1. Price below EMA 200 (trend down)
2. EMA 9 crosses below EMA 20 (momentum shift)
3. RSI crossing down through 60-50 (losing momentum)
4. Volume increasing on breakdown
5. Wait for rally to EMA 20 or EMA 9 for entry

### Exit Rules
- **Target:** 1.5:1 risk:reward (risk $100, target $150)
- **Stop:** Immediate if price closes below EMA 9 on 5-min
- **Trail:** Move stop to breakeven when up 1:1

---

## Risk Management (Non-Negotiable)

### Position Sizing
- **Max Risk Per Trade:** 1% of account
- **Max Daily Loss:** 3% of account (stop trading for the day)
- **Max Trades Per Day:*6 (quality over quantity)

### Example (if $10k account)
- Risk per trade: $100
- Stop loss: $100
- Target: $150
- Position size: Calculate based on stop distance

--

## Trade Setup Process

1. **Pre-Market (30 min):**
   - Scan for stocks with gap >2% 
   - Check news catalysts
   - Identify watchlist (10-15 stocks)

2. **Market Open (first 30 min):**
   - Watch for opening range breakouts
   - Look for volume confirmation
   - Only trade highest volume stocks

3. **During Day:**
   - Monitor existing positions
   - Look for new setups per EMA rules
   - No new trades after 2pm ET (liquidity dries up)

4. **Post-Market:**
   - Log all trades (what worked, what didn't)
   - Backtest at least 3 setups
   - Update watchlist for tomorrow

---

## What's Needed for Paper Trading

1. **Broker Account:** You'll need to open this (I can't)
2. **API Access:** For real-time data (Polygon.io, Alpaca, etc.)
3. **Paper Trading:** Most brokers offer this free

### Recommended Brokers for Paper Trading:
- **Webull** - Free paper trading, good charts
- **TradingView** - Great charts, paper trading via brokers
- **Alpaca** - API for automated trading

---

## Current Status
- [ ] Research complete
- [ ] Strategy defined
- [ ] Risk rules set
- [ ] Paper account needed
- [ ] First trade (paper)

---

*Plan last updated: 2026-04-07
}