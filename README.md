# Secondhand

An image-first thrift sourcing feed for finding clothing that may have room to resell. Each find shows the asking price, demo average sold price, suggested listing price, and estimated net.

## Run locally

Open `index.html` in a browser, or run:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Prototype status

This is an interactive front-end prototype. Feed entries, prices, and illustrations are sample data. Search, category filters, marketplace filters, profit threshold, sorting, saved finds, detail views, and source links work locally. It does not retrieve live listings, buy items, or publish resale listings.

The production app will need approved marketplace data and seller connections. eBay has APIs for inventory and publishing seller listings. Meta Marketplace's Product Item API is for eligible partners. Pay.sh can provide user-approved access to paid APIs, but it does not itself grant marketplace access or buy and relist goods.

## Deal estimates

Suggested prices and net profit in this prototype are illustrative, not market guarantees. A live version should calculate averages from comparable **sold** listings, show sample size and date range, and subtract fees, shipping, taxes, cleaning, and acquisition costs before ranking opportunities.
