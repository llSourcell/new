# Random Number Oracle

This tutorial will introduce you to generating random numbers in Solidity smart contracts using Chainlink VRF ([Verifiable Random Function](https://docs.chain.link/docs/chainlink-vrf/#generate-random-numbers-in-your-smart-contracts)). Chainlink VRF is used as a verifiable source of randomness on-chain. We will be using the Polygon (Matic) Mumbai testnet and the Remix IDE.

Solidity contracts are deterministic, therefore anyone who figures out how your contract produces randomness could predict its results. Chainlink VRF generates a random number off-chain with a cryptographic proof used to verify the result.

Feel free to stock up on test tokens (free) [here ](https://faucet.polygon.technology)before getting started with the tutorial (requires test tokens).

{% embed url="https://learn.figment.io/tutorials/chainlink-vrf-on-polygon" %}
