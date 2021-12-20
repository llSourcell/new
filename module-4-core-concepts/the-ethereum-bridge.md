# The Ethereum Bridge

## Ethereum↔Polygon Bridge

Polygon brings you a trustless two-way transaction channel between Polygon and Ethereum by introducing the cross-chain bridge with Plasma and PoS security. With this users can transfer tokens across Polygon without incurring third-party risks and market liquidity limitations. _**The Plasma and PoS Bridge is available on both Mumbai as well as Mainnet.**_

**Polygon bridge provides a scaling solution which is near-instant, low-cost, and quite flexible**. Polygon uses a dual-consensus architecture(Plasma + Proof-of-Stake (PoS) platform) to optimise for speed and decentralisation. We consciously architected the system to support arbitrary state transitions on our sidechains, which are EVM-enabled.

**There is no change to the circulating supply of your token when it crosses the bridge**;

* tokens that leave ethereum network are locked and the same number of tokens are minted on Polygon as a pegged token (1:1).
* To move the tokens back to the ethereum network, tokens are burned on Polygon network and unlocked on ethereum network during the process.

### PoS vs Plasma <a href="#pos-vs-plasma" id="pos-vs-plasma"></a>

|                                    | PoS Bridge(Recommended)                                                                  | Plasma Bridge                                                                                 |
| ---------------------------------- | ---------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| **Short Description**              | DApp Developer's looking for flexibility and faster withdrawals with POS system security | DApp Developer's looking for increased security guarantees with Plasma exit mechanism.        |
| **Structure**                      | Highly flexible                                                                          | Rigid, Less Flexible                                                                          |
| **Deposit(Ethereum → Polygon)**    | 3-5 mins                                                                                 | 3-5 mins                                                                                      |
| **Withdrawal(Polygon → Ethereum)** | 1 checkpoint = \~ 20 mins to 3 hours                                                     | 2 seconds (Challenge Period)                                                                  |
| **Security**                       | Proof-of-Stake system, secured by a robust set of external validators.                   | Polygon’s Plasma contracts piggybacks on Ethereum’s security with 2 seconds challenge period. |
| **Support Standards**              | ETH, ERC20, ERC721, ERC1155 and Others                                                   | Only ETH, ERC20, ERC721                                                                       |

[Edit this page](https://github.com/maticnetwork/matic-docs/tree/master/docs/develop/ethereum-polygon/getting-started.md)\
