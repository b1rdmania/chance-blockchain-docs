# Resolution Flows

Clear paths. Final, canonical outcomes.

Chance has three resolution paths.

Each path fits a different type of market, but all roads lead to one endpoint:

**`PredictionHub` writes the final outcome and locks it forever.**

Resolution is not optional.

It cannot drift.

It cannot fork.

It cannot depend on one team.

This is how resolution becomes infrastructure.

## 1. Automated Resolution

Deterministic events. Zero discretion.

This path handles markets where an external data source defines the outcome:

- price feeds (Pyth, Redstone, Chainlink adapters)
- on-chain metrics
- deterministic rules (block height, timestamps, ratios, spreads)

**Flow**

1. Resolver module pulls the feed.
2. Keeper verifies data freshness and threshold conditions.
3. Keeper submits resolution call.
4. `PredictionHub` records the outcome.
5. `FeeRouter` distributes fees.
6. Disputes only occur if data is stale or malformed.

Automated resolution is cheap, fast, and high-volume.

Perfect for crypto, FX, indices, and quant markets.

## 2. Template Resolution

Shared logic for known categories.

Some events repeat across time but require structured human updates:

- sports
- politics
- elections
- macro news
- economic prints
- regulatory outcomes

Template resolvers package the logic:

- input format
- allowed data sources
- dispute windows
- operator stake
- escalation rules
- fallback cases
- canonical interpretation of ambiguous situations

**Flow**

1. Operator submits outcome.
2. Resolver module validates formatting and rules.
3. Dispute window opens (bond required).
4. If challenged, it escalates to a secondary resolver.
5. `PredictionHub` writes the final outcome.
6. `FeeRouter` pays operators and stakers.

Template resolvers handle most real-world markets and eliminate bespoke oracle spaghetti.

## 3. Optimistic Resolution

Open-ended markets. Community-corrected truth.

Used for markets without a clean feed or agreed template:

- quirky cultural events
- bespoke prediction games
- one-off news events
- low-liquidity long-tail markets

**Flow**

1. Anyone proposes an outcome.
2. Bond is posted.
3. Dispute window opens.
4. If unchallenged, it is accepted.
5. If challenged, it escalates to an arbitration resolver.
6. `PredictionHub` stores the final outcome.
7. Bonds are redistributed based on correctness.

Optimistic resolution keeps blockspace open to experimentation without polluting the chain with junk outcomes.

## The Unifying Rule

**Only `PredictionHub` can write the final truth.**

Resolver modules differ, but resolution is unified:

- one registry
- one state machine
- one dispute model
- one canonical outcome per market

`PredictionHub` is the chain’s truth surface.

Everything else is plumbing.

This gives Chance the clarity prediction markets have lacked for years.



