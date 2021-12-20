# Arbitrage Bots

_Arbitrage bots_ allows you to trade discrepancies in the market, capitalizing on changes in market price between the same pairs. Dipper is a simple Polygon Paraswap stables arbitrage bot. Paraswap is a swap aggregator with support for polygon network. The logic employed in this bot is that each coin added is roughly the same price. When, for example, 1 USDC can be purchased for less than 1 USDT and the bot is also holding USDT, it will attempt to buy USDC. Later when USDT or DAI is worth less than 1 USDC, the bot will sell the USDC to buy them. This bot is also assisted by aave market to ensure that even while no trades are occurring the capital is still at work. In my experience this bot works to provide outstanding yields for amounts less than $10K USD.

{% embed url="https://github.com/NateBrune/Dipper" %}
