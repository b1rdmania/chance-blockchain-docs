Resolvers & Automation

Modular settlement for every type of market.

Resolver modules plug into PredictionHub via a clean interface.

Operators stake to register resolvers.

Resolvers can be:

Automated

For price-based markets:

Pyth

Redstone

Chainlink adapters

Custom feeds

Keepers trigger settlement.

Template

For sports, politics, macro events:

shared resolver logic

operator updates

dispute paths available

Quirky

Optimistic-mode:

anyone can propose an outcome

dispute window applies

escalates only when challenged

ResolverRegistry.sol holds all resolver modules.

This allows safe extensibility without fragmentation.


