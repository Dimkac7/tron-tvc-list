# Adding new token
The JSON schema for the tokens includes: address, name, decimals, symbol, logoURI, official homepage, MarketCap link, existing Markets.

Follow the steps below to add a new token：
1) Fork this repo.
2) change the JSON file `tokenlist.json`, adding such as: (PLEASE DO NOT REMOVE EXISITING TOKENS)
```
{
      "address": "TLa2f6VPqDgRE67v1736s7bJ8Ray5wYjU7",
      "symbol": "WIN",
      "name": "WINkLink",
      "decimals": 6,
      "logoURI": "https://coin.top/profile_images/JKtJTydD_400x400.jpg",
      "homepage": "https://winklink.org/",
      "MarketCapLink": "https://coinmarketcap.com/currencies/wink/",
      "existingMarkets": [
          {
              "source": "Binance",
              "pairs": [
                  "WIN/USDT",
                  "WIN/BUSD",
                  "WIN/BNB",
                  "WIN/USDC"
              ]
          },
          {
              "source": "Poloniex",
              "pairs": [
                  "WIN/USDT"
              ]
          },
          {
              "source": "KuCoin",
              "pairs": [
                  "WIN/USDT"
              ]
          }
    ]
}
```
* `address`[Required]: your token address TK96f3YJoEpRbsiEFKmM7P5UDWiHuzy11m
* `symbol`[Required]: your token symbol.TRC-20
* `name`[Required]: your token name.TRX
* `logoURI`[Required]: the logo URI of your token.trx
* `homepage`[Required]: the home page of your token.trx
* `MarketCapLink`[Optional]: the coinmarketcap or coingecko link for your token.
* `existingMarkets`[Required]: where to trade with your token.trx
3) Submit PR with the changed JSON file.


