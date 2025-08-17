TD Sequential - Pine Script Indicator

Overview
Complete implementation of Tom DeMark's TD Sequential indicator for TradingView, featuring both Setup and Bonus phases for precise market timing and trend exhaustion identification.

Features
- Complete TD Sequential Logic: Full implementation following DeMark's official methodology
- Setup Phase (1-9): Identifies trend weakness through 9 consecutive price comparisons vs close[4]
- Bonus Phase (10-13): Extension phase using close[2] for additional confirmation
- Visual Indicators:
  - Small triangles (red for buy signals, green for sell signals)
  - Clear floating numbers for easy identification
  - Clean, professional visualization
- Smart Alerts: Notifications for Setup 9 completion and Bonus 13 signals
- Optimized Performance: Efficient code with proper variable management

How It Works
Setup Phase
- Counts 9 consecutive closes where close < close[4] (buy setup) or close > close[4] (sell setup)
- Displays red triangles below bars for buy signals (1-9)
- Displays green triangles above bars for sell signals (1-9)

Bonus Phase
- Activates after Setup 9 completion
- Uses close[2] comparison for extended counting (10-13)
- Provides additional confirmation of trend exhaustion

Visual Elements
- Red triangles: Buy signals positioned below price bars
- Green triangles: Sell signals positioned above price bars
- Floating numbers: Clear numeric display separated from triangles
- Size optimization: Tiny triangles for clean chart appearance

Installation
1. Copy the Pine Script code
2. Open TradingView Pine Editor
3. Paste the code
4. Save as "TD Sequential"
5. Add to your chart

Usage
- Setup 9: Primary reversal signal - watch for potential trend change
- Bonus 13: Strong exhaustion signal - high probability reversal zone
- Combine with other analysis: Use alongside support/resistance, volume, etc.
- Multiple timeframes: Works on all timeframes

Alerts
- Setup 9 Buy/Sell completion
- Bonus 13 Buy/Sell completion
- Customizable alert messages

Technical Details
- Pine Script Version: 6
- Overlay: True
- Max Labels: 500 (for historical data)
- Lookback Periods: 4 bars (Setup), 2 bars (Bonus)

References
Based on Tom DeMark's Sequential methodology as described in:
- https://demark.com/sequential-indicator/
- Official DeMark studies and publications

License
Open source - feel free to modify and improve

Created by Forte11, inspired by BTC Andres
- Educational implementation of DeMark's methodology
- Follow: x.com/Forte11Cuba x.com/BTCAndres #ZoiTreider
- No financial advice intended

---
This indicator is for educational and analysis purposes only. Not financial advice.
