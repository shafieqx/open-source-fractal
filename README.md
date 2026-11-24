# ShafieqX Fractal Model

Pine Script v6 Fractal Model indicator for TradingView (C2 sweep, CISD, setup box).

Forked from [cantolab/open-source-fractal](https://github.com/cantolab/open-source-fractal) and rebuilt as an MVP under the ShafieqX project. Original work is MIT-licensed by cantolab; attribution retained in `LICENSE`.

The Fractal Model concept is based on publicly taught methodology (e.g. ttrades / toodegrees). This script is independent study tooling — not financial advice.

## Disclaimer

Do not trade this as a standalone strategy. C2 / CISD setups are structural annotations, not a proven edge.

## MVP features

- Auto, preset, or custom LTF–HTF fractal alignment
- Chart timeframe validity check
- HTF C2 buy/sell detection (sweep + reclaim)
- CISD level with confirmed-close confirmation
- C3 setup box and basic invalidation
- Bias filter (Neutral / Bullish / Bearish)
- Alerts for C2 formed and CISD confirmed

Not in MVP (later): early CISD history, std-dev projections, HTF candle preview, dashboard polish, SMT.

## Installation

1. Open TradingView → Pine Editor.
2. Paste the contents of `ShafieqXFractalModel.pine`.
3. Save and add the indicator to your chart.

## License

MIT. See `LICENSE` (copyright cantolab; this fork may add ShafieqX modifications under the same terms).
