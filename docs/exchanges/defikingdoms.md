# `defi kingdoms`

## 📁 Connector Info

* Type: SPOT AMM DEX
* Folder: [/gateway/src/connectors/defikingdoms](https://github.com/hummingbot/hummingbot/tree/master/gateway/src/connectors/defikingdoms)
* Maintainer:

## 🏆 Exchange Tier

![](https://img.shields.io/static/v1?label=Hummingbot&message=BRONZE&color=green)

Bronze exchange connectors have passed the Minimum Voting Power Threshold in the latest Poll and are included in each monthly release. They are not maintained by Hummingbot Foundation but may be maintained by a community member.

## ℹ️ Exchange Info

* Website: <https://defikingdoms.com/>
* CoinMarketCap: <https://coinmarketcap.com/currencies/defi-kingdoms/>
* CoinGecko: <https://www.coingecko.com/en/coins/defi-kingdoms>
* API docs: <https://docs.defikingdoms.com/>
* SDK: <https://github.com/DefiKingdoms/sdk>

## 🔑 Setup

1. Follow the instructions on [Setting up Gateway](/gateway/setup) to install the Gateway Docker container
2. Run `gateway connect defikingdoms` and follow the prompts to add your wallet private key. Like all API and private keys in Hummingbot, this key is encrypted with your Hummingbot password.
3. Run `create` to create an [AMM Arbitrage](/strategies/amm-arbitrage/) strategy between Defi Kingdoms and a different exchange.
4. Run `start` to start the strategy, and you're trading!

## 📘 Additional Resources

See [Harmony](/gateway/chains/ethereum/#harmony) for more information about the default configuration settings and how to change them.