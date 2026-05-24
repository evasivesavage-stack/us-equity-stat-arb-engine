# Forward Execution Logging Plan - US Equity Statistical Arbitrage Engine

The forward phase is meant to review execution behavior. It is not presented as a guarantee of future returns.

## What Will Be Tracked

- Signals generated
- Entry/exit timestamps
- Expected versus executed or estimated prices
- Bid/ask spread behavior where available
- Slippage estimates
- Rejected, missed, or delayed orders
- Daily PnL behavior
- Risk-control triggers

## What Clean Logs Should Show

- Signals fire as expected
- Fills or estimated fills remain close to tested assumptions
- Slippage and spread costs stay within acceptable limits
- Risk controls trigger correctly
- Logs are consistent enough to support a controlled deployment review
