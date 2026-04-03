# Crypto Market Longitudinal Research (2018–2019)

A quantitative research dataset built as the foundation for an algorithmic trading strategy.

## What This Is

Daily snapshots of the **top-150 cryptocurrency assets** by market cap, collected from CoinMarketCap over a 12-month period. Data was captured at consistent intervals to ensure time-series integrity.

This dataset was used to identify structural patterns in crypto market cycles, cross-asset correlations, and momentum signals that informed a risk-neutral trading strategy.

## Key Findings

- Identified recurring liquidity patterns across market cap tiers
- Modeled cross-asset correlation breakdowns during high-volatility regimes
- Built a multi-timeframe analysis toolkit (see `/tools`) for per-coin behavioral analysis

## Usage

1. Download [`CryptoPublic.xlsx`](tools/CryptoPublic.xlsx)
2. In Excel: File → Properties → Unblock (if prompted)
3. Open the `Data` sheet and select a coin
4. Navigate to the `Charts` sheet for visual analysis

Full instructions: [`docs/CryptoPublic.md`](docs/CryptoPublic.md)

## Stack

- Data collection: Python (CoinMarketCap API)
- Analysis: Excel (multi-sheet, dynamic charts)
- Scope: Top-150 assets, daily granularity, 2018–2019

## Context

This research preceded my transition into on-chain forensics and DeFi risk modeling. The same quantitative approach — collecting raw market data, identifying anomalies, and modeling expected value — now applied to blockchain transaction analysis and protocol vulnerability research.
