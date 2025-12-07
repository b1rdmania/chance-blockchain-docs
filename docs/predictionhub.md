PredictionHub

The canonical resolution engine.

PredictionHub.sol is the core contract of Chance.
It stores outcomes, routes fees, and defines settlement rules.

Key properties:

Single canonical registry

Markets register via a standard interface

Outcomes stored as immutable events

Automated resolution for price-based markets via Pyth / Redstone

Template modules for sports, crypto, macro, news

Optimistic dispute model with bonds and escalation

Batch resolution for high-volume events

FeeRouter triggers on resolution

Full on-chain verifiability

PredictionHub is the “truth layer” for the rollup.


