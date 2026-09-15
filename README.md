# Recovery Risk Ledger

An interactive calculator for recovery-ladder ("martingale") position sizing:
how a losing streak compounds, what a recovery string actually costs, and how
that compares with flat fixed-fractional sizing over the same signal.

**Live:** https://emadhejazian.github.io/sosbot/

## What it shows

- Cumulative loss down a recovery ladder, step by step
- The surplus a winning step actually returns, after spread, slippage and commission
- Recovery sizing vs flat sizing on the same equity curve
- Where a given ladder breaches a drawdown budget

## Notes

Single self-contained HTML file. No build step, no backend, no tracking.

This is an educational risk tool, not trading advice. Recovery ladders do not
create edge — they redistribute it, converting many small wins into a rare large
loss. Size accordingly.
