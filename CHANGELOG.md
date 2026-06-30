# Changelog

## 1.0.1

- Stabilized automatic spacing by using a hybrid daily range anchor
- Reduced spacing shifts during quiet market conditions
- Updated drawing logic to run on the last bar only
- Simplified line redraw lifecycle by clearing and redrawing the current level set
- Added a first-bar fallback for line coordinates
- Clarified internal auto-step naming
- Updated public description wording to match the stabilized range logic

## 1.0.0

Initial standalone open-source release of `Round Numbers`.

### Highlights

- Reduced the script to the round-number functionality only
- Reworked automatic spacing so it behaves sensibly across Forex, crypto, indices, commodities, and stocks
- Replaced earlier instrument-specific heuristics with a more generic stabilized daily range approach
- Switched the generic fallback to stabilized daily range anchoring with decimal-place snapping
- Added optional symbol override rows with configurable multipliers
- Simplified settings by removing the old top-level visibility toggle
- Removed the old `Auto/Manual` scale mode and manual global multiplier
- Removed exposed auto-scaling tuning inputs from settings
- Simplified the settings labels around the round-number use case
- Hid override inputs from the indicator header/status line while keeping them available in settings
- Removed the stock-specific contextual step override
- Removed the Forex-specific pip normalization override
- Standardized the script header with license, version, and support metadata

### Notes

- `Version: 1.0.0` marks the first polished standalone public release
- Spacing can still be fine-tuned per symbol using override rows when market convention differs from the generic model
