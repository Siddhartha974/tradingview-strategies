Overview
This strategy uses a fast/slow EMA crossover to capture trending moves, combined with stop-loss and take-profit controls. Position size is calculated as a percentage of account equity for realistic compounding.

How it works
• Long when fast EMA crosses above slow EMA
• Exit on opposite cross or when SL/TP is hit
• Commission and slippage included
• Non-repainting logic (no future data)

Why this strategy can perform well
Trend systems typically have lower win rates but aim to hold winners longer. In backtests on ETERNAL (1H timeframe), returns benefited mainly from a few strong trending periods.

Limitations
• Performs poorly in sideways/choppy markets
• Drawdowns can be significant
• Historical performance does NOT predict future results
• Results change across symbols, timeframes, and parameters

Suggested use
This script is intended for testing, learning, and strategy development. Always forward-test before risking real capital, and never rely on a single indicator to make trading decisions.
