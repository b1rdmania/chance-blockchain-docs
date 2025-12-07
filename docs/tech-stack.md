# Tech Stack

A rollup built for scale, clarity, and long-term neutrality.

## Optimism Superchain Stack

Chance is built on the Optimism Superchain stack.

The Superchain stack is a modular rollup framework that lets many L2s share the same standards, security assumptions, and upgrade path while remaining independent.

Prediction markets need blockspace that is cheap, predictable, and neutral.

They are sensitive to latency, fees, and reorg risk.

The Superchain stack gives Chance a stable EVM environment with consistent behaviour and a shared upgrade pipeline. Improvements made across the Superchain flow to Chance without fragmentation.

Chance becomes part of a wider ecosystem rather than a stranded chain.

## Ethereum Settlement

Ethereum provides the final settlement layer.

Every outcome recorded in `PredictionHub` is protected by Ethereum’s validator set.

Prediction logic cannot rely on a chain where settlement can be censored or reversed.

Ethereum provides the neutrality, credibility, and longevity that a truth engine needs.

A chain built for resolution must sit on the most secure foundation available.

## Data Availability

Chance uses EigenDA and blob-based data availability.

Prediction markets surge around real-world events.

The chain must remain fast and cheap when activity peaks.

Blobs allow large volumes of resolver updates, market creations, and settlement calls without slowing the system or increasing costs.

This keeps Chance stable in volatile periods.

## ETH as Gas

Chance uses ETH as its gas token.

There is no secondary execution token and no hidden rent extraction.

Users pay in the asset they already understand.

Costs stay simple and honest.

## Price Feeds

Automated markets need clean, verifiable data.

Chance integrates Pyth and Redstone for fast price updates.

These feeds support deterministic settlement for crypto, FX, commodities, and index markets.

When a price defines the outcome, the data must be reliable and easy to audit.

Chance uses feeds that meet that standard.

## Keepers

Chance uses a keeper network for automation.

Keepers handle settlement flows, batch operations, and liquidity maintenance.

This reduces the need for manual intervention and removes central chokepoints.

Prediction requires continuity.

Keepers ensure it.

## Indexing Layer

Chance exposes a single, consistent indexing schema through The Graph or Goldsky.

Every market, every resolver action, and every settlement event follows the same structure.

Builders integrate once and can support the entire chain.

Prediction markets cannot function without clear, queryable data.

Chance treats indexing as core infrastructure.

## Modular Resolvers

Resolution logic is modular.

Each resolver is a focused contract that plugs into `PredictionHub` through a standard interface.

Automated feeds, template resolvers, and optimistic flows all use the same pattern.

No monolithic oracle. No single point of failure.

This modularity lets new resolver types be added without touching the core chain.

## FeeRouter

All protocol revenue passes through `FeeRouter`.

Every market settlement triggers the same accounting path.

Stakers, resolver operators, builders, and the treasury see a clear, verifiable flow of fees.

Nothing sits off-chain and nothing is obscured.

## Summary

Chance uses the Optimism Superchain stack because prediction requires stability, clarity, and shared security.

Ethereum provides neutral settlement.

The Superchain stack provides predictable execution and aligned upgrades.

The rest of the system is built around modular, conservative components.

Innovation happens where it should: in resolution, incentives, and market design.

The base layer remains simple and reliable.

Chance is a prediction-native chain built on infrastructure that values public truth over complexity.



