# Arbitrage Trading Bot
This is an arbitrage trading bot for cryptocurrencies. This <u>smart contract</u> leverages <strong>flashloans</strong> to execute profitable trades on my behalf.

**Demo Sequence:**  
1. deployed solidity smart contracts to the "blockchain" (before video)
2. ran a development framework that emulated a live blockchain (ganache)
3. executed the `bot.js` script that waited for an arbitrage event
4. price differential was manually created using `manipulateprice.js` script
5. gained +0.41 WETH (wrapped ETH), which is roughly $663 USD as of SEP2023

## **Click the thumbnail** to view the demo
[![Arbitrade](/thumbnail.png)](/demo.mp4)

**Note:** Price differential occurs in production environment naturally, as price betweens different markets/exchanges is constantly in flux.