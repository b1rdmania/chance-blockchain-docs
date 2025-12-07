# Stake-to-Create

Builders stake to publish markets.

To create markets, builders post collateral into `MarketStake.sol`.

## Why it exists

It prevents spam, low-quality markets, and malicious actors.

## Staking rules

- Stake can be ETH, stETH, or LST
- A single stake can back many markets

## Slashing conditions

- false outcomes
- abandoned markets
- broken resolvers
- misconfigured oracle parameters

Clean history returns the stake.

Slashed stake → stakers + treasury.

Builders now have skin in the game.
Quality rises. Spam disappears.


