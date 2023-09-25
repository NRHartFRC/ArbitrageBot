# Arbitrage Trading Bot
This is an arbitrage trading bot for cryptocurrencies. This <u>smart contract</u> leverages <strong>flashloans</strong> to execute profitable trades on my behalf. 💰

Arbi-what? Flash-who? Arbitrage is a condition where an underlying asset is listed for two different prices on two different exchanges. A flashloan is a financial service that allows a user to borrow large amounts of money as long as they are returned in the same transaction.

How? Well the algorithm checks the prices of an ERC-20 token on different exchanges, determines the trade direction, determines profitability, then executes if and when specified conditions are met.

<div align=center><img src="./arbitragealgorithm.png" height="500px" width="350px"></div>

The algorithm, or 'smart contract', is deployed to the blockchain Here, it behaves like a bot on high alert. When the bot discovers arbitrage, it ① buys ERC-20 tokens through Market A (relatively low priced token), the ② bot receives the ERC-20 tokens, then the ③ bot 'swaps' the ERC-20 tokens from Market A for those in Market B (relatively high price), then the bot ④ sells the higher valued tokens for profit!

**Demo Sequence:**  
1. deployed solidity smart contracts to the "blockchain" (before video)
2. ran a development framework that emulated a live blockchain (ganache)
3. executed the `bot.js` script that waited for an arbitrage event
4. price differential was manually created using `manipulateprice.js` script
5. gained +0.41 WETH (wrapped ETH), which is roughly $663 USD as of SEP2023

<p align="center">
  <img src="/thumbnail.png" alt="Arbitrage">
</p>
Tap below to view the video demo!
<div align=center><video src="https://github.com/NRHartFRC/ArbitrageBot/assets/122415724/7d61ccd5-7016-4310-9705-e2483340a684" type="video/mp4"></div>

**Notes:** 
1. Price differential occurs in production environment naturally, as prices across different markets and exchanges are constantly in flux.
2. Code redacted intentionally
