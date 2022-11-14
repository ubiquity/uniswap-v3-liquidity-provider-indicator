# Uniswap V3 Liquidity Provider TradingView Indicator

This tool helps to guide research of strategies and decision making for active liquidity management in Uniswap V3 by charting positions using TradingView.

As of 14 November 2022, the indicator plots four lines:

![ETHUSDT_2022-11-14_11-48-50](https://user-images.githubusercontent.com/4975670/201571347-63483dd9-7fbb-40cf-8d3f-d8626a26a8b9.png)

1. The bottom of the Uniswap V3 LP position ($1000)
1. The top of the Uniswap V3 LP position ($2000)
1. The breakeven line of the Uniswap V3 LP position (downwards, to the right)
1. The divergence loss line of the Uniswap V3 LP position (upwards, to the right)

Optimally, the liquidity provider should seek to maintain the price of the asset (ETH) inside of all the ranges (above breakeven & bottom of range, and below divergence loss & top of range.) However, depending on your greater asset management strategy, generally it is fine to be anywhere above the breakeven line!
