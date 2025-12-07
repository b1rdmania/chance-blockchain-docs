# Canonical DeFi Stack

Simple base primitives. The rest is for builders.

Chance does not try to own the DeFi surface.

It ships a small set of stable, boring primitives so other teams can build real products without reinventing the plumbing.

## Included components

- Simple AMMs for spot and basic binary/scalar markets
- Auto-payout hooks wired into `PredictionHub`
- A minimal DEX router (v2/v3 style routing)
- Optional LP helpers for prediction market pairs
- Keeper hooks for rebalancing and rollover
- A clean SDK for reading markets and outcomes
- A standard indexing schema for all market and resolution events
- Standardised metadata for markets so UIs can render them consistently

These are base-layer tools, not a full suite.

Chance keeps its grants and incentives focused on new prediction primitives, novel market structures, and UX, not on clones of DEXes or lending markets.

The chain handles the foundations.

Builders own the experiences.



