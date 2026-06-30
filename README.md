# Round Numbers

Adaptive round-number levels for TradingView.

- Source: <https://github.com/appmux/tradingview-round-numbers>
- TradingView: <https://www.tradingview.com/script/zlY3RolI-Round-Numbers/>

This indicator highlights round, half, and quarter levels around the current price and adjusts spacing automatically across different instrument types, including Forex, crypto, indices, commodities, and stocks.

## What It Does

- Draws round-number levels around the current price
- Draws optional half and quarter levels between majors
- Adapts spacing automatically using a stabilized daily range anchor and decimal-place anchoring
- Supports symbol-based override multipliers for instruments that need custom spacing

## Why It Exists

Round numbers often act as important visual reference points on the chart and are frequently watched by larger market participants. This indicator is built to make those levels easier to see, improve chart readability, and help you stay visually oriented around the current price without cluttering the chart with unnecessary logic.

## Settings

### Round Numbers

- `Visible Levels`: number of levels to draw above and below the current anchor
- `Round / Half / Quarter`: visual style and display toggles

### Overrides

Each override row contains:

- `Multiplier`: scales the base round-number step for matching symbols
- `Symbols`: comma-separated symbol patterns to match against the TradingView ticker

Examples:

- `10` makes spacing `10x` wider
- `0.1` makes spacing `10x` tighter

## Repository Layout

- [indicator](./indicator): Pine Script source
- [CHANGELOG.md](./CHANGELOG.md): notable changes in the standalone release
- [LICENSE](./LICENSE): Mozilla Public License 2.0

## Support

Reach out via X: <https://x.com/pricefirst>

## Acknowledgements

Special thanks to [@appmux](https://x.com/appmux) for their contribution to this project.
