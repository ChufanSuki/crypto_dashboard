# crypto_dashboard
[![Build Status](https://app.travis-ci.com/RetownPlato/crypto_dashboard.svg?branch=main)](https://app.travis-ci.com/RetownPlato/crypto_dashboard)
## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## API

### [Cryptocompare](https://min-api.cryptocompare.com/)
```
GET https://min-api.cryptocompare.com/data/v2/news/?lang=EN
RETURN An arrays of news object. Below is an example.

0 : Object
id: "27014785"
guid: "https://www.cryptopolitan.com/?p=102548"
published_on: 1626249195
imageurl: "https://images.cryptocompare.com/news/default/cryptopolitan.png"
title: "Binance Coin Price Analysis: BNB/USD crashes from $334 to higher lows at $290"
url: "https://www.cryptopolitan.com/binance-coin-price-analysis-2021-07-14/"
source: "cryptopolitan"
body: "TL;DR Breakdown Binance coin bears are aiming to crash the 20-day exponential moving average. BNB/USD is undergoing short bullish gains between $291 &#8211; $295. At the time of writing, the price is up to $294 Binance Coin Price Analysis: General price overview The BNB/USD trading pair corrected downwards violently on the 24-hour chart from the [&#8230;]"
tags: "News|Binance News"
categories: "Trading|Exchange|Market"
upvotes: "0"
downvotes: "0"
lang: "EN"
 source_info: Object
name: "Cryptopolitan"
lang: "EN"
img: "https://images.cryptocompare.com/news/default/cryptopolitan.png"
```
### [Biance](https://binance-docs.github.io/apidocs/)
- Subscribe 
- Unsubscribe
- K Line
### [Coinmarket](https://coinmarketcap.com/)
![](https://s2.coinmarketcap.com/static/img/coins/64x64/1.png)...
