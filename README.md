# FDL Pro

By Canto Lab on TradingView.

A from-scratch Pine Script v5 implementation of FDL ema model.

## Disclaimer

I do not recommend trading this strategy as is.

## Why something like this does not work

A win rate quoted from a specific window, especially a trending one, is not a long-term expectation.

Any moving-average pullback system will have stretches where it looks close to unbeatable and stretches where it bleeds slowly, and the second half of that cycle tends to get left out of the marketing.

## Why open source

This should not be a paid product. It's two EMAs, a crossover check, and a distance filter. There is nothing proprietary here. You will loose money trading this.

## Features

- 100/200 EMA crossover detection with pullback entry trigger
- Configurable max distance from EMA100 by symbol (US30, NQ, SPX)
- Optional session-based time filter
- Buy/sell signal plotting with reset logic on opposite crossover

## Installation

1. Open TradingView and go to the Pine Editor.
2. Create a new indicator and paste in the contents of `fdlPro.pine`.
3. Save and add it to your chart.

## License

MIT. Do whatever you want with it
