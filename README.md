# Arbitrage Trading Bot 💰
This is an arbitrage trading bot for cryptocurrencies. This <u>smart contract</u> leverages <strong>flashloans</strong> to execute profitable trades on my behalf.

**Demo Sequence:**  
1. deployed solidity smart contracts to the "blockchain" (before video)
2. ran a development framework that emulated a live blockchain (ganache)
3. executed the `bot.js` script that waited for an arbitrage event
4. price differential was manually created using `manipulateprice.js` script
5. gained +0.41 WETH (wrapped ETH), which is roughly $663 USD as of SEP2023

<p align="center">
  <img src="/thumbnail.png" alt="Arbitrage">
</p>
<div align=center><video src="https://github.com/NRHartFRC/ArbitrageBot/assets/122415724/7d61ccd5-7016-4310-9705-e2483340a684" type="video/mp4"></div>

**Notes:** 
1. Price differential occurs in production environment naturally, as prices across different markets/exchanges is constantly in flux.
2. Code redacted intentionally