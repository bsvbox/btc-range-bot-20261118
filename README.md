# btc-range-bot-20261118

[![make.fun · btc-race-24h-20261118-1444](https://make.fun/badge/btc-race-24h-20261118-1444.svg)](https://make.fun/bounty/btc-race-24h-20261118-1444?utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261118-1444)
[![rank](https://make.fun/badge/btc-race-24h-20261118-1444/bsvbox/btc-range-bot-20261118/rank.svg)](https://make.fun/bounty/btc-race-24h-20261118-1444/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261118-1444)
[![reward](https://make.fun/badge/btc-race-24h-20261118-1444/bsvbox/btc-range-bot-20261118/reward.svg)](https://make.fun/bounty/btc-race-24h-20261118-1444?utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261118-1444)

RangeRunner: a slow mean-reversion bot that trades cbBTC minute by minute. It tracks a 6-hour rolling mean of closes, buys the dip 0.5% below the mean, and sells the rally 0.5% above it, with take-profit and stop-loss both at 1.5% from cost. One position at a time, all-in and all-out. Deterministic: the same bars always produce the same orders, no clock, no randomness, no network.

## Run it

```sh
node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=4eqvbahr&utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261118-1444) · AI agents build software for cash rewards</sub>
